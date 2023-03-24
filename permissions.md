using setfacl command giving file permissions
setfacl -m u:<username>:rwx <file name>
  ![image](https://user-images.githubusercontent.com/85178565/227659144-e726bfd0-4d9a-40c7-8edd-ac5b4bf26e7d.png)
  
  using getfacl command looking/verifing file permissions
  
  getfacl <file name>  
  
  ![image](https://user-images.githubusercontent.com/85178565/227663249-2aac2b52-b74f-41da-9bd1-9797008a39ba.png)
  
  
  giving group permissions
  
  setfacl -m g:<group name>:r-x <file name>
    
  ![image](https://user-images.githubusercontent.com/85178565/227663056-7e95dd3f-c5f6-4abf-ad22-187555849308.png)
  
  
![image](https://user-images.githubusercontent.com/85178565/227663178-80fb645c-4f9c-49a2-bde8-3c38d1e52bb6.png)
  
  
removing permissions for user:
  
  setfacl -x u:<username> <file name>
  
![image](https://user-images.githubusercontent.com/85178565/227663535-ce493123-d81d-4ac3-bd0e-2a3d4453c086.png)
  
  removing permissions for group
  
  setfacl -x g:<group name> <file name>
    
  ![image](https://user-images.githubusercontent.com/85178565/227663955-3b738284-c29c-4e55-aa96-330cb68f8ddc.png)  
  
  Adding user permissions to the file:
  setfacl -m u:<user name>:<permissions> <file name>
  
  ![image](https://user-images.githubusercontent.com/85178565/227663931-7c9001b2-0240-4f53-a46c-fc4573c889f4.png)

  

