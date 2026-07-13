# Shell 00

## Exercice 1
echo "Z" > z
// this command create a file named z containing Z (display it with cat)

## Exercice 2
we need first to create the 40 string file printf "1234567890123456789012345678901234567890" > testShell00
then we will change the permission to be exactly -r--r-xr-x, so we need to set the chmod 451 testShell00 permission
check : ls -l testShell00
 generate : tar -cf testShell00.tar testShell00
 perfect


## Exercice 3
mkdir test0
mkdir test2

echo -n "1234" > test1
echo -n "a" > test3
echo -n "ab" > test4

ln test3 test5
ln -s test0 test6

complete with the permissions

then tar -cf exo2.tar *

## Exercice 4
ssh-keygen -t rsa -b 4096 -f ~/.ssh/id_rsa

need to be added to the intra plateform
cp ~/.ssh/id_rsa.pub ex03/id_rsa_pub

cat ex03/id_rsa_pub

## Exercice 5
ls -m -p -t
Explanation
-m → separate entries with a comma and a space.
-p → append / to directory names.
-t → sort by modification time (newest first).

so echo it 
echi "command" > mid..

## Exercice 6

manipulate git commands : git log -5 --format="%H"
figure it out and push
# Shell 01

## Exercice 1
...

## Exercice 2
...

## Exercice 3
...

## Exercice 4
...

## Exercice 5
...

---

Reminder: don't forget to push.

Note: shells are coding projects.
