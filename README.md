# <img src="https://github.com/ugo-bp/nomine/blob/main/images/nomine-ico1.png" /> <p>nomine-ekey1</p>
<b>Chiave elettronica per archiviazione informazioni di accesso</b>

Saldare un pulsante tra i piedini 7 e 8 della raspebrry pi pico.


<img src="https://github.com/ugo-bp/nomine-ekey1/blob/main/images/nomine-ekey1.jpg" />

(Il pulsante in foto e' un pulsante SMD 2.9x3.9mm, 2 pin,
 TD-85XU Mini Tact Switches)


Aggiornare la raspberry pi pico come descritto nel seguente progetto:

https://github.com/dbisu/pico-ducky

Sostituire il contenuto del file code.py con il codice contenuto in example.py

Caricare su CIRCUITPY il file payload.dd

Creare su CIRCUITPY il file nomine.pem contenente la password da inviare.

Scollegare e ricollegare la raspberry pi pico.

Premere il pulsante collegato sui pin 7 e 8 per inviare la password.


