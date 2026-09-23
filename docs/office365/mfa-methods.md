# Übersicht der verfügbaren Methoden für die Zwei-Faktor-Authentifizierung

Die Zwei-Faktor-Authentifizierung (MFA) ist ein Sicherheitsmechanismus, der eine zusätzliche Schutzstufe für Konten bietet. Hier sind die verfügbaren Methoden:

## Microsoft Authenticator App
- **Beschreibung:** Die Microsoft Authenticator App generiert Einmalcodes, die zur Anmeldung verwendet werden können. Sie kann auch Push-Benachrichtigungen senden, um die Anmeldung zu bestätigen.
- **Vorteile:** Schnell, sicher und bequem. Keine Notwendigkeit, einen Code einzugeben. Einrichtung auf mehreren Geräten ist problemlos möglich.
- **Nachteil:** Erfordert eine zusätzliche App.

## Andere Authenticator Apps
- **Beschreibung:** Neben der Microsoft Authenticator App können auch andere Authenticator Apps wie Google Authenticator, die meisten Passwortmanager oder andere Sicherheitsanwendungen verwendet werden, die ebenfalls Einmalcodes generieren. 
- **Hinweis:** Die Einrichtung dieser ist etwas versteckt. Zuerst auf Microsoft Authenticator App klicken, dann auf "Ich möchte eine andere Authenticator-App verwenden" und den QR-Code mit der gewünschten App scannen.
- **Vorteile**: Flexibilität bei der Wahl der App, ebenso schnell und sicher wie die Microsoft Authenticator App. Einrichtung auf mehreren Geräten ist oft über Cloud-Synchronisierung möglich.
- **Nachteil:** Kann eine zusätzliche App und mehr Einrichtungsschritte erfordern.

## E-Mail
- **Beschreibung:** Ein Einmalcode wird an die hinterlegte **private** E-Mail-Adresse gesendet.
- **Vorteile:** Einfach zu verwenden, keine zusätzliche App erforderlich.
- **Nachteil:** Weniger sicher als andere Methoden, da E-Mail-Konten anfällig für Phishing-Angriffe sein können. Außerdem kann es zu Verzögerungen bei der Zustellung kommen und es ist ein privates E-Mail-Konto erforderlich.
  
## Passkey
- **Beschreibung:** Passkeys sind eine moderne Authentifizierungsmethode, die eine Kombination aus biometrischen Daten (wie Fingerabdruck oder Gesichtserkennung) und kryptografischen Schlüsseln verwendet. Passkeys sind die sicherste Methode und erfordern keine Passworteingabe, da sie die beiden Faktoren in einem einzigen Schritt kombinieren. Sie können auf mehreren Geräten verwendet werden, was die Flexibilität erhöht.
- **Vorteile:** Sehr sicher. Benutzerfreundlich, da zukünftig keine Passwörter eingegeben werden müssen. Lassen sich auf mehreren Geräten synchronisieren.
- **Nachteil:** Erfordert ein Gerät, das Passkeys unterstützt, und möglicherweise eine zusätzliche Einrichtung. I.d.R. ist ein Passwortmanager für die Verwaltung von Passkeys erforderlich.



