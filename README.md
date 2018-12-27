# KingNET
A Twitter/4chan-style public message board, written in Java

KingNET is dead. Long Live KingNET.

**Software requirements:**

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

Donate if you're feeling generous: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=G7LPZC684RYFL" target="_top">PayPal</a>
<form>
<input type="image" src="https://www.paypalobjects.com/en_GB/i/btn/btn_paynow_SM.gif" border="0" name="submit" alt="PayPal – The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_GB/i/scr/pixel.gif" width="1" height="1">
</form>
