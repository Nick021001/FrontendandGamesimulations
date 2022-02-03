# FrontendandGamesimulation

Das Readme für set_ game_ game _simulation steht hier

Spielsimulation und Statistik Niklas Rother & Baris Numanoglu

creatingcards in cardcreation:

Diese Funktion erstellt einfach ein Kartendeck von dem dann die Karten aufs Spielfeld kommen.

Die play Funktion in play.py:

Die play Funktion ist dazu da die Karten nach dem entfernen eines Sets wieder aufzufüllen. Sie werden vom Kartendeck genommen und aufs Spielfeld gelegt. Am Anfang werden so die 12 Spielkarten generiert

combinationsofcards in combination_function: Diese Funktion erstellt aus allen Spielkarten jede mögliche Dreier Kombination damit diese dann auf Sets überprüft werden können

compairprop in compaircardcombinations: Ein Set muss folgende Formel ergeben: ((A ∩ B) ∪ (B ∩ C) ∪ (A ∩ C)) ∩ ((A ∆ B) ∪ (B ∆ C) ∪ (A ∆ C)) = ∅ Dies erfolgt aus den Spielregeln des Spiels. Die Funktion gibt set or noset zurück erklärt warum und warum nicht und fügt die Sets einer vorübergehenden Liste hinzu die die Sets speichert

Check_set: Im Prinzip führt diese Funktion alle anderen nacheinander aus damit ein flüssiges Spiel entsteht mit einer While Schleife wird garantiert das des Spiel komplett durchgespielt wird und die for Schleife sorgt dafür das es hundert mal passiert

Quellen:

https://www.geeksforgeeks.org/python-get-unique-values-list/

https://docs.python.org/3/library/random.html
