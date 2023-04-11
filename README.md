# git_error#How to fix Github Error: Permission denied (publickey) [Best Solution 2023]


git config --global --unset core.excludesfile

git config --global --unset user.name
git config --global --unset user.email

git config --global user.name "adeleyeayodeji"

git config --global user.email "biodunhi@gmail.com"

ssh-keygen

//powershell

Get-Content ~/.ssh/id_rsa.pub | Set-Clipboard
