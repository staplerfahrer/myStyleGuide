# A Case For camelCase\*

1. one less character used, - and _ can make for longer lines 
2. one less keystroke vs _ 
3. no need to hit the relatively hard-to-reach - 
4. keyboards have **two** large shift-keys to help capitalize the next letter
5. unambigouous word boundary
	- no some\**CURSOR*\*\_identifier vs some\_\**CURSOR*\*identifier
6. super compatible with all† environments:
	- it's safe in filesystem paths
	- it's good even without case sensitivity
	- if the only spelling difference is a case difference,  
	  your code is hard to read: *someThing* vs *SomeThing*, is that good?‡
	- safe to use on identifiers in most languages
	- **\-** and **\_** could
		- have special meaning (MarkDown)
		- it may be an identifier or operator

\* Better put, dromedaryCase. Some camels have two humps.

† If not in your environment, maybe none of this applies anyway.

‡ Inconsistent case use is hard to remember, because it's hard to communicate verbally.
