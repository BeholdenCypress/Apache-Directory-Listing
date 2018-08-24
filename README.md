# Apache-Directory-Listing
'Apache Directory Listing' is a theme inspired from [Apaxy](https://github.com/AdamWhitcroft/Apaxy) which uses Apache's `mod_autoindex` module.  

# Usage
* Download or clone the repo and copy all the files of `directory-listing` folder to any folder in the server(root directory is highly preferred).
* Copy the `.htaccess` file to the root directory of your server.
* Open the `.htaccess` file and
  * Replace `{SOME_FOLDER}` to the location of `directory-listing` folder on your server.
  * Finally replace `{VIEW}` to either `grid` or `table`.

# Themes
The theme is included with two css files for grid(`grid.css`) and normal(`table.css`) for table styled indexing.

Just change the `{VIEW}` in `.htaccess` to either `grid` or `table`.

You can add your custom code in the `header.html` and `footer.html`.

# Hiding Files
When using this theme, you will notice that `grid.css`, `table.css`, and `header.css` are visible in the listing.

If you would like these to disappear, then just add the following to the `.htaccess` file

``` 
IndexIgnore /{SOME_FOLDER}/footer.html
IndexIgnore /{SOME_FOLDER}/grid.css
IndexIgnore /{SOME_FOLDER}/table.css
```
 
Once this is added, it will hide footer, grid, and table from view in the directory listing
  


### Grid style:  
![grid](https://cloud.githubusercontent.com/assets/12368291/19376773/8444eaa6-91fe-11e6-9a1e-d233553191a6.png)  

### Table style:  
![table](https://cloud.githubusercontent.com/assets/12368291/19376783/951cc542-91fe-11e6-91d1-4a41b7880f7f.png)  

## Credits
Icons referenced from [File Types Icons Set](http://uifest.com/product/file-types-icons-set).
