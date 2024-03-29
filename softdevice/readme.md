# Softdevice auf dem Micro:bit installieren _(Windows 10)_

> Damit der Micro:bit mit der Arduino-IDE programmiert werden kann, muss ein "Softdevice"-Radio auf dem Micro:bit installiert sein. Wenn der Micro:bit mit MicroPython verwendet wurde, wurde dieses Softdevice gelöscht.  
Das erneute Installieren ist ganz einfach. Laden Sie die Microbit-adv.hex Datei herunter und ziehen Sie es auf Ihr MICROBIT-Laufwerk, um ein MakeCode-Bluetooth-Werbebeispiel zu installieren.


1. Download der Datei [microbit-adv.hex](microbit-adv.hex) (*Rechtsklick -* `'Ziel speichern unter'`)


2. Den **micro:bit** am USB-Port des Computers anschliessen.  
    
    ![Laufwerk MICROBIT](bilder/laufwerk_microbit.png)  
    
    > _Der `MAINTENANCE-Modus` ist **nicht erforderlich!**_


3.  Wechsel zum *(Download-)* Ordner mit der Datei **microbit-adv.hex** und  
mit einem _Rechtsklick_ auf die Hex-Datei mit `'SENDEN AN'` Laufwerk: `MICROBIT (D:)` die Hex-Datei installieren.  

    ![Senden an](bilder/senden_an.png)  

    > Alternativ die Hex-Datei in das Laufwerk: `MICROBIT (D:)` kopieren.


4. Nun kann mit der Arduino-IDE der Micro:bit mit C programmiert werden.
