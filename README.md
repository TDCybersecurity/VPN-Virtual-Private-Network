# VPN-Virtual-Private-Network
**(VPN) Virtual Private Networks: Set up and Usage of Proton VPN**

A VPN, or Virtual Private Network, is a service that creates a **secure** and **private** connection to the internet. It acts like a **private tunnel**, _hiding your online activities from others_ and making your internet use more **secure** and **anonymous**.

**Benefits of using a VPN**

- **Privacy Protection:** Hides your IP Address and online activities from hackers, advertisers, and government surveillance.
- **Security:** Encrypts your internet connection, protecting your data from being intercepted by cybercriminals, especially on public Wi-Fi.
- **Access to Restricted Content:** Allows you to bypass geographical restrictions to access websites, streaming services, and content that may be blocked in your location.
- **Safe Browsing:** Reduces the risk of malware and phishing attacks by blocking malicious websites.
- **Anonymity:** Makes your online actions harder to trace back to you, enhancing your anonymity online.

1 In your browser type in **whatismyipaddress.com**
![VPN1 WhatismyIPAddress](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/5276774c-118e-4cc7-a6c8-de72d421239a)
![](RackMultipart20240518-1-nonpfk_html_9d52d1543893b735.jpg)

1.1 Take note of the information.

| **IPv4**| **Internet Service Provider**| **City**| **Region**| **Country**|
| --- | --- | --- | --- | --- |
| 100.2.XX.XXX | Verizon | New York City | New York | United States |

2 Create a **(VM) Virtual Machine** with **(no VPN)** in **Azure** and connect to your PC using **(RDC) Remote Desktop Protocol**.

2.1 Open a browser and enter **portal.azure.com.**
![VPN2 portalazurecom](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/7ced96bd-1214-4ba5-9936-eba19500153a)


2.2 Click on Virtual machines. Click on **Create** and select **Azure virtual machine** from the drop-down menu. ![]![VPN3 select Azure virtual machine](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/c9a5a58c-df82-485c-a50a-8eedd3fc142e)

2.3 **Create a virtual machine** by clicking on **Create new** under the Resource group\* box. Name it **ChicagoPD** and click **OK.**

![VPN4 Create new](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/52247f8d-2d18-4630-99c9-190d907a12b3)

![VPN5 Name ChicagoPD](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/75b1cc84-f9f7-46be-af71-76155dafc549)

2.4 Type in **Instance details**:

| **Virtual machine name\***| **Region\***| **Availability Option**| **Security Type**| **Image\***| **Size\***| **Username\***| **Password\***|
| --- | --- | --- | --- | --- | --- | --- | --- |
| ChicagoPD | (Asia Pacific) Southeast Asia | No infrastructure redundancy required | Standard | Windows 10 Pro, version 22H2 -x64 Gen2 | Standard\_D4s\_v3 – 4 vcpus, 16 GiB memory ($182.50/month) | **Terry**| **Berry1234567**|

![VPN6 Create a VM1](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/785597b7-48d5-4b58-b5c4-f28d63d0ab9f)
![VPN7 Create a VM2](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/aab7cba8-9eac-4883-b0b4-fc81924d33f2)


2.5  I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.

2.6 **Review + Create** then wait for ****  **Validation passed** then click on **Create.**

2.7 **Deployment is in progress,** your resources are being created. Afterwards it will say ****** Your deployment is complete**.

![VPN8 Your deployment is complete](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/b302010a-b22f-4aea-80a0-8cc2b3ff0b2e)

2.8 Click **Go to resource.** Copy and Paste the Public IP Address: **52.163.223.175**** **

**3 Establish a (RDC) Remote Desktop Connection**

3.1 Go to the Windows Start Menu Search bar and enter **Remote Desktop Connection**

3.2 Paste **Public IP Address**** 52.163.223.175 **into the** Computer **field and click on** Connect.**

![](RackMultipart20240518-1-nonpfk_html_718eccb0452943cb.png)

3.3 Enter your credentials. Click on **More choices** the **Use a different account.**

3.4 Enter **User name**** Terry **and** Password ****Berry 1234567** and click on **OK.** RDC radio box pop-up opens. Click on **Yes**

3.5 Your Virtual Machine opens, note the IP Address up top.

3.6 **Choose privacy settings for your device**. Select NO for all of them.

