## find -name chapter-10.txt
./stringsearch-data/technical/911report/chapter-10.txt

## find -name chapter-9.txt
./stringsearch-data/technical/911report/chapter-9.txt

## find -empty
./.git/objects/info
./.git/refs/tags
./stringsearch-data/.git/objects/info
./stringsearch-data/.git/refs/tags

## find -depth -empty
./.git/objects/info
./.git/refs/tags
./stringsearch-data/.git/objects/info
./stringsearch-data/.git/refs/tags


## find -type f -name *.txt
./words.txt

## find -type f -name chapter*
./stringsearch-data/technical/911report/chapter-1.txt
./stringsearch-data/technical/911report/chapter-10.txt
./stringsearch-data/technical/911report/chapter-11.txt
./stringsearch-data/technical/911report/chapter-12.txt
./stringsearch-data/technical/911report/chapter-13.1.txt
./stringsearch-data/technical/911report/chapter-13.2.txt
./stringsearch-data/technical/911report/chapter-13.3.txt
./stringsearch-data/technical/911report/chapter-13.4.txt
./stringsearch-data/technical/911report/chapter-13.5.txt
./stringsearch-data/technical/911report/chapter-2.txt
./stringsearch-data/technical/911report/chapter-3.txt
./stringsearch-data/technical/911report/chapter-5.txt
./stringsearch-data/technical/911report/chapter-6.txt
./stringsearch-data/technical/911report/chapter-7.txt
./stringsearch-data/technical/911report/chapter-8.txt
./stringsearch-data/technical/911report/chapter-9.txt

## find *.txt -depth
words.txt

## find *.class -depth
Server.class
ServerHttpHandler.class
StringHandler.class
StringServer.class
URLHandler.class

sources:
https://www.baeldung.com/linux/find-command
https://www.geeksforgeeks.org/find-command-in-linux-with-examples/
https://ucsd-cse15l-s23.github.io/week/week5/
