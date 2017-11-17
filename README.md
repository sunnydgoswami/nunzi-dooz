If you're having trouble with the contact form, make sure to follow these steps:

1. First make sure your website is hosted on a web server with PHP enabled. When the submit button is clicked, the PHP script in contact_me.php runs. If you're trying to use the form locally, the message wont send unless you have a server environment set up on your local machine.

2. If you've uploaded your site to a web server and the form still isn't sending, there is probably a permissions/security issue preventing the form from sending email. First make sure that the email address that you're sending mail to is correct. If it's correct, try using an email address with a private domain, rather than something popular like Gmail or Yahoo. A lot of web hosts prevent forms from sending to popular mail servers for spam purposes. If it still isn't working after changing the email address, contact your web host to see if they can figure out what is preventing the form from sending.

Hopefully this helps those of you having some trouble with the form! Keep in mind, that in order to use the form, you only need to change the email address on line 19 of the mail/contact_me.php file.