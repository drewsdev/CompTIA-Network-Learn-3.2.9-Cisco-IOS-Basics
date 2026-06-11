# CompTIA-Network-Learn-3.2.9-Cisco-IOS-Basics
## CompTIA CertMaster Learn v9.1

Finding and entering commands:

1. Select the SFO router and press Enter in the terminal window. The initial command prompt is the user EXEC mode, where basic commands and troubleshooting can be performed.  
2. Type ? to see a list of commands available in this mode. Each mode will have a different list as more access is granted.  
3. If the output from a command exceeds the screen, you will see --More-- at the bottom. Try using the Enter or space bar keys to navigate the output.  
    * Answer question 1.  
4. To create a shortcut, you need to find characters that uniquely identify a command. For example, type s? to see commands that start with the letter s. Notice that sh would uniquely identify the show command. Type sh h? and you can see that show history can be replaced with sh hi or sh hist.  
    * Type sh v?, and answer question 2.  

Navigating router modes:

1. To access advanced commands or configuration modes, enter en (or enable). This will change to the privileged EXEC mode.  
    * Answer question 3.  
2. To exit this mode and return to the user EXEC mode, enter disable, and notice the change in the command prompt.  
3. Return to the privileged EXEC mode by entering en.  
4. Enter conf t (or configure terminal) to change to the global configuration mode. In this mode, you can alter router settings and access individual component configurations.  
    * Answer question 4.  
5. To exit the global configuration mode, enter exit.  
6. Return to the global configuration mode by entering conf t.  
7. Imagine you want to modify a setting for the FastEthernet0/1 interface. Enter int fa0/1 (or interface FastEthernet0/1) to switch to the interface mode.  
    * Answer question 5.  
8. To exit and return to the global configuration mode, enter exit and notice the change in the command prompt.

![QnA](/Screenshot_1.png)

Explanation  
To complete this lab, do the following:

Finding and entering commands:

1. Select the SFO router and press Enter in the terminal window.  
2. Type ? to see the list of commands available in this mode.  
3. If the output exceeds the terminal window, you will see --More-- at the bottom.  
      * Press the Enter key to see what happens.  
      * Press the space bar to see what happens.  
      * Select the Questions button to open the Lab Questions dialog.  
      * (Optional) If necessary, move the terminal window to the left to view the window and the Lab Questions dialog at the same time.  
      * Answer question 1.  
      * Select the Questions button to close the Lab Questions dialog.  
4. Type s? to see commands that start with the letter s. Notice that sh would uniquely identify the show command.  
      * Type sh h? to see options that start with h.  
      * Notice that show history can be replaced with sh hi or sh hist.  
      * Type sh v? at the prompt.  
      * Select the Questions button to open the Lab Questions dialog.  
      * Answer question 2.  
      * Select the Questions button to close the Lab Questions dialog.

Navigating router modes:

1. Enter en (or enable). This will change to the privileged EXEC mode.  
      * Select the Questions button to open the Lab Questions dialog.  
      * Answer question 3.  
      * Select the Questions button to close the Lab Questions dialog.  
2. Enter disable to exit this mode, and notice the change in the command prompt.  
3. Enter en to return to the privileged EXEC mode.  
      * Enter conf t (or configure terminal) to change to the global configuration mode.  
      * Select the Questions button to open the Lab Questions dialog.  
      * Answer question 4.  
      * Select the Questions button to close the Lab Questions dialog.  
4. Enter exit to return to the global configuration mode and notice the change in the command prompt.  
5. Enter conf t to return to the global configuration mode.  
      * Enter int fa0/1 (or interface FastEthernet0/1) to switch to the interface mode.  
      * Select the Questions button to open the Lab Questions dialog.  
      * Answer question 5.  
      * Select the Questions button to close the Lab Questions dialog.  
6. Enter exit to return to the global configuration mode and notice the change in the command prompt.
