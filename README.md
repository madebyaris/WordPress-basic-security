# WordPress-basic-security
-----
**TABLE OF CONTENT**
1. Prevent brute force login (easy)
2. Use HTTPS  (easy-med)
3. Never use standard `wp-` for table name
4.
-----
### 1. Prevent brute force login
Some people doesn't care if someone can lookup their login page, if your site did not need user to login, it would be wise if you change the standard of WordPress login url or you can do another thing so the bad guy cannot `hack` you. here some ways to prevent a brute force :
- Add captcha from google. you can use this plugin https://id.wordpress.org/plugins/google-captcha/
- Rewrite the standard of WordPress login url, you can use this plugin to achive that https://id.wordpress.org/plugins/wps-hide-login/
- if your site did not need to show the author page, it's best to not show the user information about it, you can disable it with this plugin https://wordpress.org/plugins/disable-author-pages/ note: the dev seem's leave the repo.
- And the last resort, use a strong password, make an a combination that it's hard to find, and never use a generic password like `1qaz1qaz` or something like that.
-----
### 2. Use HTTPS
