# 💰 Gehalts- & Arbeitszeitrechner (Deutschland)

Dieses Streamlit-Web-Tool ermöglicht es Benutzern, ihr monatliches Netto-Einkommen basierend auf deutschen Steuergesetzen zu berechnen und abzuschätzen, wie lange sie für eine bestimmte Anschaffung arbeiten müssen.

Die Anwendung kombiniert einen detaillierten Gehaltsrechner mit einem Budget-Tool für Fixkosten und bietet zusätzlich einen praktischen Affiliate-Link-Generator für Amazon-Produkte.

## 🔗 Live-Anwendung

Die Web-Anwendung ist unter der folgenden Adresse erreichbar:

**[https://mini-webapp-niklassch.streamlit.app/](https://mini-webapp-niklassch.streamlit.app/)**

---

## ✨ Funktionen im Überblick

* **Detaillierte Nettogehalt-Berechnung:** Berücksichtigt Bruttogehalt, Steuerklasse, Bundesland (für Kirchensteuer), Kinderfreibetrag und Anstellungsverhältnis (Angestellte, Werkstudenten).
* **Sozialabgaben und Steuern:** Berechnet Lohnsteuer, Solidaritätszuschlag, Kirchensteuer, Kranken-, Renten-, Arbeitslosen- und Pflegeversicherung auf Basis der aktuellen Beitragsbemessungsgrenzen (BBG).
* **Fixkosten-Manager:** Benutzer können eine Liste ihrer monatlichen Fixkosten hinzufügen, bearbeiten und löschen, um das tatsächlich **verfügbare Einkommen** zu ermitteln.
* **Arbeitszeit-Rechner:** Ermittelt den **Netto-Stundenlohn** und zeigt, wie viel vom Nettogehalt nach Abzug der Fixkosten übrig bleibt.
* **Amazon Affiliate-Link-Generator:** Ein Tool, um schnell einen Amazon-Suchlink mit hinterlegtem Affiliate-Tag (`affiliatesche-21`) zu generieren.

## 🛠️ Technologie

Die Anwendung basiert vollständig auf:

* **Python:** Die Programmiersprache der Wahl.
* **Streamlit:** Das Framework zur schnellen Erstellung der Web-Applikation.
* **Streamlit Community Cloud:** Die Hosting-Plattform für die Bereitstellung.

## 📚 Wichtige Hinweise & Disclaimer

### Haftungsausschluss

**Wichtig:** Diese Anwendung dient ausschließlich **Informations- und Simulationszwecken**. Alle Berechnungen (insbesondere zur Lohnsteuer und den Sozialabgaben) erfolgen **ohne Gewähr** und können von den tatsächlichen Werten Ihrer Lohnabrechnung abweichen. Für verbindliche Auskünfte konsultieren Sie bitte einen Steuerberater oder nutzen Sie offizielle Rechner.

### Transparenz & Affiliate-Hinweis

Diese Website nimmt am Amazon-Partnerprogramm teil.

* Der enthaltene **Amazon Link zum Produkt Generator** verwendet den Affiliate-Tag `affiliatesche-21`.
* Als Amazon-Partner verdiene der Betreiber **Niklas Schelkle** an qualifizierten Verkäufen, die über diese Links generiert werden.
* Für Nutzer entstehen durch die Verwendung dieser Links **keine Mehrkosten**.

### Impressum und Datenschutz

Die notwendigen rechtlichen Angaben (Impressum, Kontakt) sowie Hinweise zum Datenschutz sind im Footer der Anwendung verankert, um den gesetzlichen Anforderungen in Deutschland zu entsprechen.

---

## 🚀 Lokale Installation und Start

Möchten Sie das Projekt lokal ausführen und weiterentwickeln?

1.  **Repository klonen:**
    ```bash
    git clone [IHRE_REPO_URL]
    cd [PROJEKT-ORDNER]
    ```

2.  **Virtuelle Umgebung erstellen und aktivieren (Optional, aber empfohlen):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Unter Windows: .\venv\Scripts\activate
    ```

3.  **Abhängigkeiten installieren:**
    Die Anwendung benötigt lediglich Streamlit.
    ```bash
    pip install streamlit
    ```

4.  **Anwendung starten:**
    ```bash
    streamlit run [DATEINAME].py
    # Ersetzen Sie [DATEINAME].py durch den tatsächlichen Namen Ihrer Python-Datei (z.B. app.py)
    ```
    Die Anwendung wird automatisch in Ihrem Standardbrowser unter `http://localhost:8501` geöffnet.
