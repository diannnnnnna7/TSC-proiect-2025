E-Book Reader cu e-Paper si ESP32-C6

DeskAssistant este un dispozitiv portabil de tip E-Book Reader, construit in jurul microcontrolerului ESP32-C6, cu consum redus de energie si capabilitati de conectivitate Wi-Fi. Dispozitivul utilizeaza un display e-paper pentru citirea confortabila a cartilor, fiind alimentat de la o baterie Li-Po si gandit sa functioneze autonom timp indelungat.

Componente principale:

ESP32-C6 – Microcontroler principal cu Wi-Fi, SPI si I2C

E-Paper Display – Afisaj principal, ideal pentru citirea fara oboseala a ochilor

Memorie Flash NOR 64MB – Spatiu generos pentru carti, configurari sau fisiere

Senzor ambiental BME688 – Masoara temperatura, presiunea, umiditatea si calitatea aerului

RTC DS3231 – Ceas de timp real cu precizie ridicata si consum scazut

SD Card Slot – Optiune de stocare suplimentara pentru fisiere EPUB/PDF

Fuel Gauge MAX17048 – Monitorizeaza in timp real nivelul bateriei

LDO Regulator – Asigura tensiunea de 3.3V stabila pentru toate componentele

Conector USB-C – Incarcare si comunicatie UART pentru debugging

Dispozitivul se alimenteaza de la o baterie Li-Po si poate fi incarcat prin portul USB-C, avand un circuit de incarcare dedicat (MCP73831).

Interfete de comunicatie:

SPI – Utilizat pentru E-Paper, memorie Flash si card SD

I2C – Utilizat pentru senzorul BME688, RTC si Fuel Gauge