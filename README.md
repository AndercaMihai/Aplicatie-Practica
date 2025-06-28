# Automatizarea unui sistem de benzi transportoare folosind automate programabile Siemens și Factory I/O

## Adresa repository-ului: https

## Tehnologii folosite
1. TIA Portal V15.1

2. S7-PLCSIM V15.1

3. Factory I/O
- - - 


## Pași de instalare, compilare, lansare ai aplicației:
1. Descărcați fișierul cu extensia .zap15_1.
2. Descărcați fișierul cu extensia .factoryio.
3. Deschideți TIA Portal V15.1.
4. Selectați 'Project view', apoi din bara de sus 'Project > Retrieve' și selectați fișierul .zap15_1 descărcat și directorul unde doriți să îl recuperați.
5. Selectați din panoul din stânga (Poject tree) 'PLC_1 [CPU 1215C AC/DC/Rly]', apoi mergeți la 'Program blocks > Main [OB1]' pentru programul principal, sau la 'Program blocks > MHJ-PLC-Lab-Function-S71200' pentru funcția de comunicare dintre TIA Portal și Factory I/O.
6. Selectați 'PLC_1 [CPU 1215C AC/DC/Rly]' și apăsați din bara de sus 'Start Simulation', sau dați click dreapta pe 'PLC_1 [CPU 1215C AC/DC/Rly] > Start Simulation'.
7. Alegeți 'PN/IE' ca 'type of PG/PC interface' și 'PLCSIM' la 'PG/PC interface', apoi apăsați 'Start search'.
8. Când scanarea este completă, selectați device-ul 'CPUcommon' și  apăsați 'load'.
9. În fereastra deschisă apăsați 'load', apoi modificați acțiunea câmpului 'Start modules' din 'No action' în 'Start module' și apăsați 'Finish'.
10. Deschideți fișierul .factoryio .
11. În Factory I/O, în bara de sus apăsați 'File > Driver' și selectați ca 'DRIVER' opțiunea 'Siemens S7-PLCSIM'.
12. Deschideți panoul de configurare al Driver-ului, apăsând 'CONFIGURATION' și selectați modelul de CPU 'S7-1200'.
13. Apăsați 'Esc' pentru a reveni în fereastra principală a driver-ului și apăsați în bara de sus pe 'CONNECT'.
14. Apăsați 'Esc' pentru a reveni la scenă, apoi în bara de sus apăsați 'SWITCH BETWEEN EDIT AND RUN MODE' pentru a activa modul RUN.
15. În modul RUN, apăsați BUTONUL VERDE de pe panou pentru a porni simularea, procesul de sortare și paletizare utilizând paletizatorul și brațul robotic fiind pus în practică.


