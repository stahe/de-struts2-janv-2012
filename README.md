# Einführung in das Struts-2-Framework anhand von Beispielen (2012)

🔗 **Online-Kurs:**
[https://stahe.github.io/de-struts2-janv-2012/](https://stahe.github.io/de-struts2-janv-2012/)

---

## Überblick

Dieses Dokument bietet eine **Einführung in das Struts 2-Framework** anhand eines schrittweisen, auf Beispielen basierenden Ansatzes.

Struts 2 ist ein Java-Web-Framework, das Folgendes bereitstellt:

* eine Reihe von Bibliotheken, die als **JAR**-Dateien verteilt werden
* ein Entwicklungsframework, das die Strukturierung der Webanwendungsentwicklung regelt

Ziel ist es, die grundlegenden Konzepte von Struts 2 durch praktische Übungen zu verstehen.

---

## Voraussetzungen

Um den Beispielen folgen zu können, benötigen Sie:

* Grundkenntnisse in **Java**
* Grundkenntnisse in der **Webentwicklung**, insbesondere in **HTML**

Weitere Ressourcen finden Sie unter:

* [https://stahe.github.io](https://stahe.github.io)

---

## Weiterführende Literatur

Weitere Informationen:

* **[ref1]** Offizielle Dokumentation zu Struts 2 (offizielle Projekt-Website)
* **[ref2]** *Struts 2 in Action*
  Donald Brown – Chad Michael Davis – Scott Stanlick
  Manning Publications

Das Dokument verweist gelegentlich auf *Struts 2 in Action*, um bestimmte technische Aspekte näher zu erläutern.

---

## Lernziel

Dieses Dokument wurde so verfasst, dass es auch ohne Computer gelesen werden kann.
Es enthält zahlreiche Screenshots, um das Verständnis zu erleichtern.

---

## Die Rolle von Struts 2 in einer Webanwendung

Struts 2 arbeitet **ausschließlich innerhalb der Webschicht** einer typischen mehrschichtigen Architektur.

### Allgemeine Architektur

Eine typische Webanwendung kann wie folgt aufgebaut sein:

### 1️⃣ Web-Schicht

* Benutzeroberfläche (Browser)
* Verarbeitung von HTTP-Anfragen
* Generierung von Antworten
* **Struts 2 befindet sich ausschließlich in dieser Schicht**

### 2️⃣ Geschäftsschicht

* Implementiert die Geschäftsregeln
* Beispiel: Berechnung eines Gehalts, Erstellung einer Rechnung
* Verwendet:
  * Daten aus der Webschicht
  * Daten aus der Datenbank über die DAO-Schicht

### 3️⃣ DAO-/JPA-/JDBC-Schicht

* Verwaltung des Datenzugriffs
* DAO: Data Access Objects
* JPA: Java Persistence API
* JDBC: Low-Level-Datenbankzugriff
* JPA fungiert als ORM (Object Relational Mapper)

### 4️⃣ Integration der Schichten

Kann bereitgestellt werden durch:

* **Spring**
* **EJB3 (Enterprise Java Bean)**

---

## Aufbau der Beispiele

Die meisten Beispiele in diesem Dokument verwenden **nur die Web-Ebene**, um sich auf Struts 2 zu konzentrieren.

Am Ende des Dokuments wird eine **vollständige mehrschichtige Webanwendung** erstellt:
* Web-Schicht
* Geschäftslogik-Schicht (Business Layer)
* DAO-Schicht (Data Access Object)
* JPA-/Hibernate-Schicht
* Datenbankzugriff über JDBC
Die Geschäftslogik- und Persistenzschichten werden als JAR-Dateien bereitgestellt, damit sich der Leser hauptsächlich auf die Web-Schicht konzentrieren kann.
---

## Zielgruppe

* Java-Entwickler, die Struts 2 erlernen möchten
* Studierende der Java-Webentwicklung
* Alle, die die Integration von Struts 2 in eine mehrschichtige Architektur verstehen möchten

---

## Autor

Serge Tahé: Kurs ursprünglich veröffentlicht auf developpez.com
Version 2012

---
