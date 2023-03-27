Create new group

sudo groupadd <group name>
  
  ![image](https://user-images.githubusercontent.com/85178565/227740054-de60fec7-cc82-4b99-94d7-3943ce808dc4.png)

  
  To confirm groupadd
  
  sudo gpasswd -a <user name> < group name>
  
  ![image](https://user-images.githubusercontent.com/85178565/227740155-25c081ed-e461-4a8f-b341-336ea019e723.png)

  Adding multiple users in group 
  
  
  sudo gpasswd -M <user name>,<user name> <group name>
  
  ![image](https://user-images.githubusercontent.com/85178565/227740333-5fd027b0-e0a5-42f9-98dc-f5dcdb862bca.png)

  To confirm whether -users added in to the groups 
  
  
  sudo cat /etc/group
  
  ![image](https://user-images.githubusercontent.com/85178565/227740394-f6488a5c-512a-4cf0-a74d-9224a5fe431b.png)
  
  
TO delete user from group  
  
  
  sudo gpasswd -d <user name> <group name>
  
  
  
  ![image](https://user-images.githubusercontent.com/85178565/227740474-48b7b420-8b24-4da3-a6e2-881c91b6e345.png)

  
