using awk command we can get perticular things from file

awk '/INFO/ log.txt

![image](https://user-images.githubusercontent.com/85178565/227750953-22c0ab21-3fca-4e0f-8744-c1ba195b53d0.png)

get first 1,2 colums

 awk '/INFO/ {print $1,$2}' log_file.txt
 
 ![image](https://user-images.githubusercontent.com/85178565/227751064-e80a932f-b71d-4bcc-9671-946fcfcf5f4d.png)


 getting perticular rows like lessthan 50 & grater than 10 from log_file.txt the out put shoud be sent to qa_report1.txt
 

 
![image](https://github.com/imtiaz04/Linux-Repo/assets/85178565/3c9271be-0505-4584-984a-ebfcd18b1e36)


 

