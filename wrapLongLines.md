# Wrapping long lines

1. lines are long when they exceed 70 characters (70 + cr/lf = 72*):
	- this allows for narrow windows
	- allows more side-by-side windows
	- easier to debug a program because of that
	- easier to scan your code, no surprises far to the right
	- code snippets are more portable
	- it is hard to stick to this short length but it's worth it
2. indent wrapped lines with two tabs:
	- a single tab probably indicates a code block, some languages  
	  use white-space to indicate a block (e. g. Python)
	- it's more efficient to leave as much code on the first line  
	  unless that's much harder to read

\* 72 is the line length for email text, it's as good as any length.
