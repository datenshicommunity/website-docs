---
title: "Installing the certificate and Hosts manually"
old_id: 12
---
If you're having troubles connecting to Datenshi or the switcher doesn't install the certificate properly, you can try installing it manually.

### Instructions
- First, download the certificate [by clicking here](https://datenshi.xyz/static/cert.crt)
- Then, open **cert.crt**
- Click **Install certificate...**
- Click **Next**
- Select **Place all certificates in the following store** (second option), then click **Browse...**
- A new window will pop up, select **Trusted root certification authorities** and click **Ok**
- Click **Next**
- Click **Finish**

### How to test the certificate
Once you've installed the certificate, you can test whether it was successfully installed by following these steps:  

- Open the server switcher and click on **Inspect**.  
- Wait a few seconds and all the labels in the "Server connection" section, on the right, should become green and report "OK" (like [this](http://oi66.tinypic.com/2v9q90p.jpg)). If so, you should be able to connect to Datenshi.  
- If you get **CERT ERROR**, the certificate has not been installed successfully. **Follow the instructions below.**  
- If you get **"..."**, you're not connected to Datenshi. Close the inspect window, click on **Switch to Datenshi** and try again.  

### If everything else fails...
...you can try to remove all existing Datenshi certificates and install the certificate again. Follow these steps:

- Press **Win+R**  
- Type `mmc certmgr.msc` in the run box and press **enter** to open the Certificate Manager  
- Select **Trusted root certification authorities** on the left  
- Select **Certificates** on the right  
- You should see some **[Datenshi](http://y.zxq.co/bbyxev.png)** and some **\*.ppy.sh** entries in the list. Select them, **right click** and click on **Delete**  
- Select all the positive options (Ok/Yes etc)  
- Restart the switcher, click on **Inspect**, then choose **Install certificate**, then **Yes**  
**If the inspect dialog is fine but you still can't connect to Datenshi from the game client, try running osu! as administrator**.

### Installing Certificate Manually with Image
...if you still dont understand, you can view this for tutorial installing certificate

### You need download the certificates first

- [Clickhere](https://old.datenshi.xyz/cert.crt)

### Then open or right click and Install Certificates

- ![step1](https://cdn.discordapp.com/attachments/698957154115125381/699480445208756224/unknown.png)

- ![step2](https://cdn.discordapp.com/attachments/698957154115125381/699480570375307344/unknown.png)

### Click on the Local Machine and press next

- ![step3](https://cdn.discordapp.com/attachments/698957154115125381/699480736486391928/unknown.png)

### Click Browse first, find **Trusted Root Certification Authorities** and then click OK > Next

- ![step4](https://cdn.discordapp.com/attachments/698957154115125381/699480847769927720/unknown.png)

### Next

- ![step5](https://cdn.discordapp.com/attachments/698957154115125381/699480879063629886/unknown.png)

### Finish

- ![step6](https://cdn.discordapp.com/attachments/698957154115125381/699480924848652308/unknown.png)


### Installing Hosts Manually with Image
...This is the best tutorial i made for you if you can't read LOL just kidding.

### You need download the Hosts file first or Copy-paste
- [Clickhere](https://datenshi.xyz/static/hosts.txt)
- ![step1](https://cdn.discordapp.com/attachments/700239763919339601/704337152229769217/unknown.png)

### Then open **Notepad** as administrator
- ![step2](https://cdn.discordapp.com/attachments/700239763919339601/704337857338147381/unknown.png)

### Find your `hosts` file in `C:Windows/system32/drivers/etc`
- ![step3](https://cdn.discordapp.com/attachments/700239763919339601/704337981514973274/unknown.png)

### Add the text you copy before to this hosts like this
- ![step4](https://cdn.discordapp.com/attachments/700239763919339601/704338211228614767/unknown.png)

### and then `Save` try to log-in in to the game!
..Enjoy and happy farming!