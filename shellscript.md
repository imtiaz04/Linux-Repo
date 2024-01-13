Shell Script:

what is shell script?

In simple words,a shell script is a ececutable file with set of commands with extention .sh

To create a shell script will be used like nano,vi,vim,...editors

step1: use any editor like vi,vim,nano to write script.
ex: vi <file name>.sh ---------->editor will start  
  
  start your script with #! /bin/bash ...(which called shebang)
  
  
  ![image](https://user-images.githubusercontent.com/85178565/228113098-c35fcb8a-fa5e-43a3-9f1a-3682c1337b40.png)  
    
  
step 2:
  After writing shell script set execute permission for your script as follows
  
 chmod <permission> <script file name>
  chmod 760 <file name>

![image](https://user-images.githubusercontent.com/85178565/228113407-35d43a4b-99dd-4052-b7ee-2a15eb80c649.png)


  we can add arguments in shell scripting for ex:./<filename> name1 (nj-is argument 1)

  ![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/2d4e1b5c-9f1f-4f23-a6d8-7a9b7d2033b5)

  below is script
  
#!/bin/bash


filename=$1
echo "Enter the file name"


echo "Checking if $filename exists.."

if [ -f $filename  ]
then

echo "$filename exists" 
else
echo "$filename doesn't exist"
fi
~                                                                                                                                                                                                          
~ 

we can use loop also for repeted execute

![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/ef63c18c-da29-482b-85c3-555a16cfed0f)

here is script

![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/74bd8bf8-7388-4adc-bfcf-73c113bfde5c)


we can find files in folders with scripting and i used arguments too..

![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/ca7378f4-a6aa-405c-b41a-d9175117040d)

![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/267420e0-3bc5-405c-ac17-99a7fe1e2617)

usung df -h command we can find usage of the system

![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/f44b69d7-7c8b-4da0-9fa2-5d8d72272121)







  
