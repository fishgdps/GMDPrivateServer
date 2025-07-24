# FishGDPS' GMDPrivateServer
> Fork of GMDPrivateServer for FishGDPS

Differences from GMDPrivateServer are found [here](docs/differences.md)

Supported version of Geometry Dash: 1.0 - 1.5, 1.5 is recommended

Required version of PHP: 8.0+

### Setup
1. Upload the files on a webserver
2. Import database.sql into a MySQL/MariaDB database
3. Edit the links in the lib files in your Geometry Dash 1.5 APK
#### Optional steps:
- Modify the password used in the rate tool at `/incl/misc/rateToolPassword.php`

### Credits

GMDPrivateServer by Cvolton - https://github.com/Cvolton/GNDPrivateServer

Base for account settings and the private messaging system by someguy28

Using this for XOR encryption - https://github.com/sathoro/php-xor-cipher - (incl/lib/XORCipher.php)

Using this for cloud save encryption - https://github.com/defuse/php-encryption - (incl/lib/defuse-crypto.phar)

Most of the stuff in generateHash.php has been figured out by pavlukivan and Italian APK Downloader, so credits to them

Demon, auto, and star/feature/epic rating support in the rate tool by CirnoTheUwU

Using this for the website - https://www.w3schools.com/w3css/default.asp (w3.css)