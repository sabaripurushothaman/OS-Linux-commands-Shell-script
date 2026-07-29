# OS-Linux-commands-Shell-scripting
Operating systems Lab exercise
# Linux commands-Shell scripting
Linux commands-Shell scripting

# AIM:
To practice Linux Commands and Shell Scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2:

Execute the following commands

### Step 3:

Testing the commands for the desired output. 

# COMMANDS:
### Create the following files file1, file2 as follows:
cat > file1
```
chanchal singhvi
c.k. shukla
s.n. dasgupta
sumit chakrobarty
^d
```
cat > file2
```
anil aggarwal
barun sengupta
c.k. shukla
lalit chowdury
s.n. dasgupta
^d
```
### Display the content of the files
cat < file1
## OUTPUT
<img width="417" height="191" alt="Screenshot 2026-07-28 230337" src="https://github.com/user-attachments/assets/44c73e9f-55ac-4144-ae7c-52c933342307" />


cat < file2
## OUTPUT



# Comparing Files
cmp file1 file2
## OUTPUT
<img width="343" height="47" alt="image" src="https://github.com/user-attachments/assets/0b8c284e-522e-41f7-8afe-3461fb286543" />

<img width="1920" height="1080" alt="Screenshot_20260727_134518" src="https://github.com/user-attachments/assets/2bfc1c6e-12f0-48db-8faa-4d13e8caf4c9" />
<img width="1920" height="1080" alt="Screenshot_20260727_215151" src="https://github.com/user-attachments/assets/e3e5b89c-1122-4b76-92a2-b8a47d293636" />
<img width="324" height="129" alt="Screenshot_20260728_222029" src="https://github.com/user-attachments/assets/b6d719ed-797c-40c9-b7be-8c9486d0d0ca" />
<img width="1920" height="1080" alt="Screenshot_20260727_215119" src="https://github.com/user-attachments/assets/ffcb8183-58a7-4eb2-93e6-963480047047" />
<img width="1920" height="1080" alt="Screenshot_20260727_214354" src="https://github.com/user-attachments/assets/052a1580-566c-4e03-a126-0cbe76c984cb" />
<img width="800" height="155" alt="Screenshot_20260727_213841" src="https://github.com/user-attachments/assets/235a5d4c-4e79-4bac-9fb3-7b734a5c965f" />
<img width="765" height="266" alt="Screenshot_20260727_213623" src="https://github.com/user-attachments/assets/58fdaf3e-15ea-46dc-b5c9-ab677129274c" />
<img width="1920" height="1080" alt="Screenshot_20260727_213349" src="https://github.com/user-attachments/assets/917c766c-1c71-4fdb-8a55-5f86fe692924" />
<img width="749" height="209" alt="Screenshot_20260727_213118" src="https://github.com/user-attachments/assets/1fbebe9f-b9c8-4540-8745-6e4197b5252d" />
<img width="622" height="206" alt="Screenshot_20260727_212844" src="https://github.com/user-attachments/assets/c7690502-2a3b-4c9d-a3a3-d883898d198f" />
<img width="531" height="247" alt="Screenshot_20260727_211158" src="https://github.com/user-attachments/assets/4e41e16b-f77f-4a0e-bb13-702c1d56d0c4" />
<img width="1920" height="1080" alt="Screenshot_20260727_210551" src="https://github.com/user-attachments/assets/26d95251-f166-4d7e-9091-275e47854a49" />
<img width="1920" height="1080" alt="Screenshot_20260727_205434" src="https://github.com/user-attachments/assets/86e6e2d7-9038-4652-a33b-cf22ba121c4c" />
<img width="1920" height="1080" alt="Screenshot_20260727_200341" src="https://github.com/user-attachments/assets/28d5a311-1c4b-456f-b621-ba11aab75306" />
<img width="1920" height="1080" alt="Screenshot_20260727_200144" src="https://github.com/user-attachments/assets/b71409ab-085e-494b-9683-6f207e8f7719" />
<img width="1920" height="1080" alt="Screenshot_20260727_200138" src="https://github.com/user-attachments/assets/861cdd13-405b-4137-a468-d9b8d20cef87" />
<img width="1920" height="1080" alt="Screenshot_20260727_195713" src="https://github.com/user-attachments/assets/899b1b0d-b779-4dbf-8b16-fcf6887d4b47" />
<img width="726" height="290" alt="Screenshot_20260727_194846" src="https://github.com/user-attachments/assets/ac06e504-4709-4c45-81ef-333a8d1ac57c" />
<img width="1920" height="1080" alt="Screenshot_20260727_143931" src="https://github.com/user-attachments/assets/dc3d5381-d252-467e-839d-70773d9ea5ce" />
<img width="893" height="198" alt="Screenshot_20260727_143048" src="https://github.com/user-attachments/assets/f489f606-45e4-4c63-bb76-e28689ba0c24" />
<img width="893" height="76" alt="Screenshot_20260727_142649" src="https://github.com/user-attachments/assets/41d1d9f1-67e1-484a-afc2-a5a6fdf257ab" />
<img width="936" height="507" alt="Screenshot_20260727_142132" src="https://github.com/user-attachments/assets/5322ea0a-53e5-4aa9-bdde-db406ca0780a" />
<img width="1920" height="1080" alt="Screenshot_20260727_141636" src="https://github.com/user-attachments/assets/bc60f153-bea7-44fb-8f6e-11d0b063ae5f" />
 <img width="1920" height="1080" alt="Screenshot_20260727_141543" src="https://github.com/user-attachments/assets/91a52004-f4ca-47fd-8663-1a62391f9345" />
