This Joke site Php web application is created by Anup Saha.
anyone who uses this app should not remove the readme.txt file and the div having footer class.

Donot Remove this readme.txt file

How to Use-

1. create a mysql database with the name of your choice.
2. import the sql file into the database created which will create a jokes table with required columns and data types.
3. open config.php file.
4. Enter the following details in the variables in config.php file -

$hostname = "your mysql host name";
$username = "your mysql username";
$password = "your mysql password";
$database = "your mysql database name";
$port = "tour mysql port number";

5. if you want to add more categories then just add an <li> in the category list of index.html page
    and add an <option>Category Name </option> in the "add jokes.html"

    example:-
    add -
    <li>
      <a href="#" onclick="changecategory('Category Name')">Category Name</a>
    </li>
    in the "index.html" file.


    and  add-
    <option>Category Name </option>
      in the "add jokes.html" file.

6. change content of the contact.html and add your own contact email and contact number.

7. you can change the number of jokes to fetch at once by changing the value of the variable "numofjokestofetch" in "js/index.js" file . 

8. You can also add your content in about.html file but you shouldn't remove the content already present in "about.html" page.
    you can add content in "about.html" page but shouldn't change the content already present in it.
    if you want to add any content in "about.html" file then add it after the content already present in "about.html" file.
