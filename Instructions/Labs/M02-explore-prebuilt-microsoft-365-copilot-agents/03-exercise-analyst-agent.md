Da Organisationen zunehmend datengesteuert arbeiten, ist die Fähigkeit, Erkenntnisse aus Rohdaten schnell zu interpretieren und zu kommunizieren, von entscheidender Bedeutung. Genau dies ermöglicht der Analyse-Agent von Microsoft 365 Copilot benutzenden Personen, indem er Daten direkt in vertrauten Tools wie Excel und Forms analysiert und visualisiert. Dieses Lab bietet eine praktische exemplarische Vorgehensweise zur Verwendung des Analyse-Agents, um vorhandene Datasets (sei es aus Umfragen, Tabellenkalkulationen oder Umfrageergebnissen) zu verstehen und mit minimalem Aufwand in umsetzbare Erkenntnisse umzuwandeln.

In dieser szenariobasierten Übung erfahren Sie, wie Sie den Analyse-Agent verwenden, um Trends zu untersuchen, Anomalien zu identifizieren und visuelle Elemente zu generieren, die das Data Storytelling verbessern. Ganz gleich, ob Sie Berichte über die Teamleistung, Kundenfeedback oder operative Metriken erstellen – in diesem Lab erfahren Sie, wie Sie aus bloßen Zahlen eine übersichtliche Zusammenfassung oder für Projektbeteiligte aufbereitete Diagramme erstellen. Der Analyse-Agent ist eine leistungsstarke Methode, um Zeit zu sparen, manuellen Aufwand zu reduzieren und Vertrauen in Ihre KI-gesteuerte analytische Entscheidungsfindung aufzubauen.

### Übung

Sie wurden beauftragt, die Umfrageergebnisse für eine interne Unternehmensinitiative namens „Project Nexus“ zu analysieren, ein sechswöchiges Pilotprogramm zur Verbesserung der abteilungsübergreifenden Zusammenarbeit mithilfe einer neuen digitalen Arbeitsbereichsplattform. Am Projekt waren Mitarbeitende aus verschiedenen Abteilungen beteiligt (darunter IT, Personalverwaltung, Marketing und Betrieb), die die Plattform für die tägliche Kommunikation, die Dokumentfreigabe und die Aufgabenverwaltung nutzen sollten. Ziel des Projekts war es, die Effektivität der Plattform im Hinblick auf die Verbesserung der Produktivität, die Optimierung der Kommunikation und die Einhaltung von Projektfristen zu bewerten. 

Nach Abschluss des Pilotprojekts wurden die Teilnehmenden befragt, um ihre Zufriedenheit mit dem Projekt, die Klarheit und Effektivität der Kommunikation, die Einhaltung des geplanten Zeitrahmens und ihre Gesamterfahrung mit dem neuen System zu bewerten. Sie möchten die Umfrageergebnisse von „Project Nexus“ mit dem vorkonfigurierten Analyse-Agent von Microsoft 365 Copilot untersuchen. Wie bei jedem vorkonfigurierten Agent können Sie Ihre eigenen benutzerdefinierten Prompts eingeben oder die Starterprompts des Agents verwenden. Die Starterprompts des Analyse-Agents sind dafür konzipiert, quantitative, qualitative und visuelle Analysen sowie allgemeine Erkenntnisse und Empfehlungen zu einem Projekt zu generieren.

Führen Sie die folgenden Schritte aus, um den Analyse-Agent anzuleiten, die Umfrageergebnisse zu „Project Nexus“ zu interpretieren und zu visualisieren:

