Overview
===========

Typeprotect allows you to password-protect any of your pages with a single line of PHP code. 


Demo
===========
http://preview.typebig.com/typeprotect/

Benefits
===========
1. Minimal yet extremely usuable user interface. 
2. Lightweight - ~4kb
3. Simple - one single file, no external CSS


Instructions
===========
1. Copy & paste <strong>typeprotect.php</strong> to your directory
2. Open up <strong>typeprotect.php</strong> and change the value for $password to your own SHA-1 hashed password (http://hash.online-convert.com/sha1-generator). The default password is <em>test</em>, which is "a94a8fe5ccb19ba61c4c0873d391e987982fbbd3" when SHA-1 hashed. 

3. Include the following code on the first line of the document you'd like to protect.

	<strong><?php require('typeprotect.php'); ?></strong>

4. To create a sign-out link, add the following line of code. 
 
	<strong>&lt;a href="typeprotect.php?signout=1"&gt;Sign Out&lt;/a&gt;</strong>
