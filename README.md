<h1>MES-System in Python</h1>
</br>
Willkommen zum rudimentären Manufacturing Execution System (MES) in Python! Dieses Projekt dient als Beispiel dafür, wie ein einfaches MES entwickelt werden kann, um Produktionslinien zu verwalten, Produktionsaufträge zu erstellen, diese zu starten und zu beenden sowie die Produktionseffizienz zu berechnen.

<h2>Funktionen</h2>

<h3>MES-Klasse</h3>
add_production_line(name)
</br>
Fügt eine neue Produktionslinie mit dem angegebenen Namen hinzu.

get_production_line(name)
</br>
Gibt die Produktionslinie mit dem angegebenen Namen zurück.

create_production_order(production_line_name, order_number, product_name, quantity)
</br>
Erstellt einen neuen Produktionsauftrag auf der angegebenen Produktionslinie mit der angegebenen Bestellnummer, dem Produktnamen und der Menge.

start_production_order(production_line_name, order_number)
</br>
Startet den angegebenen Produktionsauftrag auf der angegebenen Produktionslinie.

finish_production_order(production_line_name, order_number)
</br>
Beendet den angegebenen Produktionsauftrag auf der angegebenen Produktionslinie.

<h3>mes_utils-Klasse</h3>
get_order_by_number(production_line, order_number)
</br>
Findet in der gegebenen Produktionslinie den Auftrag anhand der Auftragsnummer und gibt den Auftrag zurück.

calculate_production_progress(order)
</br>
Berechnet den Produktionsfortschritt des angegebenen Produktionsauftrags.

<h3>Produktionsklassen</h3>

init(self, order_number, product_name, quantity)
</br>
Initialisiert einen neuen Produktionsauftrag.

get_order_number(self)
</br>
Gibt die Bestellnummer zurück.

start(self)
</br>
Startet den Produktionsauftrag.

finish(self)
</br>
Beendet den Produktionsauftrag.

produce(self, units)
</br>
Produziert die angegebene Anzahl an Einheiten.

get_production_progress(self)
</br>
Gibt den Produktionsfortschritt zurück.

<h3>ProductionLine</h3>

init(self, name)
</br>
Initialisiert eine neue Produktionslinie mit dem angegebenen Namen.

add_order(self, order)
</br>
Fügt einen neuen Produktionsauftrag zur Produktionslinie hinzu.

get_production_line_name(self)
</br>
Gibt den Namen der Produktionslinie zurück.

get_orders(self)
</br>
Gibt alle Aufträge der Produktionslinie zurück.

<h2>Anforderungen</h2>
Python 

Arbeiten nach SCRUM
