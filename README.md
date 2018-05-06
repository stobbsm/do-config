# do-config
Scripts to provision servers on digital ocean. Meant to speed up deployment and ensure things work consistently.

## Description
Facing the fact that I will be moving most of my clients to their own DigitalOcean droplets in the near future, I need a way to consistently provision those droplets.

This script will generate a bash script that can be used by DigitalOcean's 'User Data' function to automatically provision a new server with the required software, as well as download the needed web application and configure nginx (or apache, if the client prefers).

Feel free to modify the script as you need, and send me any pull requests. If this tool helps, it would be nice to know that as well.

## Planned features
- [ ] Provide a package list to have the user-data entry set when provisioning a new server.
- [ ] Install provided ssh pubkeys.
- [ ] Install configuration management tools (puppet, ansible, etc. Haven't decided what I want to use yet).
- [ ] Provision servers on accounts that are specified, when the user is added to the "team" of said client.

## Disclaimer
This software is licensed under the GPL-3.0 license. If it's useful, great, if it breaks something, I am in no way responsible.