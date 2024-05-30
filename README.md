# compiler_lab

Fast cmd's:

src/driver/dtiger -o test.o test.tig
g++ -no-pie test.o src/runtime/posix/libruntime.a -o test
./test 

echo "1*2+3" | src/driver/dtiger  --dump-ast -
echo "2*3" | src/driver/dtiger  -e -
