Linuxcnc Component

3 Componenten für Linuxcnc, für das Spindel und Forschub Poti des Siemens Sinumerik 840C Panels  
und eine für die Jog Taster(-,~,+) und increment Taster (.,1,10,100,1000,10000)



Die jeweilige Datei müssen ins verzeichnis /usr/lib/linuxcnc/modules/  kopiert verden.  
Über ein Terminal die Dateiverwaltung öffnen  (sudo Thunar) oder (sudo caja)


In eurer HAL:

loadrt siemens_f_poti count=1  
addf siemens-f-poti.0  servo-thread

loadrt siemens_s_poti count=1  
addf siemens-s-poti.0  servo-thread
  
loadrt siemens_jog count=1  
addf siemens-jog.0  servo-thread
