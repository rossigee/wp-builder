WordPress Builder
=================

Just a couple of very basic scripts that I use to help me download and deploy WordPress to my various working environments.

The main script ('build-wordpress') just grabs the latest WordPress zipfile, and any client-specific plugins and themes, unzips and assembles them into place. It will also copy in a prepared 'wp-config.php' file and various other files as specified before creating a ZIP file.

There are then optional scripts (i.e. 'deploy-wordpress-to-aws-beanstalk') which will deploy the ZIP to hosting environments.

