# branding-template

Template of branding that can be shown on yoru JATOS' home page instead of the standard welcome message.

## Howto
1. Click 'Use this template' button
1. Change the content of `branding-template.html` to your needs
1. Add necessary files (e.g. logo images) to your repository
1. In your JATOS installation folder edit `conf/production.conf` - add `jatos.brandingUrl` but change `my-user` and `my-repo`:

   ```
   jatos.brandingUrl = "https://raw.githubusercontent.com/my-user/my-repo/main/branding-template.html"
   ```

1. Restart JATOS
1. You can update `branding-template.html` at any time to add new information (e.g. anouncement of JATOS maintance work)
