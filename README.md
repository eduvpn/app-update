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

The files are uploaded to:

    https://app.eduvpn.org/windows/update.json
    https://app.eduvpn.org/windows/update.json.minisig

And:

    https://app.letsconnect-vpn.org/windows/update.json
    https://app.letsconnect-vpn.org/windows/update.json.minisig
