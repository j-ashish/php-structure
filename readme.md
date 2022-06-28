# PHP Project Structure
- #### **This is the structure that is created, to build the whole project which is PHP based.**
- #### **This is kind of boiler plate for the project.**
- #### **This structure will help the user to organize the files.**
<dl>
<dt><b style="color: red;">/class/js-classes/</b></dt>
<dd>Create folders according to the name of the class to implement easily. Ex: <i style="color:yellow">/class/js-classes/User/User.js</i>. File Allowed: <b style="color:limegreen;">.js</b></dd>
<dt><b style="color: red;">/class/php-classes/</b></dt>
<dd>Create folders according to the name of the class to implement easily. Ex: <i style="color:yellow">/class/php-classes/create_account/create_account.php</i> it defines that account for account creation use this class. File Allowed: <b style="color:limegreen;">.php</b></dd>
<dt><b style="color: red;">/config/json/</b></dt>
<dd>Here we have to create more folders depends on the project needs and add files into those folders. Ex: <i style="color:yellow">/config/json/settings/setting.json</i>. File Allowed: <b style="color:limegreen;">.json</b></dd>
<dt><b style="color: red;">/config/xml/</b></dt>
<dd>Here we have to create more folders depends on the project needs and add files into those folders. Ex: <i style="color:yellow">/config/xml/user-details/user_details.xml</i>. File Allowed: <b style="color:limegreen;">.xml</b></dd>
<dt><b style="color: red;">/database/</b></dt>
<dd>Ex: <i style="color:yellow">/database/account/accounts.db</i> to store pre-configured database files. File Allowed: <b style="color:limegreen;">.sqlite3 .db</b></dd>
<dt><b style="color: red;">/functions/</b></dt>
<dd>Create folders according to the use of the function which is going to be defined in it. Ex: <i style="color:yellow">/functions/delete/delete.php</i> it indicates that functions related to deletion are here. File Allowed: <b style="color:limegreen;">.php</b></dd>
<dt><b style="color: red;">/php/</b></dt>
<dd>Please create folders for every application in it. Ex: <i style="color:yellow">/php/database/database.php</i> to store php file for databases. File Allowed: <b style="color:limegreen;">.php</b>
<dt><b style="color: red;">/static/css/</b></dt>
<dd>Create folders and name them according to application and templates. And then add stylesheet depends on that particular application. Ex: <i style="color:yellow">/static/css/header/header.css</i> to store stylesheet for files that is used as header. File Allowed: <b style="color:limegreen;">.css</b></dd>
<dt><b style="color: red;">/static/js/</b></dt>
<dd>Create folders and name them according to application and templates. And then add scripts depends on that particular application. Ex: <i style="color:yellow">/static/js/footer/footer.js</i> to store scripts for files that is used as footer. File Allowed: <b style="color:limegreen;">.js</b></dd>
<dt><b style="color: red;">/templates/html/</b></dt>
<dd>Create folders according to their use, because these files are going to be used again and again. Ex: <i style="color:yellow">/templates/html/header/header.html</i> to store markup files that are going to be used in header. File Allowed: <b style="color:limegreen;">.html</b></dd>
<dt><b style="color: red;">/visual/images/</b></dt>
<dd>Create folders according to use and add images with names that describe them easily. Ex: <i style="color:yellow">/visual/images/homepage/home.png</i> to store images that are going to be represented on homepage. File Allowed: <b style="color:limegreen;">.png .jpeg .jpg .webp</b></dd>
<dt><b style="color: red;">/visual/videos/</b></dt>
<dd>Create folders according to use and add videos with names that describe them easily. Ex: <i style="color:yellow">/visual/videos/blogs/blog.mpeg</i> to store videos that are going to be represented on blogs. File Allowed: <b style="color:limegreen;">.mpeg .mp4</b></dd>
</dl>

___
## Folder and File Structure Inside The Root
___
- class![alt text](z/folder.png)
  - js-classes![alt text](z/folder.png)
    - Account![alt text](z/folder.png)
      - Account.js![alt text](z/js.png) ![alt text](z/class.png)
  - php-classes![alt text](z/folder.png)
    - User![alt text](z/folder.png)
      - User.php![alt text](z/php.png) ![alt text](z/class.png)
___
- config![alt text](z/folder.png)
  - json![alt text](z/folder.png)
    - javascript object notation 1![alt text](z/folder.png)
      - json1.json![alt text](z/json.png)
    - javascript object notation 2![alt text](z/folder.png)
      - json2.json![alt text](z/json.png)
  - xml![alt text](z/folder.png)
    - extensible markup 1![alt text](z/folder.png)
      - xml1.xml![alt text](z/xml.png)
    - extensible markup 2![alt text](z/folder.png)
      - xml2.xml![alt text](z/xml.png)
___
- database![alt text](z/folder.png)
  - database 1![alt text](z/folder.png)
    - account.db![alt text](z/database.png)
___
- functions![alt text](z/folder.png)
  - data delete![alt text](z/folder.png)
    - data_del.php![alt text](z/php.png) ![alt text](z/function.png)
___
- php![alt text](z/folder.png)
  - php 1![alt text](z/folder.png)
    - php1.php![alt text](z/php.png)
  - php 2![alt text](z/folder.png)
    - php2.php![alt text](z/php.png)
___
- static![alt text](z/folder.png)
  - css![alt text](z/folder.png)
    - stylesheet 1![alt text](z/folder.png)
      - css1.css![alt text](z/css.png)
    - stylesheet 2![alt text](z/folder.png)
      - css2.css![alt text](z/css.png)
  - js![alt text](z/folder.png)
    - javascript 1![alt text](z/folder.png)
      - js1.js![alt text](z/js.png)
___
- templates![alt text](z/folder.png)
  - html![alt text](z/folder.png) 
    - template 1![alt text](z/folder.png)
      - html1.html![alt text](z/html.png)
    - template 2![alt text](z/folder.png) 
      - html2.html![alt text](z/html.png)
___
- visual![alt text](z/folder.png)
  - images![alt text](z/folder.png)
    - pictures one![alt text](z/folder.png)
      - img.png![alt text](z/img.png)
    - pictures two![alt text](z/folder.png)
      - img.jpeg![alt text](z/img.png)
  - videos![alt text](z/folder.png)
    - graphics 1![alt text](z/folder.png)
      - video.mpeg![alt text](z/video.png)
    - graphics 2![alt text](z/folder.png)
      - video2.mp4![alt text](z/video.png)
___
#### Folders are represented with folder image at the end.
#### Files are represented with their respective extensions. Ex: .html - .js - .php and image at the end

___

### **To Clone The Structure Do This:-**
___
```
  gh repo clone j-ashish/php-structure
```
<div style="border-top: 1px solid green"></div>

|   Author    |      Description      |              WebSite              |
| :---------: | :-------------------: | :-------------------------------: |
| Ashish Jain | PHP Project Structure | [Ashish](http://ashishjain.rf.gd) |

<div style="border-top: 1px solid green"></div>

![alt directory structure](z/directory-structure.png)
  



