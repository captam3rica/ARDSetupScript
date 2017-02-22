# ARDSetupScript

For some reason, the script completely works the best when kickstart is called multiple times. Versus calling it once with all arguments contained in one line.

This script will do the following:

- Initialize a variable to store the kickstart app location
- Activate ARD
- Turn access on for specified user(s) and grant all privilages to that user
- Allow access to the specified user(s) 
- Set the ARD agent to showup in the tool bar
