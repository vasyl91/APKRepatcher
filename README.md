# APKRepatcher

Updated [fork](https://www.youtube.com/watch?v=H3tnNVyCJfk) by cs.anurag.jain@gmail.com

I updated it probably only once for single purpose, therefore if you want any further updates, please pick your own fork.

# Website (Full Doc/Tutorial/Screenshot):
https://cooltrickshome.blogspot.in/2017/03/apkrepatcher-now-decompile-recompile.html

# How to create APKRepatcher.jar in case someone wants to update it in the future

1. Download and unpack or clone this repository.
2. Remove `APKRepatcher_lib` and `Projects` folders from directory `APKRepatcher-master`
3. Install [Eclipse](https://www.eclipse.org/downloads/)
4. `File` -> `Open Projects from File System...` 
5. Select `APKRepatcher-master` folder and press finish.
6. Update what you need. 
7. Right-click on source folder (`APKRepatcher`) -> Export...
8. Select `JAR file` and press `Next >`
9. Deselect every file in resources to export (`.classpath`, `.gitignore`, `.project`, `LICENSE` and so on), specify export destination path with file name `APKRepatcher`, press `Next >` and in the following window `Next >` again.
10. Check `Use existing manifest from workspace` and choose `APKRepatcher/MANIFEST.MF`. Press `Finish`
11. Copy generated `.jar` file to main directory of `APKRepatcher` folder (NOT `APKRepatcher-master`) containing `APKRepatcher_lib` (must contain all libs), `Projects` folders and `Settings.txt`. Or replace existing `APKRepatcher.jar` file in unpacked `APKRepatcher V1.1.1.rar`. 