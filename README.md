WP Extract
==========

The easy way to deploy WordPress on your server

Just follow three easy steps:

 - Download wordpress ZIP package from [WordPress.org](http://wordpress.org/download/)
 - Upload the WordPress ZIP package and wp-extract.php to your server
 - Go to http://your-server-address/folder/wp-extract.php and follow the instructions

The script tries to locate the ZIP package automatically but you may enter it manually, and will extract the entire ZIP contents to the folder where you uploaded the files.

There's a minor drawback: the ZIP package contains the WordPress instance in a 'wordpress'folder so you will have to move the files out of it.

You may want to modify the WordPress package to suit your needs (get rid of the 'wordpress'folder, delete themes, etc.)

Also, you must have the ZipArchive extension enabled for this to work; if you don't have it enabled and can't enable it you may use the PclZip library from [PhpConcept.net](http://www.phpconcept.net/pclzip)

THIS SOFTWARE IS DISTRIBUTED "AS IS". NO WARRANTY OF ANY KIND IS EXPRESSED OR IMPLIED. YOU USE AT YOUR OWN RISK. THE AUTHORS WILL NOT BE LIABLE FOR DATA LOSS, DAMAGES, LOSS OF PROFITS OR ANY OTHER KIND OF LOSS WHILE USING OR MISUSING THIS SOFTWARE.