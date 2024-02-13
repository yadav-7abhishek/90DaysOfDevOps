3.
   ```console
   # to make a file and give it exceutable permission
   ubuntu@ip-172-31-18-155:~$ touch file.sh
   ubuntu@ip-172-31-18-155:~$ chmod u+x file.sh
   ```
   ```console
   # give the following input
   #!/bin/bash
   echo "I will complete #90DaysOofDevOps challenge"
   ```
4. 
   ```console
   # to give user defined input variable
   #!/bin/bash
   read name
   echo "My name is $name$1"
   ```
   ```console
   #to execute the script with arguement
   ubuntu@ip-172-31-18-155:~$ ./file.sh yadav
   Abhishek
   My name is Abhishekyadav
   ```
5.
   ```console
   num1=1000
   num2=1000

   if [ $num1 -eq $num2 ];
   then
        echo "Both num1 and num2 are equal"
   elif [ $num1 -gt $num2 ];
   then
        echo "num1 is greater than num2"
   else
        echo "num2 is greater than num1"
   fi
   ```
