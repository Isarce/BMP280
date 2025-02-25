# BMP280
Pour voir ce qu'on peut mettre sur BMP280

Le BMP280 mesure la pression atmosphérique en Pascal et la température en degrés Celsius ou Farenheit
brochage :  Vcc  3,3v
            Gnd  Masse
            Sda  Données
            Scl  Horloge
            Csb  Sélection du bus
            Sbo  Sélection de l'adresse
Il supporte le I2C et le SPI
En I2C  Bmp280  sur  µc 
        Vcc          3,3 ou 5V 
        Gnd          Gnd
        Scl          A5 (si Arduino)
        Sda          A4 (si Arduino)
