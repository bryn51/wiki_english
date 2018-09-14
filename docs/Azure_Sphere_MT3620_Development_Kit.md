---
title: Azure Sphere MT3620 Development Kit
category: Azure
bzurl:
oldwikiname: 
prodimagename: 
surveyurl:  
sku: 
---

![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/azure.jpg)

Azure Sphere MT3620 Development Kit is specially designed for rapid prototyping and help developer experience Azure Sphere technology. MT3620 is the first Azure Sphere certified MCU. Azure Sphere certified MCUs are a new class of secured, connected crossover microcontrollers. MT3620 features three user-accessible microcontroller cores, one application processor subsystem based on an ARM Cortex-A7 core which runs at up to 500MHz, two general purpose ARM Cortex-M4F I/O subsystems, each of which runs at up to 200MHz. MT3620 were designed to support real-time requirements when interfacing with a variety of on-chip peripherals including UART, I2C, SPI, I2S, and ADC. It has built-in security subsystem with its own dedicated CM4F core for secure boot and secure system operation, dual-band 802.11a/b/g/n Wi-Fi.

The MT3620 Development Kit has expanded most MT3620 hardware resources on the expansion pin headers, by wiring to breadboard or adding a shield board , user can easily connect to other hardware accessories.

The Azure Sphere operating system is pre-installed on the MT3620 and is designed to work with the Azure Sphere Security Service to create a secured IoT platform. Together the Azure Sphere OS and security service deliver:  

- Certificate-based device authentication to any web service
- Software attestation and secure boot
- Threat detection via failure reporting
- Ongoing security updates
- An integrated, secured end-to-end IoT solution

MT3620 software development is supported using the powerful Microsoft Visual Studio IDE: Install Visual Studio and the Azure Sphere extension, plug the development board into a PC over USB, and start developing IoT applications with unprecedented levels of security.

<iframe width="800" height="450" src="https://www.youtube.com/embed/iiDF26HNh-Y" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


