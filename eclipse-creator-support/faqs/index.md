---
title: FAQs
menu_order: 4
taxonomy:
    doc_category: eclipse-creator-support
---

# FAQs

## Security

### Is client SOP/protocol data stored in the cloud?

No, all SOP and protocol data is store locally under JSON files and within the clients own personal network.

### Does any client information leave the local network?

The only outgoing request outside the local network will be the license validation request which contains no business/personal identifiable data.

### Where is the SOP/protocol data and collection files written to?

Eclipse Creator desktop app writes your SOP data to the local disk only and never sends it out to any external server. You can find the data in JSON format in the installation directory. In addition, you can choose to store your SOP JSON files in a secondary location for ease of organisation and distribution.

### Are users able to distribute SOPs and collections if they wish?

SOPs/protocols within collections can be exported as a .json file. Following this they can be distributed and shared as an attached file.

## Network

### Eclipse headset app and Eclipse SOP Creator desktop app are not syncing.

Ensure both are connected to the same network. Both apps will show they are connected by symbols outlined in this document. If connected over the same network there may be connection stability issues or blocks to prevent the connection of new devices. In this scenario, try connecting via a home network. If you are continuing to have issues contact us [here](https://fourplus.co.uk/contact-us-fourplus/).

### Error code in headset: Failed to sync, defaulting to cached SOP data.

Headset should be reconnected to the same network as the Eclipse Creator desktop app. If the error code continues to appear, ensure you are on the most current version of the desktop app or update it.

### I am connected to the institution's network but headset and desktop are not syncing:  Failed to sync and load cached data, loaded default SOP data.

Check you are connected to the **same** network on **both** the desktop and headset apps. Alternatively, if you are using a network with strict security blockers (e.g. Eduroam) it may be worth speaking to IT about the network blocking synchronisation. If you require information on the software architecture to see how the network may be blocking the devices, contact FourPlus admin team directly.

### I am having issues syncing the desktop and headset when using a university or company computer.

Check with the IT department or within the PC settings that the computer security is not blocking the headset synchronisation.

### What is the best type of network to use for syncing the headset to the desktop app?

It is best to use a home network or a mobile hotspot/ broadband dongle as these should not block the synchronisation between headset and desktop application. There is a possibility that strict networks (e.g. Eduroam) may block the synchronisation.

### Do you need a network connection to receive desktop app and headset app updates?

Yes, you will need to connect to wifi on both devices to receive app updates.

### I accepted the invite to the beta channel but the app didn't appear in headset.

Try using a private browsing session to access the invite link and accept through that. Allow some time for the servers to process the invite.

### Do you need a network connection to perform the SOPs/protocols that are already synced to headset?

No you do not. However, you cannot edit SOPs and sync the changes to headset without a network connection.

### How do I know my headset and PC are connected to the same network and syncing?

There is a health icon in the top right of Eclipse SOP Creator desktop app which lights green upon an active connection. Additionally in headset the connection icon on the SOP selection interface will do the same.

## Headsets

### What types of headsets can I install the VR applications onto?

Meta (Oculus) Quest 2, 3 and Pro.

### As an organization with access to multiple headsets, what is the best way of downloading and managing applications onto this?

We recommend Meta for Business or the Headset Management system ArborXR. These both come with their unique differences and perks but overall allow you to manage your fleet of Meta Quests. Take control of your fleet, set up headsets quickly, configure settings & deploy apps. These do however come with a fee. Find out more at [ArborXR](https://arborxr.com/) and [Meta](https://forwork.meta.com/gb/meta-horizon-managed-solutions/).

### What are all the options for fleet headset management?

1. Use a different email per headset and download our app freely from the store on separate individual accounts

2. Use the official Meta MDM through MEta for Business and sign up as an organization. This allows access to the official MDM features through a single organization account. [Link Here](https://forwork.meta.com/gb/meta-horizon-managed-solutions/)

3. Use an external MDM like ArbourXR to manage your apps through a single external organization account. [Link Here](https://arborxr.com/supported-devices/meta)

4. Download our apps as unofficial APK builds and install them manually on every headset via developer mode and ADB (Android Debugging Bridge). This way you won't receive automatic updates and have to redo the process every time we release a new version.

### What are the steps for headset set up and app installation as a new customer?

1. Create or apply an email account to create an account with the Meta Store. 
2. Prior to doing this we recommend looking into Meta for Business. 
3. Login to your Meta account on PC, the mobile app and headset.
4. Download the apps from the Meta Horizon store.
5. Enter your unique license key to experience the software.

### Where can I find my license key for installation?

License keys are unique to each customer and will be sent via email. Under the license agreement these should not be shared outside of the paying organization. If you have lost of forgotten your license key, contact our <admin@fourplus.co.uk> or sales team <sales@fourplus.co.uk> to receive it.

### I need more assistance with my Meta headset or Meta account.

If you are having technical issues unrelated to the FourPlus applications and related to Meta then contact their help and advice team directly or visit a forum.

### How do I make use of the Meta Quests features e.g. casting?

Follow this [link](https://www.meta.com/en-gb/help/quest/562419235163295/) for headset features support.

## Applications

### Can you toggle pass-through on and off for the FourPlus software?

No you cannot toggle pass-through with the current applications because they are either 100% VR or 100% MR/AR.

### What size play/floor space is required for the FourPlus applications?

Both applications require at least a 2 x 2m floor space to be experienced safely and with full effectiveness.

### Eclipse Creator - When performing group training, my virtual laboratory space keeps intersecting with the walls/other users areas.

Try repositioning your space using the Reset Orientation option via the hand menu in headset. Alternatively, quit the games and redraw your roomscale boundaries to roughly 2.5m x 2.5m of space or more, ensuring multiple user play spaces do not overlap.