Experiment-6 
Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional 
operator2 and operator3 users.Set their passwords as well. Run the usermod -c command to update the comments of the operator1 
user account. Remove the operator3 user from the system.

Approach:
Create the operator1, operator2, and operator3 users, set their passwords, and confirm their existence. Update operator1’s 
comment using usermod -c, then remove operator3 from the system.

<img width="353" alt="image" src="https://github.com/user-attachments/assets/47769f63-baa9-421a-a72e-22025f158481" />
<img width="407" alt="image" src="https://github.com/user-attachments/assets/dc7a0d08-06c4-4d54-afe7-3a4056948edf" />


Commands used:
useradd operator1, passwd operator1, useradd operator2, passwd operator2, useradd operator3,passwd operator3, 
usermod -c "" operator1, userdel operator3
