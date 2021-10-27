# U20 | Car-Simulator

Erstellen Sie ein Programm, das den Verkehr auf einer mehrspurigen
Straße animiert:

- Alle Fahrzeuge starten am linken Rand der Zeichenfläche.

- Die Fahrzeuge fahren in Spuren, jede Spur ist so hoch wie die
  Fahrzeuge (die Fahrzeughöhe ist konstant).

- Auf einer Spur können mehrere Fahrzeuge mit unterschiedlichen
  Geschwindigkeiten fahren.

- Fährt ein Fahrzeug rechts aus dem Bild heraus, so wird seine
  Position wieder auf den Anfang derselben Spur gesetzt.

- Jedes Fahrzeug besteht:
  - aus einer Karosserie und einem Dach, die die gleiche Farbe haben, aber diese Farbe inkl. Alpha-Transparenz (vgl. verfügbare Konstruktoren der Klasse `Color`) wird zufällig bestimmt
  - schwarze Reifen 
  - Wählen Sie sinnvolle geometrische Primitive aus `GraphicsApp`, um das Auto zu modellieren
  - Fassen Sie die Bestandteile in einem ```GraphicsObject[]``` zusammen 

- Die Geschwindigkeit des Fahrzeugs wird ebenfalls zufällig bestimmt
  (zwischen `2.0` und `10.0`).

![Cars!](./docs/09_cars.png)

Die Klasse ```Car``` ist vollständig für die Berechnung der Fahrzeugfarben und Positionen zuständig. Aus der Klasse ```Cars``` werden lediglich die Methoden ```update()``` und ```draw()``` der Objekte der Klasse ```Car``` aufgerufen.
