# linuxdeployqt

__This is not working yet.__ Help is appreciated.

```
Usage: linuxdeployqt app-binary [options]

Options:
   -verbose=<0-3>     : 0 = no output, 1 = error/warning (default), 2 = normal, 3 = debug
   -no-plugins        : Skip plugin deployment
   -appimage          : Create an AppImage
   -no-strip          : Don't run 'strip' on the binaries
   -use-debug-libs    : Deploy with debug versions of frameworks and plugins (implies -no-strip)
   -executable=<path> : Let the given executable use the deployed frameworks too
   -qmldir=<path>     : Scan for QML imports in the given path
   -always-overwrite  : Copy files even if the target file exists
   -libpath=<path>    : Add the given path to the library search path

linuxdeployqt takes an application as input and makes it
self-contained by copying in the Qt libraries and plugins that
the application uses.
```