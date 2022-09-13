# Lernbericht
# Lern-Bericht
Simon Veljkovic

## Einleitung

Ich musste als Auftrag einen Number guesser programmieren.

## Was habe ich gelernt?

Ich habe gelernt, wie man richtig Zahlen generiert und wie man gewisse Limits im Spiel einbaut.

## Beschreibung



Ich habe mit den verschiedenen Variablen bzw. Operatoren gearbeitet, hauptsächlich mit if-Schleifen. Natürlich brauchte ich auch die Eingabefunktion "Console.WriteLine()" damit das Programm weiss was ich eingeben möchte. Ich musste jeweils die Zahlen auch definieren und Limite bestimmen. Und für die absichtlichen Crashes habe ich extra keine "try->catch-Schleife" und auch keine "do->while-Schleife" eingebaut, da sich sonst das ganze wiederholen würde, aber mein Ziel war es, dass das Spiel manipuliert wird, wenn man miiten im Spiel etwas falsches eingibt oder wenn man von Beginn an etwas falsches eingibt, dass das Spiel ganz abstürzt, wobei auf Ersteres ich keinen grossen Einfluss hatte.

```csharp

  while (zahl != zahl1)
                {
                    if (zahl > zahl1)
                    {
                        
                        Console.WriteLine("Die gesuchte Zahl ist kleiner");



                    }
                    else if (zahl < zahl1)
                    {
                        Console.WriteLine("Die gesuchte Zahl ist grösser");
                    };


                    Console.WriteLine("Geben sie erneut eine Zahl zwischen 1 und 100 ein");
                    zahl = Convert.ToDouble(Console.ReadLine());


                    if (zahl < 1 || zahl > 100)
                    {



                        Console.WriteLine("Falsche Eingabe, bitte geben sie eine neue Zahl ein");
                        zahl1 = Convert.ToDouble(Console.ReadLine());
                    };
                };

```



https://user-images.githubusercontent.com/110892495/189848417-7c7305bb-7377-483e-a75a-80a4652e7e86.mp4

## Verifikation

Text: Beschreibt die Einzelheiten des Codes, wie z.B. was für Elemente ich verwendet habe und was ich beachten musste.
Code Snippet: Zeigt, wie der Code letztendlich aussieht.
Video: Spielt das Spiel durch mit allen möglichen Runden, sprich die normale Runde, die direkt beendete Runde durch Absturz und die manipulierte Runde mit der plötzlichen falschen Info.

# Reflektion zum Arbeitsprozess

Was lief gut?

Ich konnte mich ziemlich gut an die zeitlichen Vorgaben halten, die uns Herr Colic aufgegeben hat. Zudem konnte ich einigermassen produktiv arbeiten.

Was lief nicht so gut?

Wenn mal was nicht funktioniert hat, war schnell frustriert und dies raubte mir auch die Motivation. Ich konnte nur noch irgendwie an Wunder glauben, um mich aus der Frustration zu befreien.

VBV:

Ich sollte nächstes Mal nicht komplett ausrasten wenn mal was schief läuft und zudem einfach mal ausprobieren was geht. Ausserdem sollte ich mein Vorgehen besser planen und mich mit den einzelnen Funktionen mehr auseinandersetzen, um etwas kreativeres zu erschaffen.
