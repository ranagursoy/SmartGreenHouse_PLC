# Smart Greenhouse Automation System 
# PLC automation

This project focuses on automating key systems of a smart greenhouse using a PLC (Programmable Logic Controller) to optimize resource use, improve crop production, and streamline operations. The greenhouse simulates a fully automated environment where various parameters such as ventilation, humidity, lighting, and more are controlled to ensure consistent production while saving time and resources. It also includes preventive measures like fire alarms and security features.

### **Key Features**

- Automated control of:
    - **Ventilation** for airflow and temperature management.
    - **Humidity** levels to maintain ideal growing conditions.
    - **Lighting** for plant photosynthesis based on daylight levels.
    - **Irrigation** to ensure consistent water supply.
    - **Disinfection** to prevent disease spread.
    - **Fertilization** for precise nutrient delivery.
    - **Temperature Control** to maintain optimal growth environments.
    - **CO2 Control** for enriched growing atmospheres.
    - **Solar Panel Integration** for renewable energy utilization.
    - **Fire Alarm** system for safety.
    - **Water Tank Management** to monitor and control water levels.
    - **Security Systems** to prevent unauthorized access.
    - **Harvest Notifier** for timely alerts when crops are ready for harvesting.
- **User Interface (UI)**: Designed for easy monitoring and control of greenhouse systems.

### 3. **System Overview**

The smart greenhouse is equipped with various sensors and actuators connected to a PLC, which automates all the key processes. The user interface provides control capabilities.

- **Inputs**: Sensors for temperature, humidity, CO2, soil moisture, light intensity, water level, fire, and motion detection.
- **Outputs**: Actuators for fans, pumps, lights, CO2 injectors, alarms, and security systems.
- **Communication**: The system is designed to communicate via [protocol], ensuring seamless integration between hardware and software.

### 4. **Hardware**

For more detailed information on the hardware, you may review the SMART_GREENHOUSE.pdf file.

- **PLC Model**: FX5U-8AD Mitsubishi FX series and  FX5U-32MT/ES-A Mitsubishi FX series
- **Sensors**: Temperature, humidity, CO2, light, water level, motion, fire sensors.
- **Actuators**: Ventilation fans, irrigation pumps, lights, CO2 injectors, security system alarms.
- **Solar Panels**: Integrated for sustainable power generation.
- **User Interface**: It’s thought to be a touch-screen.

![System_requirements](https://github.com/user-attachments/assets/212c9eee-e617-4945-8a2f-a66716557b38)

### 5. **Software**

- **Programming Environment**: The system is programmed using FPWIN program with ladder logic for controlling the processes.
- **Control Logic**: Each system (ventilation, lighting, irrigation, etc.) has its own set of rules triggered by sensor inputs.
- **User Interface**: Custom UI designed for real-time monitoring and manual override usin GTWIN PRO.

### **Control Logic & Decision Diagrams**

Each subsystem in the smart greenhouse follows specific rules determined by sensor inputs and outputs. The following decision diagrams illustrate how the logic is implemented for each system, showcasing the conditions that trigger automated actions. To review every decision diagram for each system, please refer to the SMART_GREENHOUSE.pdf file.

**Temperature Control Logic**:

![temp_diagram](https://github.com/user-attachments/assets/50446e15-ea03-4616-8d29-90ddc5729bdb)

**Lighting Control Logic**:

![Lighting_diagram](https://github.com/user-attachments/assets/34a91062-108d-41e4-a1f5-dff6fd2e6a54)

**Fire Alarm System Logic**:

![fire_diagram](https://github.com/user-attachments/assets/880e78ff-5c3a-430c-9d63-41d1dba332c9)

