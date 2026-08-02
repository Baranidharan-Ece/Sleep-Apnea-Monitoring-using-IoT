# Working Principle

The IoT-Enabled Water Management System continuously monitors water quality, tank levels, and water flow using multiple sensors connected to an Arduino Uno. The processed data is displayed on an LCD and transmitted to the NodeMCU ESP8266 for remote IoT monitoring.

## Step-by-Step Working

### Step 1 – System Initialization
- Arduino Uno initializes all sensors, LCD display, and communication modules.
- Both solenoid valves remain OFF during startup.

### Step 2 – Water Quality Monitoring
- The turbidity sensor measures the quality of the water.
- The measured value is displayed on the 16×2 LCD.

### Step 3 – Tank Level Detection
- Float Switch 1 monitors Tank 1.
- Float Switch 2 monitors Tank 2.
- If the water level is low, the corresponding solenoid valve is turned ON.
- Once the tank reaches the required level, the valve is automatically turned OFF.

### Step 4 – Water Flow Measurement
- The flow sensor generates pulses proportional to the water flow.
- Arduino calculates:
  - Flow Frequency
  - Flow Rate (L/min)
  - Total Water Consumption

### Step 5 – Data Display
The LCD continuously displays:
- Turbidity Value
- Water Flow Rate
- Total Water Used

### Step 6 – IoT Communication
- Arduino sends sensor data to the NodeMCU ESP8266 through Serial Communication.
- NodeMCU uploads the data to the Blynk IoT Cloud via Wi-Fi.
- Users can monitor the system remotely using the Blynk Mobile Application.

## Working Flow

Water Source
→ Flow Sensor
→ Turbidity Sensor
→ Float Switches
→ Arduino Uno
→ LCD Display
→ NodeMCU ESP8266
→ Blynk IoT Cloud
→ Mobile Dashboard

## Outcome

The system provides:
- Real-time water quality monitoring
- Automatic tank filling control
- Accurate water flow measurement
- Remote IoT monitoring
- Efficient water management with reduced water wastage
