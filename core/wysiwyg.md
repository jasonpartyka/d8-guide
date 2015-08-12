Text Editors/WYSIWYG

Text fields have received a major upgrade with Drupal 8, as the WYSIWYG software CKEditor is now built in to core. There are four built-in text formats:

* Basic HTML
	* A very basic set of HTML tags are allowed. These are <a> <em> <strong> <cite> <blockquote> <code> <ul> <ol> <li> <dl> <dt> <dd> <h4> <h5> <h6> <p> <br> <span> <img>. The toolbar provided with this text format is very basic as well - bold, italic, add link, remove link, ordererd and unordered lists, quotes, images, and view source. 
	* This text format is generally very safe and is a good starting point for the default text format for your site.
* Restricted HTML
  * This text format allows for even fewer tags then Basic HTML, but does not come with CKEditor enabled by default. These tags are: <a> <em> <strong> <cite> <blockquote> <code> <ul> <ol> <li> <dl> <dt> <dd> <h4> <h5> <h6>. This is a good starting point for untrusted users.
* Full HTML
	* This text format allows all HTML and is generally something to use with caution. It should not be enabled for anyone except for very trusted users.
* Plain Text
	No HTML at all.
