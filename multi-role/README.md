# PCB Multi role

#### PCB généraliste permettant son utilisation dans beaucoup de projets diy.

Il s'articule autour d'un **<u><mark>esp32u</mark></u>**

**Connections possibles :**

- 1x RS485 (1 uart)

- 1x TTL (1 uart)
  
  => reste 1 uart possible via les gpio de l'esp32

- 4 Led simple via pca6416

- 10 entrées binary on/off via pca6416

- 16x sorties binary on/off via pcf8575

- 2x led rgb ws2812b indépendantes

- 1x ads1115

- 1x bme280 onboard

- 10x gpio reliés directement à l'esp32 (8 si les leds rgb sont utilisées)

- Plusieurs ports i2c sont disponibles

- Connecteur rtc

****

**Problemes à corriger next rev :**



- Trous parfois trop proche des composants

- quelques condensateurs mals placés

- Connecteur a poussoir pas géniale selon les cables

- manque au moins un connecteur i2c 5v

- remplacer le pcf8575 par un deuxieme pca6416
  
  