<img width="911" height="587" alt="Screenshot_20260727_140803" src="https://github.com/user-attachments/assets/3644f442-f1c4-463e-bc98-feba19589384" />
<img width="1920" height="1080" alt="Screenshot_20260727_140732" src="https://github.com/user-attachments/assets/b93bea8d-71d3-47d5-9a2a-b5e387128bbd" />
<img width="1920" height="1080" alt="Screenshot_20260727_140138" src="https://github.com/user-attachments/assets/81bca610-3efb-41fd-ba2f-ca396e97387f" />
<img width="1920" height="1080" alt="Screenshot_20260727_140711" src="https://github.com/user-attachments/assets/6f21673a-d16f-4b92-8914-45e7eaa3d47d" />
<img width="1920" height="1080" alt="Screenshot_20260727_135653" src="https://github.com/user-attachments/assets/b77af53b-d10f-4d2c-9605-30cb67291a8d" />
<img width="1920" height="1080" alt="Screenshot_20260727_135102" src="https://github.com/user-attachments/assets/5a82c2be-6fb1-4e60-b5f4-55e4386cdc9a" />

comm file1 file2
 ## OUTPUT
<img width="282" height="136" alt="image" src="https://github.com/user-attachments/assets/c0e12fa6-0426-49e8-a451-20dbd0975dc1" />

 
diff file1 file2
## OUTPUT
<img width="291" height="122" alt="image" src="https://github.com/user-attachments/assets/c410ff67-7ea9-4c3f-b73a-51d41ff56e57" />

#Filters

### Create the following files file11, file22 as follows:

cat > file11
```
Hello world
This is my world
^d
```
cat > file22
```
1001 | Ram | 10000 | HR
1002 | tom |  5000 | Admin
1003 | Joe |  7000 | Developer
^d
```


cut -c1-3 file11
## OUTPUT

<img width="236" height="42" alt="image" src="https://github.com/user-attachments/assets/e8cc4860-0dbb-4018-bc6c-27f3e2e5afb1" />



cut -d "|" -f 1 file22
## OUTPUT
<img width="177" height="65" alt="image" src="https://github.com/user-attachments/assets/2756bfb1-0992-4184-b661-4dc04cc1773c" />



cut -d "|" -f 2 file22
## OUTPUT
<img width="197" height="65" alt="image" src="https://github.com/user-attachments/assets/4ac0078d-1be0-40af-a644-c16211e6de96" />


