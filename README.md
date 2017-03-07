## hexedit with auto-refresh
A fork of https://github.com/pixel/hexedit  
Added auto-refresh which is useful with frequently updated files.

### Download
```bash
git clone https://github.com/mathfigure/hexedit
```
### Build
```bash
cd hexedit
autoreconf -fi
./configure
make
```
### Install
```bash
sudo make install
```
### Test
```bash
hexedit /dev/urandom
hexedit /dev/shm/some-highly-dynamic-file
```
