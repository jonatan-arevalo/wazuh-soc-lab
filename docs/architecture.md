# Architecture

## Overview

The lab consists of one Wazuh server and two monitored Windows endpoints.

## Components

### WAZUH

- Ubuntu Server 24.04
- Wazuh Manager
- Wazuh Dashboard

### DC01

- Windows Server 2022
- Active Directory
- DNS Server
- Wazuh Agent

### CLIENT01

- Windows 11
- Domain Joined
- Wazuh Agent

## Network

LABNET

192.168.10.0/24

WAZUH      192.168.10.50
DC01       192.168.10.10
CLIENT01   192.168.10.20
