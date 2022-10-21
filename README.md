# Joomla! 4 Symlink Filesystem Plugin

This is a plugin to allow the media directories to be symlinked in the joomla directory. Designed for sites that are 
deployed with [PHP Deployer](https://deployer.org/) where the media files are stored in the `shared` directory.

If you are getting the following error message, this plugin may be what you need:

    Joomla\CMS\Filesystem\Path::check() - Snooping out of bounds @ /var/www/sites/your_site/shared/images/

### Configuring the plugin
1. Download `plg_filesystem_symlink.zip`.
2. Install the plugin.
3. Open plugin manager (System, Manage, Plugins).
4. Search for "filesystem".
5. Disable plugin "FileSystem - Local".
6. Edit plugin "FileSystem - Symlink".
7. Change status to "Enabled".
8. Add directory "files".
9. Click "Save & Close".
