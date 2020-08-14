# WordPress-basic-security
-----
**TABLE OF CONTENT**
1. Prevent brute force login (easy)
2. Use HTTPS  (easy-med)
3. Never use prefix standard `wp_` for table name (easy)
4. Hide your Index Directory (easy-med)
5. Always update your plugins, Themes, WordPress (easy)
6. Never use a Nulled version of the plugins or Themes (easy-med)
-----
### 1. Prevent brute force login
Some people doesn't care if someone can lookup their login page, if your site did not need user to login, it would be wise if you change the standard of WordPress login url or you can do another thing so the bad guy cannot `hack` you. here some ways to prevent a brute force :
- Add captcha from google. you can use this plugin https://id.wordpress.org/plugins/google-captcha/
- Rewrite the standard of WordPress login url, you can use this plugin to achive that https://id.wordpress.org/plugins/wps-hide-login/
- if your site did not need to show the author page, it's best to not show the user information about it, you can disable it with this plugin https://wordpress.org/plugins/disable-author-pages/ note: the dev seem's leave the repo.
- And the last resort, use a strong password, make an a combination that it's hard to find, and never use a generic password like `1qaz1qaz` or something like that.
- Disable `xmlrpc` , some of attacker will try to login via xmlrpc, BUT before you disable,  you need to consider if you use something that need xmlrpc, here's the full article and how to disable it https://www.greengeeks.com/tutorials/article/how-to-enable-and-disable-xmlrpc-php-in-wordpress-and-why/
-----
### 2. Use HTTPS

### 3. Never use prefix standard  `wp_` for table name
Never use standard prefix 'wp_' for the table name, because when attacker can access your sql with by any mean. For the most brual ways, they can log in to your dashboard as admin (with change your admin password). So use not a prefix standard, it will come a handy in the future.

### 4. Hide your Index Directory
Hide your index directory, so the attacker cannot see your directory (also file) structure of your site. you can follow this step to secure this one : https://www.wpbeginner.com/wp-tutorials/disable-directory-browsing-wordpress/

### 5. Always update your plugins, Themes, and WordPress 
Update your plugins, Themes, and WordPress, so if there are vulnerability on the website, and the author spot it on and update it. so your site will be secure.

### 6. Never use a Nulled version of the plugins or Themes
If there are a backdoor of your site (because it included on the nulled plugins ort themes ), mean, your site are already vulnerable to be attack, most of the cases, they  changed your front-page so you will contact their, and pay to change it back, to the way as it is. But, remember, they can still can attack you because the backood is still there, DELETE IT NOW!!!
