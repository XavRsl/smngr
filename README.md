smngr - Site Manager
=====

Site manager for CentOS / Apache FastCGI / phpFPM

Options:  
*  -h, --help display this help message and exit.  

*  -c, --create **site_name**    create Site  
where 'site_name' is the Site name (eg. www.dsi.uvsq.fr).

*  -u, --user **user_name**    user associated with the site  
where **user_name** is the Name of the user associated with the site.

*  -m, --move **site_name**    move the site (requires user argument : -u)  
where **site_name** is the name of the site to move.

*  -d, --delete **site_name**    delete a site  
where **site_name** is the name of the site to delete.

*  -s, --sync **site_name**    sync a site  
where **site_name** is the name of the site to sync with it\'s current location.

*  -l, --list              list sites installed on this server (without site size)

*  -ll, --listlong           list sites installed on this server (with site size = slow !)

*  -r, --restart           restart apache and php-fpm servers

**NOTE**: You must be the superuser to run this script.
