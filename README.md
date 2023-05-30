1. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ 
   $ pwd
2. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ 
   $ mkdir test1
3. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ 
   $ cd test1
4. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test1   
   $ touch file1 file2 file3
5. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test1 
   $ ls -la
6. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test1
   $ cd ~
   user@DESKTOP-JT4MPD8 MINGW64 ~
   $ mkdir test2
7. user@DESKTOP-JT4MPD8 MINGW64 ~
   $ rmdir test2
8. user@DESKTOP-JT4MPD8 MINGW64 ~
   $ cd DZ/test1
   $ rm file2
9. user@DESKTOP-JT4MPD8 MINGW64 ~/DZ
   $ mkdir test3
   $ cd test3
   $ touch file1 file2 
10.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test3
   $ cd ..
   $ rm -rf test3
11.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ
    mkdir test4
12.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ
   $ mv test1/file1.txt test4
   $ mv test1/file3.txt test4
13.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ
   $ cd test4
   $ echo line > file1.txt
   $ echo line >> file1.txt
   $ echo line >> file1.txt
14.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test4
   $ cat file1.txt
15.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test4
   $ echo line > file3.txt
   $ echo line >> file3.txt
   $ echo line >> file3.txt
16.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test4
   $ cat file1.txt file3.txt
17.user@DESKTOP-JT4MPD8 MINGW64 ~/DZ/test4
   $ nano file1.txt file3.txt
   ^\ Replace --> line ---> LINE_NEW --> A (ALL)  --> ^X  ---> Y (save) ---> file3.txt the same