zypper update

zypper in emacs 

zypper in git

zypper in xf86-video-intel

zypper in python

zypper in gcc

zypper in gcc-c++

zypper in ibus-pinyin

settings --> region & language --> input sources
add chinese(pinyin)

zypper in gsynaptics

zypper in firefox

#firefox

FoxyProxy
Adblock Plus


#github

zypper in git

ssh-keygen -t rsa -C "Heysion@Develop"


#ssh login

- 在A机器上生成ssh-key 将A机器的公钥放到B机器(将被登录的机器)的被登录用户 .ssh/authorized_keys

- 修改 /etc/ssh/sshd_config (PermitRootLogin no RSAAuthentication yes PubkeyAuthentication yes AuthorizedKeysFile	.ssh/authorized_keys PasswordAuthentication no)

- 重启sshd 服务 service sshd restart

