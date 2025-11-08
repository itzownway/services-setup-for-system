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
																			|                      |---- 
																			|                      |---- 
																			|                      |---- 
																			|                      |---- reboot
																			|
																			|
																			|------------ grub screen (here also we can fix ) 







				

                
