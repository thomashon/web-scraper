# web scraper
simple web scraper for events

F�r die Scrapper wurden die Seiten
- https://www.hall-tirol.at/veranstaltungen und
- http://www.stromboli.at/index.php/programm verwendet.

F�r die Scrapper gebe es sicher elegantere L�sungen, er erf�llt jedoch seinen Zweck.  
Apache Airflow konnte leider nicht zum Laufen gebracht werden.  
F�r �bung 6 wurde TfidfVectorizer von sklearn.feature_extraction.text verwendet, der die �hnlichkeit von Strings bestimmt.  
Nach h�ndischer Nachpr�fung wurde die threshold auf 20% gesetzt.  
Events, die sich zu �hnlich sind, werden nicht in der DB gespeichert.  
Davon waren letztlich 2 von 83 Events betroffen.

