# web scraper
simple web scraper for events

Für die Scrapper wurden die Seiten
- https://www.hall-tirol.at/veranstaltungen und
- http://www.stromboli.at/index.php/programm verwendet.

Für die Scrapper gebe es sicher elegantere Lösungen, er erfüllt jedoch seinen Zweck.  
Apache Airflow konnte leider nicht zum Laufen gebracht werden.  
Für Übung 6 wurde TfidfVectorizer von sklearn.feature_extraction.text verwendet, der die Ähnlichkeit von Strings bestimmt.  
Nach händischer Nachprüfung wurde die threshold auf 20% gesetzt.  
Events, die sich zu ähnlich sind, werden nicht in der DB gespeichert.  
Davon waren letztlich 2 von 83 Events betroffen.

