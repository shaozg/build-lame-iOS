# lame-ios-build

script to build lame for iOS

## Usage

* build fat library for all architectures
```
./build-lame.sh
```

* build libraries for specified architectures
```
./build-lame.sh arm64 x86_64
```

* build fat library from thin libraries
```
./build-lame.sh lipo
```

