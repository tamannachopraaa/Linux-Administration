Experiment4
Create the /home/consultants directory. Add write permission to the consultants directory. Use the symbolic method for setting the appropriate permissions. Forbid others from
accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. Change the default umask for the operator1 user. The new 
umask prohibits all access for users that are not in their group. Confirm that the umask is changed.

Approach:
Create the /home/consultants directory, set write permission using the symbolic method, and restrict access for others using the octal method. Change the default umask for 
operator1 to deny all access for non-group users, then verify the updated umask setting.


commands used-
mkdir
chmod
