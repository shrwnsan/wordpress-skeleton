# WordPress skeleton
For use as a primer and starting-point for CMS-based projects. The WordPress files are versioned using the official Git repository.

Based on [David Winter's writeup](http://davidwinter.me/articles/2012/04/09/install-and-manage-wordpress-with-git/)

---------------------------------------
## To update the base WordPress install files
Change into the WordPress subrepository:
```cd wp
git fetch --tags
git checkout 3.5.1
```

Replace 3.5.1 with the correct and latest version number.

Now commit the changes subrepository version to your main project:
```cd ..
git commit -m "Update WordPress to version 3.5.1"
```
