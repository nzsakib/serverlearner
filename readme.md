# PHP remote code execution learning platform

1. User gives an input, we run it and get the output of the commant, and show it top the user

2. But we need to store the state of the current position. for example if user cd into a dir and then run ls. 
we have to remember the previous commands. 

3. We need to know if the command ran successfully or not.
    - if successfull we remember it
    - if not successful we dont remmeber it .

4. We need to test if the command passes our test