cat < newfile 
```
Hello world
hello world
^d
````
cat > newfile 
Hello world
hello world
 
grep Hello newfile 
## OUTPUT


grep -v hello newfile 
## OUTPUT
<img width="146" height="27" alt="image" src="https://github.com/user-attachments/assets/1410f52f-444d-43cb-a160-b00a3f093fc3" />



cat newfile | grep -i "hello"
## OUTPUT
<img width="215" height="33" alt="image" src="https://github.com/user-attachments/assets/2cd251a5-9037-4865-be51-89a906732221" />




cat newfile | grep -i -c "hello"
## OUTPUT
<img width="280" height="27" alt="image" src="https://github.com/user-attachments/assets/0642a076-a0bb-498d-9465-b7a50d76d883" />


grep -R ubuntu /etc
## OUTPUT
<img width="461" height="118" alt="image" src="https://github.com/user-attachments/assets/861c18a5-2b09-424b-a6ad-428b0deca52f" />


grep -w -n world newfile   
## OUTPUT
<img width="221" height="37" alt="image" src="https://github.com/user-attachments/assets/aba9be61-0222-4caa-aff2-48a94fdabd07" />


cat < newfile 
```
Hello world
hello world
Linux is world number 1
Unix is predecessor
Linux is best in this World
^d
```

cat > newfile
```
Hello world
hello world
Linux is world number 1
Unix is predecessor
Linux is best in this World
^d
 ```
egrep -w 'Hello|hello' newfile 
## OUTPUT

<img width="200" height="35" alt="image" src="https://github.com/user-attachments/assets/8e5aed6c-6b9b-4cad-926b-e94589fda16c" />


egrep -w '(H|h)ello' newfile 
## OUTPUT
<img width="238" height="35" alt="image" src="https://github.com/user-attachments/assets/41afe711-4ba3-4146-861d-ec9ff6c663df" />


egrep -w '(H|h)ell[a-z]' newfile 
## OUTPUT
<img width="246" height="35" alt="image" src="https://github.com/user-attachments/assets/c50891f7-13fa-45cf-ba57-eeb75de887bd" />




egrep '(^hello)' newfile 
## OUTPUT
<img width="301" height="27" alt="image" src="https://github.com/user-attachments/assets/112a73d8-0d81-4129-bf82-9ace8d38eb1f" />



egrep '(world$)' newfile 
## OUTPUT

<img width="247" height="47" alt="image" src="https://github.com/user-attachments/assets/1659864d-0fb3-473d-9903-33630dfb8268" />


egrep '(World$)' newfile 
## OUTPUT

<img width="248" height="27" alt="image" src="https://github.com/user-attachments/assets/ba7b308d-2910-4ce3-8056-47c9d7694d47" />

egrep '((W|w)orld$)' newfile 
## OUTPUT
<img width="406" height="72" alt="image" src="https://github.com/user-attachments/assets/93f98be8-fe19-4074-af1e-cae7dbcca782" />



egrep '[1-9]' newfile 
## OUTPUT
<img width="243" height="26" alt="image" src="https://github.com/user-attachments/assets/100762d3-558d-409e-9d8c-ce3ab98a2ec7" />



egrep 'Linux.*world' newfile 
## OUTPUT
<img width="332" height="40" alt="image" src="https://github.com/user-attachments/assets/52fa1233-ce13-43c6-bc76-4fd59e3a3eb5" />


egrep 'Linux.*World' newfile 
## OUTPUT

<img width="318" height="36" alt="image" src="https://github.com/user-attachments/assets/831eb893-f0be-4381-a9e3-20b0e853db39" />

egrep l{2} newfile
## OUTPUT

<img width="308" height="43" alt="image" src="https://github.com/user-attachments/assets/959aaede-9b3e-4365-b2d2-0747b156ce3e" />


egrep 's{1,2}' newfile
## OUTPUT 
<img width="323" height="57" alt="image" src="https://github.com/user-attachments/assets/a3a4f565-537c-4166-bb24-38da15aba71c" />


cat > file23
```
1001 | Ram | 10000 | HR
1001 | Ram | 10000 | HR
1002 | tom |  5000 | Admin
1003 | Joe |  7000 | Developer
1005 | Sam |  5000 | HR
1004 | Sit |  7000 | Dev
1003 | Joe |  7000 | Developer
1001 | Ram | 10000 | HR
^d
```


sed -n -e '3p' file23
## OUTPUT
<img width="292" height="37" alt="image" src="https://github.com/user-attachments/assets/d3142e70-4828-489e-926e-cf9074a70b91" />



sed -n -e '$p' file23
## OUTPUT

<img width="257" height="35" alt="image" src="https://github.com/user-attachments/assets/fe690571-a416-4142-819a-1c9a3efccb0a" />


sed  -e 's/Ram/Sita/' file23
## OUTPUT
<img width="348" height="131" alt="image" src="https://github.com/user-attachments/assets/f63d6de4-4546-4aa5-b6d0-738b293ff378" />



sed  -e '2s/Ram/Sita/' file23
## OUTPUT
<img width="406" height="133" alt="image" src="https://github.com/user-attachments/assets/d992089e-c19a-43b9-b74f-aa7b3bbd6d9e" />


sed  '/tom/s/5000/6000/' file23
## OUTPUT

<img width="431" height="132" alt="image" src="https://github.com/user-attachments/assets/7c54b0c0-646f-4ec0-9629-cafd6d88d606" />


sed -n -e '1,5p' file23
## OUTPUT


<img width="352" height="132" alt="image" src="https://github.com/user-attachments/assets/4fb0d3a8-58ea-4aec-895a-03335975de83" />


sed -n -e '2,/Joe/p' file23
## OUTPUT


<img width="377" height="107" alt="image" src="https://github.com/user-attachments/assets/616c44ce-c8d1-40a9-8f66-c6f2ed37c718" />



sed -n -e '/tom/,/Joe/p' file23
## OUTPUT

<img width="347" height="52" alt="image" src="https://github.com/user-attachments/assets/48c066cf-0cef-4264-bb01-2f067aead133" />


seq 10 
## OUTPUT
<img width="242" height="142" alt="image" src="https://github.com/user-attachments/assets/386a41c7-ad26-4c00-90c9-ee82befd0c23" />



seq 10 | sed -n '4,6p'
## OUTPUT

<img width="347" height="65" alt="image" src="https://github.com/user-attachments/assets/59f9987d-ea18-40e2-a539-25c9ae553a9d" />


seq 10 | sed -n '2,~4p'
## OUTPUT
<img width="372" height="60" alt="image" src="https://github.com/user-attachments/assets/395595ee-c410-48ad-bcf5-07c247d0400a" />


seq 3 | sed '2a hello'
## OUTPUT
<img width="327" height="73" alt="image" src="https://github.com/user-attachments/assets/f9783c1e-7a20-4415-a8b9-a823238bd0ed" />



seq 2 | sed '2i hello'
## OUTPUT

<img width="245" height="63" alt="image" src="https://github.com/user-attachments/assets/c4d60b4c-1c4a-446d-ac01-8cee9da7886c" />

seq 10 | sed '2,9c hello'
## OUTPUT
<img width="370" height="58" alt="image" src="https://github.com/user-attachments/assets/400f021f-b90d-465f-bae4-d5413e98881c" />


sed -n '2,4{s/^/$/;p}' file23
## OUTPut


<img width="371" height="65" alt="Screenshot 2026-07-28 233727" src="https://github.com/user-attachments/assets/945369c1-0a83-48dc-b034-b402277154bd" />

sed -n '2,4{s/$/*/;p}' file23


<img width="178" height="23" alt="image" src="https://github.com/user-attachments/assets/d4a09385-134b-46fc-8e23-bde8a3661195" />

#Sorting File content
cat > file21
```
1001 | Ram | 10000 | HR
1002 | tom |  5000 | Admin
1003 | Joe |  7000 | Developer
1005 | Sam |  5000 | HR
1004 | Sit |  7000 | Dev
``` 
sort file21
## OUTPUT


cat > file22
```
1001 | Ram | 10000 | HR
1001 | Ram | 10000 | HR
1002 | tom |  5000 | Admin
1003 | Joe |  7000 | Developer
1005 | Sam |  5000 | HR
1004 | Sit |  7000 | Dev
``` 
uniq file22
## OUTPUT



#Using tr command

cat file23 | tr [:lower:] [:upper:]
 ## OUTPUT

cat < urllist.txt
```
www. yahoo. com
www. google. com
www. mrcet.... com
^d
 ```
cat > urllist.txt
```
www. yahoo. com
www. google. com
www. mrcet.... com
 ```
cat urllist.txt | tr -d ' '
 ## OUTPUT


 
cat urllist.txt | tr -d ' ' | tr -s '.'
## OUTPUT



#Backup commands
tar -cvf backup.tar *
## OUTPUT


mkdir backupdir
 
mv backup.tar backupdir

cd backupdir
 
tar -tvf backup.tar
## OUTPUT


tar -xvf backup.tar
## OUTPUT

gzip backup.tar

ls .gz
## OUTPUT
 
gunzip backup.tar.gz
## OUTPUT

 
# Shell Script
```
echo '#!/bin/sh' > my-script.sh
echo 'echo Hello World‘; exit 0 >> my-script.sh
```
chmod 755 my-script.sh
./my-script.sh
## OUTPUT

 
cat << stop > herecheck.txt
```
hello in this world
i cant stop
for this non stop movement
stop
```

cat herecheck.txt
## OUTPUT


cat < scriptest.sh 
```bash
\#!/bin/sh
echo “File name is $0 ”
echo "File name is " `basename $0`
echo “First arg. is ” $1
echo “Second arg. is ” $2
echo “Third arg. is ” $3
echo “Fourth arg. is ” $4
echo 'The $@ is ' $@
echo 'The $\# is ' $1#
echo 'The $$ is ' $$
ps
^d
 ```

cat scriptest.sh 
```bash
\#!/bin/sh
echo “File name is $0 ”
echo "File name is " `basename $0`
echo “First arg. is ” $1
echo “Second arg. is ” $2
echo “Third arg. is ” $3
echo “Fourth arg. is ” $4
echo 'The $@ is ' $@
echo 'The $\# is ' $\#
echo 'The $$ is ' $$
ps
```
 
chmod 777 scriptest.sh
 
./scriptest.sh 1 2 3

## OUTPUT

 
ls file1
## OUTPUT

echo $?
## OUTPUT 
./one
bash: ./one: Permission denied
 
echo $?
## OUTPUT 
 
abcd
 
echo $?
 ## OUTPUT


 
# mis-using string comparisons

cat < strcomp.sh 
```bash
\#!/bin/bash
val1=baseball
val2=hockey
if [ $val1 \> $val2 ]
then
echo "$val1 is greater than $val2"
else
echo "$val1 is less than $val2"
fi
^d
```

cat strcomp.sh 
```bash
\#!/bin/bash
val1=baseball
val2=hockey
if [ $val1 \> $val2 ]
then
echo "$val1 is greater than $val2"
else
echo "$val1 is less than $val2"
fi
```
##OUTPUT



chmod 755 strcomp.sh
 
./strcomp.sh 
## OUTPUT


# check file ownership
cat < psswdperm.sh 
```bash
\#!/bin/bash
if [ -O /etc/passwd ]
then
echo “You are the owner of the /etc/passwd file”
else
echo “Sorry, you are not the owner of the /etc/passwd file”
fi
^d
```

cat psswdperm.sh 
```bash
/#!/bin/bash
if [ -O /etc/passwd ]
then
echo “You are the owner of the /etc/passwd file”
else
echo “Sorry, you are not the owner of the /etc/passwd file”
fi
 ```
./psswdperm.sh
## OUTPUT

# check if with file location
cat>ifnested.sh 
```bash
\#!/bin/bash
if [ -e $HOME ]
then
echo “$HOME The object exists, is it a file?”
if [ -f $HOME ]
then
echo “Yes,$HOME it is a file!”
else
echo “No,$HOME it is not a file!”
if [ -f $HOME/.bash_history ]
then
echo “But $HOME/.bash_history is a file!”
fi
fi
else
echo “Sorry, the object does not exist”
fi
^d
```
cat ifnested.sh 
```
\#!/bin/bash
if [ -e $HOME ]
then
echo “$HOME The object exists, is it a file?”
if [ -f $HOME ]
then
echo “Yes,$HOME it is a file!”
else
echo “No,$HOME it is not a file!”
if [ -f $HOME/.bash_history ]
then
echo “But $HOME/.bash_history is a file!”
fi
fi
else
echo “Sorry, the object does not exist”
fi
```

./ifnested.sh 
## OUTPUT



# using numeric test comparisons
cat > iftest.sh 
```bash
\#!/bin/bash
val1=10
val2=11
if [ $val1 -gt 5 ]
then
echo “The test value $val1 is greater than 5”
fi
if [ $val1 -eq $val2 ]
then
echo “The values are equal”
else
echo “The values are different”
fi
^d
```


cat iftest.sh 
```bash
\#!/bin/bash
val1=10
val2=11
if [ $val1 -gt 5 ]
then
echo “The test value $val1 is greater than 5”
fi
if [ $val1 -eq $val2 ]
then
echo “The values are equal”
else
echo “The values are different”
fi
```

$ chmod 755 iftest.sh
 
$ ./iftest.sh 
##OUTPUT

# check if a file
cat > ifnested.sh 
```bash
\#!/bin/bash
if [ -e $HOME ]
then
echo “$HOME The object exists, is it a file?”
if [ -f $HOME ]
then
echo “Yes,$HOME it is a file!”
else
echo “No,$HOME it is not a file!”
if [ -f $HOME/.bash_history ]
then
echo “But $HOME/.bash_history is a file!”
fi
fi
else
echo “Sorry, the object does not exist”
fi
^d
```

cat ifnested.sh 
```bash
\#!/bin/bash
if [ -e $HOME ]
then
echo “$HOME The object exists, is it a file?”
if [ -f $HOME ]
then
echo “Yes,$HOME it is a file!”
else
echo “No,$HOME it is not a file!”
if [ -f $HOME/.bash_history ]
then
echo “But $HOME/.bash_history is a file!”
fi
fi
else
echo “Sorry, the object does not exist”
fi
```

$ chmod 755 ifnested.sh
 
$ ./ifnested.sh 
##OUTPUT

# looking for a possible value using elif
cat elifcheck.sh 
```bash
\#!/bin/bash
if [ $USER = Ram ]
then
echo "Welcome $USER"
echo "Please enjoy your visit"
elif [ $USER = Rahim ]
then
echo "Welcome $USER"
echo "Please enjoy your visit"
elif [ $USER = Robert ]
then
echo "Special testing account"
elif [ $USER = gganesh ]
then
echo "$USER, Do not forget to logout when you're done"
else
echo "Sorry, you are not allowed here"
fi
```

$ chmod 755 elifcheck.sh
 
$ ./elifcheck.sh 
## OUTPUT


# testing compound comparisons
cat> ifcompound.sh 
```bash
\#!/bin/bash
if [ -d $HOME ] && [ -w $HOME ]
then
echo "The file exists and you can write to it"
else
echo "I cannot write to the file"
fi
```
$ chmod 755 ifcompound.sh
$ ./ifcompound.sh 
## OUTPUT

# using the case command
cat >casecheck.sh 
```bash
case $USER in
Ram | Robert)
echo "Welcome, $USER"
echo "Please enjoy your visit";;
Rahim)
echo "Special testing account";;
gganesh)
echo "$USER, Do not forget to log off when you're done";;
*)
echo "Sorry, you are not allowed here";;
esac
```
$ chmod 755 casecheck.sh 
 
$ ./casecheck.sh 
 
cat > whiletest
```bash
#!/bin/bash
#while command test
var1=10
while [ $var1 -gt 0 ]
do
echo $var1
var1=$[ $var1 - 1 ]
done
```
$ chmod 755 whiletest.sh
 
$ ./whiletest.sh
 
 
cat untiltest.sh 
```bash
\#using the until command
var1=100
until [ $var1 -eq 0 ]
do
echo $var1
var1=$[ $var1 - 25 ]
done
``` 
$ chmod 755 untiltest.sh
 
 
 
cat forin1.sh 
```bash
\#!/bin/bash
\#basic for command
for test in Alabama Alaska Arizona Arkansas California Colorado
do
echo The next state is $test
done
 ```
 
$ chmod 755 forin1.sh
 
 
cat forin2.sh 
```bash
\#!/bin/bash
\# another example of how not to use the for command
for test in I don't know if this'll work
do
echo “word:$test”
done
 ```
 
$ chmod 755 forin2.sh
 
cat forin2.sh 
```bash
\#!/bin/bash
\# another example of how not to use the for command
for test in I don't know if this'll work
do
echo “word:$test”
done
```
$ chmod 755 forin2.sh
 
$ ./forin2.sh 
 
cat forin3.sh 
```bash
\#!/bin/bash
\# another example of how not to use the for command
for test in I don\'t know if "this'll" work
do
echo "word:$test"
done
```
$ ./forin3.sh 
 
cat forin1.sh 
```bash
#!/bin/bash
# basic for command
for test in Alabama Alaska Arizona Arkansas California Colorado
do
echo The next state is $test
done
```
$ chmod 755 forin1.sh

## OUTPUT
cat forinfile.sh 
```bash
#!/bin/bash
# reading values from a file
file="cities"
for state in `cat $file`
do
echo "Visit beautiful $file“
done
```
$ chmod 777 forinfile.sh
$ cat cities
Hyderabad
Alampur
Basara
Warangal
Adilabad
Bhadrachalam
Khammam

## OUTPUT


cat forctype.sh 
```bash
#!/bin/bash
# testing the C-style for loop
for (( i=1; i <= 5; i++ ))
do
echo "The value of i is $i"
done
````
$ chmod 755 forctype.sh
$ ./forctype.sh 
## OUTPUT

