# drauger-plymouth-theme
Plymouth boot theme for Drauger OS

The only executable files in here should be the Post-Install, Pre-Remove, 
and Post-Remove scripts that go in the the \*.deb package. 

Everything else is handled by Plymouth, initramfs, or `update-alternatives`.

To install, run:

    ./build.sh
    
This will place a \*.deb file in the parent directory.

To install this package, you can use a package such as GDebi Package installer, or run

    sudo apt install /path/to/file.deb
