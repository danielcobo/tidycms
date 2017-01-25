# tidycms

## Drafting idea

1. Read raw data
2. Parse raw data
3. Model data into one large object
4. Provide access to current item as reference in large object 
5. Provide access to whole daat object via db namespace

itemPath --> replace('/' with '') within object
list of items within a single folder

data - for each extension there is a parser, else copy (via buffer? or set encoding?)

Note:
for 4. and 5. folders and files must not have same name
and files with different ext must not have same name

What about nested includes of templates?
Template engine processing is separate from parsing (parsing is done before)?

Each these is installed as a packing (npm module)
(How to list themes? How to select theme?)
theme 	/ templates
		/ files
		/ settings
		/ template engine 
		/ parsers
