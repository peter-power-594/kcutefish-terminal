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

## License

This project has been licensed by GPLv3.
