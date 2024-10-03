# Finding Your Public and Private IP Address

The internet works like a giant network of connected computers. Your computer needs an address to communicate with others online, and there are two main types:

* **Public IP Address:** This unique identifier, assigned by your internet service provider (ISP), acts like your house address on the internet. Websites and services use it to find your computer.
* **Private IP Address:** This address is used within your local network, like a street address within your neighborhood. Other devices connected to your network (like your phone or printer) have private IP addresses.

## Why Cloud Security Engineers know this? 
* **Public IPs** are used to connect your systems to the outside world, making them vulnerable if not properly secured.
* **Private IPs** are used for internal network communications and help keep your sensitive resources isolated.
Understanding and managing both public and private IPs is crucial in cloud security engineering to ensure secure, controlled access and communications between systems while minimizing exposure to external threats.

### Finding Your Public and Private IP Address

**Windows:**

**1. Open Command Prompt:** Press the _**Windows key + R**_, type _**cmd**_, and press _**Enter**_.  

**2. Use ipconfig:** Type _**ipconfig**_ and press _**Enter**_. Look for 'IPv4 Address' under'Wi-Fi' or 'Ethernet'. This is your _private IP_ address.

**3. Open Command Prompt. Type:** _**nslookup myip.opendns.com resolver1.opendns.com**_
Your public IP will appear under 'Address'.

### Finding Your Public IP with Linux/macOS:  

**1. Open Terminal:**
* **Linux:** Locate Terminal in your applications menu.
* **macOS:** Open Spotlight search _**(Cmd + Space)**_, type _**Terminal**_, and press _**Enter**_.

**2.** type _**hostname -I**_ This will show your private IP address.

**3.** Type _**curl ifconfig.me**_ and press _**Enter**_. The response displayed is your public IP address. This command sends a request to a web service that reveals the _public IP_ of the incoming request.

Now you know how to unveil your public IP address, a vital piece of information for various online interactions!


