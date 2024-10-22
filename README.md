# Please use this [website](https://whysoooofurious.netlify.app) if not using it already!
# New DNS redirect method is up and working

## Introduction
Hello and welcome to my guide on how to sideload on Apple Devices!

Some of the advantages with using this method:
- Free!
- No PC!
- No App Limits!
- On Device Signing!
- No Privacy Concerns!
- Easy to Setup and use!
- Takes 5 Minutes to Setup!

The only disadvantage I can think of is: No VPN support at all, unless you're making your own DNS.

If you are hesitant of the WhySooooFurious Configuration Profile, open it up on a PC using iMazing or Apple Configurator!

If you have any issues, requests or ideas please make an issue here on GitHub.

## Scarlet, Feather and other sideloaders
The DNS is compatible with all services as long as they rely on enterprise certificates to install.

Feather is also available to download and the steps should be similar as ESign's.

Follow Part 1 and 2 of my guide to install the WSF Configuration Profile for these services.

You do not need to follow Part 3, 4 and 5 as these install and setup ESign itself.

## How does this method work?
By using leaked business enterprise certificates, We can sign apps using their credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate, the WhySooooFurious Configuration Profile blocks Apple servers from contacting your device about the revoked certificate which in turn lets you use the apps for however long as you'd like.

---

