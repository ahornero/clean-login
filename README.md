[![WordPress](https://img.shields.io/wordpress/v/clean-login.svg)](https://wordpress.org/plugins/clean-login/)
[![Licence](https://img.shields.io/badge/license-GPLv2-orange.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![WordPress](https://img.shields.io/wordpress/plugin/dt/clean-login.svg)](https://wordpress.org/plugins/clean-login/)

![Clean Login icon](https://ps.w.org/clean-login/assets/icon-128x128.png)

# Basic Overview
Responsive Frontend Login and Registration plugin for WordPress. A plugin for displaying login, register, editor and restore password forms through shortcodes.
```
[clean-login]
[clean-login-edit]
[clean-login-register]
[clean-login-restore]
```

# Installation
* Install **Clean Login** automatically through the WordPress Dashboard or by uploading the ZIP file in the _plugins_ directory.
* Then, after the package is uploaded and extracted, click&nbsp;_Activate Plugin_.

Now going through the points above, you should now see a new **Clean Login menu** item under Settings menu in the sidebar of the admin panel, see figure below of how it looks like.

![Setting Menu image link](https://ps.w.org/clean-login/assets/screenshot-8.jpg)

If you get any error after following through the steps above please contact us through item support comments so we can get back to you with possible helps in installing the plugin and more. On successful activation of this plugin, you should be able to see the login form when you place this shortcode *[clean-login]* in any page or post

# Settings
Below, the description of each shortcode for use as registration, login, lost password and profile editor forms
* *[clean-login]* This shortcode contains login form and login information.
* *[clean-login-edit]* This shortcode contains the profile editor. If you include in a page/post a link will appear on your login preview.
* *[clean-login-register]* This shortcode contains the register form. If you include in a page/post a link will appear on your login form.
* *[clean-login-restore]* This shortcode contains the restore (lost password?) form. If you include in a page/post a link will appear on your login form.

Also, in the Clean Login settings page you can check the plugin status as follows:

![Plugin status image link](https://ps.w.org/clean-login/assets/screenshot-9.jpg)

In this setting page you can also find the way to enable/disable the differents options of the plugin, like below:

![Options image link](https://ps.w.org/clean-login/assets/screenshot-10.jpg)

Regarding the widget usage, just place the *Clean Login status and links* widget in the widget area you prefer. It will show the user status and the links to the pages/posts which contains the plugin shortcodes.

Please feel free to contact us if you have any questions.

# Example
A post/page need to be created by typing the main shortcode *[clean-login]* in the content.

When you save or update this post/page you will see the login form.

And also in the setting page *[clean-login]* entry will be updated pointing to the current post/page which contains the shortcode (and generates the login form):

![Settings updated image link](https://ps.w.org/clean-login/assets/screenshot-11.jpg)

We would repeat the same process with the rest of shortcodes if we need it:
* *[clean-login-edit]* to create an edit profile form
* *[clean-login-register]* to create a registration form
* *[clean-login-restore]* to create a forgotten password and restore form

# Contribution
Contributions to *Clean Login* are always welcome, and please feel free to contact us if you have any doubt. You can help us in different ways:
* Open an issue with suggestions or code changes for improvements and errors you're facing
* Fork this repository and submit a pull request
* Improve the documentation
