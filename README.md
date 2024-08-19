# PicoCTF Gym Vault-Door-Training
This is an easy level challenge from picoCTF. I wanted to document my studies regardless of difficulty so that I can hopefully help those new to the field trying to improve their skills.

## What's the Goal?
from picoCTF - Your mission is to enter Dr. Evil's laboratory and retrieve the blueprints for his Doomsday Project. The laboratory is protected by a series of locked vault doors. Each door is controlled by a computer and requires a password to open. Unfortunately, our undercover agents have not been able to obtain the secret passwords for the vault doors, but one of our junior agents obtained the source code for each vault's computer! You will need to read the source code for each level to figure out what the password is for that vault door. As a warmup, we have created a replica vault in our training facility.

## The Source Code
This is some pretty basic java. Hopping into the 'main', you'll notice the visitor is prompted to enter a password. The format is then listed, with the picoCTF{} flag indicator. The code then calls the 'checkPassword' method to validate the entered password. This method compares the supplied password to the hardcoded password found within the code. If this matches, an "Access granted" is printed. If they don't match, an "Access denied" is printed. 
