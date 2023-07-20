# ESP32_To_Databases_Control
To access the source ESP32 code, [Click Here](https://github.com/marMroc/ESP32_To_Databases_Control/blob/main/esp32_to_Server.ino)

# 📋 Index:
- [Summary](#id01)
- [Components](#id02)
- [Libraries](#id04)
- [Challenges](#id05)
- [Learnings](#id06)

## Summary: <a name="id01"></a>
This project consists of building an ESP32 client that makes HTTP requests to a PHP script to insert data - which in this case are sensor readings - into an SQL database.

## Components: <a name="id02"></a>
- One DOIT ESP32 Board - ESP32-WROOM-32D
- One Protoboard
  
## Challenges: <a name="id05"></a>
Ensure that the sensor data is correctly formatted before sending the HTTP request, ensuring that the information is sent to the server properly.

## Learnings: <a name="id06"></a>
- Establish a Wi-Fi connection using the WiFi.h library to connect the ESP32 to a Wi-Fi network.
- Perform an HTTP request using the HTTPClient.h library to send data to a web server.
- Format sensor data correctly before sending the HTTP request, ensuring that the information is sent to the server appropriately. This includes preparing the data in the required format for the POST request to the PHP server and validating the API key to ensure the security of received data.
