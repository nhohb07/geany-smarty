geany-smarty
============

Geany Plugin: Smart auto close xml/html tag, smart indent, highlight match xml/html tag, smart close brackets and quoctes, smart delete brackets and quoctes [http://www.thegioiwebre.com/]

FEATURED:
============
  1. Smart auto close XML/HTML tag with mutil tag. 
    - EX: <div><a href="http://www.thegioiwebre.com/c20-thiet-ke-web-ban-hang.html">, only type </, geany-smarty will auto           add </a>, type </ again geany-smarty will auto add </div>
    - 
  2. Smart indent close XML/HTML tag such as open tag when enter and close tag with </
  3. Highlight open and close XML/HTML tag when cursor inside tag.
  4. Smart auto close brackets and quoctes.
  5. Smart delete brackets and quoctes.

============
Comliter and add to geany plugin:

* On Linux 64bit:
    - Open terminal and run this command:
    - gcc -c GeanySmarty.c -fPIC `pkg-config --cflags geany` && gcc GeanySmarty.o -o GeanySmarty.so -shared `pkg-config --libs geany` && sudo cp GeanySmarty.so /usr/lib/x86_64-linux-gnu/geany

* On Linux 32bit:
    - Open terminal and run this command:
    - gcc -c GeanySmarty.c -fPIC `pkg-config --cflags geany` && gcc GeanySmarty.o -o GeanySmarty.so -shared `pkg-config --libs geany` && sudo cp GeanySmarty.so /usr/lib/x86-linux-gnu/geany

* On other OS: NOT TEST
