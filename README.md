Hello and welcome to my Scratch game 'Mario Wars Hide n Seek'. Click the URL on the repo homepage to play.
I made this game for a computer science course I am taking with Hardvard called CS50x.

<iframe src="https://scratch.mit.edu/projects/392086996/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>

<input id="text" type="text" placeholder=" Enter something...">
// Autocomplete demo
var availableTags = ["ActionScript", "AppleScript", "Asp", "BASIC", "C", "C++", "Clojure",
	"COBOL", "ColdFusion", "Erlang", "Fortran", "Groovy", "Haskell", "Java", "JavaScript",
	"Lisp", "Perl", "PHP", "Python", "Ruby", "Scala", "Scheme" ];

$('#text')
	.keyboard({ layout: 'qwerty' })
	.autocomplete({
		source: availableTags
	})
	// position options added after v1.23.4
	.addAutocomplete({
		position : {
			of : null,        // when null, element will default to kb.$keyboard
			my : 'right top', // 'center top', (position under keyboard)
			at : 'left top',  // 'center bottom',
			collision: 'flip'
		}
	})
	.addTyping();



          Space = Jump
          Left arrow = Move left
          Right arrow = Move right
          
Good luck and have fun! It won't take long :)


