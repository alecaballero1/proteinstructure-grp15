# proteinstructure-grp15
Code for final project for the subject protein structure 

Initial instructions


#1. Identify yourself to git

git config --global user.name "yourgithubname"

git config --global user.email "yourgithubemail"


#2. Create pubkey

ssh-keygen -t ed25519 -C "yourgithubemail"


#3. Copy pubkey (all that appears in the console)

cat ~/.ssh/id_ed25519.pub


#4. Link terminal to github profile 
Go to github

→ Settings

→ SSH and GPG keys

→ New SSH key

→ Paste key on the description part


#5. Test the connection
ssh -T git@github.com


Should say something along the lines

"Hi alecaballero1! You've successfully authenticated, but GitHub does not provide shell access."


#6. Clone the repository 

You can click 
→ <> Code 
→ SSH 
→ git@github.com:youruser/proteinstructure-grp15.git

git clone git@github.com:youruser/proteinstructure-grp15.git
