# Akamai EdgeGrid Authorization for Insomnia REST Client

!!! DEPRECATED !!! Use the actively maintained plugin https://github.com/rveldhuizen/insomnia-plugin-akamai-edgegrid instead.


This is a plugin for the [Insomnia REST Client](https://insomnia.rest/)

Akamai EdgeGrid Authorization: https://developer.akamai.com/legacy/introduction/Client_Auth.html

## Install

Go to Preferences->Plugins, install `insomnia-plugin-edgegrid`

## How to use

1. Setup your environment to include your .edgerc configuration

![Screenshot](https://raw.githubusercontent.com/schwabix/insomnia-plugin-edgegrid/master/insomnia-environment.png)

2. Add a "dummy" header EdgeAuthorization - this triggers the generation of the Akamai Authorization header

![Screenshot](https://raw.githubusercontent.com/schwabix/insomnia-plugin-edgegrid/master/edgegrid-header.png)
