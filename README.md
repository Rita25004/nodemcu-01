# nodemcu-01

Syftet med detta repo är att lära nya studenter hur man använder Arduino-funktioner och kontrollerar en mikroprocessor.

## Vad är NodeMCU?
NodeMCU är ett litet kort med en ESP8266-mikrokontroller, som är som en liten “dator” som kan köra program för att styra elektronik.
## Blink Program?
Detta är det första programmet man brukar lära sig.
Det gör att LED-lampan på kortet blinkar fram och tillbaka
## Arduino IDE
Arduino IDE är programmet där vi skriver koden och skickar den till NodeMCU

## "Blinkprogram" på NodeMCU
Instruktion för att utföra blink med Arduino IDE och Pulsivo
* Installera Arduino IDE på din dator
* Installera ESP8266-stöd i Arduino IDE (Klicka på Fil → Inställningar/Preferences → Additional Boards Manager URLs → Klistra in följande länk: http://arduino.esp8266.com/stable/package_esp8266com_index.json
→ Gå till boards manager → Sök efter ESP8266 och installera paketet som visas → Gå till tools → ESP8266 Boards och välj Generic ESP8266 Module.
* Anslut NodeMCU till datorn med USB-kabel.
* Klicka på Fil → Ny för att öppna ett nytt fönster → Kopiera följande kod:
<img width="1415" height="586" alt="Skärmbild 2025-12-04 122947" src="https://github.com/user-attachments/assets/a2344c7c-a964-448f-88b7-fea0abe64903" />


## Två basfunktioner i Arduino
#### setup()
Denna funktion körs endast en gång när programmet startar

Vi använder den för att bestämma vilken pin som ska vara utgång (Output) eller ingång (Input).

#### loop()
Denna funktion körs kontinuerligt så länge kortet är påslaget.

Här skriver vi det som ska upprepas, t.ex. slå på och stänga av LED.

## Portinitialisering?
Det betyder att man bestämmer funktionen för varje pin på kortet:

Output (utgång): skickar ström, t.ex. LED eller motor

Input (ingång): läser ström, t.ex. knapp eller sensor


<img width="268" height="20" alt="PIn" src="https://github.com/user-attachments/assets/0481e5f8-2741-4258-83fe-fe43d7305c1f" />
