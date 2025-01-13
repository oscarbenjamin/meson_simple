This project is a simple demonstration of how to build a Cython-based Python
package using meson and meson-python.

The steps to build and test locally are:

    git clone https://github.com/oscarbenjamin/meson_simple
    cd meson_simple
    pip install -r requirements-dev.txt
    meson setup build --wipe
    meson compile -C build
    spin test
