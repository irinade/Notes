- Create a pair of key
```
ssh-keygen #Enter a pasword
```
- copy public key on github
- install terminal programm
```
sudo apt install mate-terminal
```
- run a terminal with a ssh agent
```
ssh-agent mate-terminal & #is_in_background
```
- from mate-terminal
```
ssh-add ~/.ssh/id_rsa
```
- use git with ssh
