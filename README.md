# ROSE Documentation

This is a mirror of the essential ROSE developer documents from http://rosecompiler.org.  Also see our alternate Downloads mirror: https://bitbucket.org/rosecompiler/rose/downloads.

### User Manual
Download the [rose-docs/user_manual/ROSE-UserManual.pdf](https://github.com/rose-compiler/rose-docs/blob/master/user_manual/ROSE-UserManual.pdf?raw=true).

### Tutorial
Download the [rose-docs/tutorial/ROSE-Tutorial.pdf](https://github.com/rose-compiler/rose-docs/blob/master/tutorial/ROSE-Tutorial.pdf?raw=true).


### Doxygen
To use the Doxygen web reference: you will need to first clone the repository.

```bash
  $ git clone https://github.com/rose-compiler/rose-docs.git
  $ cd rose-docs/doxygen
  
  # Use a browser to open the Doxygen home page
  $ firefox index.html
  
  # -or- Mac OS X
  $ open index.html
```


---
**Synchronization**
```bash
$ rsync -avzW /global/homes/l/liaoch/www.rosecompiler.org/ROSE_Tutorial/  /global/homes/l/liaoch/workspace/web-docs-backup/ROSE_Tutorial/
$ rsync -avzW /global/homes/l/liaoch/www.rosecompiler.org/ROSE_UserManual/  /global/homes/l/liaoch/workspace/web-docs-backup/ROSE_UserManual/
$ rsync -avzW /global/homes/l/liaoch/www.rosecompiler.org/ROSE_HTML_Reference/  /global/homes/l/liaoch/workspace/web-docs-backup/ROSE_HTML_Reference
```
