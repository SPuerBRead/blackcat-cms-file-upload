# Blackcat-cms-file-upload     CVE-2017-14399

   BlackCat CMS 1.2.2.The vulnerability appears in the \backend\media\ajax_rename.php file,this file does not
validate the file suffix that the user enters, and the user can change the suffix name to an executable script file by changing the contents of the extension parameter.

   Remote authenticated users upload a .jpg or other permitted file types,then rename the file,fill in a new
name for "new name" parameter and extension .php. 

Upload .jpg or other permitted file types
![](https://github.com/SPuerBRead/blackcat-cms-file-upload/blob/master/pic1.png)
Change file name
![](https://github.com/SPuerBRead/blackcat-cms-file-upload/blob/master/pic2.png)
Getshell
![](https://github.com/SPuerBRead/blackcat-cms-file-upload/blob/master/pic3.png)
