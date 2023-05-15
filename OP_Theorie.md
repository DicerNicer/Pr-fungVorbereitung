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
