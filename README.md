# EGL Info

eglinfo is a little tool that dumps all available EGL configurations to stdout.

## Build (linux)

```
git clone <URL> src
#git clone --branch codefruit-no-x11 https://github.com/codefruit/eglinfo.git src

mkdir -p build
cd build

qmake ../src
make

./eglinfo
```
