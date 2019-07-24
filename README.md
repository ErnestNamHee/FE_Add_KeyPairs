# How to add New Key Pair to Flexible Engine ECS to allow multiple users to users (with associated key pair) to login to ECS

## 1. Login in the ECS 
### 1.1 SSH login to your ECS using EIP
### 1.2 Download the Git repository (using GIT)


## 2. Create New SSH Keys
chmod 755 create_new_key_pair.sh
./create_new_key_pair.sh

## 3. Add the New SSH Keys to authorize access
nano ~/.ssh/authorized_keys
Add the entry starting with ssh-rsa from file with extension .pub (Public Keys)

## 4. (Option) Import the New SSH Keys to Flexible Engine Console
## 4. Connect using the New SSH Keys using PUTTY
