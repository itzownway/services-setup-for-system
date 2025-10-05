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

                
