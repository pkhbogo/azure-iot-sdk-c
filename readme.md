# Overview - Azure IoT C SDK

The Azure IoT C SDK and accompanying libraries enable developers to more easily create IoT solutions for Azure written in the C99 Language standard.

# Components

* **Azure IoT Hub Device C SDK:** to connect devices running C code to Azure IoT Hub.
* **Azure IoT Hub Device Provisioning Service Client SDK:** for enrolling devices with [Azure IoT Device Provisioning Services](https://docs.microsoft.com/azure/iot-dps/) and managing enrollments lists.
* **Azure IoT Hub Service C SDK:** to interface with an Azure IoT Hub service instance from a server-side C application.
* **Serializer Library for C:** to help serialize and deserialize data on your device.

# Packages and Libraries

  The simplest way to get started with the Azure IoT SDKs is to use the following packages and libraries:

* Linux: [Device SDK on apt-get](./iothub_client/readme.md#aptgetpackage)
* mbed:                                      [Device SDK library on MBED](./iothub_client/readme.md#mbed)
* Arduino:                                   [Device SDK library in the Arduino IDE](./iothub_client/readme.md#arduino)
* Windows:                                   [Device SDK on NuGet](./iothub_client/readme.md#nugetpackage)
* iOS:                                       [Device SDK on CocoaPod](https://cocoapods.org/pods/AzureIoTHubClient)

# Samples

  Here are a set of simple samples that will help you get started:

* [Device SDK Samples](./iothub_client/samples/)
* [Service SDK Samples](./iothub_service_client/samples/)
* [Serializer Library Samples](./serializer/samples/)

# Compile the SDK

When no package or library is available for your platform or if you want to modify the SDK code, or port the SDK to a new platform, then you can leverage the build environment provided in the repository.

* [Device SDK](./iothub_client/readme.md#compile)
* [Service SDK](./iothub_service_client/readme.md#compile)

# SDK API Reference Documentation

The API reference documentation for the C SDKs can be found [here][c-api-reference].

# Other Azure IoT SDKs

To find Azure IoT SDKs in other languages, please refer to the [azure-iot-sdks][azure-iot-sdks] repository.

# Developing Azure IoT Applications

To learn more about building Azure IoT Applications, you can visit the [Azure IoT Dev Center][iot-dev-center].

-----

# [Further Details about C SDK and Libraries](./readme-annex.md)

-----