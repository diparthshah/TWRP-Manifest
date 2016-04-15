#Setting up a minimal tree for building TWRP


###To initialize the main repository:

````
repo init -u https://github.com/diparthshah/TWRP-manifest.git -b master
````
```````
repo sync 
```````
BUILDING IT FOR GIONEE M2 

$ cd [twrp source which synced from above]

$ source build/envsetup.sh 

$ lunch omni_m2-userdebug 

$ make clean && make -j# recoveryimage  [# : no. of cpu cores ] 