cat forctype1.sh 
```bash
#!/bin/bash
# multiple variables
for (( a=1, b=5; a <= 5; a++, b-- ))
do
echo "$a - $b"
done
```
$ chmod 755 forctype.sh
$ ./forctype1.sh 
## OUTPUT

cat fornested1.sh 
```bash
#!/bin/bash
# nesting for loops
for (( a = 1; a <= 3; a++ ))
do
echo "Starting loop $a:"
for (( b = 1; b <= 3; b++ ))
do
echo " Inside loop: $b"
done
done
```
$ chmod 755 fornested1.sh
 
$ ./fornested1.sh 
 ## OUTPUT

 
cat forbreak.sh 
```bash
#!/bin/bash
# breaking out of a for loop
for var1 in 1 2 3 4 5
do
if [ $var1 -eq 3 ]
then
break
fi
echo "Iteration number: $var1"
done
echo "The for loop is completed“
```
## OUTPUT

$ chmod 755 forbreak.sh
 
$ ./forbreak.sh 
 
cat forbreak.sh 
```bash
#!/bin/bash
# breaking out of a for loop
for var1 in 1 2 3 4 5
do
if [ $var1 -eq 3 ]
then
continue
fi
echo "Iteration number: $var1"
done
echo "The for loop is completed“
```

 
$ chmod 755 forcontinue.sh
 
