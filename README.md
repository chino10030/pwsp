<php 

# pwsp
simple authentication logining php code


 Page Password Protect 2.13

 Visit http://www.zubrag.com/scripts/ for updates


 Usage:
 Set usernames / passwords below between SETTINGS START and SETTINGS END.
 Open it in browser with "help" parameter to get the code
 to add to all files being protected. 
 Example: password_protect.php?help
 Include protection string which it gave you into every file that needs to be protected

 Add following HTML code to your page where you want to have logout link
 <a href="http://www.example.com/path/to/protected/page.php?logout=1">Logout</a>


-------------------------------------------------------------------
SAMPLE if you only want to request login and password on login form.
Each row represents different user.

$LOGIN_INFORMATION = array(
'zubrag' => 'root',
'test' => 'testpass',
'admin' => 'admin'
);

--------------------------------------------------------------------
SAMPLE if you only want to request only password on login form.
Note: only passwords are listed

$LOGIN_INFORMATION = array(
'root',
'testpass',
'passwd'
);


