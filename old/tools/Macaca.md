sudo xcode-select -switch /Applications/Xcode.app/Contents/Developer

sudo chown -R $(whoami) /usr/local/lib/node_modules

platform=android macaca run -d ./macaca-test/mobile-app-sample.test.js