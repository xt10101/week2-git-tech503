

ssh-keygen -t rsa -b 4096 -C "Email"

-t type of encryption 

-b bytes of the key

-C ID


eval `ssh-agent -s`


ssh-add <private-key-name-here>

ssh -T git@github.com

git remote set-url origin <your-ssh-repo-url>

git@github.com:xt10101/week2-git-tech503.git