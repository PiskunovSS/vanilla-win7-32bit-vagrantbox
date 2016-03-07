Diese Box hat den fokus auf
---------------------------

* vagrant-konformes Windows 7 32bit
* Basissystem ohne zusatzsoftware
* Nicht sicher sondern komfortabel
* deutsch


Folgende Schritte m�ssen zur Erstellung im GUI der VM manuell durchgef�hrt werden
---------------------------------------------------------------------------------

* Download most up to date image from "https://dev.windows.com/en-us/microsoft-edge/tools/vms/windows/"
* Unpack image
* ``vagrant box add "IE11 - Win7.box" --name IE11Win7`` auf host ausf�hren
* ``vagrant up``
* Networklocation auf "Home Network" einstellen (aber nichts freigeben)
* ``\\VBOXSRV\vagrant\step1_run_on_guest_as_IEUser_as_admin.cmd`` auf guest als admin ausf�hren
* "Agree" anklicken
* ``\\VBOXSRV\vagrant\step2_run_on_guest_as_vagrant_as_admin.cmd`` auf guest als admin ausf�hren
* ``\\VBOXSRV\vagrant\step3_run_on_host.cmd`` auf host ausf�hren