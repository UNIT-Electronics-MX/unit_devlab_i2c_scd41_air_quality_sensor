## **5 Board Operation**

### **5.1 Before Connecting** {.section-page}

Check the product-specific UE0179 pinout or schematic for power, ground, SDA, and SCL. The board views alone do not establish voltage limits or connector numbering.

### **5.2 I2C Bus Check**

After confirming the wiring and supply limits, use the generic Arduino or MicroPython I2C scanner in `software/examples/i2c/`. Set the host SDA and SCL pins for your controller. A responding address confirms only that a device acknowledged on the bus; it does not identify the module or validate its measurement protocol.
