
# Sustainable-Smart-Building-Management-System
This project demonstrates Sustainable-Smart-Building-Management-System integration of a Raspberry Pi online web simulator with Azure IoT Hub and visualizing the data in Power BI Desktop.


## Overview

The Raspberry Pi Web Simulator to Azure IoT Hub project provides a simulated environment to mimic the behavior of a Raspberry Pi device and send telemetry data to Azure IoT Hub. The data is then collected, processed, and visualized using Power BI Desktop for real-time monitoring and analysis.

## Architecture

The project architecture consists of the following components:

1. Raspberry Pi Web Simulator: A web-based simulator that emulates a Raspberry Pi device and generates simulated telemetry data.

2. Azure IoT Hub: A cloud-based service that acts as a messaging hub for bi-directional communication between devices and the cloud. It receives telemetry data from the simulator and forwards it for processing.

3. Azure Stream Analytics: A real-time data processing service that processes and filters incoming telemetry data from Azure IoT Hub. It can transform, aggregate, and route the data to various destinations.

4. Power BI Desktop: A powerful data visualization and analytics tool used to connect to Azure Stream Analytics and create real-time dashboards and reports based on the received telemetry data.

## Prerequisites

Before getting started, ensure that you have the following:

1. An Azure subscription: Create an Azure account and set up an IoT Hub resource.

2. Raspberry Pi Web Simulator: Access to the Raspberry Pi online web simulator. (https://azure-samples.github.io/raspberry-pi-web-simulator/?lang=en#getstarted)

3. Power BI Desktop: Install Power BI Desktop on your local machine to visualize the data.

## Setup and Configuration

Follow these steps to set up and configure the project:



### Simulated Raspberry Pi Device Setup:


Open the Raspberry Pi online web simulator in your preferred web browser.
Customize the simulated device's characteristics and data generation parameters as needed.
Obtain the connection string for the simulated device.
### Azure IoT Hub Configuration:

Create an Azure IoT Hub resource if you don't have one.
Set up the necessary configurations in Azure IoT Hub, including device provisioning and security.
Register a device and obtain its connection string.
### Azure Stream Analytics Configuration:

Create an Azure Stream Analytics job in your Azure account.
Configure the input as Azure IoT Hub and specify the device connection string obtained in the previous step.
Set up a suitable query to process and transform the incoming data in real-time.
Configure the output as Power BI and specify the necessary credentials.
### Power BI Desktop Integration:

* Launch Power BI Desktop.
* Connect to Azure IoT Hub as a data source using the obtained connection string.
* Design visualizations and dashboards based on the available data.
## Usage
* Start the Raspberry Pi online web simulator and configure it to use the previously obtained connection string.

* Run the simulation on the Raspberry Pi online web simulator to generate sample data.

* The simulated data will be transmitted to Azure IoT Hub.

* Azure Stream Analytics will receive the data from IoT Hub, process it according to the defined query, and send the transformed data to Power BI.

* Use Power BI Desktop to connect to the output of the Azure Stream Analytics job and import the processed data.

* Design visualizations and dashboards in Power BI Desktop based on the imported data.

## Contributing
Contributions to this project are welcome! If you want to contribute, please follow these guidelines:

Fork the repository and create a new branch for your feature or bug fix.

Make your changes and ensure that the code follows the project's coding style.

Write tests to cover your code changes, if applicable.

Submit a pull request, describing your changes and referencing any related issues.

## License
*******************************************************************************
 * Copyright (c) 2013 IBM Corp.
 
 * All rights reserved. This program and the accompanying materials
 * are made available under the terms of the Eclipse Public License v1.0
 * and Eclipse Distribution License v1.0 which accompany this distribution. 
 
 * The Eclipse Public License is available at 
 *    http://www.eclipse.org/legal/epl-v10.html
 * and the Eclipse Distribution License is available at 
 *   http://www.eclipse.org/org/documents/edl-v10.php.
 

 *******************************************************************************






## Acknowledgments
We would like to acknowledge the following resources that have been helpful in the development of this project:

Raspberry Pi online web simulator (https://azure-samples.github.io/raspberry-pi-web-simulator/?lang=en#getstarted)
Azure IoT Hub documentation (https://learn.microsoft.com/en-us/azure/iot-hub/iot-hub-raspberry-pi-web-simulator-get-started )
Power BI Dashboard (https://app.powerbi.com/groups/me/reports/91bd22ff-0ad9-416a-9a20-da4d65cfc439/ReportSection?experience=power-bi)

## 🔗 Links
 youtube vedio-complete explanation: https://youtu.be/IAIgKMfIUKc

 power BI Dashboard:https://app.powerbi.com/groups/me/reports/91bd22ff-0ad9-416a-9a20-da4d65cfc439/ReportSection?experience=power-bi

 github repository:https://github.com/AleenaMathew21/Sustainable-smart-building-management-system
                                                               



## Support

For any inquiries or feedback, please contact us at 
mohammedrehaman7@gmail.com
pothugantisaivamshi123@gmail.com
akanksha.thadakamalla@gmail.com
aleenamathew2109@gmail.com

For more detailed  user guides, please visit our youtube vedio https://youtu.be/IAIgKMfIUKc

Feel free to customize and modify this example to suit your specific Sustainable Building Management System project.