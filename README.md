# Raxfian OS for Marshmallow


To initialize the repo, run this in terminal:
-----------------------------------------------

repo init -u git://github.com/Raxfian-OS/manifest -b M-6.0

To sync up, run this in terminal:
----------------------------------

repo sync


To Build :- 
------------

. build/envsetup.sh
lunch
<choose Device>

make -j# otapackage

