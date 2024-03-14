Installation
============

.. todo: #HR: verifizieren: standardmäßig mit OXID eShop 7.x, 7.1?

:productname:`OXID Cookie Management powered by usercentrics` 3.0 wird standardmäßig mit OXID eShop 7.1 ausgeliefert.

Bei einer normalen Installation müssen Sie das Modul also nicht installieren, sondern können direkt mit dem Konfigurieren loslegen.

Abhängig von Ihrer Installation des OXID eShops können Sie das Modul jedoch bei Bedarf manuell nachinstallieren.

.. todo: #HR: folgt etwas aus den Änderungen:
            Gibt es neue Funktionen
            oder
            reicht es, wie bisher auf index.html auf das Changelog zu verweisen?
    ### Added
    - ``Core\ViewConfig::getUsercentricsModuleSettings``
    - ``Service\Integration\Pattern\*->scriptSource`` type definition
    - ``Service/ModuleSettingsInterface::getSmartProtectorBlockingDisabledServices``
    - Code style tools
    ### Removed
.. todo: #HR: folgt etwas daraus, dass Smarty nicht mehr unterstützt wird, weisen wir darauf hin?
    - Smarty support
    - ``Core\ViewConfig`` methods:
      - ``getUsercentricsID``
      - ``isSmartDataProtectorActive``
      - ``isDevelopmentAutomaticConsentActive``
      - ``getSmartDataProtectorDeactivateBlockingServices``
    ### Changed
    - Rename ``getSmartProtectorBlockingDisabledList`` to ``getSmartProtectorBlockingDisabledServices`` and change return
    type to ``string[]`` for:
      - ``Service/ModuleSettingsInterface``
      - ``Service/ModuleSettings``
    - Change ``Service/ModuleSettings::getStringSettingValue`` from protected to private


|prerequisites|

.. todo: #HR: verifizieren: OXID eShop 7.x, 7.1?

Sie haben OXID eShop Version 7.1.

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