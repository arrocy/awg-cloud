<h1 align='center'><img alt="Arrocy logo" src="https://arrocy.com/assets/img/site/arrocy.com.png" height="75"/><br>Arrocy Whatsapp Gateway Cloud</h1>
<div align='center'>AWG-Cloud is a Frontend-Backend management tool for interacting with the WhatsApp Web API.</div>

# History
AWG-Cloud is the successor of AWG-Extended.

# Sponsor
If you'd like to financially support me, you can do so by having a `fully-managed` Arrocy Whatsapp Gateway Cloud version (same like https://arrocy.com, but with your own domain name, your own logo, and admin access). No coding or server maintenance knowledge, you just need to provide me your domain name and your logo. All maintained (bug fixes and updates) by me.<br>
You can also donate to my crypto wallet:
<h1 align='center'><img alt="Arrocy crypto" src="https://arrocy.com/bitcoin-qr.jpg" height="75"/></h1>

# Disclaimer
This project is not affiliated, associated, authorized, endorsed by, or in any way officially connected with WhatsApp or any of its subsidiaries or its affiliates.
The official WhatsApp website can be found at whatsapp.com. "WhatsApp" as well as related names, marks, emblems and images are registered trademarks of their respective owners.

The maintainers of Arrocy Whatsapp Gateway do not in any way condone the use of this application in practices that violate the Terms of Service of WhatsApp. The maintainers of this application call upon the personal responsibility of its users to use this application in a fair way, as it is intended to be used.
Use at your own discretion. Do not spam people with this. We discourage any stalkerware, bulk or automated messaging usage.

## Requirements
- CPU: min. 1
- RAM: min 1 GB
- Storage: min. 1 GB
- PHP: v8.2 - v8.4

## Install

Clone the project:
```
git clone https://github.com/arrocy/arrocy-cloud.git
```

OR just download the zip file, upload it to your web server, then extract.

## Update
It is highly recommended to delete these before you extract the new version:
- /bootstrap/cache/delete-all-files-except-gitignore
- /storage/framework/views/delete-all-files-except-gitignore
- /vendor/delete-all-files-and-folder-except-gitignore

## Warning
- This is not an update from AWG-Extended! The base-code and database are not compatible.
- This script will connect to Arrocy WG Cloud backend, and the backend will do the sending with the data sent from this script.
- You are operating the frontend with all the features, the backend just processing your messages and send them.
- Database with all information (including customers data and phonebook contacts) will be managed by you and stays in the frontend side.

## Usage
- Open url: https://my-domain.com
- Register new Super Admin account
- Documentation: https://my-domain.com/docs
- Install instruction: https://visimisi.net/documentation/137919
