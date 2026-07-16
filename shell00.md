# Shell 00
note : Fix the repo problem  ,
time problem in the ex 1 and 2 
ex 2 lint file 3 and 5 with ln 
reclone the repo
push wisly 
push what's demanded
## Exercice 0
echo "Z" > z
// this command create a file named z containing Z (display it with cat)

## Exercice 1
we need first to create the 40 string file printf "1234567890123456789012345678901234567890" > testShell00
then we will change the permission to be exactly -r--r-xr-x, so we need to set the chmod 451 testShell00 permission
check : ls -l testShell00
 generate : tar -cf testShell00.tar testShell00
 perfect


## Exercice 2
mkdir test0
mkdir test2

echo -n "1234" > test1
echo -n "a" > test3
echo -n "ab" > test4

ln test3 test5
ln -s test0 test6

complete with the permissions

then tar -cf exo2.tar *

## Exercice 3
ssh-keygen -t rsa -b 4096 -f ~/.ssh/id_rsa

need to be added to the intra plateform
cp ~/.ssh/id_rsa.pub ex03/id_rsa_pub

cat ex03/id_rsa_pub

## Exercice 4
ls -m -p -t
Explanation
-m → separate entries with a comma and a space.
-p → append / to directory names.
-t → sort by modification time (newest first).

so echo it 
echi "command" > mid..

## Exercice 5

manipulate git commands : git log -5 --format="%H"
figure it out and push



Create a file named git_ignore.sh with the following content:

#!/bin/sh
git ls-files --others --ignored --exclude-standard






