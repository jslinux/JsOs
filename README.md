##[runtime.js](https://github.com/runtimejs/runtime) os example application

### Install

Clone this repository and install dependencies:

```
git clone https://github.com/sasha240100/JsOs.git
cd JsOs
npm install
```

### Run

Make sure you have QEMU installed, then

```
npm start
```

*Note: runtime.js is work in progress*

### dependencies

see: https://github.com/runtimejs/runtime

```
# install dependencies
npm install runtimejs
npm install runtimeify -g
npm install runtime-tools -g

# bundle up ramdisk image
runtimeify index.js -o initrd

# make sure you have QEMU installed
brew install qemu           # OSX
sudo apt-get install qemu   # Ubuntu

# run it in QEMU
runtime-qemu ./initrd
```