## Before we start
- This might not work for you if you've been using services such as Scarlet/Feather/Esign before as the certificates might be revoked!
- If you are revoked you will need to follow this [guide](#revoked)
- This will work as long as you read and do all of the steps required
- WhySooooFurious = WSF

---

## Compatibility
This should work for all iOS and iPadOS devices on the latest versions

Beta versions will work but *may* become revoked around the 1-2 week mark. It is better to be on a release version!

Versions that might not be supported are below iOS 12, iPadOS 13

---

## Ultimate Sideloading Guide

### Part [1/4] Installing the Configuration Profile
1. Go down to [Downloads](#downloads) and click on the link, then Configuration Profiles and then select WSF's Configuration Profile
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. The DNS should now automatically be enabled, this also installs a Web Clip for easy access to my website (someone please make me a logo lol)
5. Continue onto [Part 2](#part-24-installing-esign) if you want to install ESign

### Part [2/4] Installing ESign
1. Go down to [Downloads](#downloads) and click on the link, then click on Downloads, then ESign and choose any link
3. Click on install once the popup comes up
4. Open settings and go to General > VPN & Device Management > (should show the ESign app under the link you picked back in Step 1.)
5. Click on Trust at the top then click on allow, after this your device might need to be restarted
6. If your device was restarted, swipe up and click on install profile
7. ESign should now be on your home screen, fully functional
8. Continue onto [Part 4](#part-34-setting-up-esign) to setup ESign
 
### Part [3/4] Setting up ESign
1. Open ESign and accept the agreements
2. Go into Settings and click on Get Device UDID
3. Select allow and then you should be redirected to settings
4. After opening settings go to General > VPN & Device Management
5. Install the Query Device UDID profile
6. You should be redirected back to ESign
7. Now go down to [Downloads](#downloads), click the link and then go into certificates, download the ESign certificates, and the Certificates should be downloaded
8. Extract the ESign-Certificates.zip and select the one that corresponds to the ESign app in VPN & Device Management
9. Go into ESign Settings and click on Import Resources
10. Find and select the certificate you selected back in Step 8 and click on Import
11. Now go over to AppStore in ESign and click on App Source
12. Click on the plus icon and paste in the sources from [here](#esign-sources), click on add all
13. You now have setup ESign with all sources ready to install apps
14. Continue onto [Part 4](#part-44-using-esign)

### Part [4/4] Using ESign
1. Download any app using the AppStore in ESign or you can import your own .ipa using Import Resource in which case you can skip to step 4
2. Check the download status in the Download tab if downloading from the ESign AppStore
3. Click on the downloaded IPA and select Import App Library
4. Your app should now be visible in the Unsigned Apps tab, select unsigned or signed by selecting the bar on top of ESign
5. Click on the app and select Signature
6. You can change your app and edit it here
7. Select Signature and ESign should sign the app using the certificate you selected before
8. There might be red text saying this certificate is revoked, this is normal! Click on the blue button saying Install, then click Install on the prompt again
9. The app should be on your homescreen now
10. Open settings and go to General > VPN & Device Management
11. Select the app you installed and click on Trust
12. Click on Allow, after this your device might need to be restarted
13. If your device was restarted, swipe up and click on Install Profile
14. The app should now be on your home screen, fully functional
15. Now read the [Post Install Notes](#post-install-notes) carefully

### Post Install Notes
- You cannot use a VPN, unless you have made your own DNS and are following the VPN [guide](#using-a-vpn)
- You must never disable the DNS!
- Don't install a lot of apps at once!
- Don't install Safari extensions!
- Go into Airplane Mode if you're switching DNS
- Don't use Cowabunga otherwise the DNS will disappear! There is a [workaround](#using-nugget-or-cowabunga)
- Don't use Nugget otherwise the DNS will disappear! There is a [workaround](#using-nugget-or-cowabunga)
- If you have made your own DNS, NextDNS has a limit of 300000 queries per month! If you reach this limit, you will be revoked! It is recommended to make multiple accounts and making more profiles or using the WSF Configuration Profile

Not following the above guidelines will make your apps revoked!

## Troubleshooting

### Unable to Install? Integrity could not be verified?

You need to follow this [guide](#revoked)

---

## Downloads

### [All Downloads!](https://whysoooofurious.netlify.app/downloads)

---

## ESign Sources
My sources for ESign                    
###
    source[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]

---

## Questions/Answers

-

Q - Won't a VPN bypass the DNS and revoke my apps?

A - If you have made your own DNS, it is compatible. If you want to use a VPN, Use this [guide](#using-a-vpn).

-

Q - Will a restart bypass the DNS and revoke my apps?

A - Simple answer, No.

-

Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?

A - No, Those listed services use developer signing instead of Enterprise signing so they are fine to use alongside! You might need to edit SideStore's WireGuard and edit the DNS inside to match your NextDNS settings in this [guide](#using-a-vpn), although this isn't compatible with the WSF Configuration Profile.

-

---

## Miscellaneous Guides

### Making your own DNS
Depreciated, I recommend installing the WhySooooFurious DNS Blocker now, although this will still work!

#### Part [1/2] Making your DNS
1. Go to this [website](https://shorturl.at/hfr4V) and make your own account
2. Go to the Denylist tab and add the following domains:
   
   vpp.itunes.apple.com
   
   appattest.apple.com
   
   certs.apple.com
   
   crl.apple.com
   
   valid.apple.com
   
   ocsp2.apple.com
   
   ocsp.apple.com

3. Go to the Allowlist tab and add the following domains:
   
   app.localhost.direct

   register.appattest.apple.com

4. Go into the Privcy tab and click on the cross next to the NextDNS Ads and Trackers

5. Continue onto [Part 2](#part-22-installing-the-dns) to finish the DNS installation

### Part [2/2] Installing the DNS
1. Go to the Setup tab, find and click on the hyperlinked apple.nextdns.io which should redirect you to the NextDNS Profile website
2. Select the profile you edited
3. Click on More Options
4. Then Enable the Trust NextDNS Root CA and Bootstrap IPs toggle
5. Click on Download, and the profile should be imported into settings automatically
6. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
7. The DNS should now automatically be enabled, Do not change the DNS settings to automatic otherwise your apps will get revoked!
8. Now, go back and then go to General > About > Certificate Trust Settings
9. Enable Full Trust for the NextDNS Root Certificate, if Full Trust does not show you cannot use VPNs at all
10. Continue onto [Part 2](#part-35-installing-esign) of the main guide if you want to install ESign


### Using a VPN 
This will not work with the WSF Configuration Profile!

So you want to use a VPN with the DNS blocker, Follow the steps below and you should be able to use your VPN normally and on-demand, I still do not recommend using a VPN with the DNS, You should know how to configure your VPN's DNS server yourself as there are different steps for each VPN app.

#### Method 1
1. Go to this [website](https://shorturl.at/hfr4V)
2. You should be at the Setup tab, Find your 2 DNS servers under Linked IPs
3. Insert either one or both if you can in your VPN's DNS configuration, if you can't find that option you likely can't use that VPN with the DNS

### Revoked?
So you've gotten yourself revoked, Follow the methods listed below and you should be unrevoked.

Method 1 should work
Method 2 will completely reset your device and will definitely work

You must not use your backups with Method 2

#### Method 1
1. Remove the DNS and uninstall ESign
2. Back up your device, here is a [guide](https://shorturl.at/fnR5J)
3. After backing up, reset your device, here is a [guide](https://shorturl.at/JKnhG), iTunes restore in Recovery Mode or DFU mode is heavily recommended
5. Now if you have an iCloud backup you should be prompted to restore from your backup after logging in to your Apple ID, if you have a local backup all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
6. Then follow Part 1 of the guide to prevent revokes

#### Method 2
1. Remove the DNS and uninstall ESign
2. Follow this [guide](https://shorturl.at/JKnhG)
3. Then follow Part 1 of the guide to prevent revokes

### Using Nugget or Cowabunga
Profiles disappear when using Nugget and Cowabunga. This can easily be bypassed but is a bit annoying as it requires a PC.

#### Fix for macOS:
Only the macOS version of Nugget is compatible with this guide. Not the app itself! You must always follow this guide when wanting to use Nugget and Cowabunga!

##### Part [1/2] Using Nugget/Cowabunga
1. Forget all WiFi networks and disable Cellular Networks and put your device in Airplane Mode.
2. Remove the WSF Configuration Profile you have or DNS profiles. Don't delete your installed apps.
3. Now you can use Nugget or Cowabunga as you please.
4. Continue onto the [Part 2](#part-22-installing-the-dns)


##### Part [2/2] Installing the WSF Configuration Profile
1. Go down to [Downloads](#downloads) and click on the link, then Configuration Profiles and then select the WSF Configuration Profile
2. Click on Download, and the profile should be downloaded to your Downloads folder
6. Download Apple Configurator from the Mac App Store
7. Make sure your device is connected to your macOS device
8. Input your password on your device if it requires it
9. Find your device, right click and select Add > Profiles
10. Select the WSF Configuration Profile and then it should be installed and activated automatically
