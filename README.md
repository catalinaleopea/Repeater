Proiect: Proiect pe matricea de LED-uri
Autor:Leopea Catalina,grupa 243
 Nume joc: Repeater
 Tip: Single player
Hardware: Arduino Uno, display matrice 8x8 cu driver 7219, 4x butoane, display LCD,
potentiometru de 10K ohm,
4x rezistente 10K ohm, fire de legatura, 3x breadboard mare,1x breadbard mic
Am asamblat componentele dupa modelele urmatoare:
-matricea dupa modelul de la laborator
-butoanele https://www.arduino.cc/en/Tutorial/Button
-display-ul LCD https://www.arduino.cc/en/Tutorial/HelloWorld
 Software:
Ideea joculului e de a afisa o secventa de sageti pe matrice, iar jucatorul sa o reproduca cu
ajutorul a 4 butoane (stanga, dreapta, sus, jos) avand doar doua vieti, reprezentate prin doua led-uri fizic.
Daca a introdus corect secventa trece la nivelul urmator, unde va fi generata o alta secventa de
dimensiune mai mare cu o unitate.
Jocul se termina atunci cand utilizatorul introduce o secventa gresita, mai exact la prima sageata
gresita din secventa. La primele doua greseli viata jucatorului scade , led-urile se sting succesiv si se repeta nivelul la care a
gresit cu o noua secventa generata de sageti, la a treia greseala jocul s-a terminat.
Cu ajutorul display-ului LCD afisez un mesaj de inceput, pentru a sugera jucatorului sa apese un
buton pentru a juca, apoi incepe afisarea secventei, urmata de un afisaj special "GO" care indica
randul jucatorului si un “smiley face” daca datele au fost corecte sau “sad face” altfel. La
sfarsitul jocului ecranul LCD va afisa un mesaj de final, dupa o apasare de buton scorul, iar inca
o apasare va insemna optiunea de intoarcere la nivelul 1.
Evolutie in timp:
-doua vieti
-nivel
-dificultate: consta in numarul de sageti care apar pe display
 Ex: La nivelul k apar k sageti pe display
 La nivelul k+1 apar k+1 sageti
