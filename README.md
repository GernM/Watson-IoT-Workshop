# Watson-IoT-Workshop

Die erste eigene IoT App: Avnet IoT Hands-On Workshop

Behandelte Themen: Raspberry Pi, Node-RED, Watson Internet of Things Platform, Cloudant NoSQL Database, Twitter, Twilio, und Wetterdaten für IBM Bluemix.

In diesem Workshop werden wir ein Raspberry Pi und den passenden SenseHat verwenden um eine Verbindung zu IBM Bluemix und der Watson IoT Platform herzustellen. 
Wir werden die Temperatur über das SenseHat abfragen und Daten an die Watson IoT-Plattform senden. 
Mit Node-RED, auf dem Raspberry Pi und in Bluemix, liest die Anwendung den Temperaturwert von dem SenseHat. Steigt die Temperatur an, wird eine LED-Anzeige eingeschaltet. Die Temperatur wird über Watsons Internet of Things Platform-Dienst an eine Node-RED-Anwendung gesendet, die auf IBM Bluemix gehostet wird. Wenn das SenseHAT übermäßige Beschleunigungsschocks erleidet, senden wir dies als Message.
Wir werden Außenwetterdaten abrufen und auf einem LED-Bildschirm anzeigen, der mit dem SenseHat verbunden ist. Wir speichern Beschleunigungsschocks in einer Cloudant NoSQL-Datenbank um Muster in den Daten erkennen zu können. Schließlich erstellen wir einen HTTP-Endpunkt, der die historischen Beschleunigungsschocks enthält, die Drittanbieteranwendungen verwenden um Analysen oder andere Dinge ausführen zu können.

