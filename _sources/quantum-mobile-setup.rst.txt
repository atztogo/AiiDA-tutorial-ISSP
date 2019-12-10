.. _quantum_mobile_setup:

Quantum Mobile setup
====================

Virtualbox VM
--------------

Ready to use AiiDA environment so-called Quantum Mobile is prepared by
AiiDA team at
https://github.com/marvel-nccr/quantum-mobile/releases/. This is the
virtualbox virtual machine (VM) image. 

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
https://github.com/marvel-nccr/quantum-mobile/releases/. To import
this VM image, you can just follow the installation instruction
written this page. To download the VM image, it may need long time
from Japan. Therefore the same VM image is put on Kyoto university,
http://phonondb.mtl.kyoto-u.ac.jp/quantum_mobile_19.09.0.ova, before
and during the AiiDA tuotrial ISSP Univ. Tokyo.

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
