# Overview
This dataset was collected during our greenhouse automation graduation project in the Computer Science program at King Abdulaziz University. It contains over 60,000 time series records captured from LoRaWAN sensors from September 26 to December 5, 2025.  

# Hardware
**Sensors:** [RAK7204 WisNode Sense Home](https://docs.rakwireless.com/product-categories/wisnode/rak7204/datasheet/)  
**Gateway:** [RAK7289V2 WisGate Edge Pro](https://docs.rakwireless.com/product-categories/wisgate/rak7289v2/datasheet/)  

# Deployment
We deployed 8 sensors. Only 6 of them lasted until the end of the project.

## Installation Method
Sensors were mounted on the greenhouse's structural poles at a height of 2.5m above ground, with 2.5m spacing between nodes. The greenhouse dimensions are 30m × 9m. Sensors were secured using cable ties and duct tape.
![Illustration of installment in the greenhouse](https://github.com/AbeerAlshalawi/greenhouse-dataset/blob/main/deployment-illustration.png)
*Greenhouse illustration (Credits: Lujin Banasir [(Github)](https://github.com/LUJIN-0)).*

## Pictures
![greenhouse](https://github.com/AbeerAlshalawi/greenhouse-dataset/blob/main/greenhouse.jpeg)
*Greenhouse.*  

![gateway](https://github.com/AbeerAlshalawi/greenhouse-dataset/blob/main/gateway.jpeg)
*Gateway.*  

![sensor](https://github.com/AbeerAlshalawi/greenhouse-dataset/blob/main/sensor.jpeg)
*Sensor.*  

# Dataset Columns
The dataset contains a total of 17 columns.
| Column | Unit | Description |
|-------------|-----------|------|
| devEui | - | Device Extended Unique Identifier - unique 64-bit identifier for each LoRaWAN sensor node |
| temperature | Degree Celsius (℃) | Ambient air temperature measured by the sensor |
| humidity | Percent Relative Humidity (% RH) | Relative humidity of the greenhouse air |
| barometer | Hectopascal (hPa) | Atmospheric pressure |
| gasResistance | Kilo-ohm (kΩ) | Gas sensor resistance value |
| battery | voltage (V) | Remaining battery voltage of the sensor node |
| bandwidth | Kilohertz (kHz) | LoRaWAN transmission bandwidth used for the packet |
| codeRate | - | Forward error correction coding rate |
| fCnt | - | Frame counter - incremental count of uplink messages from the device |
| fOptLen | - | Length of the frame options field in bytes |
| fPort | - | LoRaWAN application port number used for the message |
| frequency | Hertz (Hz) | Radio frequency used for transmission |
| spreadingFactor | - | LoRaWAN spreading factor (7-12) - affects range and data rate tradeoff |
| channel | - | LoRaWAN channel index used for transmission |
| rssi | Decibel-milliwatts (dBm) | Received Signal Strength Indicator - signal strength at gateway reception |
| snr | Decibels (dB) | Signal-to-Noise Ratio - signal quality metric |
| timestamp | - | Date and time when the reading was recorded |
