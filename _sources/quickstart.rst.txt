Usage
=====

Using GUI portal for registering hostnames and assign IP address
****************************************************************

* Open the link https://edudns.services.fedcloud.eu/ in your browser:

.. image:: images/edudns-home.png
  :width: 512
  :alt: Vault scheme

* Click on ``Log in`` to go to login screen and choose eduTEAMS:

.. image:: images/edudns-login.png
  :width: 512
  :alt: Vault scheme

* After logging in via your eduTEAMS account, go to ``Overview`` tab:

.. image:: images/edudns-overview.png
  :width: 512
  :alt: Vault scheme

* Now you can manage your existing hostnames (if any) or register new ones. Click on
  ``Add Host`` to register a new hostname:

.. image:: images/edudns-create-host.png
  :width: 512
  :alt: Vault scheme

* Enter a hostname, choose a domain for your hostname then click on ``Create`` :

.. image:: images/edudns-create-host-demo.png
  :width: 512
  :alt: Vault scheme

* Your hostname has been create with a secret for updating IP. For your convenience, the
  whole URL for updating IP address (in form
  https://HOSTNAME:SECRET@@edudns.services.fedcloud.eu/nic/update ) is also printed for copy
  and paste. Save the URL securely for late use.

.. image:: images/edudns-url.png
  :width: 512
  :alt: Vault scheme

* Go back to the ``Overview`` tab, your newly registered hostname is now listed. Click
  on the hostname to perform any action: update IP address, show configuration or
  delete it:

.. image:: images/edudns-edit-host.pgn
  :width: 512
  :alt: Vault scheme

Using command line to update IP address
***************************************

For automation, it is useful to update IP address via command-line or API, e.g. for
assigning IP in installation script. Simply send a request to the URL, e.g. using ``curl``
command will update the IP address of the hostname to the actual host (where the command
is executed):

::

    $ curl https://demo.vm.edudns.eu:qZaSxT5GnC@edudns.services.fedcloud.eu/nic/update
    good 147.213.76.198