|Product Name | How to Buy|
|----------------|-----------|
|Azure Sphere MT3620 Development Kit US Version|[![](https://raw.githubusercontent.com/SeeedDocument/Seeed-WiKi/master/docs/images/get_one_now_small.png)](https://www.seeedstudio.com/Azure-Sphere-MT3620-Development-Kit-p-3052.html)|
|Azure Sphere MT3620 Development Kit JP Version|[![](https://raw.githubusercontent.com/SeeedDocument/Seeed-WiKi/master/docs/images/get_one_now_small.png)](https://www.seeedstudio.com/Azure-Sphere-MT3620-Development-Kit_JP-Version-p-3135.html)|
|Azure Sphere MT3620 Development Kit EU Version|[![](https://raw.githubusercontent.com/SeeedDocument/Seeed-WiKi/master/docs/images/get_one_now_small.png)](https://www.seeedstudio.com/Azure-Sphere-MT3620-Development-Kit_EU-Version-p-3134.html)|



## Features

- Azure Sphere: End-to-end security for IoT devices.
- Dual-band 802.11 a/b/g/n with antenna diversity.
- Tri-core microcontroller with on-chip RAM & flash.
- Microsoft Visual Studio development environment.
- Online authentication & updates for device lifetime.
- Expand UART, I2C, I2S, SPI, ADC, GPIO resource on pin header.

## Specification

**Hardware**

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-baqh"><span style="font-weight:bold">Description</span></th>
    <th class="tg-baqh"><span style="font-weight:bold">Value</span></th>
  </tr>
  <tr>
    <td class="tg-amwm" rowspan="2"><br>MCU</td>
    <td class="tg-0lax">1 * ARM Cortex A7 core @500MHz , 4MB RAM</td>
  </tr>
  <tr>
    <td class="tg-0lax">2 * ARM Cortex M4 core @200MHz, 64KB RAM</td>
  </tr>
  <tr>
    <td class="tg-amwm" rowspan="5"><br><br><br><br>ISU</td>
    <td class="tg-0lax">4 * “ISU” serial interface which can be configured as:</td>
  </tr>
  <tr>
    <td class="tg-0lax">&nbsp;&nbsp;- I2C runs at up to 1MHz</td>
  </tr>
  <tr>
    <td class="tg-0lax">&nbsp;&nbsp;- SPI runs at up to 40MHz</td>
  </tr>
  <tr>
    <td class="tg-0lax">&nbsp;&nbsp;- UART runs at up to 3Mbps</td>
  </tr>
  <tr>
    <td class="tg-0lax">ISU is Serial Communication Interface</td>
  </tr>
  <tr>
    <td class="tg-amwm">Connectivity</td>
    <td class="tg-0lax">2.4/5GHz dual-band 802.11a/b/g/n Wi-Fi</td>
  </tr>
  <tr>
    <td class="tg-amwm">I2S</td>
    <td class="tg-0lax">1 * I2S support slave and TDM slave mode</td>
  </tr>
  <tr>
    <td class="tg-amwm">ADC</td>
    <td class="tg-0lax">4 * 12-bit ADC input I/O</td>
  </tr>
  <tr>
    <td class="tg-amwm">RTC</td>
    <td class="tg-0lax">1 * RTC with CR2032 3V battery holder</td>
  </tr>
  <tr>
    <td class="tg-amwm">USB</td>
    <td class="tg-0lax">1 * Micro USB port for power supply and debugging, 5V/1A</td>
  </tr>
  <tr>
    <td class="tg-amwm">DC Jack</td>
    <td class="tg-0lax">1* 5V/1A DC power jack</td>
  </tr>
  <tr>
    <td class="tg-amwm">Operating Temperature</td>
    <td class="tg-0lax">-40~85°C</td>
  </tr>
  <tr>
    <td class="tg-amwm">Dimensions</td>
    <td class="tg-0lax">L:85mm*W:50mm*H:16mm</td>
  </tr>
  <tr>
    <td class="tg-amwm">Certification</td>
    <td class="tg-0lax">CE / FCC / MIC / RoHS</td>
  </tr>
</table>

**Software**

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <td class="tg-0pky">IDE</td>
    <td class="tg-0pky">Visual Studio</td>
  </tr>
  <tr>
    <td class="tg-0lax">System</td>
    <td class="tg-0lax">Windows10</td>
  </tr>
  <tr>
    <td class="tg-0lax">Programming Language</td>
    <td class="tg-0lax">C</td>
  </tr>
</table>


## Hardware Overview

**Board Diagram**

<a href="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/Diagram.png" target="_blank"><img src="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/Diagram.png"/></a>

- **J1**: ADC Reference Voltage, On: using internal 2.5v; Off: Connect External 1.8v to Pin 1. Off by default. 
- **J2**: 3.3V Isolation, On: Enable system 3.3v power; Off: Cut off the system 3.3v power. On by default.
- **J3**: RTC Power Selection: Left 2 pins: Using RTC Battery(Model:CR2032) at backside.
- **4 User RGB LED**: LED model is LTST-C19HE1WT.
- **USB Port**: Power supply(5V/1A) and debug, connected to FT4232HQ chip at backside. 
- **4 System LED**: Led1(Near USB port): Green, FTDI Activity LED. Led2: RED, Power Indicator. Led3: RGB, Wifi Status. Led4: RGB, App Status.
- **DC Power**: 5V/1A
- **3 System Button**: Button A&B(White) are user botton. Button Reset(Blue) is System Reset.
- **MT3620**：The [MT3620](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/datasheet/MediaTek%20MT3620%20Product%20Brief.pdf) is a highly integrated, high performance IoT MCU with the high level of security necessary for modern, robust internet-connected devices. The MT3620 targets a wide range of IoT applications including smart home, commercial, industrial and many other domains thanks to its extensive I/O peripheral subsystem that allows device design flexibility and freedom.
- **FT4232HQ**: The [FT4232H](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/datasheet/DS_FT4232H.pdf) is a USB 2.0 High Speed (480Mb/s) to UART/MPSSE ICs.

**Board Pinmap**

<a href="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/PinMap.png" target="_blank"><img src="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/PinMap.png"/></a>

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/H1_2.png)

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/H3_4.png)

**Dimensions**

<a href="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/dimension.png" target="_blank"><img src="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/dimension.png"/></a>

**Power**

Power to the Azure Sphere MT3620 Development Kit is supplied via the on-board USB Micro B connector or directly via the DC connector. 

- GPIO voltage is 3.3v, has a limited overhead of only 100mA available.
- 5v_out on H3 connector has a limited overhead of only 500mA available.
- 3.3v on H3 connector has a limited overhead of only 400mA available. 
- Typical average current consumption is 150mA with 5V Wi-Fi on. Wifi scan current is typically 330ma.

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/power.png)


**Hardware Design and Manufacture**

The current Azure Sphere software release does not support all features of the [MT3620](https://www.mediatek.com/products/azureSphere/mt3620) hardware. For example, the following are **not yet supported** in software:

- 2 x ARM Cortex-M4 with FPU
- ADC, I2C, I2S, PWM and SPI peripheral interfaces (GPIO and UART are supported)
- Wi-Fi 802.11a (b/g/n are supported)
- RTC with clock selection and battery backup

!!!Tip
    For more info, please refer to [Information and tools for hardware design and manufacture](https://docs.microsoft.com/en-us/azure-sphere/manufacturers/hardware-manufacturing).

## Product Handling

**Packaging**

The Azure Sphere MT3620 Development Kit packaging contains Azure Sphere MT3620 Development Kit and Micro B USB cable.

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/box.JPG)

**ESD Precautions**

The Azure Sphere MT3620 Development Kit contains highly sensitive electronic circuitry and is an Electrostatic Sensitive Device (ESD). Handling The Azure Sphere MT3620 Development Kit without proper ESD protection may destroy or damage it permanently. Proper ESD handling and packaging procedures must be applied throughout the processing, handling and operation of any application that incorporates Azure Sphere MT3620 Development Kit.

## Applications

- Agriculture
- Building
- Public safety

!!!Tip
    To understand how Azure Sphere works in a real-world setting, consider [Contoso, Ltds cenario](https://docs.microsoft.com/en-us/azure-sphere/product-overview/scenario).

## Qualification and approvals

| US FCC | Europe CE | Japan MIC |ROHS |
|--------|-----------|-----------|-----------|
| [![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/fcc.png)](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/certification/Azure%20Sphere%20MT3620%20Development%20Kit-FCC-FCC.zip)       |   [![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/ce.png)](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/certification/Azure%20Sphere%20MT3620%20Development%20Kit-CE.zip)        |  [![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/mic.jpg)](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/certification/Azure%20Sphere%20MT3620%20Development%20Kit-MIC.zip)         |![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/rohs-logo.jpg)|

- CE ID: 18/0331/SZ
- FCC ID: Z4T-MT3620DEVB 
- MIC ID: CSRT18207

## Quickstarts for Azure Sphere

To use MT3620 Dev Board for Azure Sphere, you’ll need a Windows 10 PC with the latest Windows Updates, alongwith the Visual Studio Tools for Azure Sphere (which will be available for download from Microsoft). These tools will include application templates, development tools and the Azure Sphere software development kit (SDK).

The quickstarts guide you through:

- [Setting up an account](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-azure-directory-account) for Azure Sphere
- [Installing Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-install) and setting up your development board
- [Claiming your device](https://docs.microsoft.com/en-us/azure-sphere/quickstart/claim-device)
- [Configuring Wi-Fi](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-configure-wifi) and updating your device OS
- [Building your first application](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-blink-application) by using the Visual Studio Tools Preview for Azure Sphere
- [Deploying the application](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-first-deployment) over Wi-Fi
- [Setting up an Azure IoT Hub to work with Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-setup-iot-hub)

## Azure Sphere Demo

We build two demoes which combine Sphere dev kit and [Seeed Grove system](http://wiki.seeedstudio.com/Grove_System/). 

**Demo1**: Sphere performs as an MCU, which connects with temperature sensor(SHT31), relay, fan, display, analog device. Demo simulates a fan with IoT connectivity, people can measure the ambient temperature and setup a threshold value to turn on/off the fan from Azure Cloud. The temperature will display on the LED display. User can swap the resistor to change the fan’s speed level from 0,1,2,3(0 means switch off the fan).

**Demo2**: Sphere works as an IoT safety connectivity device, which will be connect to an already made appliance, the appliance has its own MCU , which in this demo, we use an Arduino to simulate a fan’s control board, the board can get the status of the fan’s motor data , by analyzing the data , people can get the failure status and send maintainer to fix it. By pushing the button, this simulates the health status of the fan device , when button being pushed, that means the device need maintenance.

### Hardware

**Part List**


| MT3620 development kits | Grove - Temperature&Humidity Sensor (SHT31)|  Grove - Relay |
|--------------|-------------|-----------------|
|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/azure_s.jpg)|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/SHT3_s.jpg)|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/Relay_s.jpg)|
|[Get One Now](https://www.seeedstudio.com/Azure-Sphere-MT3620-Development-Kit-p-3052.html)|[Get One Now](https://www.seeedstudio.com/Grove-Temperature-Humidity-Sensor-SHT3-p-2655.html)|[Get One Now](https://www.seeedstudio.com/Grove-Relay-p-769.html)|

| Grove - Slide Potentiometer | Grove - 4-Digit Display |   Grove - Blue LED Button  |
|--------------|-------------|-----------------|
|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/Slide_Potentiometer_s.jpg)|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/4_digital_s.jpg)|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/Grov-Blue_led_button.jpg)|
|[Get One Now](https://www.seeedstudio.com/Grove-Slide-Potentiometer-p-1196.html)|[Get One Now](https://www.seeedstudio.com/Grove-4-Digit-Display-p-1198.html)|[Get One Now](https://www.seeedstudio.com/Grove-Blue-LED-Button-p-3104.html)|


| MT3620 Grove Shield |Seeeduino V4.2  | Base Shield  |
|--------------|-------------|-----------------|
|![enter image description here](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/mt3620groveshieldb_s.jpg)|![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_Light_Sensor/master/images/gs_1.jpg)|![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_Light_Sensor/master/images/gs_4.jpg)|
|[Get One Now](https://www.seeedstudio.com/MT3620-Grove-Shield-p-3145.html)|[Get One Now](http://www.seeedstudio.com/Seeeduino-V4.2-p-2517.html)|[Get One Now](https://www.seeedstudio.com/Base-Shield-V2-p-1378.html)|

**System Diagram**

<a href="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/demo1.png" target="_blank"><img src="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/demo1.png"/></a>

<a href="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/demo2.png" target="_blank"><img src="https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/demo2.png"/></a>

**MT3620 Grove Shield**

The current Azure Sphere software release does not support all features of the [MT3620](https://www.mediatek.com/products/azureSphere/mt3620) hardware. For example, the following are **not yet supported** in software: ADC, I2C, I2S, PWM and SPI peripheral interfaces, only **GPIO and UART are supported**. 

MT3620 Grove Shield includes 2 chips, AD7992(Anlog to I2C) and SC18IM700(I2C to UART) to enable the ADC and I2C function from hardware side. So the analog sensors' signal go through AD7992 and then SC18IM700 to UART of develop board. The I2C sensors go through SC18IM700 to UART of develop board as well.

The [AD7992](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/datasheet/AD7992.pdf) is a 12-bit, low power, successive approximation ADC with an I2C-compatible interface. It transforms the anlog signal A0, A1 to I2C data.

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/ADC_2_I2C.png)

The [SC18IM700](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/datasheet/SC18IM700.pdf) is designed to serve as an interface between the standard UART port of a microcontroller or microprocessor and the serial I2C-bus; this allows the microcontroller or microprocessor to communicate directly with other I2C-bus devices. It transforms SDA/SCL signals to GPIO26_TXD0 and GPIO28_RXD0. 

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/I2C_2_UART.png)

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/MT3620_Grove_Shield-2018-09-11.png)

<div style="text-align:center">MT3620 Grove Shield Hardware Overview</div>


**Hardware Connection**

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/MT3620_demo_Front.jpg)

<div style="text-align:center">Front View of hardware setup</div>

![](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/img/MT3620_demo_backside.jpg)

<div style="text-align:center">Top View of hardware setup</div>

- Step 1. Connect Grove-Blue LED Button to port 2 of Grove base shield.
- Step 2. Connect Fan PWM signal to port 5 of Grove base shield.
- Step 3. Connect port 7(Software Serial Port) of Grove base shield to UART3 of MT3620 Grove Shield.
- Step 4. Plug Grove-Base shield to Seeeduino/Arduino.
- Step 5. Connect Grove-4 Digital Display to GPIO4 port of MT3620 Grove Shield.
- Step 6. Connect Grove-Temperature&Humidity Sensor(SHT31) to I2C port of MT3620 Grove Shield.
- Step 7. Connect Grove-Relay to GPIO0 port of MT3620 Grove Shield and Grove-Relay output terminal to control Fan on/off.
- Step 8. Connect Grove-Slide Potentiometer to Analog port of MT3620 Grove Shield.
- Step 9. Plug the MT3620 base shield to Azure Sphere MT3620 Development board.
- Step 10. Plug the USB cable to Azure Sphere MT3620 Development board and PC.
- Step 11. Plug the USB cable to Ardunio/Seeeduino and PC.
- Step 12. Plug the power supply to Fan. 


### Software

The software include the smart fan simulation system and Azure Sphere MT3620 Development system. 

- For the smart fan simulation system, use the arduino board to read Grove-Blue LED button press/release input signal, output the PWM to control the fan speed and control the Grove-Blue LED button LED status as well. Then use the port 7 to communicate with Azure Sphere MT3620 Development system through UART. 

- For Azure Sphere MT3620 Development system, Grove-4 Digital LED displays the temperature from Grove-Temperature&Humidity Sensor(SHT31) sensor, which demonstrates the UART-I2C shield function and MT3620 GPIO output function. Slide the Grove-Slide Potentiometer to change the fan speed, which demonstrates the MT3620 I/O input function. Configure a threshold temperature value from Azure Cloud, when value > threshold, Grove-relay turns fan on, otherwise turns fan off. User also can adjust Grove-Slide Potentiometer,  when the fan working status goes wrong, the fan's MCU will post the failure to Azure Sphere by UART, then failure report goes to the Azure Cloud and wait for maintance. 

**Smart Fan Simulation System**

- Step 1. Open the Arduino IDE.
- Step 2. Copy [Arduino Smart Fan Simulation code](https://raw.githubusercontent.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/master/sdk/Azure_Sphere_Sample_Smart_Fan-master/Arduino_code/Arduino_code.ino) and paste to Arduino IDE. 
- Step 3. Select Arduino/Seeeduino v4 as board from Tools menu. 
- Step 4. Select related COM port from Tools menu. 
- Step 5. Click upload to upload code the Arduino/Seeeduino. 

!!!Note
    If you do not know how to upload the code, please check [how to upload code](http://wiki.seeedstudio.com/Upload_Code/).

**Azure Sphere MT3620 Development System**

- Step 1. Download [Azure Sphere Code](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/sdk/Azure_Sphere_Sample_Smart_Fan-master/Azure_Sphere_Code.zip) and unzip. 
- Step 2. Follow [Quickstarts for Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-overview) to open the **AzureSphereDemo2.vcxproj** project.
- Step 3. Open the main.c under Source Files. 
- Step 4. Modify wifiSsid and wifiPsk.
- Step 5. Follow [Build and run the Blink sample](https://docs.microsoft.com/en-us/azure-sphere/quickstart/qs-blink-application#build-and-run-the-blink-sample) to run Azure Sphere Code.

**Demo Video**

Pending for video...

## Resource

- **[Product]** [Azure Sphere MT3620 Development Kit Product Brief](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/product_document/Azure%20Sphere%20MT3620%20Development%20Kit%20Product%20Brief-2018-09-10.pdf)
- **[Product]** [Welcome to Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/)
- **[Certification]** [Azure Sphere MT3620 Development Kit-CE](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/certification/Azure%20Sphere%20MT3620%20Development%20Kit-CE.zip)
- **[Certification]** [Azure Sphere MT3620 Development Kit-FCC](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/certification/Azure%20Sphere%20MT3620%20Development%20Kit-FCC-FCC.zip)
- **[Certification]** [Azure Sphere MT3620 Development Kit-MIC](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/certification/Azure%20Sphere%20MT3620%20Development%20Kit-MIC.zip)
- **[DataSheet]]** [MediaTek MT3620 Product Brief](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/datasheet/MediaTek%20MT3620%20Product%20Brief.pdf)
- **[DataSheet]** [DS_FT4232H](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/raw/master/datasheet/DS_FT4232H.pdf)
- **[Mechanical]** [Azure Sphere MT3620 Development Board-2D-Drawing](https://github.com/SeeedDocument/Azure_Sphere_MT3620_Development_Kit/tree/master/mechanical)

## Tech Support
Please submit any technical issue into our [forum](http://forum.seeedstudio.com/).