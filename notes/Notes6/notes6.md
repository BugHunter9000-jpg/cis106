
# Notes 6 Chapter 6 
## Include at least 3 examples of each 

## Explain how to use each of these wildcards `*,7,and []`

# Defintions 
* Definition `*` is used to match 0 to any number of characters 
* Definition `?` is used to match 1 character 
* Definition `[]` is used to match 1 character from a set

# Examples 
* Example 1`la ~/Downloads/*.png`
* `ls -1d wildcard_extra_practice/*/`
* `mv wildcard_extra_practice/*.sh wildcard_extra_practice/scripts/`

* Example 2 `ls ~/Downloads/f?ll.sh`
* `ls -1X wildcard_extra_practice/*.????`
* `ls -1X wildcard_extra_practice/i*.????`

* Example 3 `ls ~/Downloads/f[0-9]ll.sh`
* `ls wildcard_extra_practice/[A-Z]*`
* `ls wildcard_extra_practice/*[0-9]*`

## Explain how to use brace expansion `({})`

* Brace expansion is not a wildcard but a feauture of the bash shell that allows you to create strings without needing loops. The strings can be filenames, sequences, or patterns. Brace expansion is handled before file globing and variable expansion.

# Examples

* `touch {index,about,contact}.html`
* `touch {index,about,contact}.html`
* `mkdir -vp website/{assets/{imgs,audio},scripts/{js,python},extras/{docs,helper}}`