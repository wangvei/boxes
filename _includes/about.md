# ASCII Box Drawing - the *boxes* filter program


                                 /*********************/ 
    boxes draws any              /* boxes draws any   */
    kind of boxes        ===>    /* kind of boxes     */
    around your text!            /* around your text! */
                                 /*********************/

*Boxes* is a [text filter]({{ site.baseurl }}/docs/filters.html) which can draw ASCII art boxes around its input text. These boxes may also be removed, even if they have been badly damaged by editing of the text  inside. Since boxes may be open on any side, *boxes* can also be used to create regional comments  in  any programming  language. With the help of an editor macro or mapping, damaged boxes can easily be repaired.

This is useful for making the function headers in your programming language look better, for spicing up your news postings and emails, or just for decorating your documentation files.

New box designs of all sorts can easily be added and shared by appending to a free format configuration file. *boxes* was originally intended to be used with the vim(1) text editor, but can be tied to any text editor which supports filters.


## Some Of The Features

  - Drawing of ASCII art boxes around input text
  - Generation of regional comments in any programming language
  - Freely and conveniently user-configurable boxes
  - Alignment and positioning of text inside a box
  - Removal of boxes, even if box is damaged by editing of contained text
  - A number of preconfigured box designs in example config file
  - Many useful command line options (such as box size specification etc.)
  - Regular expression substitutions on input text
    (e.g. used for quoting closing comment tags in a C comment box)


## Author

*Boxes* is developed by Thomas Jensen {{ page.bxemail }}.

Special thanks go to the many [contributors]({{ site.baseurl }}/contributing.html#contributors), who have helped improve *boxes* over the years.

*Boxes* is free software. Go and download your copy from the [download page]({{ site.baseurl }}/download.html)!