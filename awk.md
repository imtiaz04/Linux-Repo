using awk command we can get perticular things from file

awk '/INFO/ log.txt

![image](https://user-images.githubusercontent.com/85178565/227750953-22c0ab21-3fca-4e0f-8744-c1ba195b53d0.png)

get firt 1,2 colums

 awk '/INFO/ {print $1,$2}' log_file.txt
 
 ![image](https://user-images.githubusercontent.com/85178565/227751064-e80a932f-b71d-4bcc-9671-946fcfcf5f4d.png)

