# compiler_lab
<br />
Fast cmd's:

src/driver/dtiger -o test.o test.tig<br />
g++ -no-pie test.o src/runtime/posix/libruntime.a -o test<br />
./test <br />
<br />
echo "1*2+3" | src/driver/dtiger  --dump-ast -<br />
echo "2*3" | src/driver/dtiger  -e -<br />
