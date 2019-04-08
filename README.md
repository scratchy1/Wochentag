# Wochentag
1. Der Konstruktor soll einWochentag-Objekt erzeugen und den aktuellen Wochentag auf Montag setzen. 
2. Die Methode naechsterTag() soll einWochentag-Objekt auf den folgenden Wochentag setzen. (Die Wochentage werden zyklisch behandelt!) 
3. Die Methode vorhergehenderTag() soll ein Wochentag-Objekt auf den vorhergehendenWochentag setzen.
4. Die Methode setTag(int i) soll den Wochentag des Wochentag- Objektes setzen (0 für Montag, 1 für Dienstag, usw.). Falls ein int-Wert kleiner null oder größer sechs übergeben wird, soll eine KeinTagException geworfen werden. Vereinbaren Sie eine Klasse KeinTagException. KeinTagException soll als der Subklasse der Klasse Exception deklariert sein.
5. Die Methode getTag() soll den Tag codiert als int-Wert als Ergebnis liefern.
6. Die toString()-Methode soll den Namen desWochentages als String zurückliefern.
