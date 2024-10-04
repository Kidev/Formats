### Some of my custom formats
- `.clang-format` is adapted from the one made by the Qt team to work with the latest C++ initilization style (`int var {42}`). Otherwise, there are tweaks to match my personal code style, and ends up being a custom mix between Qt and Google style
- `.cmake-format` is adapted from the default one (`cmake-format --dump-config`) and is tweaked to have spaces before controls, to be easily readble. It's also adapted to work with Qt's CMake functions (`qt_add_qml_module`...)
