# my-macports-ports



# Usage

Edit `/opt/local/etc/macports/sources.conf`:

```
# Custom path before [default]
file:///Users/[Username]/YourPortsPath
rsync://rsync.macports.org/macports/release/tarballs/ports.tar.gz [default]
```

Import:

```bash
sudo portindex ~/YourPortsPath
```