$ ./forcontinue.sh 
## OUTPUT
 
cat exread.sh 
```bash
#!/bin/bash
# testing the read command
echo -n "Enter your name: "
read name
echo "Hello $name, welcome to my program. "
 ```
 
$ chmod 755 exread.sh 
 
$ ./exread.sh 
## OUTPUT


 cat exread1.sh
```bash
#!/bin/bash
# testing the read command
read -p "Enter your name: " name
echo "Hello $name, welcome to my program. “
``` 
$ chmod 755 exread1.sh 

## OUTPUT



$ ./exread1.sh 
 
cat funcex.sh
```bash
#!/bin/bash
# trying to access script parameters inside a function
function func {
echo $[ $1 * $2 ]
}
if [ $# -eq 2 ]
then
value=`func $1 $2`
echo "The result is $value"
else
echo "Usage: badtest1 a b"
fi
```
## OUTPUT
 ./funcex.sh 

 
 ./funcex.sh 1 2

 
cat argshift.sh
```bash
#!/bin/bash 
 while (( "$#" )); do 
  echo $1 
  shift 
done
```
$ chmod 777 argshift.sh

## OUTPUT
$ ./argshift.sh 1 2 3
 
 cat argshift1.sh
```bash
 #/bin/bash 
 # store arguments in a special array 
args=("$@") 
# get number of elements 
ELEMENTS=${#args[@]} 
 # echo each element in array  
# for loop 
for (( i=0;i<$ELEMENTS;i++)); do 
    echo ${args[${i}]} 
done
```
$ chmod 777 argshift.sh
## OUTPUT
$ ./argshift.sh 1 2 3
 
