We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
gpg: key 785574D692B60025 marked as ultimately trusted
gpg: directory '/home/nisha/.gnupg/openpgp-revocs.d' created
gpg: revocation certificate stored as '/home/nisha/.gnupg/openpgp-revocs.d/F3CD1FE388E3E09A2DA3FC69785574D692B60025.rev'
public and secret key created and signed.

pub   rsa3072 2025-11-14 [SC] [expires: 2027-11-14]
      F3CD1FE388E3E09A2DA3FC69785574D692B60025
uid                      Nisha <hins.2026@gmail.com>
sub   rsa3072 2025-11-14 [E] [expires: 2027-11-14]


when the docker image is opened, the password is Brainagingmap?19




##### for Git 

id_ed25519  id_ed25519.pub

ssh-keygen -t ed25519 -C "hins.2026@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/nisha/.ssh/id_ed25519): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/nisha/.ssh/id_ed25519
Your public key has been saved in /home/nisha/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:cjokuoxSmUE9uWhoMrKFJWKl2PJmMhLFIN2kKUps3tE hins.2026@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|o+o=..           |
|*+*o*            |
|B@+o E           |
|@** o            |
|O*+=. o S        |
|o=+. o +         |
| ..   o          |
|.o .   .         |
|o o              |
+----[SHA256]-----+

cat ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIBgmfIYVHTA8WdLtKD4KJmqCaXbJO5Wkp77oGX3BlBrz hins.2026@gmail.com