1. Wählen Sie den folgenden Link aus, um eine Kopie der Datei [Project Nexus Survey Results](https://github.com/MicrosoftLearning/MS-4004-Empower-workforce-copilot-use-cases/raw/refs/heads/master/ResourceFiles/Project_Nexus_survey_results.xlsx) herunterzuladen. Wählen Sie oben auf dem Bildschirm die Schaltfläche **Herunterladen** aus, um die Datei auf Ihr Gerät herunterzuladen.
1. Öffnen Sie in **Microsoft Edge**eine neue Registerkarte, und geben Sie die folgende URL ein: [**https://M365copilot.com**](https://M365copilot.com)
1. Wählen Sie in **Microsoft 365** den **Analyse-Agent** aus, wenn er im Navigationsbereich im Abschnitt **Agents** angezeigt wird. Wählen Sie andernfalls im Navigationsbereich **Alle Agents** und dann im Fenster **Agents-Store** im Abschnitt **Erstellt von Microsoft** die Option **Analyse-Agent** aus. 
1. In **Microsoft 365** wird das Fenster **Analyse-Agent** angezeigt. Wählen Sie im Promptfeld das Symbol **Inhalt und Agents hinzufügen** (das Pluszeichen **+**) aus. 
1. Wählen Sie im daraufhin angezeigten Menü **Von diesem Gerät hochladen** aus. Navigieren Sie im **Datei-Explorer** zum Ordner **Downloads**, wählen Sie die zuvor heruntergeladene Datei **Project Nexus Survey Results** und dann **Öffnen** aus. 
1. Geben Sie im Promptfeld neben der verknüpften Datei „Project Nexus Survey Results“ den folgenden Prompt ein: **Analysiere diese Tabelle und nenne mir die drei wichtigsten Trends**.

   > [!NOTE]
   > Beachten Sie, dass der Analyse-Agent mehrere Python-Befehle ausführt, um die endgültige Liste der Trends zu erzeugen. Es kann etwa eine Minute dauern, bis alle Befehle ausgeführt sind und der Agent die Ergebnisse aggregieren und die drei wichtigsten Trends ermitteln kann. Unter jedem Befehl finden Sie eine Beschreibung der Ergebnisse des jeweiligen Befehls. Scrollen Sie in den Ergebnissen weiter nach unten, um die drei wichtigsten Trends anzuzeigen.
1. Da Sie einen tieferen Drilldown in jede Kategorie ausführen möchten, geben Sie zunächst den folgenden Prompt ein: **Wie lautet die durchschnittliche Bewertung für jede Umfragekategorie**?
1. Bei unseren Tests sieht die Rückgabe des Agents wie eine leere Seite aus. Tatsächlich ist es jedoch keine leere Seite, sondern nur ein großer Leerraum zwischen der Antwort des Agents und dem Promptfeld. Wenn dies bei Ihnen der Fall ist, scrollen Sie mit der vertikalen Scrollleiste nach oben. Dann sollten Sie die Antwort sehen. Wenn Sie auf der Seite ganz nach unten scrollen, sollten Sie das Promptfeld sehen. Dieser Agent ist neu. Daher scheint es so, als wäre der große leere Bereich ein Problem, das behoben werden muss. Bis Sie diese Übung durchführen, könnte das Problem mit dem überflüssigen Leerraum allerdings bereits behoben sein. Überprüfen Sie in jedem Fall die Ergebnisse. Wenn der Analyse-Agent einen nächsten Schritt wie „Möchten Sie einen visuellen Vergleich dieser Durchschnittswerte sehen?“ vorschlägt, geben Sie **Ja** in das Promptfeld ein (wenn das Problem mit dem Leerraum noch besteht, müssen Sie auf der Seite nach unten scrollen, um das Promptfeld anzuzeigen).
1. Scrollen Sie wieder nach oben zu den Ergebnissen des vorherigen Prompts (falls erforderlich), und prüfen Sie die Ergebnisse.
1. Sie können sich an dieser Stelle so viel Zeit nehmen, wie Sie möchten, um die Umfrageergebnisse mit dem Analyse-Agent zu analysieren. Sie können Ihre eigenen benutzerdefinierten Prompts eingeben oder einen der folgenden Prompts ausprobieren, je nachdem, welche Art von Analyse Sie ausführen möchten:
   - Prompts für die quantitative Analyse:
      - **Welche Kategorie erhielt die höchste durchschnittliche Bewertung und welche die niedrigste**?
      - **Wie viele Teilnehmende haben die Projektzufriedenheit mit 4 oder höher bewertet**?
      - **Wie hoch ist der Prozentsatz der Teilnehmenden, die die Einhaltung des Zeitrahmens mit einem Wert unter 3 bewertet haben**?
      - **Gibt es Korrelationen zwischen der Effektivität der Kommunikation und der Gesamterfahrung**?
   - Prompts für die qualitative Analyse:
      - **Fasse die häufigsten Themen im Kommentarabschnitt zusammen**.
      - **Gibt es wiederkehrende Probleme oder Vorschläge, die in den Kommentaren erwähnt werden**?
      - **Ermittle alle Kommentare, in denen Probleme mit der Kommunikation oder Zeitachse erwähnt werden**.
   - Prompts für Erkenntnisse und Empfehlungen:
      - **Was sind basierend auf den Umfragedaten die drei wichtigsten Stärken von „Project Nexus“**?
      - **Was sind die wichtigsten Verbesserungsbereiche, die von den Teilnehmenden vorgeschlagen werden**?
      - **Erstelle einen Zusammenfassungsbericht der Umfrageergebnisse mit umsetzbaren Empfehlungen**.
   - Prompts für die quantitative Visualisierung:
      - **Generiere ein Kreisdiagramm zur Verteilung der Gesamtbewertungen**.
      - **Erstelle ein Balkendiagramm mit einem Vergleich der durchschnittlichen Bewertungen für Projektzufriedenheit, Effektivität der Kommunikation, Einhaltung des Zeitrahmens und Gesamterfahrung**.
      - **Zeichne ein Histogramm der Zufriedenheitsbewertungen, das die Verteilung der Bewertungen zeigt**.
      - **Generiere ein Punktdiagramm, um die Beziehung zwischen der Effektivität der Kommunikation und der Gesamterfahrung zu analysieren**.
      - **Erstelle ein Wärmebild der Korrelation für alle numerischen Bewertungskategorien**.
      - **Erstelle ein Boxplotdiagramm für jede Bewertungskategorie, das die Spanne und die Quartile zeigt**.
      - **Zeichne ein Liniendiagramm, das die Bewertungen für die Einhaltung des Zeitrahmens der Teilnehmenden nach Teilnehmenden-IDs sortiert darstellt**.
