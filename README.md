# How AWS IoT works:

## The IoT universe

![Iot](/assets/iot-core.png)

## Apps

Apps give end users access to IoT devices and features provided by the cloud services to which those devices are connected.

## Cound services

Cloud services are distributed, large scale data storage and processing services that are connected to the internet. Examples include:

- IoT connection and management services
- Compute services such as Amazon Elastic Compute Cloud and AWS Lambda.
- Database service, such as Amazon DynamoDB

## Communication

Devices communicate with cloud services by using various technologies and protocols. Ex:

- Wifi/Broadband internet
- Narrow and cellular data
  -Long range Wide Area Network
- Propritary RF communication

## Devices

- Respberry Pi
- Arduino
- Voice- interface assistants.
- LoraWAN and devices.
- AWS sidewalk devices
- Custom IoT devices.

## Interface

- User interfaces
- Sensors
- Actuators

# AWS IoT services overview

![](/assets/architect.png)

## AWS IoT device software

AWS IoT provides this software t support your IoT devices.

1. AWS IoT device SDK
2. AWS IoT device Tester
3. AWS IoT ExpressLink
4. AWS IoT Greengrass
5. FreeRTOS

## AWS IoT control services

Connect to the following AWS IoT servives to manage the devices in your IoT solution.

1. AWS IoT Core
2. AWS IoT Core Device Advisor.
3. AWS IoT Device Defender
4. AWS IoT device Management

## AWS IoT data services

Analyze the data from the devices in your IoT solution and take appropriate action by using the following AWS IoT services.

1. Amazon Kinisis Video Stream Video Stream
2. Amazon Kinesis Video Stream with WebRTC
3. AWS IoT Analytics
4. AWS IoT Events
5. AWS IoT FleetWise
6. AWS IoT SiteWise
7. AWS IoT TwinMaker

# AWS IoT Core services

![](/assets/core-services.png)

## AWS IoT Core messaging services

1. Device gateway

Enable devices to securely and efficiently.

2. Message Broker

3. AWS IoT Core for LoraWAN

4. Rules engine

## AWS IoT Core control services

1. Custom Authentication service
2. Device Provisioning service
3. Group registry
4. Jobs service
5. Registry
6. Security and Identify services

## AWS IoT Core data services

1. Device shadow
2. Device Shadow service

## AWS IoT Core support service

1. Amazon Sidewalk Integration for AWS IoT Core

# Connect to AWS IoT Core

![](/assets/iot-endpoints.png)

- AWS IoT device endpoint: from IoT devices
- AWS IoT Core for LoraWAN: from LORA WAN gateways and devices
- AWS IoT Core service endpoint: from Apps and services

## AWS IoT Core for LoRaWAN gateways and devices

# Connect AWS devices to Internet

## AWS IoT device endpoint

Support communication between your IoT devices and AWS IoT.

- **Endpoint**

[Describe endpoint](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/iot/describe-endpoint.html)

AWS IoT Core - data plane

AWS IoT Device Management - jobs data

AWS IoT Device Advisor - data plane

AWS IoT Device Management - Fleet Hub

AWS IoT Device Management - secure tunneling

- **SDKs**
- **Authentication**

The device endpoints use X.509 certificates or AWS IAM users with credentials to authenticate users.

- **Learn more**

For more information about configuring and connecting wireless devices, see[ AWS IoT Core for LoRaWAN](https://docs.aws.amazon.com/iot/latest/developerguide/connect-iot-lorawan.html).
