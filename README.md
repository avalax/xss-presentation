
# Cross Site Scripting (XSS)

---

## Security Lab und Juice Shop
![cat](img/owasp_juice_shop.png)
* "Saftladen" mit diversen Sicherheitslücken

Quelle: http://bkimminich.github.io/juice-shop/#/


---

## OWASP

* Open Web Application Security Project
* Top Ten der Sicherheitsprobleme
* Ganz oben: XSS

---


## XSS

* Webserver Schadcode platzieren
* Zugriff der User über Browser
* Ungefilterte Inhalte werden von Webserver weitergreicht
* Skripte werden ausgeführt

---

## reflected XSS attack
```javascript
<script>alert("XSS1")</script>
```
* Forms
* Url parsing

---

## persisted XSS attack
```javascript
<script>alert("XSS2")</script>
```
* Database
* "external Scripts"

---

## Beef Framework
* Kali Linux: Penetration Testing Distribution
* BeEF Project: Browser Exploitation

![cat](img/beef.png)
![cat](img/beef_panel.png)

Quelle: picateshackz.com, funinformatique.com 

---

## Xenotics Framework
![cat](img/Xenotix.jpg)

Quelle: https://www.owasp.org/index.php/OWASP_Xenotix_XSS_Exploit_Framework

---

<iframe src="http://www.youtube.com/embed/HnhLMYjOOtQ?version=3&loop=1&playlist=HnhLMYjOOtQ" allowfullscreen="" frameborder="0" height="480" width="853"></iframe>

---

<iframe src="http://www.youtube.com/embed/eGOQqnfMdmI?version=3&loop=1&playlist=eGOQqnfMdmI" allowfullscreen="" frameborder="0" height="480" width="853"></iframe>

---

<iframe src="http://www.youtube.com/embed/RvYjfavvf2E?version=3&loop=1&playlist=RvYjfavvf2E" allowfullscreen="" frameborder="0" height="480" width="853"></iframe>

---

<iframe src="http://www.youtube.com/embed/qqv4887uWBk?version=3&loop=1&playlist=qqv4887uWBk" allowfullscreen="" frameborder="0" height="480" width="853"></iframe>

---

## Social Engineering
* nicht-technische Seite häufig nötig
* User werden manipuliert über falsche Informationen
* Aktives Zustimmen ermöglicht den Angriff
* z.B. Kamera aktivieren, Persistent Browser Keylogger "Update installieren"

---

## Fazit
* Vielfältige Angriffe sind möglich
* Sicherheit in der Webentwicklung
* Vertraue keinen externen Scripten
* Script block notwendig => Whitelist
