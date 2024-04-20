# CutefishOS Terminal

A terminal emulator for Cutefish.

### Third Party Code

[qmltermwidget](https://github.com/Swordfish90/qmltermwidget).

## OpenMandriva Dependencies

```shell
sudo dnf in task-develop
sudo dnf install extra-cmake-modules
(qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev)
```

## Ubuntu

```shell
sudo apt install extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev
```

## Build

```shell
mkdir build
cd build
cmake ..
make
```

## Install

```shell
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-terminal
rm /usr/share/applications/cutefish-terminal.desktop
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/libcutefishqmltermwidget.so
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/qmldir
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/QMLTermScrollbar.qml
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/BlackOnLightYellow.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/BlackOnRandomLight.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/BlackOnWhite.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/BreezeModified.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/cool-retro-term.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/Cutefish-Dark.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/Cutefish-Light.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/DarkPastels.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/GreenOnBlack.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/BlackOnLightColor.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/DarkPicture.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/Example.Schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/GreenOnBlack.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/GreenTint.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/GreenTint_MC.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/LightPicture.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/Linux.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/README.default.Schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/README.Schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/syscolor.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/Transparent.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/Transparent_darkbg.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/Transparent_lightbg.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/Transparent_MC.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/vim.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic/XTerm.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/Linux.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/Solarized.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/SolarizedLight.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/Tango.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/Ubuntu.colorscheme
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/WhiteOnBlack.schema
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/default.keytab
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/historic
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/historic/vt100.keytab
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/historic/x11r5.keytab
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/linux.keytab
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/macbook.keytab
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/README
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/solaris.keytab
rm /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts/vt420pc.keytab
rm -rf /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes/historic
rm -rf /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/color-schemes
rm -rf /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/kb-layouts
rm -rf /usr/lib/x86_64-linux-gnu/qt5/qml/Cutefish/TermWidget/
```

## License

This project has been licensed by GPLv3.
