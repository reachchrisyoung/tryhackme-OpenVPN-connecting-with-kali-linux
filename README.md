# TryHackMe OpenVPN - Connecting in Kali Linux

This write-up is a simultaneous attempt to figure out how to, and successfully document, my efforts to get started on TryHackMe by connecting to the OpenVPN.

<h2>Step 1: Navigate to File Acquisition Section</h2>

In the upper-right of the screen, I successfully produced the drop-down menu.<br />
<br />

From here, I Clicked On "Access" [SEE BELOW]: <br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/f5dbb022-6227-44d2-b87f-46530f77ab74)
<br />
<br />

<h2>Step 2: Navigate to the desired VPN Server</h2>

After navigating to the dropdown menu for VPN server collection and selecting a VPN Server closest to a given location...<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/aeec4834-e599-4de6-9fab-9e64430921e7)
<br />
<br />

<h3>Step 3: Download Configuration File/h3>

Below the dropdown menu for VPN Server is a button that reads: "Download Configuration File."  CLICK IT!<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/7b98016f-52ef-40ba-a154-446ab4aeca07)
<br />
<br />

<h4>Step 4: Confirm the File Name</h4>

It's important to know the file name of what was just downloaded -- it will be utilized in the next step.<br />
<br />

Navigate accordingly to find the name and make a mental note of it before proceeding...<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/92f08fb0-99c0-46fd-a02b-f9d859b20dea)
<br />
<br />

<h2>Step 5: Access the File</h2>

Open the Terminal in Kali Linux and type the following in:<br />
<br />

sudo openvpn [FileName].ovpn<br />
<br />

In this case...<br />
<br />

sudo openvpn tryhackmefile.ovpn<br />
<br />

NOTE: I changed the name of the file in this step to better reflect which file I'm intending to utilize; this is the same file that was downloaded from TryHackMe at this point in time, simply with a different file name going forward.
<br />
<br />

Result: If you've done the steps successfully up to this point, the Terminal should ask for your password, as show here:
<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/188062c4-b6c6-4a1d-a495-5f181aa37f28)
<br />
<br />

<h2>Step 5(a): Enter your password</h2>

Self-explanatory step; just give the Terminal your password.
<br />
<br />

Note: No photo is needed for this step.
<br />
<br />

<h2>Step 6: I'm stuck and need help...</h2>

The result is not progressing as I had anticipated, and I'm struggling to find answers online as to the next step(s) to take.<br />
<br />

Below is the error message I am receiving; the "help" feature isn't working.<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/b21bd832-772e-478b-aa49-445cb5bc3483)














