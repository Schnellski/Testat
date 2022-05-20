# Codebuch 
									
Erhoben wurden die Daten aus folgender Quelle: https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79

NA: "definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus. (Wie von ihnen angegeben)	"								

								
## nodelist

id: Vereinsname/Rückennummer/Nationalität des Spielers	

country: Land		

name: Spielername/Vereinsname	

type: Art des Akteurs (1: Spieler, 2: Verein) 

			
									
## edgelist				

from: Land bzw. Verein des Spielers/Rückennummer

to: Rückennummer des Spielers		

weight: Transfersumme in 100.000 Euro Schritten, gerundet falls abweichend	

season: transferfenster. nur erste Jahreszahl des Fensters als JJJJ verwenden							
									
									
									
									
									
