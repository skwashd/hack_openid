Hack OpenID module for Drupal

This module makes it possible to user to login with gmail/google apps using
OpenID without having to use the admin form.  This is great for intranets or
other sites with a closed audience. Create a menu link or block that links to
user/login/gapps.

If you want you can assign a user a role based on their email domain, you can
set the hack_openid_domain_role_map variable as an array which maps
@domain => role_name.  If user's are in the domain map they will be 
automagically approved on their first login.

This module has been released on github as I am unlikely to maintain it. You
are free to use it, modify it, do whatever you like with it, so long as you
observe the requirements of the GPL.

Created by Dave Hall - http://davehall.com.au
