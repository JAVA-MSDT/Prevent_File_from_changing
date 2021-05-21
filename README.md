# Prevent_File_from_changing
How to prevent file from push or pull 


to perserve the local changes

git fetch

git rebase origin/master --autostash


To prevent local change from pushing remotelly

git update-index --assume-unchanged path/to/file.txt

git update-index --no-assume-unchanged path/to/file.txt.





