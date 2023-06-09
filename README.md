# Lern-Bericht
Gruppe Heliotrope
Sathana Suganthasri, Joel Simon Juan. Haldimann und Kilian Adil. Staeuble


## Einleitung

In diesem Spiel geht es um unsere Base zu schützen. 
✍️ Ein Satz, worum es in dem Projekt ging. Muss für einen externen Leser einfach zu verstehen sein.

## Was habe ich gelernt?
Wie man so programmiert, das den erstellten Gerät automatisch den Pfaden folgt. 
✍️ Beschreiben Sie in einem Satz **eine** Sache, die Sie bei diesem Projekt gelernt haben und die Sie in diesem Lern-Bericht dokumentieren.



## Beschreibung

✍️ Verwenden Sie drei verschiedene Medien, um zu zeigen, was Sie gelernt haben. Zum Beispiel:

* Eine textliche Beschreibung
* Ein deutliches, aussagekräftiges Bild oder eine kommentierte Bildschirm-Aufnahme
* Ein gut dokumentierter Code-Fetzen

```csharp
        public class Waypoints : MonoBehaviour
        {           
            public static Transform[] points;
            
            void Awake()
            {
                points = new Transfrom[transform.childCount];
                for (int i = 0; i < points.Length; i++)
                {
                    points[i] = transform.GetChild(i);
                }
            }
        }

```


* Ein Link zu einem *selbst aufgenommenen* youtube-Video oder `.gif`.

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

Die Aufgabenteilung war gut und jeder wusste, was sie machen mussten. 
👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 


Als wir Online-Unterricht hatten, konnten wir unsere Projekt nicht zusammen fügen und hatten Mühe den Problem herauszufinden. 👎 und etwas, was nicht gut lief.

**VBV**: Nächste Mal, wenn es im Gruppenarbeit eine Zusammenfügen eines Projekt geht, werden wir alle an einem Ort treffen und den Projekt zusammenfügen. 
✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
