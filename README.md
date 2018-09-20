# whJavaScript
# *Primitive Datentypen*
## Datentypen die so elementar sind, dass die Art und Weise sie zu repräsentieren in Java eingebaut ist.
## Die 8 primitven Datentypen: 
+ byte 
+ short 
+ int 
+ long 
+ float 
+ double
+ char 
+ boolean
# *Variablen*
## Eine Variable ist ein abstrakter Behälter für eine Größe, welche im Verlauf eines Rechenprozesses auftritt.Im Normalfall wird eine Variable im Quelltext durch einen Namen bezeichnet und hat eine Adresse im Speicher einer Maschine.
# *Logische Operatoren*
## Mit logischen Operatoren kann man mehrere Bedingungen prüfen, in dem man diese mit logischen Operatoren veknüpft. Z.B. ob Bedingung X und Bedingung Y wahr sind.
# *Negation*
## Mit der Negation wird ein Wert invertiert, also umgekehrt. D.h. aus wahr wird falsch und aus falsch wird wahr. Die Negation erreichen wir mit einem einfachen Anführungszeichen !. 
## int a=5;
## if(!0) printf("aus falsch wird wahr, 0 -> 1\n");
## if(!a) printf("aus wahr wird falsch, 5 -> 0\n");
## aus falsch wird wahr, 0 -> 1
# *UND Verknüpfung*
## Mit dem logischen UND && prüfen wir ob mehrere Bedingungen erfüllt sind.
## int a=0, b=3;
## if(!a && b > 1) {
##         print("a ist nicht mehr wahr und b ist groesser 1\n");
## }
## a ist nicht mehr wahr und b ist groesser 1
# *ODER Verknüpfung*
## Muss nur eine von mehreren Bedingungen erfüllt sein, verwenden wir die ODER Verknüpfung mit ||.
## int a=0, b=1;
## if(a || b) {
##         printf("a oder b ist wahr\n");
## }
# *Arithmetische Operatoren*
## Arithmetische Operatoren verwenden numerische Werte (Literale oder Variablen) als Operanden und geben einen einzelnen numerischen Rückgabewert zurück. Die arithmetischen Standardoperatoren sind Addition (+), Substraktion (-), Multiplikation (*) und Division (/).
# *Vergleichsoperatoren*
## Ein Vergleichsoperator (auch relationaler Operator) ist ein zweistelliger logischer Operator, also ein Operator, der auf zwei Argumente angewendet wird und einen Wahrheitswert liefert. In Programmiersprachen werden Vergleichsoperatorenmeist in Schleifen und Bedingungen verwendet. 
# *Schleifen*
## Eine Schleife (auch "Wiederholung" oder englisch loop) ist eine Kontrollstruktur in Programmiersprachen. Sie wiederholt einen Anweisungs-Block - den sogenannten Schleifenrumpf oder Schleifenkörper -, solange die Schleifenbedingung als Laufbedingung gültig bleibt bzw. als Abbruchbedingung nicht eintritt.
# *Verzweigungen* 
## Bedingte Anweisung und Verzweigung. Eine Bedingte Answeisung ist in der Programmierung ein Programmabschnitt, der nur unter einer bestimmten Bedingung ausgeführt wird. Eine Verzweigung legt fest, welcher von zwei (oder mehr) Programmabschnitten, abhängig von einer (oder mehreren) Bedingungen, ausgeführt wird.
# *Kommentar*
## Kommentare sind Annotationen innerhalb von Programmiersprachen und Textschreibungssprachen. Vereinzelt werden Kommentare allerdings auch zur Speicherung maschinenlesbarer Metainformationen oder zur Ergänzung einer Sprache genutzt (siehe #Verwendung entgegen der Definition).
# *Ausgabe auf dem Bildschirm*
## Eine Ausgabe auf dem Bildschirm ist mit der Funktion "printf" möglich. Sie hat folgende Syntax: "int printf (const char *format, ...);". In den Klammern befinden sich die Parameter. Die Funktion kann aber noch mehr Parameter beinhalten, was durch die drei Punkte angezeigt wird. Die Werte, die der Funktion übergeben werden, bezeichnet man als Argumente. In unserer ersten Übung "Hallo Welt", haben wir der Funktion "printf" zum Beispiel das Argument "Hallo Welt" übergeben. 
### (c) Florian Trube 2018
