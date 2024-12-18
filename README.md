# **Custom CaptiveFlask Plugin**

## **Overview**  
This project involves creating a **Custom CaptiveFlask Plugin** designed for educational purposes using **WiFiPumpkin3**. The plugin mimics a target organization's login page, captures credentials, and ensures internet access post-capture. This plugin was created as part of an assessment for understanding Captive Portal design and log capture processes.

---

## **Features**  
- **Target Organization**: [Organization Name] *(to be specified by the user)*  
- Mimics the organization's **login page** for staff, employees, or customers.  
- Captures user-entered credentials securely.  
- Provides **internet access** after credential submission, simulating a real Captive Portal.  

---

## **Files Included**  
- **custom/**: Directory containing essential files for the CaptiveFlask plugin.  
- **custom.py**: The main plugin script for WiFiPumpkin3.  

---

## **Requirements**  
- **Kali Linux** with **WiFiPumpkin3** installed.  
- Compatible **USB Wi-Fi adapter** attached to the Kali VM.  
- Python 3.x environment.  

---

## **Installation Steps**  

1. **Launch WiFiPumpkin3**:  
   ```bash
   sudo wifipumpkin3

Install the Plugin
Replace <path_to_plugin_zip_file> with the actual file path.
> install plugin_name path_to_plugin_zip_file  

Restart WiFiPumpkin3  
Restart the tool to ensure the plugin is active.

Activate CaptiveFlask Proxy
> set proxy captiveflask  

Verify Plugin Activation  
Check the list of available proxies and ensure the plugin is active.
> proxies  

Activate the Custom Plugin
> set captiveflask.custom true  

Test the Plugin  
Connect a device to the captive portal and verify the following:
- The web page closely mimics the target login page.
- Credentials are captured successfully.
- Internet access is provided after credential capture.

Testing and Documentation  
Document the process followed to install, activate, and test the plugin.  
Include screenshots of the plugin in action:  
- Web page mimicry.  
- Captured credentials.  
- Internet access verification.

Disclaimer  
This project is intended strictly for educational purposes and must not be used for any malicious activities.
