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

The services that will be hosted on the device.

### Jellyfin

[Jellyfin](https://jellyfin.org) will be used as a local streaming service, having a web interface and app on mobile devices.
Currently, there exists an error with the Jellyfin systemctl service for Fedora, thus a Docker image is preferred at this point. 

### Home Assistant

[Home Assistant](https://home-assistant.io) will be used to automate and control home devices, such as lights and electricity meter.
If add-ons is a requirement, a vm will be a preferred for installation, else a Docker image.

### Kavita

Kavita will be used for local access to digital reading, being with only through a web interface. Will be using a Docker Image for easier update.

### Minecraft Server Manager

[MSM](https://msmhq.com) will be used to manage several Minecraft server instances.

## Specifications

The specifications are still undecided.

{% include tag.html tag="Server" %}
{% include tag.html tag="Hosting" %}
{% include tag.html tag="Streaming" %}
