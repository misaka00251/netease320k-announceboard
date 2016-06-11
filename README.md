# What is this?
 This is used by Netease cloudmusic to deal with the music quality, which is based on [myTinyTodo](http://www.mytinytodo.net/).
 You can find our Project site [here](http://163.uushare.info/announce/).
 If you find any issue please post [here](https://github.com/misaka00251/netease320k-announceboard/issues/new).

# Fetures
## Original:
* Multiple lists
* Task notes
* Tags (and tag cloud)
* Due dates (input format: y-m-d, m/d/y, d.m.y, m/d, d.m)
* Priority (-1, 0, +1, +2)
* Different sortings including sort by drag-and-drop
* Search
* Password protection
* Smart syntax improves creation of tasks (usage: /priority/ Task /tags/)
* Print-friendly CSS
* Style for mobiles devices

## This project will:
Well, we haven't finish develop yet...
* Protect your notes (only you can see)
* Guests post
* Output into JPG & PNG format

# System requirements
* PHP 5.2.0 or greater;
* PHP extensions: php_mysql (MySQL version), php_pdo and php_pdo_sqlite (SQLite version). 
* Apache / Nginx

# How to install?
 * 1.Just clone it to your server:
 ``git clone https://github.com/misaka00251/netease320k-announceboard.git``
 * 2.Run setup.php, select and specify settings of database you prefer. For sqlite usage make sure that database file 'db/todolist.db' is writable for webserver/php.Then click "Install" to create tables in database. It's recommended to delete this file after installation.
 * 3.To protect your tasks from modification by the others you may specify password in settings. By default session files are stored in 'tmp/sessions' directory. Make sure it's writable for webserver/php.
 * 4.Open 'index.php' in your browser to run the application. Then go to settings and specify your time zone.

# Lisence
 This is under the GNU GPL License.
