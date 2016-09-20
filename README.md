Welcome to [PROJECT_TEMPLATE]!
============================


Hey! This is your development **onboarding**! Don't delete me, I'm very helpful! 

----------

Ready?
----------------

#### <i class="icon-pencil"></i> Install Drupal Console

I'm a very useful tool! You need me so please install me. Instructions can be found here https://drupalconsole.com/articles/how-to-install-drupal-console.

#### <i class="icon-folder-open"></i> Clone [PROJECT_TEMPLATE]

I will be your project folder and the new home for your Drupal 8 site. Don't delete me unless you want to start from scratch or you're leaving this project.

* ``` $ git clone https://github.com/wouteradem/my_project_template ```
* ``` $ cd my_project_template ```

Set?
----------------

#### <i class="icon-pencil"></i> Download Drupal 8

We are all set to download Drupal 8 and start a local PHP server. Fire this command:

* ``` $ drupal chain --file=quick-start.yml ```

**Drupal docroot lives in drupal8.dev!**

> **Note:**

> - You can always use DevDesktop or DrupalVM instead of a local PHP server
> - To start the local PHP server from your terminal use the command ``` $ /usr/bin/php -S 127.0.0.1:8088 /Users/wouter.adem/.console/router.php ```

Go!
----------------
#### <i class="icon-pencil"></i>  Install Drupal 8

Now we are set to install Drupal 8. Supposing **you are able to setup your local Database connection** go to your site URL in your browser e.g. http://127.0.0.1:8088/"

Copy our custom profile by invoking this command ```$ cp -Rf my_profile drupal8.dev/profiles``` to the directory **drupal8.dev**. Now use the UI and select the ```my_profile``` profile and let the magic happen. You need to fill in the required fields but the values don't matter.

For the moment you now need to apply two hacks:
* Open ```settings.php``` and add the line ```$config_directories['sync'] = 'profiles/my_profile/config/sync';``` at the bottom and save.
* Open ```core.extension.yml```
* Replace the word ```standard``` with ```my_profile``` and save the file

After the site is installed it looks kind of bad! But go to ```/admin/config/development/configuration``` and scroll down and just click import. You'll see Drupal importing all its required site configuration.

Done! New World Record!

----------


