

javac JNIDemo.java
gcc -I/usr/lib/jvm/java-1.7.0-openjdk-amd64/include/ -fPIC -shared -o libnative.so native.c
export LD_LIBRARY_PATH=.
java JNIDemo 


add by andy test

add by andy test2
123

add by andy test3 other computer