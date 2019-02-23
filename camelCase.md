# A Case For camelCase
Or, better put, dromedaryCase. Because some camels have two humps. 

1. one less character used, - and _ can make for longer lines 
2. one less keystroke vs _ 
3. no need to hit the relatively hard-to-reach - 
4. keyboards have **two** large shift-keys to help capitalize the next letter
5. unambigouous word boundary, no word*CURSOR*\_word vs word\_*CURSOR*word 
6. plays nice in all environments:
	- it's safe in filesystem paths
	- always\* safe as an identifier in programming languages
	- \- and \_ may have special meaning for markup, or it may be an operator

\* And if it doesn't work in your programming environment, maybe none of this applies anyway.