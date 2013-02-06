# ROSE Documentation

This is a mirror of the essential ROSE documents for users and developers from http://rosecompiler.org.

Also see our alternate Downloads mirror: https://bitbucket.org/rosecompiler/rose/downloads.

For manual and tutorial, you can directly download from the github web.

To use Doxygen reference: you should first clone the git repo. 
then

  $cd localGitCheckout/ROSE_HTML_Reference
  $firefox index.html # using a browser to open the index page of web references



# command line to sychronize the files
rsync -avzW /global/homes/l/liaoch/www.rosecompiler.org/ROSE_Tutorial/  /global/homes/l/liaoch/workspace/web-docs-backup/ROSE_Tutorial/
rsync -avzW /global/homes/l/liaoch/www.rosecompiler.org/ROSE_UserManual/  /global/homes/l/liaoch/workspace/web-docs-backup/ROSE_UserManual/
rsync -avzW /global/homes/l/liaoch/www.rosecompiler.org/ROSE_HTML_Reference/  /global/homes/l/liaoch/workspace/web-docs-backup/ROSE_HTML_Reference
