# List of services

This is a comprehensive list of services added to `nebulusom`, which is running [Fedora Server](https://getfedora.org/en/server/).

## Jellyfin

[Jellyfin](https://jellyfin.org) will be used as a local streaming service, having a web interface and app on mobile devices.
Currently, there exists an error with the Jellyfin systemctl service for Fedora, thus a Docker image is preferred at this point. 

## Home Assistant

[Home Assistant](https://home-assistant.io) will be used to automate and control home devices, such as lights.
If add-ons is a requirement, a vm will be a preferred for installation, else a Docker image.

## Minecraft Server Manager

[MSM](https://msmhq.com) will be used to manage several Minecraft server instances.
