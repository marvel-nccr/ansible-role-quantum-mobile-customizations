# Welcome to {{ qm_customizations_vm_name }} version {{ qm_customizations_vm_version }}

*Quantum Mobile* is a Virtual Machine for computational materials science, distributed by the {{ qm_customizations_vm_author }}.

It comes with a collection of software packages for quantum mechanical calculations, including

 * [Quantum ESPRESSO](http://www.quantum-espresso.org/)
 * [Yambo](http://www.yambo-code.org/)
 * [fleur](http://www.flapw.de/)
 * [Siesta](https://gitlab.com/siesta-project/siesta)
 * [CP2K](https://www.cp2k.org)
 * [Wannier90](http://www.wannier.org)

all of which are set up and ready to be used on their own or through [AiiDA](http://www.aiida.net).

# Getting started

 * Click the Terminal icon and type `workon aiida`

 * All executables haven been installed in `/usr/local/bin`

 * Use `mpirun -np {{ qm_customizations_vm_cpus }}` in order to run in parallel.

 * Find pseudopotentials in `{{ qm_customizations_data_folder }}`

 * To share a folder with the VM, stop the VM, select
     Machine => Settings => Shared Folders => Add Folder Icon
   and tick "Automount". The folder will appear in "/media/sf_<folder_name>".

For troubleshooting, click the "FAQ" icon on the Desktop.
