# License info

While the actual code in this repository is covered by the provided [license](LICENSE),
using freesurfer and FSL requires accepting their respective licenses. By using this
container, you must agree to these licenses.

[Freesurfer license](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferSoftwareLicense)

[FSL license](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/Licence)

You must acquire a freesurfer license from 
https://surfer.nmr.mgh.harvard.edu/registration.html
Ensure that the license file is visible from the container,
and set the environment variable FS_LICENSE to point to it
(or copy the file to /opt/freesurfer/license.txt from
inside the container)
