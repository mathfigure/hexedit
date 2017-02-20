## hexedit with auto-refresh
A fork of https://github.com/pixel/hexedit  
Added auto-refresh which is useful with frequently updated files.

### download & build
git clone https://github.com/mathfigure/hexedit  
cd hexedit  
autoconf  
autoheader  
./configure  
make

### test
./hexedit /dev/shm/some-highly-dynamic-file
