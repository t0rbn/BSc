* Was ist Projektarbeit und was sind die besonderen organisatorischen Herausforderungen?
* Warum möchte S2 so ein Tool?
* Requirements Analysis
  * funktional
  * nicht funktional
* Marktanalyse
  * was gibt es, was kann das, was es gibt? (z.B. Skills Base, engage! Talent Management, SkillsDB Pro)
  * Gibt es auf dem Markt das, was wir wollen?
* Konzept Eigenbau
  * Fitness Algorithmus
    * Wir bewerten, wie gut ein Mitarbeiter mit seinen Skills und Präferenzen die gesuchten Skills passt
    * Was muss ein Algorithmus können/sein, der das bewerten soll?
    * Gibt es schon passende Algorithmen, die man abwandeln kann?
    * Wie soll der eingesetzte Algorithmus konkret aussehen?
  * evtl. Recommendation für Suche
    * Ich suche Skill A und B, System schlägt mir vor nach Skill C zu suchen, weil das andere die A und B suchten auch taten
    * Was gibt es da so? (Stichwort Markovkette)
    * Wie kann man das bauen?
  * Interface und Nutzungsparadigmen (angerissen)
    * Wie soll sich die Anwendung anfühlen?
    * Wie viele Features/wie komplex zu bedienen?
* Umsetzung
  * Architektur
     * MongoDB (was ist das und warum will man es benutzen?)
     * LDAP
     * Reverse Proxy
     * API
  * Infrastruktur (rauswerfen?)
    * Maven
    * Gitlab CI/CD
  * Backend
    * Spring MVC, Data
    * LDAP Anbindung
    * Swagger
    * Testing
* Evaluierung
  * kann das Tool was wir wollten?
    * ableich mit aufgestellten Requirements
  * wie gehen Nutzer mit dem Tool um?
    * was wurde im Konzept nicht beachtet?
