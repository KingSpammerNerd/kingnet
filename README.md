# KingNET
A Twitter/4chan-style public message board, written in Java

**So, due to ISP issues, as of now I've given up hope of taking KingNET online. Anyway, for what it's worth, here's the kind of system setup needed:**

The JRE of your choice

Apache Tomcat

MySQL or a compatible equivalent (I personally use MariaDB)

**The SQL tables need to be setup as follows:**

table users:
username, passhash, sessionid

table threads:
threadid, title, posts_dir

**SQL credentials for KingNET:**

username: knet

password: knet123

If you dig hard enough through the source code, you can find ad edit these values. I know I shouldn't hardcode credentials, but I'm lazy. Go figure :P
