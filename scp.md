using scp command i can copy the files from local to aws server ubuntu

scp -i <.pem file> <file name> <destination server ssh>:<file path>

![image](https://user-images.githubusercontent.com/85178565/228051058-db251dc9-003f-4422-b7f4-7cc467df8622.png)

file transfered from local to remote server
  
  
![image](https://user-images.githubusercontent.com/85178565/228051377-37f15a54-3205-4b30-95f0-ac887011245a.png)

using scp -i file transfermation from remote to local
  
  
  scp -i <.pem> <ssh of the remote server>:<path of the file> .
  
  
  ![image](https://user-images.githubusercontent.com/85178565/228055311-5421b7b3-5a8f-49f8-9e83-f7a68fbf47bb.png)
