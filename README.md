
# tp1-communiquer deux cartes ARDUINO (une maitre et l’autre esclave) en utilisant le protocole I2C

on désire faire communiquer deux cartes ARDUINO (une maitre et l’autre esclave) en utilisant le protocole I2C. L’application
consiste à commander la fréquence de clignotement d’une LED connectée sur la carte
ARDUINO esclave, en utilisant un potentiomètre 1k dont le curseur est branché sur la
broche analogique A0 de la carte ARDUINO maitre.
L’application devrait être testée en utilisant la plateforme en ligne « Tinkercad ».

<img src="images/app1"></img>

# tp2-communiquer par protocole I2C, une horloge temps réel

cette  application consiste à faire communiquer, par protocole I2C, une horloge temps réel, RTC (Real Time Clock),
DS1307 en tant qu’esclave et une carte ARDUINO en tant que maitre. L’affichage de
de l’heure, issu de l’horloge DS1307, sera réalisé en utilisant un afficheur LCD, LM016L.
Pour bien comprendre le fonctionnement du circuit DS1307, vous devrez faire appel à
son datasheet.
Cette application devrait être testée en utilisant l’IDE Arduino et le logiciel ISIS.

<img src="images/app2"></img>

# tp3-arduino

C ette troisième application consiste à faire
communiquer, par protocole I2C, une carte Arduino en tant que maitre, une horloge
temps réel, RTC (Real Time Clock), DS1307 en tant qu’esclave 1 et un afficheur LCD
I2C (PCF8574+LCD LM016L), et un autre afficheur LCD parallèle connecté directement
sur le maitre. Pour bien comprendre le circuit PCF8574, vous devrez utiliser son
datasheet.
Cette application devrait être testée en utilisant l’IDE Arduino et le logiciel ISIS.

<img src="images/app3"></img>