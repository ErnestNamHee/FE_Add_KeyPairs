# How to add New Key Pair to Flexible Engine ECS to allow multiple users to users (with associated key pair) to login to ECS

## 1. Login in the ECS 
### 1.1 SSH login to your ECS using EIP
### 1.2 Download the Git repository (using GIT)


## 2. Create New SSH Keys
#### chmod 755 create_new_key_pair.sh
#### ./create_new_key_pair.sh

## 3. Add the New SSH Keys to authorize access
#### cd ~
#### nano ~/.ssh/authorized_keys
#### Add the entry starting with ssh-rsa from file generated in STEP2 with the extension .pub (Public Keys)

## 4. (Option) Import the New SSH Keys to Flexible Engine Console
## 5. Connect using the New SSH Keys with PUTTY
### 5.1 Download the Private Key File (ie. cloud@ferev1 without the .pub extension) generated in STEP 2 using winscp to Local PC
### 5.2 Use Putty Key Generator and load the Private Key File and SAVE THE PRIVATE KEY (to cloud@ferev1.PPK) format
