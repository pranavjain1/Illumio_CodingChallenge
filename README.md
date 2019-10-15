# Illumio_Coding_Challenge
Illumio Coding Challenge 

Thank you, Illumio for giving me the opportunity to work on this problem.

I have written the code within the time limit of 90 minutes apart from writing this read me file.
Time: Oct 14th 2019 EST 6:35 PM to 8:05 PM
(and extra 15 minutes to write this Readme.)

Code Explanation:
In the given time limit, I was able to solve the given problem statement. The explanation for my code is as below:

Illumio_Firewall.java The main class with a constructor that takes in a file path for the input rules. It reads the CSV file line by line and store the rules in a HashMap. I used Hashmap because I wanted to have single values for multiple keys and to ensure quick lookup.If the port or ip parameter is in the range of the ip, then my acceptPacket method returns true or false based on the conditions.
The time complexity to insert would be O(1) for a single IP and a single Port.
The time complexity for look-up will always be constant.

Assumptions:
This program will always assume that the input is valid. I ran out of time before I could test more inputs.

Testing:
I wrote some test cases on my own to check whether the code is working for those cases or not.

Long port range, single IP. (Passed)
Long port range, medium IP range. (Passed)
Single port, long IP range. (Passed)
Medium port range, long IP range. (Passed)
Long port range, long IP range. (Passed).

Future Optimization:
If I had more time, I would have liked to increase the efficiency of the for loop that goes through every single sub rule for a certain key. This could take a significant amount of time if the array list is very large.

Team:
I would be interested in working in the Data Team.

Thank you for taking the time to read through this.

Regards,

Pranav Jain
