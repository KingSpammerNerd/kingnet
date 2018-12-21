# KingNET
A Twitter/4chan-style public message board, written in Java

**KingNET should be online soon. I'll be linking to it when it finally is.**

The JRE of your choice

Apache Tomcat

MySQL or a compatible equivalent (I personally use MariaDB)

**The SQL tables need to be setup as follows:**

table users:
username, passhash, sessionid

table threads:
threadid, title, posts_dir

table bios:
username, bio

**(Hardcoded) SQL credentials for KingNET:**

username: knet

password: knet123

If you dig hard enough through the source code, you can find and edit these values. I know I shouldn't hardcode credentials, but I'm lazy. Go figure :P
