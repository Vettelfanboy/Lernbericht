# Lernbericht
# Lern-Bericht
Simon Veljkovic

## Einleitung

Ich musste als Auftrag einen Number guesser programmieren.

## Was habe ich gelernt?

Ich habe gelernt, wie man richtig Zahlen generiert und wie man gewisse Limits im Spiel einbaut.

## Beschreibung



Ich habe mit den verschiedenen Variablen bzw. Operatoren gearbeitet, hauptsächlich mit Doubles und mit if-Schleifen. Natürlich brauchte ich auch die Eingabefunktion "Console.WriteLine()" damit das Programm weiss was ich eingeben möchte. Ich musste jeweils die Zahlen auch definieren und Limite bestimmen. Und für die absichtlichen Crashes habe ich extra keine "try->catch-Schleife" und auch keine "do->while-Schleife" eingebaut, da sich sonst das ganze wiederholen würde, aber mein Ziel war es, dass das Spiel manipuliert wird, wenn man miiten im Spiel etwas falsches eingibt oder wenn man von Beginn an etwas falsches eingibt, dass das Spiel ganz abstürzt, wobei auf Ersteres ich keinen grossen Einfluss hatte.

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

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
