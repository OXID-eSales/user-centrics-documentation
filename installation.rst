Installation
============

:productname:`OXID Cookie Management powered by usercentrics` 2.0 wird standardmäßig mit OXID eShop 7.0 ausgeliefert.

Bei einer normalen Installation müssen Sie das Modul also nicht installieren, sondern können direkt mit dem Konfigurieren loslegen.

Abhängig von Ihrer Installation des OXID eShops können Sie das Modul jedoch bei Bedarf manuell nachinstallieren.

|prerequisites|

Sie haben OXID eShop Version 7.0 oder höher.

|procedure|

1. Laden Sie das Modul :productname:`OXID Cookie Management` aus dem Repository herunter und installieren Sie es.

   Führen Sie dazu im Hauptverzeichnis des Shops (in dem die Datei :file:`composer.json` liegt) folgenden Befehl aus:

   .. code:: bash

      composer require oxid-professional-services/usercentrics

2. Um das Modul zu aktivieren, tun Sie Folgendes:

   a. Wählen Sie :menuselection:`Erweiterungen --> Module`.
   b. Wählen Sie das Modul.
   c. Wählen Sie auf der Registerkarte :guilabel:`Stamm` des Moduls die Schaltfläche :guilabel:`Aktivieren`.

3. Um temporäre Dateien zu löschen, löschen Sie aus dem Verzeichnis :file:`/tmp` des Shops alle Dateien und Ordner außer der Datei :file:`.htaccess`.

.. Intern: oxdajl, Status: