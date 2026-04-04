---
layout: post
title: "How to Protect Yourself in Webex Meetings"
date: 2026-03-04
categories:
  - security
tags:
  - business
  - networking
  - privacy
---

# How to Protect Yourself in Webex Meetings
Cisco Webex Meetings is a digital platform that enables workgroups to set up a meeting and collaborate in real-time. What makes Webex meetings stand out is the diverse caliber of users it attracts. Government agencies, as well as educational institutions, are increasingly finding the platform more useful by the day.

Cisco is popular for having a thorough and disciplined approach to its user-based services. This also includes security and privacy. 
This article explores several ways to keep your connection secure while on a Webex meeting. The security tools needed to give you seamless audio and video conferencing experience are also highlighted here.

![Browser in incognito mode](/assets/images/posts/how-to-stay-anonymous-online/browser-incognito.png)



 
## What Security Features Does Webex Have?
![Browser in incognito mode](/assets/images/posts/how-to-stay-anonymous-online/browser-incognito.png)
 
Here are some of the security features of the Webex:

# End-to-End Encryption
Webex servers always decrypt media in meetings that employ the use of SRTP to encrypt media shared across the network. This standard procedure ensures that privacy protocols are not breached by the platform. However, this only happens for conferencing providers that support SIP, H323, PSTN, and so on. 
In cases where a higher level of security is required, Webex provides end-to-end encryption. 

This means that the Webex cloud can't access the encryption keys the participants use and hence can't decrypt their streams.
End-to-end encryption works by the meeting host generating an encryption key. This key is then distributed to other participants in the meeting. 

The meeting host also has the responsibility of encrypting the meeting key before transmitting it.
As a participant, your Webex app generates a public and private key pair and sends the public key to the host's Webex app. In turn, the host's Webex app encrypts the meeting key using the participants' public key. This is then returned to the participant's app. The meeting is then decrypted using the RSA private key. 
Features not supported when end-to-end encryption is enabled includes:
●	Personal room meetings
●	Join before host
●	Video-device enabled meeting
●	Breakout sessions
●	Webex assistant 
●	Remote computer sharing


## Protection of dormant data
Another interesting security feature of Webex is stores meeting data that you may find critical to your business. How does Webex meeting protect data at rest? Webex employs the following procedures to do that:
●	Uses a SHA-2 hashing algorithm to store all user passwords
●	Encrypts other passwords like those used in meetings or recordings 
●	Encrypts stored Network Based Recordings. Webex recordings are encrypted both at the file level and logical volume level. In file encryption, files, alongside the sensitive data they contain are encoded so they can be sent securely. This prevents unauthorized access and modification by malicious individuals.


## Encryption at Run Time
Every form of communication between Webex apps, Webex room devices, and Webex cloud takes place over encrypted channels. Webex uses Transport Layer Protocol (TLS) 1.2. For encryption at run time, once a session is initiated over TLS, all media streams become encrypted. This includes audio VoIP, video, screen share, and document share.
These encrypted media can be transported over UDP, TCP, or TLS. User Datagram Protocol (UDP) is a highly recommended protocol for Webex voice and video streams. Wonder why this is so? It's because TCP and TLS are connection-oriented and works specifically by delivering correctly ordered data to the upper-layer protocol. 


# What Features are Available on Webex for Videos and Audio Devices?
## Video Devices
Users can start or join a meeting with a video device. As a meeting participant, you have options of using either Webex Room devices or Webex cloud registered devices. Other options include any third-party standards-based video device or application. To join a Webex meeting, all you have to do is dial the meeting video address.
Webex Room devices also allow Webex app users to use the proximity feature to join a meeting. 

One thing that makes this a seamless experience is that there is no additional bridging equipment required. 
Signing into a meeting from a random device with an unencrypted client triggers an insecure icon in the meeting window that everyone can see. This way, the other meeting members can censor themselves from discussing sensitive details until that participant returns with a new device that supports an encrypted connection.

## Audio connected via the cloud 
A feature called Cloud Connected Audio (CCA) in Webex is an end-to-end audio solution on the platform. It uses your IP telephony network to provide an audio service for your Webex meetings. Webex CCA uses Session Initiation Protocol(SIP) rather than conventional PSTN connection. 
Nonetheless, this solution still offers you an amazing user experience like other audio options available on Webex. 

Another reason why Webex CCA stands out is that it is highly protected. This means that execution of many attacks is significantly difficult. Even though the infrastructure is shared, inter-tenant routing is not provided.
This feature is effective for blocking malicious traffic from other tenants. Also, traffic over the trunk is limited to the UDP protocol.

# How Do I Set up Security Settings on Webex Meeting?
You can configure your Cisco Webex to be more secure while still having a seamless conferencing experience. As a host, the security jurisdiction of the meeting resides solely with you. You can make certain changes and tweak the settings features to suit what you expect. 
Some of the security adjustments you can make on Webex are discussed below.

## Require attendees to have an account before joining
Setting this up automatically prompts all attendees to have an account on your site before they can be granted access to the meeting. To enable this setting:
1.	Log in to webex.umd.edu
2.	You find a green Schedule Meeting button. Click it, then click the follow-up Show advanced options to expand the menu.
3.	Click Scheduling Options
4.	The check requires attendees to have an account on this site to join the meeting checkbox.


## Assign passwords to recordings
The best way to prevent malicious actors from having access to recordings is not to have recordings at all. If you still want to create recordings, however, you can edit meeting recordings and add passwords for protection. Recordings protected by passwords require recipients to have the passwords to view them. To enable this:
1.	Log in to webex.umd.edu
2.	Navigate to Recordings and click on it
3.	Click the share symbol next to the recording
4.	A pop-up dialog appears. Check the Password protection checkbox
5.	In the Password protection field, set up a password for this recording
6.	Finally, click Save


# Conclusion
Cisco's Webex has grown to become a trusted web and video conferencing platform. It not only offers a tweakable structure or architecture, but it also provides multilayer security. With lots of protocols to ensure third-party industry standards are adhered to, it is simply one of the best conferencing platforms. 
Learn how to adjust Webex security settings to meet your conference specifications. The options are quite cool and effective in keeping out insecure networks, servers, and malicious users.
