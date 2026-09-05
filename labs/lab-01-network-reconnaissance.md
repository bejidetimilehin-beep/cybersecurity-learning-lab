# 🧪 Lab 01 — Network Reconnaissance

## 🎯 Objective

Learn how to gather basic information about a network using built-in Windows networking commands.

## 🖥️ Environment

- Operating System: Windows 11
- Tools: Windows Command Prompt
- Target: My own computer/network

## 🔍 Commands

### 1. ipconfig

Displays information about the computer's network interfaces.

```cmd
ipconfig

## 🧪 Practical Results

### ipconfig
Successfully identified the local IPv4 configuration, subnet mask, and default gateway.

### ping 127.0.0.1
Tested the local loopback interface.

### ping gateway
Tested connectivity between the computer and its network gateway.

### ping example.com
Tested DNS resolution and network connectivity.

### tracert example.com
Observed the network path and intermediate hops toward the destination.

### nslookup example.com
Used DNS lookup to examine the IP address associated with a domain.

## 🧠 Key Lesson

Network reconnaissance begins with understanding how a system communicates.
Before investigating suspicious network activity, an incident responder needs to understand IP addresses, gateways, DNS, and network paths.
