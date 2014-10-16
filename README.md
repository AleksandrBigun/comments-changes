Using comments for marking changes in HTML and CSS files
================

To mark the changes in CSS and HTML files is recommended to mark updated line by commentary. For easy text search on the file changes in the future, all comments begin a sequence of characters ```/**/``` in CSS and ```**``` in HTML. There are several kinds of comments. They are presented below in the form of snippets.

### Snippets Sublime Text
For comfortable working type the snippet shortcode ```/``` then press <kbd>Tab</kbd> and choose comments option to complete the snippet.

### Install Snippets
Place recommended snippets files in the folders ```\snippets\comments-changes\``` in ```\Data\Packages\User\``` your Sublime Text.

#### block-changes-marker-changes-css
```
/**//* change start */

/**//* change end */
```

#### block-new-marker-changes-css
```
/**//* new start */

/**//* new end */
```

#### block-delete-marker-changes-css
```
/**/
/*

*/
/**//* delete */
```

#### line-changes-marker-changes-css
```
/**/
```

#### line-new-marker-changes-css
```
/**//* new */
```

#### block-delete-marker-changes-html
```
<!-- ** changes start  -->

<!-- ** changes end  -->
```
