## **3 Functional Overview**

The DevLab I2C SCD41 Air Quality Sensor provides air quality sensing for an I2C-based system. The UE0179 schematic shows the SCD41 sensor connected to VSYS, GND, SDA, and SCL. It shows SDA and SCL pull-ups to VSYS, supply decoupling capacitors, a power indicator, and three I2C hub connectors.

### **3.1 Integration Boundary** {.section-page}

The UE0179 pinout and schematic identify the connector signals and board connections. The firmware release and sensor documentation establish the I2C address and commands. The generic I2C scanner in `software/` serves as a bus diagnostic.
