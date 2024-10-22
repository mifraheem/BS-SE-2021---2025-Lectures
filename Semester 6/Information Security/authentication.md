
## Authentication 
## Verification
## Authorization

### Credentials
* username
* password
* token

### Authentication Flow
1. User submits username and password
2. Server verifies credentials

## Password
secret code for authentication <br>
two parts of passowrd.
1. username
2. secret code/password

### Entropy of password
it represent the unsertinity of the password. basically it measures how strong and unpredictable a password is.<br>
This measurements based on:
* length of password
* mix of characters
* Unpredictability

### Two type of entropy
1. High Entropy <br>
higher entropy shows that the password is strongest and harder to crack
2. Low Entropy<br>
low entropy shows that the password is weak and easy to crack.


## Password Verification
it is the process of confirming that a user's provided password matches the stored password in DB.
it is done by hashing the provided password and comparing it with the stored hash.

### Two types of password verification
1. Static <br>
Comparing the user input password with stored password.
2. Dynamic <br>
advance auth like hashing and 2FA etc

## Possible Attacks against password system
### 1. Brute Force
guessing password using automated methods until access is gained. hackers uses public info to generate possible passwords
### 2. Credentials Stuffing
Credentials stuffing is a cyber attack where hackers use tolen username and password to access multiple accounts. This works when people uses the same login credentials accross different websites and devices. 
### 3. Key Login
Key login attacks involve mellisious softwares that records key stocks on infected devices. Allowing attackers to steal password and other personal information.
### 4. Dictionary Attack 
Attackers used list of common words from cracking dictionaries.
### 5. Phishing Attack
It involves fake emails, text, or messages that trick victoms into sharing sensitive information. Scammers pose as trust worthy source such as banks,  social media, or email providers. 
### 6. Password Sprey Attack
A password sprey attack is when hackers try a common password on many accounts. This is possible when people uses same password across multiple accounts. 

## How to avoid password attacks
### 1. Password Protection
dicrease the limit to try password. <br>
2. Multifector Authentication <br>
3. Require Complex password and unique passwords<br>
4. Update password regularly<br>

### 2. Extra Security Layer
1. Use 2FA<br>

### 3. Strong password.
