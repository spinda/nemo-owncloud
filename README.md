# nemo-owncloud

Adds ownCloud integration to the [Nemo](https://github.com/linuxmint/nemo) file
manager.

Adapted from the Nautilus ownCloud plugin by Klaas Freitag.

Requires
[`owncloud-client`](https://www.archlinux.org/packages/community/x86_64/owncloud-client/)
and
[`nemo-python`](https://www.archlinux.org/packages/community/x86_64/nemo-python/).

## Usage

Install `usr/share/nemo-python/extensions/syncstate.py` to the corresponding
directory on your system.

Make sure the ownCloud client is running, then run `nemo -q` to close any
running Nemo instances and load the plugin.

The ownCloud client must be running before Nemo opens, or the plugin will fail
to load.

## License

GPLv2 or later (see
[`syncstate.py`](usr/share/nemo-python/extensions/syncstate.py))

