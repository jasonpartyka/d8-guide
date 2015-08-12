File and image fields are part of core. These fields are flexible from the point of view that content-editors are able to upload arbitrary files and images. However, it is important to note that the primary purpose of these fields is to upload file(s) and then make them available. This is the capability "out of the box".

Files and images may be stored in either public or private locations on the web server. Public locations are enabled by default, and private locations are enabled by editing your site's settings.php file (look for the $settings['file_private_path'] entry). Private locations add overhead to a page load because Drupal must make sure that the user requesting the file has the privilege to access the file.

Generally speaking, file fields are useful for providing files like text files, PDFs, spreadsheets, word processor documents, tar/gz/zip files. 

The widget for a file field allows you to configure:
*  Enable Display field
   * Select this to have a link to your file render when the entity is viewed. If disabled, the file will still be attached to the entity, just not viewable.
   * Files displayed by default
     * This checkbox will appear if you have selected "Enable Display field".

The widget for an image field allows you to configure:
* Label: The field's title as presented to the end-user
* Help Text: A descriptive paragraph on what is expected in this fields. Be as descriptive as possible for your end-user to help insure correct content.
  * Default Image: Provides a default if none is provided. Highly recommended if this field is required.
* Allowed file extensions: Prefilled with typical image file formats. If in doubt, leave this alone.
* File directory: A location in your public or private directory (as configured earlier). Please do not ignore this field outright, especially if you are going to have many file or image fields.
* Maximum image resolution/Minimum image resolution/Maximum upload size
  * Highly recommended that these fields reflect your designs and mockups. If you have not settled on a design yet, please be sure to make a task to come back to it.
 
Like all fields, you can configure as many istances as you need.
