CODEBUCH												
Wert	Kommentar											
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).											
from	definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort											
to	definiert den Empfaenger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen !	
relation  Art der Beziehung (1 = familiaer, 2 = freundschaftlich, 3 = Bekanntschaft, 4 = Feindschaft, 5 = Liebesbeziehung, 6=Tod, 7=Verhaftung, 8=Angriff, 9=Mitgliedschaft)
start Beginn der Beziehung/Mitgliedschaft in einer Gruppe
end Ende der Beziehung/Mitgliedschaft in einer Gruppe (1 = 21.11.1942)
duration Dauer der Beziehung/Mitgliedschaft
date Zeitpunkt des Ereignisses (1 = 10.11.1944, 2 = 04.12.1942, 3 = 18.10.1943, 4 = 1940, 5 = 1941, 6 = 1944, 7 = Oktober 1942, 8 = Fruehjahr 1942, 9 = Sommer 1942, 10 = Fruehjahr 1941, 11 = Juni 1944)

nodelist	Grundregel: die IDs der Nodelist muessen mit den IDs der Edgelist komplett uebereinstimmen. Auspraegungen der Attribute in der Regel numerisch definieren.											
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.											
name	Name der Person	
nickname	Spitzname der Person (innerhalb der Protestgruppe)									
age	Alter der Person zum Todeszeitpunkt 										
social group	Angehoerigkeit zu gesellschaftlicher Gruppe (1 = ehemaliger KZ-Haeftling, 2 = Ex-Soldat (desertiert), 3 = ("Halb"-)Jude, 4 = Arbeiter, 5 = Kommunist)	
sex Geschlecht der Person (1 = maennlich, 2 = weiblich, 3 = divers)
protest group Angehoerigkeit zu jeweiliger Untergruppe der Edelweisspiraten / Widerstandsbewegung (1 = Club, 2 = Ehrenfeld, 3 = Fricke, 4 = Leipziger Platz, 5 = Manderscheider Platz, 6 = Muelheim, 7 = Volksgarten, 8 = Steinbrueck)
death	Todesdatum
arrest Zeitpunkt der Verhaftung
release Zeitpunkt der Entlassung aus dem Gefaengnis																				
date of birth Geburtsdatum der Person
type Art des Knotens (1 = Person, 2 = Widerstandsgruppe, 3 = Ereignis)
