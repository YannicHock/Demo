# Demo-Projekt

Dieses Demo-Projekt dient als Beispielanwendung, um grundlegende Java-Funktionalitäten zu demonstrieren. Es enthält eine einfache `main`-Methode, die eine Begrüßungsnachricht ("Hello World!") in der Konsole ausgibt.

## Zweck

- Demonstration einer minimalen Java-Anwendung.
- Verwendung von Maven zur Projektverwaltung.
- Integration von Javadocs in das Projekt und die Maven-Site.
- Bereitstellung der generierten Maven-Site (inklusive Javadocs) über GitHub Pages.

## Voraussetzungen

- Java 21 oder höher
- Maven 3.x

## Ausführung

1. Klonen Sie das Repository:
   ```bash
   git clone https://github.com/YannicHock/Demo.git
   cd Demo
   ```
2. Bauen und starten Sie die Anwendung:
   ```bash
   mvn compile
   mvn exec:java -Dexec.mainClass="de.hock.demo.Demo"
   ```
   
3. Generieren Sie die Maven-Site (inklusive Javadocs):
    ```bash
   mvn site
    ```

Die generierte Site kann lokal unter `target/site/index.html` angezeigt werden oder wird bei Verwendung von GitHub Actions automatisch auf GitHub Pages veröffentlicht.