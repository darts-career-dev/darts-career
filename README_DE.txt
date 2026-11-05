DARTS CAREER – Web Prototype 0.1

Enthalten:
- 3D-Dartboard in Three.js
- Touch-/Maus-Timing in zwei Schritten
- 501 Double-Out und Bust-Regel
- Single-, Double-, Triple- und Bull-Wertung
- einfache Anzeige für Punkte und Aufnahme

Start am PC:
1. ZIP entpacken.
2. Terminal/Eingabeaufforderung im Ordner öffnen.
3. `python -m http.server 8000` ausführen.
4. Browser auf `http://localhost:8000` öffnen.

iPhone-Test:
PC und iPhone müssen im selben WLAN sein. Am PC die lokale IP-Adresse
ermitteln und auf dem iPhone in Safari `http://PC-IP:8000` öffnen.
Alternativ kann der Ordner auf einen statischen Webhoster geladen werden.

Technik:
HTML, CSS, JavaScript und Three.js über jsDelivr (Internet nötig).

Grenzen:
Dies ist ein früher spielbarer Prototyp, kein fertiges Spiel. Der Dartflug ist
noch vereinfacht; die Position wird aus dem Timing abgeleitet. Karriere,
Gegner-KI, Spielereditor, Speicherstände, Kommentatoren, Animationen und
fertige App-Veröffentlichung fehlen noch. Die Web-Version ist der erste
Entwicklungsschritt; später können wir die Spiellogik in Unity übertragen.
