# epl_acoustic_system
Distortion Products assay coupler

This is my personal fork of the original project
https://github.com/EPL-Engineering/epl_acoustic_system

Authorship Note: I was a contributor in trivial ways to earlier version of the acoustic system but the only versions I got to design more or less clean sheet was the db_driver which is still in progress. The db_driver I did from scratch along with the other content of that directory.

pe275-010_driver - This version has great performance but it requires the pe275-010 tweeter from Parts-Express which is no longer available.

cui_drivers - This version is the last one EPL (Eaton Peabody Lab) used before the pe275-010 tweeter was found. The CUI driver has good max SPL but it isn't as even in frequency response because of breakup of the vibrational modes on the speaker cone.

db_driver - This contains both a version I designed clean sheet that has some cross talk issues. More importantly it contains the adapters needed to fit the db driver (which I believe is for cellphone speakers) into the cui_drivers 3D printed body. That is the one I currently produce on request. The smaller size of the driver means vibrational modes are not as much of a factor because it can be more rigid but the small size means it is more dependent on one time use only gasketting to reach higher SPL levels.


