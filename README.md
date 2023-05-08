# **Bandit Challenge**
- ## **Level 0 => Level 1**
```sh
cat readme
```
**Password level 1 :** <span class="pwd">NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL</span> 

<hr>

- ## **Level 1 => Level 2**
```sh
cat ./-
```
**Password level 2 :** <span class="pwd">rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi</span>

<hr>

- ## **Level 2 => Level 3**
```sh
cat "space in this filename"
```
**Password level 3 :** <span class="pwd">aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG</span>

<hr>

- ## **Level 3 => Level 4**
```sh
ls -a inhere

cat inhere/.hidden
```
**Password level 4 :** <span class="pwd">2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe</span>

<hr>

- ## **Level 4 => Level 5**
```sh
cd inhere

file ./*

cat ./-file07
```
**Password level 5 :** <span class="pwd">lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR</span>

<hr>

- ## **Level 5 => Level 6**
```sh
find -size 1033c

cat inhere/maybehere07.file2
```
**Password level 6 :** <span class="pwd">P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU</span>

<hr>

- ## **Level 6 => Level 7**
```sh
find / -size 33c -user bandit7 -group bandit6 -type f

cat ./var/lib/dpkg/info/bandit7.password
```
**Password level 7 :** <span class="pwd">z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S</span>

<hr>

- ## **Level 7 => Level 8**
```sh
grep "millionth" data.txt
```
**Password level 8 :** <span class="pwd">TESKZC0XvTetK0S9xNwm25STk5iWrBvP</span>

<hr>

- ## **Level 8 => Level 9**
```sh
sort data.txt | uniq -cu
```
**Password level 9 :** <span class="pwd">EN632PlfYiZbn3PhVK3XOGSlNInNE00t</span>

<hr>

- ## **Level 9 => Level 10**
```sh
strings data.txt | grep "==" 
```
**Password level 10 :** <span class="pwd">G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s</span>

<hr>

- ## **Level 10 => Level 11**
```sh
cat data.txt | base64 -d 
```
**Password level 11 :** <span class="pwd">6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM</span>

<hr>

- ## **Level 11 => Level 12**
```sh
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
**Password level 12 :** <span class="pwd">JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv</span>

<hr>

- ## **Level 12 => Level 13**
```sh
xxd -r data.txt data1
mv data1 data2.gz
gzip -d data2.gz
mv data2 data3.bz2
bzip2 -d data3.bz2
mv data3 data4.gz
gzip -d data4.gz
tar -xvf data4
tar -xvf data5.bin
mv data6.bin data7.bz2
bzip2 -d data7.bz2
tar -xvf data7
mv data8.bin data9.gz
gzip -d data9.gz
cat data9
```
**Password level 13 :** <span class="pwd">wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw</span>

<hr>

- ## **Level 13 => Level 14**
```sh
cat sshkey.private 

ssh -i sshkey.private bandit14@localhost -p 2220

cat /etc/bandit_pass/bandit14

```
**Password level 14 :** <span class="pwd">fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq</span>

<hr>

- ## **Level 14 => Level 15**
```sh
cd /etc/bandit_pass/bandit14

cat bandit14

echo fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq | nc localhost 30000
```
**Password level 15 :** <span class="pwd">jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt</span>

<hr>

- ## **Level 15 => Level 16**
```sh
cat /etc/bandit_pass/bandit15

openssl s_client -connect localhost:30001
```
**Password level 16 :** <span class="pwd">JQttfApK4SeyHwDlI9SXGR50qclOAil1</span>

<hr>

- ## **Level 16 => Level 17**
```sh
nmap -A localhost -p 31000-32000
openssl s_client -connect localhost:31790
cd  /tmp
vim ssh-myKey.private ( to copy the ssh key )
chmod 600 ssh-myKey.private
ssh -i ssh-myKey.private bandit17@localhost -p 2220
```
**Password level 17 :** <span class="pwd">VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e</span>

<hr>

- ## **Level 17 => Level 18**
```sh
diff passwords.new passwords.old
```
**Password level 18 :** <span class="pwd">kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd</span>

<hr>

- ## **Level 18 => Level 19**
```sh
ssh -i sshkey.private bandit14@localhost -p 2220 cat readme
```
**Password level 19 :** <span class="pwd">awhqfNnAbc1naukrpqDYcF95h7HoMTrC</span>

<hr>

- ## **Level 19 => Level 20**
```sh
file bandit20-do 

./bandit20-do

./bandit20-do cat /etc/bandit_pass/bandit20
```
**Password level 20 :** <span class="pwd">VxCazJaVykI6W36BkBU0mJTCM8rR95XT</span>

- ## **Level 20 => Level 21**
```sh
file ./suconnect

echo -n 'VxCazJaVykI6W36BkBU0mJTCM8rR95XT' | nc -lp 1234

./suconnect 1234
```

