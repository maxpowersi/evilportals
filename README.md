## Evil Portals+

Evil Portals+ is a collection of portals that can be loaded into the Evil Portal module and can be used for phishing attacks against WiFi clients in order to obtain credentials or infect the victims with malware using the [Hak5](https://hak5.org/) [WiFi Pineapple](https://wifipineapple.com/) [Tetra](http://hakshop.myshopify.com/products/wifi-pineapple?variant=11303845317) and [Nano](http://hakshop.myshopify.com/products/wifi-pineapple?variant=81044992).

This project requires you to install captive portal module. Install on the Pineapple, Modules -> Manage Modules -> Get Modules from WiFiPineapple.com -> Evil Portal.

You can install EvilPortalReloaded, a fork of EvilPortal, that works betters in some specific case.

This repo is forked, the original is from [Kleo Bercero](https://kbeflo.github.io/). I have just forked, and add some custom portals.

---
#### Usage

Clone the repository

	git clone RepoURL

Change directory to evilportals/portals/

	cd evilportals/portals/

Copy the portals you wish to use on the Tetra at `/root/portals/` or on the Nano at `/sd/portals/`

    scp -r portal-login root@172.16.42.1:/root/portals/

Finally on the WiFi Pineapple web interface, start the Evil Portal module and then activate the portal you wish to use.

After gathering credentials, captured data will be shown as a notification on the WiFi Pineapple web interface, and also stored on the Tetra at `/root/evilportal-logs/portal-login.txt` or on the Nano at `/sd/evilportal-logs/portal-login.txt` with additional profiling.

---

#### Screenshots

<img src="https://user-images.githubusercontent.com/13497504/34363974-1b5e5f1e-eabc-11e7-99f5-78043f8b3ac9.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34363975-1d4b32ca-eabc-11e7-8532-2105a160c5c1.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34363977-1e8f4ca2-eabc-11e7-885e-e7dbd845e217.png" width="200"/>

<img src="https://user-images.githubusercontent.com/13497504/34363979-1f66e108-eabc-11e7-8dbb-39fa8b22c3a7.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34363982-20258324-eabc-11e7-93e0-b775fa1bcc25.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34366525-bba03dc4-ead7-11e7-8bea-a3fa9ae33ef4.png" width="200"/>

---

#### License
Evil Portals is distributed under the GNU GENERAL PUBLIC LICENSE v3. See [LICENSE](https://github.com/kbeflo/evilportals/blob/master/LICENSE) for more information.

#### Disclaimer
* Usage of Evil Portals for attacking infrastructures without prior mutual consistency can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state and federal laws. Authors assume no liability and are not responsible for any misuse or damage caused by this program. 

---

Some of the portals here are also available for [Wifiphisher](https://github.com/wifiphisher/wifiphisher), available here [wifiphisher/extra-phishing-pages](https://github.com/wifiphisher/extra-phishing-pages)

Discussion thread - [Hak5 Forums](https://forums.hak5.org/index.php?/topic/39856-evil-portals/)