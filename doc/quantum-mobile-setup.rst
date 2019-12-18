.. _quantum_mobile_setup:

Quantum Mobile setup
====================

Virtualbox VM
--------------

Ready to use AiiDA environment so-called Quantum Mobile is prepared by
AiiDA team but in this tutorial, we use slightly modified version of
it,
http://phonondb.mtl.kyoto-u.ac.jp/aiida_tutorial/Quantum_Mobile_ISSP.ova.
This is the virtualbox virtual machine (VM) image.

Virtualbox
~~~~~~~~~~
To use this, you need to
install virtualbox on your computer. Virtualbox is downloaded at
https://www.virtualbox.org/wiki/Downloads. It is recommended to
install the one for your operating system (linux, too) from this web
site.

Quantum Mobile VM
~~~~~~~~~~~~~~~~~
The VM image is downloaded at
http://phonondb.mtl.kyoto-u.ac.jp/aiida_tutorial/Quantum_Mobile_ISSP.ova. To
import this, File => Import Appliance.

Network and X-forwarding settings
---------------------------------
.. toctree::
   :maxdepth: 1

   macOS-setup
   windows-WSL-setup


Trouble shooting
~~~~~~~~~~~~~~~~
If you encounter any issue on the installation, please have a look at
this page, https://github.com/marvel-nccr/quantum-mobile/wiki/Frequently-Asked-Questions.

Ansible playbook
-----------------
For some people who want to install Quantum Mobile to your own
physical or virtual machine, you can use Ansible playbook provided by
AiiDA team, https://github.com/marvel-nccr/ansible-playbook-workhorse.
The short instruction is written in this page, but some knowledge on
Ansible is required.
