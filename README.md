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

<h2>Step 6(a): Navigate to File Location & Re-Attempt</h2>

I began by identifying where I was in the Terminal, using pwd:
<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/96219bdd-9074-4174-8ab4-9839f9c76a09)
<br />
<br />

Thereafter, I navigated to the desired folder; in this case, it was the Downloads folder, using cd Downloads:<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/abe04ffc-be27-431e-977a-098115637ddb)
<br />
<br />

Next, I confirmed that I was in the desired folder, using pwd:
<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/0cda3b59-5369-41a2-aaf8-38737e113f8f)
<br />
<br />

Before continuing, I wanted to make certain that I had the desired file in this Folder location; I listed the files in the Folder using ls:
<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/ba70e01c-3053-4959-a9f9-9995ea3afdfa)
<br />
<br />

Now, I'm executing the command again and hoping for a different result:
<br />
<br />

![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/453c096f-871d-4aeb-a326-223083299523)
<br />
<br />

RESULT: SUCCESS!  I've unlocked progress and achieved a different result.
<br />
<br />
![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/74058cf8-075b-4d7d-85f1-311306b7b559)
<br />
<br />

<h2>Step 7: Refresh TryHackMe to Confirm Connection</h2>
<br />
<br />

Attempted to refresh in 2 ways to identify whether the connection was successful -- <br />
<br />
![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/23ddf77a-7aef-4bac-a84a-db9d5d29faae)
<br /> 
<br />
NOTE: NOT SUCCESSFUL!  The "Not connected" red indicator did not change nor otherwise indicate a connection was made.
<br />
<br />
I have extra language below the "Initialization Sequence Completed" line -- more language than just beyond what was seen in a tutorial YouTube Video [Click Here to See What I'm Following Along With:](https://youtu.be/1Z5CqWS6Les?si=T6GMi--laFYfU0J1&t=61)
<br />
<br />
![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/c5c0275e-29d3-4765-9d54-c8ef34826940)
<br />
<br />
<h2>Step 7(a): I feel stuck again</h2>

I'm consistently getting the same output, without the ability to connect to TryHackMe via OpenVPN... <br />
<br />
I'm getting this same error regardless of selecting East or West USA VPN Servers:<br />
<br />
![image](https://github.com/reachchrisyoung/tryhackme-OpenVPN-connecting-with-kali-linux/assets/104402775/5da972ed-abad-4496-914c-d28c0aec96b5)
<br />
<br />
Copying and pasting sections of the code to explore troubleshooting -- up to and including adding "cipher AES-256-CBC" to the downloaded file continues to not make any influence on the various files downloaded (and still no successful connection thus far with TryHackMe). <br />
<br />


<br />
<br />





