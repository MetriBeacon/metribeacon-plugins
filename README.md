# MetriBeacon

Connect MetriBeacon to inspect your monitors, investigate incidents and explore retained measurements. The plugin includes six English and German skills for monitoring setup, server profiles, incident investigation, telemetry, analysis and reports, and status pages.

Add the plugin from your client’s directory, then connect https://metribeacon.com/mcp/catalog using OAuth. You need an existing MetriBeacon account. Read permissions are selected by default. Select config:write or telemetry:write only when you want to change configuration or send measurements. Workspace roles and account quotas apply to every operation.

The embedded overview, history and incident views display the results of authorized tools. They receive neither OAuth tokens nor private API credentials. Measurement values, event messages and monitoring configuration may be sent to your selected AI service when you request them. The service’s own privacy rules also apply.

Manage API keys, secret HTTP headers, notification credentials, subscribers and domain ownership checks on the MetriBeacon website. These operations are excluded from this plugin. Revoke access under Account → Plugin connections. Access tokens expire after 15 minutes; the connection expires after 30 days or seven days without use.

Documentation: https://metribeacon.com/documentation/mcp/plugins
Support: https://metribeacon.com/contact
Privacy: https://metribeacon.com/datenschutz
Terms: https://metribeacon.com/nutzungsbedingungen

The plugin files are licensed under MIT; see LICENSE. The MetriBeacon backend is not included.

# MetriBeacon

Verbinde MetriBeacon, um deine Monitore zu prüfen, Vorfälle zu untersuchen und aufbewahrte Messwerte auszuwerten. Das Plugin enthält sechs englische und deutsche Skills für die Monitoranlage, Serverprofile, Vorfallanalyse, Telemetrie, Analysen und Berichte sowie Statusseiten.

Füge das Plugin über das Verzeichnis deines Clients hinzu und verbinde https://metribeacon.com/mcp/catalog per OAuth. Du benötigst ein bestehendes MetriBeacon-Konto. Leserechte sind vorausgewählt. Wähle config:write oder telemetry:write ausdrücklich aus, wenn du Konfigurationen ändern oder Messwerte senden möchtest. Arbeitsbereichsrollen und Kontingente gelten bei jedem Aufruf.

Die eingebetteten Übersichts-, Historien- und Vorfallansichten zeigen Ergebnisse freigegebener Werkzeuge. Sie erhalten weder OAuth-Tokens noch private API-Zugangsdaten. Angeforderte Messwerte, Ereignistexte und Monitoring-Konfigurationen können an deinen gewählten KI-Dienst übermittelt werden. Dessen eigene Datenschutzregeln gelten zusätzlich.

API-Schlüssel, geheime HTTP-Header, Benachrichtigungszugangsdaten, Abonnenten und Domainnachweise verwaltest du auf der MetriBeacon-Website. Diese Vorgänge sind vom Plugin ausgeschlossen. Widerrufe Verbindungen unter Konto → Plugin-Verbindungen. Zugriffstokens laufen nach 15 Minuten ab; die Verbindung nach 30 Tagen oder sieben Tagen ohne Nutzung.

Dokumentation: https://metribeacon.com/de/documentation/mcp/plugins
Support: https://metribeacon.com/de/contact
Datenschutz: https://metribeacon.com/de/datenschutz
Nutzungsbedingungen: https://metribeacon.com/de/nutzungsbedingungen

Die Plugin-Dateien stehen unter MIT; siehe LICENSE. Der MetriBeacon-Backendcode ist nicht enthalten.
