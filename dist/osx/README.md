# Building the OS X bundle

Bundle Spek:

    ./dist/osx/bundle.sh CXX='/usr/bin/clang++' CPPFLAGS='-I/opt/local/include' CXXFLAGS='-Os' LDFLAGS='-L/opt/local/lib'
