Linuxcnc Component

2 Componenten für Linuxcnc, für das Spindel und Forschub Poti des Siemens Sinumerik 840C Panels



Die beiden Dateien müssen ins verzeichnis /usr/lib/linuxcnc/modules/  kopiert verden.
Über ein Terminal die Dateiverwaltung öffnen  (sudo Thunar) oder (sudo caja)


In eurer HAL:

loadrt siemens_f_poti count=1
addf siemens-f-poti.0  servo-thread

loadrt siemens_s_poti count=1
addf siemens-s-poti.0  servo-thread
