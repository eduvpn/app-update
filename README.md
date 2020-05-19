These files are used by the Windows application of Let's Connect! and eduVPN 
to fascilitate auto updating.

The JSON files are signed using 
[minisign](https://jedisct1.github.io/minisign/).

To generate a (new) key:

    $ minisign -G -p windows.pub -s windows.key

To sign:

    $ ./sign.sh

To upload:

    $ ./upload.sh
