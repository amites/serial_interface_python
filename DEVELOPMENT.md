# Install Guix
[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)

# Clone Repository

```shell
git clone https://github.com/janelia-pypi/serial_interface_python
cd serial_interface_python
```

# Edit .single-source-of-truth

```shell
make dev-shell
make edits
make files
exit
```

# Test Python package using ipython shell

```shell
make ipython-shell
import serial_interface
exit
```

# Test installation of Guix package

```shell
make installed-shell
exit
```

# Test command line interface

```shell
make installed-shell

exit
```

# Upload Python package to pypi

```shell
make dev-shell
make upload
exit
```

# Test direct device interaction using serial terminal

```shell
make serial-shell
[C-a][C-x] # to exit
```
