# Lineage Manifests
Build Lineage 17.1 for i9515 (ALPHA)

![lineage logo](https://github.com/linusdan/local_manifests/raw/lineage-16.0/lineage.png)


```
1. mkdir -p lineage-17.1

2. cd lineage-17.1

3. Initialize your local repository using the Lineage trees, use a command
  repo init  --depth=1 -u git://github.com/LineageOS/android.git -b lineage-17.1
  
4. Sync it:
  repo sync -c --force-sync --no-tags --no-clone-bundle -j4 --optimized-fetch --prune 

5. Clone my repo:
  git clone https://github.com/SparXFusion/jf_manifest.git -b lineage-17.1 .repo/local_manifests

6. Sync the repo:
  repo sync --no-tags --no-clone-bundle --force-sync -c

7. To build:
  . build/envsetup.sh
  lunch jfvelte
  brunch jfvelte
```

Credits
-------
* [**rINanDO**](https://github.com/rINanDO)
* [**LineageOS**](https://github.com/LineageOS)
