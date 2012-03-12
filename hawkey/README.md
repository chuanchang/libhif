This is hawkey, library providing simplified C and Python API to libsolv
[1].

## Building for Fedora

From your checkout dir:

    mkdir build
    cd build/
    cmake ..
    make

## Building with a custom version of libsolv

Libsolv is checked out at /home/akozumpl/libsolv, built at
/home/akozumpl/libsolv/build):

    mkdir build
    cd build/
    cmake -D LIBSOLV_PATH="/home/akozumpl/libsolv/" ..
    make

To trigger a rebuild of the libsolv header files remove solv/ in libsolv's build
directory.

## More information

Collaborators are welcome, contact Ales Kozumplik <akozumpl@redhat.com> with
ideas and patches.

[1] https://github.com/openSUSE/libsolv