# blackcat-cms-file-upload
blackcat cms file upload

  BlackCat CMS 1.2.2.The vulnerability appears in the \backend\media\ajax_rename.php file,this file does not
validate the file suffix that the user enters, and the user can change the suffix name to an executable script file by changing the contents of the extension parameter.
  remote authenticated users upload a .jpg or other permitted file types,then rename the file,fill in a new
name for "new name" parameter and extension .php. 

upload jpg or other permitted file types
![](https://github.com/SPuerBRead/blackcat-cms-file-upload/blob/master/pic1.png)
change name
![](https://github.com/SPuerBRead/blackcat-cms-file-upload/blob/master/pic2.png)
get shell
![](https://github.com/SPuerBRead/blackcat-cms-file-upload/blob/master/pic3.png)
