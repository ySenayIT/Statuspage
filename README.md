# ySenayIT Statusseite - Anleitung

  

Diese Anleitung führt dich Schritt für Schritt durch die Installation der Semi-Selfhosted Statusseite von ySenayIT.

  

## Installation auf dem Webserver

 ### Vorraussetzungen:
 - PHP Version > 7.3
 - Apache/nginx Webserver installierrt

  
### Installation:
Lade die `installer.php` Datei von unserer GitHub-Repo auf deinen Webserver herunter und öffne in deinem Browser folgende URL: `http(s)://DEINEIPADRESSE/installer.php`

Gebe jetzt deine Lizenzdaten ein und klicke auf "Installieren".
Nach einem Moment sollte sich die Statusseite automatisch neu laden und die Inhalte geladen werden.


### Status neu laden:
Die Verbindung zu den einzelnen Elementen, dessen Status abgefragt werden soll, wird in einem Intervall von einer Stunde überprüft. Dies passiert automatisch über den Zentralserver - Nicht über deinen (Deshalb auch Semi-Selfhosted)

