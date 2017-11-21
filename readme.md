First checkout wrong_master and then do
	
	unalias gitk  # in case you have aliased gitk to 'gitk --all'
	gitk

Read the noteX tags in order : 1, 1.1, 2, 3, 4 

Then do

	gitk --all

and read note5 and note6

And finally do

	git checkout good_ending
	gitk

to see the end result that we want with the whole procedure explained in notes 5
and 6.
