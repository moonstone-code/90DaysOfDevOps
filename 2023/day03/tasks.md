Day 3 Task: Basic Linux Commands

Task: What is the linux command to

1. To view what's written in a file. `cat pathOfFileName`
2. To change the access permissions of files. `chmod "rwxrwxrwx" fileName`
3. To check which commands you have run till now. `history`
4. To remove a directory/ Folder. `rm -r directory/Folder Name`
5. To create a fruits.txt file and to view the content. 
   - `touch fruits.txt`
   - `cat fruits.txt`
6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.
    - `touch devops.txt`
    - `vi devops.txt`
    - `Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava`
    - `:wq`
    - `cat devops.txt`
7. To Show only top three fruits from the file.
    - `head -n 3 fruits.txt`
8. To Show only bottom three fruits from the file.
    - `tail -n 3 fruits.txt`
9. To create another file Colors.txt and to view the content.
   - `touch Colors.txt`
   - `cat Colors.txt`
10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.
    - `touch Colors.txt`
    - `vi Colors.txt`
    - `Red`
    - `Pink`
    - `White`
    - `Black`
    - `Blue`
    - `Orange`
    - `Purple`
    - `Grey`
    - `:wq`
11. To find the difference between fruits.txt and Colors.txt file.$ diff Colors.txt fruits.txt
        1,8c1,7
        < Red
        < Pink
        < White
        < Black
        < Blue
        < Orange
        < Purple
        < Grey
        ---
        > Apple,
        > Mango,
        > Banana,
        > Cherry,
        > Kiwi,
        > Orange,
        > Guava

 # day 3 is completed