![VPN10VMIPaddressandPrivacysettings](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/f689a3d3-ba0a-4f5e-9f31-d6156ada53c2)

3.7 They are Location, Diagnostic data, Tailored experiences, Find my device, Inking &typing, and Advertising ID Click **Accept**

3.8 Ignore installation set-up guide and then open **Microsoft Edge.** Click on **Start without your data.** Uncheck **Bring over data.**

3.9Click on **Continue without this data.** Uncheck **Make you Microsoft experience more useful to you.**

3.9.1 **Confirm and start browsing****.**

3.9.2 Type **whatismyipaddress.com** in the **Edge browser.** Note the results are different from your PC
![VPN11 VM IPAddress in Singapore](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/13902ea6-5a1d-446e-a152-4f8209ce7641)


| **IPv4**| **Internet Service Provider**| **City**| **Region**| **Country**|
| --- | --- | --- | --- | --- |
| 52.163.223.175 | Microsoft | Singapore | Singapore | Singapore |

![](RackMultipart20240518-1-nonpfk_html_c5fdac510b3d13a7.png)

**4 Access**  **Proton VPN**  **inside your PC so that you can download and install it in the VM which is in Singapore.**

4.1 Google Proton VPN. Click on **Create account.**
![VPN12Proton VPN](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/b2047698-d41c-4829-84c4-0c128a5c489c)

![](RackMultipart20240518-1-nonpfk_html_bde12071307f46ff.png) Click on **sign up for free.**
![VPN13 signupforfree](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/93f89246-c632-4874-a068-d3c7a92c3253)

![](RackMultipart20240518-1-nonpfk_html_7c88bcc924227c7b.png)

4.2 Enter **Email address** and click on **Start using**  **Proton VPN****. **Choose your own password** Berry1234567**

4.3 Copy the URL **account.protonvpn.com/downloads** from **your PC** and paste it **into the VM browser** to open.

4.4 Sign in using **Email address** and **Proton VPN**  **password**** Berry1234567 **. Click on** Sign in**.
![VPN13protonemail](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/f2fae347-dcab-4e84-91af-c7766f871f2e)



4.5 On Get Proton VPN for Windows click on **Download**  **Proton VPN**.
![VPN15 Proton Download](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/10ac466c-8173-4abe-819d-6118b420a4c6)


4.6 Go to **Downloads** and open the **ProtonVPN\_v3.2.11** application.
![VPN17 Install Proton VPN](https://github.com/TDCybersecurity/VPN-Virtual-Private-Network/assets/142702123/690c53db-2f6e-4109-ae2f-89325342c1fb)


4.7 Access **Proton VPN** on the **VM** and sign in using **Email** and **Password**. Click on **Sign in** enter Email

4.8 Open file and **complete installation** pop up box, with **Language**  **English**** OK **then** Next **,** Next, and Install.**

4.9 Sign in with **email** and **password**. They send a **verify** to your email. **Verify your email to continue to Proton**.

![](RackMultipart20240518-1-nonpfk_html_8a85c9da36132a4e.png)

4.9.1 Go to **Windows Search Bar** to find **Proton VPN**.

![](RackMultipart20240518-1-nonpfk_html_9f30728a177c1c36.png)

4.9.2 When get into **ProtonVPN**, where are you **CONNECTED**, what is your **IP Address**.

![](RackMultipart20240518-1-nonpfk_html_f38bb379fcc6978d.png)

|
 |
 |
 |
 |
 |
| --- | --- | --- | --- | --- |
| 138.199.21.197 | Wireguard | Japan | Japan | Japan |

4.9.3 Go back to **whatismyipaddress.com** and **refresh it** to confirm the IP Address and location.

![](RackMultipart20240518-1-nonpfk_html_4b46b0351755086a.png)

| **IPv4**| **Internet Service Provider**| **City**| **Region**| **Country**|
| --- | --- | --- | --- | --- |
| 138.199.21.197 | DataCamp Limited | Shinjuku City | Tokyo | Japan |

4.9. Browse **Netflix** to see that you are getting **Netflix in Japan** because your **Proton VPN** is in **Japan**.

![](RackMultipart20240518-1-nonpfk_html_209d6c9fcd239bc0.png)

5 Go back to your **(VM) Virtual Machine** and **DELETE all your Resources** in the Azure account to **avoid charges**.

Thank you for stopping by……..hope this improved your understanding of VPNs.
