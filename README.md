# urldatabaseassignment
Creating JSON file and performing CURD operations in Java.


Problem statement
Develop a program in Java(urldatabase) that can be run in the command line as per given requirements below.



Requirements
1. To start the program: run java urldatabase. Further, the program will wait for the user to enter the following
commands.
2. The command storeurl shall take a URL as a parameter and save that into a table with a unique short key and a
count(usage count) initialized to 0.
a. Use local variables instead of a database to store the data.
b. Use any appropriate logic to generate the unique short key.
3. The command get shall take a URL as a parameter and return the unique short key after incrementing the usage
count.
4. The command count shall take a URL as a parameter and should return the latest usage count.
5. The command list should return all urls and counts. The return value is in JSON.
6. The command exit should terminate the program

