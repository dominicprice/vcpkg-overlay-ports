# vcpkg-overlay-ports

The overlay ports which I use with vcpkg to control versioning. 

# Usage

To ensure vcpkg uses a particular version of a library, pass it the `--overlay-ports=/path/to/portfiledir` argument, so to install
gtkmm3 use `vcpkg --overly-ports=<this-repo>/gtkmm3-22 install gtkmm:x64-windows`.
