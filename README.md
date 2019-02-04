# OptionSelector
Options selector with progress bar

A single HTML page (single html file with js+css embedded inside) which has the following functionality.

* page is split to a 'top toolbar' (where 'options' are displayed) and'content' (rest of the page)
* the 4 'option placeholders' for options on top of a page behave as follows:
* 'All' option is a virtual option, is always there and is selected by default
* 'All' option is exclusive to other options but other options are not
   exclusive to themselves and behave like 'toggle options' (if one is selected
   it can be unselected and vice versa)
* always at least one option must be selected (either 'All' or any combination
   of other options - e.g. Opt2 or Opt1+Opt3 or Opt1+Opt2+Opt3 etc)
* selecting any of other options shall automatically deselect 'All' option
* selecting 'All' option shall automatically (if not selected currently)
   deselect all other options
* the progress bar runs just below the 'option placeholders'while all elements are loading 
* values of active options is configurable by page url 'hash'.
  E.g. adding "#red|green|blue" to page url will cause the page to
  have 3 options, "red", "green", "blue" (plus 'All'). <dfn>After adding hash values to URL press enter and reload the page.</dfn>
* the default options setup is as described above and is used whenever no
   'hash' value is added (it is equivalent of having '#Opt1|Opt2|Opt3' hash)
   
   Check it <a href="http://optionselector.surge.sh/" target="_blank">here</a>

