Matthew J Kemp

To run the program you need to have mysql installed and the root password must be password.
If you cant change the root password you should be able to make a new database and modify the code in Database.java
line 25 where it says "root" and "password".
If you are having trouble running the program on a mac then try opening the jar file through
the command line, for some reason this fixes it.
Also make sure you aren't on a vpn as this was causing problems with the smtp connection.

here is the email to test the program:
email: testemailtestemail852@gmail.com
pass: test123%

to test the check inbox option:
email yourself on the test email this:
to: testemailtestemail852@gmail.com
subject:Book Checked Out
content Date: 8/3/2018 | Time: 9:48:35 AM
Fines/Fees Owed: $0.00
Total Checked Out: 1
Checked Out
Title: Valley of genius : the uncensored history of Silicon Valley, as told by the hackers, founders, and freaks who made it boom Barcode: 0000123358814 Due Date: 8/24/2018,23:59

You can modify Fines, Checked Out, Title, and Due Date.

The program checks the inbox every minute, ideally it would only do this once a day.
You can easily edit the rate at which it checks the inbox in the MainGUI.java at line 244.

Videos:
Vid1:https://youtu.be/6oS6znRLFIg
vid2:https://youtu.be/S4zr22tSkjs
