# XML



**1. Create a remote repository called XML.**

 `On GitHub push: Repositories, New, Create repository.`


---


**2. Clone the XML repository to the local computer.**

`git clone link to repository https://github.com/AnastasiiaChyzhykova/XML.git`


---


**3. Create a "new.xml" file inside the XML context.**

`touch new.xml`


---


**4. Add the file to git.**

`git add new.xml`


---


**5. Commit the file.**

`git commit -m "commit name"`


---


**6. Send the file to a remote GitHub repository.**

`git push origin main (the name of the branch where we want to put the code)`


---


**7. Edit the content of the "new.xml" file - write information about yourself (name, age, number of pets, future desired salary). Write everything in XML format.**

```
 vim new.xml,
 i - switch to edit mode,
 esc - switch to command mode,
 :wq - save changes and exit
 ```
  
  ```javascript
<?xml version="1.0" encoding="UTF-8" ?>
<personal_info>
  <name>Anastasiia</name>
  <surname>Chyzhykova</surname>
  <age>27</age>
  <number_of_pets>0</number_of_pets>
  <salary>1400$</salary>
</personal_info> 
```


---


**8. Send changes to a remote repository.**

 ```
 git add new.xml,
 git commit -m "commit name",
 git push origin main (branch name)
 ```


---


**9. Create a preferences.xml file.**

`touch preferences.xml`


---


**10. In the preferences.xml file, add information about your preferences (favorite movie, favorite series, favorite food, favorite season, country you would like to visit) in XML format.**

```
 vim preferences.xml,
 i - switch to edit mode,
 esc - switch to command mode,
 :wq - save changes and exit
```

```javascript
<?xml version="1.0" encoding="UTF-8" ?>
<my_preferences>
  <favorite_series>Sherlock</favorite_series>
  <favorite_food>borsch</favorite_food>
  <favorite_season>spring</favorite_season>
  <the_country_you_would_like_to_visit>Greece</the_country_you_would_like_to_visit>
  <avorite_movie>Harry Potter </avorite_movie>
</my_preferences>
```


---


**11. Create a file sklls.xml, add information about skills that will be learned at the course in XML format.**

`cat> skills.xml`

```javascript
<?xml version="1.0" encoding="UTF-8" ?>
<skills>
  <theory>types of testing</theory>
  <theory>testing methods</theory>
  <theory>SDLC</theory>
  <theory>STLC</theory>
  <documentation>check list</documentation>
  <documentation>test case</documentation>
  <documentation>test plan</documentation>
  <documentation>bug report</documentation>
  <client_server_architecture>client</client_server_architecture>
  <client_server_architecture>server</client_server_architecture>
  <client_server_architecture>database</client_server_architecture>
  <client_server_architecture>data transfer protocols</client_server_architecture>
  <client_server_architecture>status codes</client_server_architecture>
  <programs>Postman</programs>
  <programs>Charles</programs>
  <programs>Fidler</programs>
  <programs>Android Studio</programs>
  <programs>XCode</programs>
  <programs>Jmeter</programs>
  <SQL>Create</SQL>
  <SQL>Delete</SQL>
  <SQL>Drop</SQL>
  <SQL>Insert Into</SQL>
  <SQL>Select</SQL>
  <SQL>Join</SQL>
</skills>
```

---


**12. Make a commit in one line.**

`git commit -a -m "commit name"`


---


**13. Send two files at once to the remote repository.**

 ```
 git add .
 git commit -m "commit name"
 git push origin branch name
 ```


---


**14. Create the bug_report.xml file at the web interface.**

 ```
 add file,
 create new file,
 commit new file
 ```


---


**15. Make Commit changes (save) changes at the web interface.**

```
 edit this file,
 press the button "commit changes"
```


---


**16. Modify the bug_report.xml file at the web interface and add the bug report in XML format.**

`edit this file (bug_report.xml)`

```javascript
<?xml version="1.0" encoding="UTF-8" ?>
<bug_report>
  <bug_id>155</bug_id>
  <severity>minor</severity>
  <priority>medium</priority>
  <environment>Windows 10 Pro</environment>
  <environment>Chrome 112</environment>
  <environment>Firefox 112</environment>
  <bug_title>Clicking on the Instagram icon on the [About us] page in the footer of the website will take you to the Instagram Home Page (instagram.com)</bug_title>
  <STR>Navigate to ourwebsite.com</STR>
  <STR>Go to the page [About us]</STR>
  <STR>Move down to the page footer</STR>
  <STR>Click on the Instagram icon</STR>
  <AR>The Home Page of Instagram opens</AR>
  <ER>The company's page on Instagram opens</ER>
  <Attachment>Link</Attachment>
  <Author>Anastasiia Chyzhykova</Author>
</bug_report>
```


---


**17. Make Commit changes (save) changes at the web interface.**

 `press the button "commit changes"`


---


**18. Synchronize remote and local XML repository.**

 `git pull oridgin main (branch name)`
 
 
---
