Installation
============

Dieses Dokument beschreibt die Installation des Moduls OXID Cookie Management für den OXID eShop (Compilation) Version 6.2.0 bis 6.2.3. Ab OXID eShop 6.2.4 wird das Modul standardmäßig mit ausgeliefert. Haben Sie eine solche Shopversion im Einsatz, können Sie direkt mit der :doc:`Konfiguration <konfiguration>` des Moduls beginnen.

.. |schritt| image:: media/icons/schritt.jpg
               :class: no-shadow

Systemvoraussetzungen
---------------------
Für das Modul OXID Cookie Management sind keine speziellen Systemvoraussetzungen notwendig. Es gelten die des OXID eShop Version 6.2.x: https://docs.oxid-esales.com/eshop/de/6.2/installation/neu-installation/server-und-systemvoraussetzungen.html.

--------------------------------------------------

Neu-Installation
----------------

|schritt| Modul installieren
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Das Modul OXID Cookie Management muss aus dem Repository heruntergeladen und installiert werden. Dazu wird per Konsole folgendes Kommando im Hauptverzeichnis des Shops ausgeführt:

.. code:: bash

   composer require oxid-professional-services/usercentrics

|schritt| Modul aktivieren
^^^^^^^^^^^^^^^^^^^^^^^^^^
Das Modul muss im Shop unter :menuselection:`Erweiterungen --> Module` aktiviert werden. Auf der Registerkarte :guilabel:`Stamm` des Moduls betätigen Sie die Schaltfläche :guilabel:`Aktivieren`.

|schritt| Temporäre Dateien löschen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Löschen Sie alle Dateien und Ordner außer der Datei :file:`.htaccess` aus dem Verzeichnis :file:`/tmp` des Shops.


.. Intern: oxdajl, Status: