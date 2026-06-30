# epl_acoustic_system
Distortion Products assay coupler

This is my personal fork of the original project
https://github.com/EPL-Engineering/epl_acoustic_system

TLDR; You want one and you don't want to build it? Ok Contact me.

You want to build one. Ok, I suggest the cui_driver version fitted with the db_driver/round2rect_fixture-Body.stl 3D printed adapter for the db driver to fit it. 

What is the process of making one of these like?
* buy all the parts for this project and
https://github.com/evanfoss/eef_acousticsyscable
https://github.com/evanfoss/eef_acousticsysmic
* cut and polish the fine stainless steel tubes to fit into the nose of the acoustic system.
* precision ream the holes in the 3D printed body of the device.
* precision align, and insert the tiny cut and polished tubes. Be sure to epoxy them with "2 Ton" epoxy or other similar hydrophobic slow cure adheasive. Do not get excess epoxy in the acoustic paths.
* insert db drivers into adapters and solder wires to them.
* insert the driver assemblies into the acoustic system body remembering to peel the plastic off the adheasive first.
* solder the wires to the connector. (again follow diagram)

What are all these files?

calibration - This is a calibration coupler for the device to a 1/4" microphone for calibration. While the use of a 1/8" microphone is prefered for calibration a simple to produce calibrator for that purpose is not yet available. This was designed by Ishmael.

pe275-010_driver - This version has great performance but it requires the pe275-010 tweeter from Parts-Express which is no longer available. This was a redesign of the cui_driver design done by Mike Ravicz with the assistance of the MGH Model Shop.

cui_drivers - This version is the last one EPL (Eaton Peabody Lab) used before the pe275-010 tweeter was found. The CUI driver has good max SPL but it isn't as even in frequency response because of breakup of the vibrational modes on the speaker cone. This was designed by Ishmael, Chis, Mike, using input from various parties.

db_driver - This contains both a version I designed clean sheet that has some cross talk issues. More importantly it contains the adapters needed to fit the db driver (which I believe is for cellphone speakers) into the cui_drivers 3D printed body. That is the one I currently produce on request. The smaller size of the driver means vibrational modes are not as much of a factor because it can be more rigid but the small size means it is more dependent on one time use only gasketting to reach higher SPL levels. Ishmael found the driver and I did the rest of the work.

nosepiece - Ishmael designed this precision machinable nose piece. Manufacturing this part requires a precision lathe for small parts and the ability to cut or better grind very small features.

wiring - This is the common wiring between all the acoustic systems here. Again Ishmael's handy work.


