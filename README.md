# dots-build-plugin

Follow the below step to create the basic structure of a plugin
1. Open your web browser and navigate to "https://wppb.me/".
2. On the "https://wppb.me/" site, you'll find a form for generating your plugin's boilerplate. Fill in the following details:
    
    * **Plugin Name:** Enter your desired plugin name.
    * **Plugin Slug:** Provide a slug, which is a unique identifier for your plugin. Use lowercase letters and hyphens only.
    * **Plugin URL:** Enter the URL where your plugin will be hosted (usually your website URL).
    * **Author Name:** Your name or your organization's name.
    * **Author Email:** Your contact email.
    * **Author URI:** Your website's URL.
    * **Plugin Short Description:** A brief description of your plugin's purpose.

Once you've filled in all the required details, click on the "Build Plugin". This should generate a downloadable zip file containing the boilerplate for your plugin.

Now, We will use the above header and footer (PHP and CSS) files from the GIT repo.

3. Navigate to the "admin/partials" directory, where we will place the "header" folder of this GIT repo.
4. Then Navigate to the "admin/css" directory, where we will place the "plugin-header.css" file of this GIT repo.
5. We need to enqueue these files in the "class-{slug_of_plugin}-admin.php" file which is in the admin folder of your plugin.
6. Now you must find and replace text-domain "build-my-plugin" to "{your_plugin_text_domain}" of PHP file.
7. Alright! you have prepared thedotstore plugin boilerplate.
