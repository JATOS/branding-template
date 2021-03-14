# Customized Welcome Page

This is a template for a customized welcome page. This HTML block can be shown on your JATOS' home page instead of the standard welcome message.

## Howto
1. Click 'Use this template' button to create a copy of this repository
1. Change the content of `foobar-university-welcome-page.html` to your needs
1. Add necessary files (e.g. logo images) to your repository
1. In your JATOS installation folder edit `conf/production.conf` - add `jatos.brandingUrl`:

   ```
   jatos.brandingUrl = "https://raw.githubusercontent.com/my-user/my-repo/main/branding-template.html"
   ```
   
   Remember to change `my-user` and `my-repo`.

1. Restart JATOS
1. You can update your welcome page at any time to add new information (e.g. anouncement of JATOS maintance work) and the changed page will be use immediately. 
