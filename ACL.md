ACL-Access control list 
will show the access permissions 

getfacl <file name> this command similar to ls -la <file name>
  
  ![image](https://user-images.githubusercontent.com/85178565/227751243-807ccc88-32fe-450f-b2f0-f6c974ec7f0e.png)
  
 setfacl <file name> this command will set permissions to the user
  
  setfacl -m u:imtiyaz:rwx log_file.txt
  
  ![image](https://user-images.githubusercontent.com/85178565/227751433-ea713e47-f1b2-4757-a2bb-1a51cd7f2486.png)

