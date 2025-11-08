# services-setup-for-system
all type of system setup like - project or personal (any type of machine)



SMTP Setup
------------

     SMTP Installation For Magento - 2
     ----------------------------------
       Guide Link 
       -----------
                 - https://github.com/mageplaza/module-core  (reference )
                    - sudo composer require mageplaza/module-core     - install 
                    - sudo composer require mageplaza/module-smtp     - 
                    - sudo composer remove mageplaza/module-core      - un-install
                    - sudo composer remove mageplaza/module-smtp

                   - sudo composer update mageplaza/module-core    - If Previous version is not working then update the extension ( licence 				 activation issue after adding  gmail account app password )
                   - sudo composer require mageplaza/module-smtp
	       
    Magento Market Place Key
    ------------------------
     - Magento Market Place (https://marketplace.magento.com/)
     My Profile-->Access Key --> Create new --> give any name
     
                    Public Key   = 27f19ff144e9ec3b7a66a844feb13a4f
                    Private Key  = e435d9f2831d076f07f6a5666ecc0c27

    Configuratin
    ------------ 
         Store--> Configuration ---> Mageplaza Extensions
                                      |
                                      |--------- SMTP
                                                  |
                                                  |  
                                                  |----- Module information 
                                                  |                 |----- userName - sanjay
                                                  |                 |----- Email    - sanjay.d@gmail.com
                                                  |
                                                  |----- General Configuration
                                                  |                 |
                                                  |                 |------Enable Mageplaza SMTP  ----> make it yes
                                                  |                 |------Log Emails             ----> make it Yes 
                                                  |
                                                  |----- SMTP Configuration Options
                                                                     |
                                                                     |--- Host           - smtp.gmail.com
                                                                     |--- Port           - 587
                                                                     |--- Protocol       - TLS
                                                                     |--- Authentication - LOGIN
                                                                     |--- Username       - sanjay.d@codilar.com
                                                                     |--- Password       - You got from (App Password for Gmail Account)                                   

    Get App Password
    -----------------
            Search on google 
                |--- app password gmail (create one)


















Ubuntu Hacks
----------------

#### If Any File Icon Miss

- sudo apt install nautilus

#### VPN connection

visit this site -  https://www.vpnbook.com/

- download any country wise file 
- extract and open terminal 

start the vpn
------------------
cd Downloads
cd vpnbook-openvpn-ca196

sudo openvpn vpnbook-ca196-tcp443.ovpn

Username: vpnbook
Password: 545ae57


test vpn ip
---------------------
curl ifconfig.me


test vpn is from here - https://www.dnsleaktest.com/

### Free Video Editing Software Ubuntu

Go this This = https://kdenlive.org/download/

   Download ---> linux 
          
           - AppImage
           - cd Downloads
           - chmod +x kdenlive-25.08.3-x86_64.AppImage
          
       To Start The application (lunch application)
       
                    - ./kdenlive-25.08.3-x86_64.AppImage

## Ubuntu Broke Any Reason

     - Hold power button to --- switch off the laptop

	 - Hold power button to start the laptop

	 - once laptop is starting ---> quickly press not contineous by giving quick immediate gap the "esc"  button ---------> it will take to  
	                                                                        |
																			|------------ ubuntu recover screen (some time recover will work) ---> else fix we can fix from terminal (in this recover we will get the terminal)
																			|                      |
																			|                      |---- apt install --reinstall gdm3 ubuntu-desktop -y
																			|                      |---- mkdir -p "[daemon]\nWaylandEnable=false" > /etc/gdm3/custom.conf
																			|                      |---- update-initramfs
																			|                      |---- reboot
																			|
																			|
																			|------------ grub screen (here also we can fix ) 



Free kdenlive Video Editing Software Ubuntu
===========================================


Install kdenlive -1
===================
Go this This = https://kdenlive.org/download/


   Download ---> linux 
          
           - AppImage
           
           - cd Downloads
           - chmod +x kdenlive-25.08.3-x86_64.AppImage
          
       To Start The application (lunch application)
       
                    - ./kdenlive-25.08.3-x86_64.AppImage

Install kdenlive -2 
====================

   1) visit the site = https://kdenlive.org/download/
   
   
   2) select the -- linux one
   
   3) download - Flatpak way
   
              to install this run this command 
                       |
                       |----------------- flatpak install flathub org.kde.kdenlive
                       |
                       |----------------- flatpak run org.kde.kdenlive
                       |
                       |----------------- sudo apt install flatpak  (may got some error )
                       |
          
				  You’re almost there—Flatpak is installed, but Flathub isn’t added yet. Do this:

			          1) Add Flathub (the app repo)
      
			             command -  flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

			          2) Install Kdenlive from Flathub
      
			             command -   flatpak install flathub org.kde.kdenlive

			         3) Fix the XDG_DATA_DIRS notice (so the app shows in your menu)

			          That message just means your session hasn’t picked up Flatpak’s paths yet. Log out and log back in (or reboot) once after 
			          step 2. After that, “Kdenlive” should appear in your app launcher.

			        Optional (GUI install via “Ubuntu Software”)
			          If you want Flatpak apps to appear in Ubuntu Software:
			             sudo apt install gnome-software gnome-software-plugin-flatpak
			             (Then log out/in and open “Software” → search Kdenlive.)

                       
         Alternatives (if you prefer)

                Snap: sudo snap install kdenlive

                  AppImage: you already downloaded one—just make it executable and run it:

                           1) chmod +x ~/Downloads/kdenlive-*.AppImage
                           2) ~/Downloads/kdenlive-*.AppImage

 



				

                
