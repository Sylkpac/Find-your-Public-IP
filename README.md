## Finding Your Public IP Address

The internet works like a giant network of connected computers. Your computer needs an address to communicate with others online, and there are two main types:

* **Public IP Address:** This unique identifier, assigned by your internet service provider (ISP), acts like your house address on the internet. Websites and services use it to find your computer.
* **Private IP Address:** This address is used within your local network, like a street address within your neighborhood. Other devices connected to your network (like your phone or printer) have private IP addresses.

## Why Cloud Security Engineers know this? 
* **Public IPs** are used to connect your systems to the outside world, making them vulnerable if not properly secured.
* **Private IPs** are used for internal network communications and help keep your sensitive resources isolated.
Understanding and managing both public and private IPs is crucial in cloud security engineering to ensure secure, controlled access and communications between systems while minimizing exposure to external threats.

### Finding Your Public IP Address

Here's how to uncover your public IP address on different operating systems:

**Windows:**

**1. Open Command Prompt:** Press the _**Windows key + R**_, type _**cmd**_, and press _**Enter**_.  

**2. Use ipconfig:** Type _**ipconfig**_ and press _**Enter**_. Look for "IPv4 Address" under your 'network adapter'. This is your private IP address, not the public one.

### Finding Your Public IP with Linux/macOS:  

**1. Open Terminal:**
* **Linux:** Locate Terminal in your applications menu.
* **macOS:** Open Spotlight search (Cmd + Space), type Terminal, and press _**Enter**_.

**2. Use curl:** Type _**curl ifconfig.me**_ and press _**Enter**_. The response displayed is your public IP address. This command sends a request to a web service that reveals the _public IP_ of the incoming request.

## Private IP Note:
The command ipconfig getifaddr en0 is specific to macOS and might not be applicable on all systems. It's generally recommended to stick with curl ifconfig.me for a simpler and more universal approach to finding your public IP address.
Now you know how to unveil your public IP address, 


