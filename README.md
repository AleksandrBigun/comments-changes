Using comments for marking changes in HTML and CSS files
================

To mark the changes in CSS and HTML files is recommended to mark updated line by commentary. For easy text search on the file changes in the future, all comments begin a sequence of characters ```/**/``` in CSS and ```**``` in HTML. There are several kinds of comments. They are presented below in the form of snippets.

### Snippets Sublime Text
For comfortable working type the snippet shortcode ```/``` then press <kbd>Tab</kbd> and choose comments option to complete the snippet.

### Install Snippets
Place recommended snippets files in the folders ```\snippets\comments-changes\``` in ```\Data\Packages\User\``` your Sublime Text.

#### marker-changes-block-css
```
/**//* change start */

/**//* change end */
```

#### marker-changes-css
```
/**/
```

#### marker-changes-delete-block-css
```
/**/
/*

*/
/**//* delete */
```

#### marker-changes-new-block-css
```
/**//* new start */

/**//* new end */
```

#### marker-changes-block-css
```
/**//* changes start */

/**//* changes end */
```

#### marker-changes-new-string-css
```
/**//* new */
```

#### marker-changes-delete-block-html
```
<!-- ** changes start  -->

<!-- ** changes end  -->
```
