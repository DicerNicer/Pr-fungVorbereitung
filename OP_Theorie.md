# Call by Reference / Call by Value
## Call by Value 
Nur Wert der Variable wird an Methode übergeben.
Variable wird nicht verändert.

Bsp. methode(x)

## Call by Reference
Speicherstelle der Variable wird an Methode übergeben.
D.h. Wert der Variable kann geändert werden
Es gibt 2 Möglichkeiten

### Ref
Variable muss zuvor einen Wert zugewiesen bekommen haben.
Muss jedoch nicht in Methode beschrieben werden.

Bsp.: methode(ref x)

### Out
Variable muss zuvor keinen Wert zugewiesen bekommen haben.
Muss jedoch in Methode beschrieben werden.

Bsp.: methode(out x)

# Klassen
Eine Klasse ist der Bauplan nach dem Objekte erstellt werden.

## Konstruktor
Zum erstellen des Objektes wird der Konstruktor der Klasse aufgerufen.
Dieser wird folgendermaßen deklariert:
public NameDerKlasse()
{
}

## Atribute
Atribute sind die Variablen eines Objektes.
Sie werden als private deklariert und werden nur von Methoden des Objektes gelesen und beschrieben.
Diese Methoden nennt man getter und setter.
Bsp:
private int nr;
public void setNr(){}
public int getNr(){}

## Methoden
Zusätzlich zu den Atributen besitzen Objekte auch Methoden. Zum Beispiel die Klasse Würfel hat die Methode würfeln().