cat argshift.sh
```bash
#!/bin/bash 
set -x 
while (( "$#" )); do 
  echo $1 
  shift 
done
set +x
```
## OUTPUT
 ./argshift.sh 1 2 3
 
 
cat > nc.awk
```bash
BEGIN{}
{
print len=length($0),"\t",$0 
wordcount+=NF
chrcnt+=len
}
END {
print "total characters",chrcnt 
print "Number of Lines are",NR
print "No of Words count:",wordcount
}
 ```
cat>data.dat
```bash
bcdfghj
abcdfghj
bcdfghj
ebcdfghj
bcdfghj
ibcdfghj
bcdfghj
obcdfghj
bcdfghj
ubcdfghj
```
awk -f nc.awk data.dat
## OUTPUT 
 
cat > palindrome.sh
```bash
#num=545
echo "Enter the number"
read num
s=0
rev=""
temp=$num
while [ $num -gt 0 ]
do
	# Get Remainder
	s=$(( $num % 10 ))
	# Get next digit
	num=$(( $num / 10 ))
	# Store previous number and
	# current digit in reverse
	rev=$( echo ${rev}${s} )
done
if [ $temp -eq $rev ];
then
	echo "Number is palindrome"
else
	echo "Number is NOT palindrome"
fi
```
## OUTPUT 


# RESULT:
The Commands are executed successfully.
