Installation
============

:productname:`OXID Cookie Management powered by usercentrics` 2.0 is shipped with OXID eShop 7.0 by default.

So in a normal installation you don't need to install the module, you can start configuring it directly.

However, depending on your OXID eShop installation, you can install the module manually if necessary.

|prerequisites|

You have OXID eShop version 7.x.

|procedure|

1. Download the :productname:`OXID Cookie Management` module from the repository and install it.

   To do so, in the main store directory (where the :file:`composer.json` file is located), run the following command:

   .. code:: bash

      composer require oxid-professional-services/usercentrics

2. To activate the module, do the following:

   a. Choose :menuselection:`Extensions --> Modules`.
   b. Choose the module.
   c. On the :guilabel:`master` tab of the module, choose the :guilabel:`Activate` button.

3. To delete temporary files, from the :file:`/tmp` directory of the store delete all files and folders except the :file:`.htaccess` file.

.. Internal: oxdajl, status:
