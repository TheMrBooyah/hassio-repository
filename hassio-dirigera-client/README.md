# Home Assistant Add-on: DIRIGERA API Client

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

## About

DIRIGERA API client is an unofficial client API for the IKEA's new Smart home Hub [DIRIGERA](https://github.com/wjtje/DIRIGERA).
The API uses the DIRIGERA's REST interface at port 8443. 
The vast majority has been implemented. However, most are barely tested and some are known as inoperable.

For more information about what is known to work/not work visit [dvdgeisler's repository](https://github.com/dvdgeisler/DirigeraClient)

## Configuration

This add-on requires the following configuration:
* dirigera_host
  * The hostname or IP-address the DIRIGERA is running on
* mqtt_host
  * The hostname or IP-address of your Mosquitto broker. If running one in home assistant, you can leave this on the default value 'core-mosquitto'
* port
  * The port your Mosquitto broker is running on. Default '1883'
* username
  * The username for your Mosquitto broker. Only required when your Mosquitto broker requires authentication.
* password
  * The password for your Mosquitto broker. Only required when your Mosquitto broker requires authentication.
* token
  * The Authentication Token to communicate with your DIRIGERA gateway. Follow [the instructions from this page](https://github.com/dvdgeisler/DirigeraClient#integration-to-home-assistant) to get your access token.

## Support

Got questions?

Do you have questions about or problems with the add-on? Create a support ticket [here](https://github.com/TheMrBooyah/hassio-dirigera-client/issues)

Do you have questions about or problems with the client API? Create a support ticket [here](https://github.com/dvdgeisler/DirigeraClient/issues)


[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg