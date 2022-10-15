---
layout: page
title: nebulosum
permalink: devices/nebulosum/
menubar_toc: true
toc_title: Navigation
---

{% include notification.html message="This is a concept build, nothing is finalised yet." 
status="is-danger" 
icon="fas fa-exclamation-triangle" %}

This is the self-hosted machine that I plan to build, which will be running [Fedora Server](https://getfedora.org/en/server/).

## Services

The services that `nebulosum` will host for the local devices to utilise.

### Jellyfin

[Jellyfin](https://jellyfin.org) will be used as a local streaming service, having a web interface and app on mobile devices.
Currently, there exists an error with the Jellyfin systemctl service for Fedora, thus a Docker image is preferred at this point. 

### Home Assistant

[Home Assistant](https://home-assistant.io) will be used to automate and control home devices, such as lights.
If add-ons is a requirement, a vm will be a preferred for installation, else a Docker image.

### Minecraft Server Manager

[MSM](https://msmhq.com) will be used to manage several Minecraft server instances.

## Specifications

The specifications are still undecided.
