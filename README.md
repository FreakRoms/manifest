
How to Build?
-------------

To initialize your local repository using the AospExtended trees, use a 
command like this:

```bash
  repo init -u git://github.com/AospExtended/manifest.git -b 7.x
```
  
Then to sync up:
----------------

```bash
  repo sync -c -jx --force-sync
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch aosp_device-userdebug
  mka bacon 
```
