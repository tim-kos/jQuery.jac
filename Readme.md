# jQuery Auto Completer Plugin (Jac)

A Jquery plugin that will allow you to tab-complete a set of strings found in your markup

## Usage / Docs

Auto complete a comment textarea with names scraped from the markup of the page (all strong elements with class author-name). If somebody starts to type in the name of any of the values captured by $('strong.author-name') and then hits tab, the name will be auto-completed.

    $('#comment-box').jac({items: 'strong.author-name'});

Auto complete a comment textarea with a pre-defined array of tab values:

    $('#comment-box').jac({items: ['lorem', 'ipsum', 'declorum', 'est']});

## Missing Features

 * Support for tabbing through multiple possible matches instead of only making the first one available
 * Show a visual clue on the available matches - otherwise users might not even notice this plugin being used

## Known Bugs

None