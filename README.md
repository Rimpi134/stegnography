# Stegnography with AI/ML
steganography application that provides two functionalities:

1. Data Hiding: It can hide any data within an image file.

2. Watermarking: Watermarking image files with an invisible signature. It can be used to detect unauthorized file copying.

## Usage

### For GUI:
Use menu shortcut for OpenStego if you used installer. For zip downloads, use the bundled batch file or shell script to launch the GUI.
```
stegnography.bat                (Windows)
```
```
./stegnography.sh               (Linux / MacOS)
```



## Development
Fork the repository, clone it locally and execute following to build it fully:
```
gradlew clean dist           (Windows)
```
```
./gradlew clean dist         (Linux / MacOS)
```
*Note:* Windows installer will be generated only if you execute build on Windows environment. It needs [Inno Setup](https://jrsoftware.org/isdl.php) to be installed, and `iscc.exe` to be on `PATH`. If you don't want to generate Windows installer, you can skip the same using following command:
```
./gradlew clean dist -x distWin
```

## Author
Rimpi Balmiki

## Homepage
https://github.com/Rimpi134/

## License
GNU General Public License 2.0 (GPL) (see ```LICENSE``` file)

