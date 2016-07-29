# PostgreSQL-installation

##For Windows:
1. Go to http://www.enterprisedb.com/products-services-training/pgdownload#windows
    - Pick the download right under the Beta version.
    - Your download should begin shortly

2. When the download is finished, double click on the downloaded file
    - Click Next>
    - Specify which directory you want PostgreSQL to be installed (or just click next)
    - Make a password for your database (**REMEMBER THIS!!!)
    - Select the port number that the server will listen and click next. (you can always change this http://dba.stackexchange.com/questions/41458/changing-postgresql-port-using-command-line)
    - Click next when the default locale comes up (default is United States)
    - When the PostgreSQL setup wizard is complete, uncheck the "Stack Builder" option.
    - Click finish
3. Find the PostgreSQL app and double click it. You can look through all files to find it. I would pin this program to your start menu.
    - When the application appears, double click the "PostgreSQL 9.5 (localhost:[port #])
    - It'll ask for your password (did you remember it?) Only check "Store password" if you are not making a production server.
4. Now we need to make a roles. There are group roles and login roles. For now, we are only going to make Login Roles.
    - Right-click "Login Roles" and select "New Login Role".
    - In the properties tab, make a Role name. The name should be the name of the app
    - In the definition tab, create a simple passwork and type it in again.
    - (If you have a group role, go to the Role membership tab and select the group name. Push the >> button to add the app to the group role.)
    - Click OK.
5. Next we'll create a new database. Do this by selecting the blue arrow in nav bar (the 4th option from the left)
    - Write a database name in the properties tab
    - Select the owner is. If you select a the group role name, every login role that is a member of that group can have access to the database.
    - You can check the SQL code on the SQL tab.
    - Click Ok. This takes a moment.


Congratulations! You now have your first database.


##For Mac OS X:
* Watch https://www.youtube.com/watch?v=1wvDVBjNDys to create a PostgreSQL database using pgAdmin
* Watch https://www.youtube.com/watch?v=xaWlS9HtWYw to create a PostgreSQL database using the command line.

* download PostgreSQL --> http://www.enterprisedb.com/products-services-training/pgdownload#macosx



## Copyright

© DevMountain LLC, 2016. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.
