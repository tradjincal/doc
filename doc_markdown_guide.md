# Markdown Guide


**Index**  

- [Header levels](#HeaderLevels)
- [Emphasis](#Emphasis)
- [Create links](#CreateLinks)
  + [Create anchor](#CreateAnchor)
-[Images](#Images)
-[Quotes](#Quotes)
-[Lists](#List)
  + [Ordered lists](#OrderedLists)
  + [Unordered lists](#UnorderedLists)
-[Tables](#Tables)
-[Blockquotes](#Blockquotes)

Markdown is a lightweight markup language created in 2004, many implementation exist which may add additional features.
Purpose of this guide is to be or try to be exaustif with possibilities of this language for the Yunohost framework and not for general use.

Markdown is a lightweight and easy-to-use syntax for styling all forms of writing.
You only need a text editor to start *coding* Markdown but many software exists (Markdown on [framalibre.org](https://framalibre.org/recherche-par-crit-res?keys=markdown)).

## Header levels <a name="HeaderLevels"></a>

Writing headers as following:
```markdown
# This is an header level 1
## This is an header level 2
### This is an header level 3
#### This is an header level 4
##### This is an header level 5
###### This is an header level 6
```

it should appear as:
# This is an header level 1
## This is an header level 2
### This is an header level 3
#### This is an header level 4
##### This is an header level 5
###### This is an header level 6

## Emphasis <a name="Emphasis"></a>

To create a line break, end a line with **two or more spaces**, and then type return.

Here is an example to bold, italicize, strickthrough some text

```markdown
Italicized text is the *cat's meow*. 
I just love **bold text**.
To strickthrough word wrapped ~~text~~ with two tildes.
```

We get:
Italicized text is the *cat's meow*. 
I just love **bold text**.
To strickthrough word wrapped ~~text~~ with two tildes.

## Create links <a name="CreateLinks"></a>

To create a link to any webpage:
```markdown
[text to display](https://domain.tld)
```
[text to display](https://domain.tld)


It is the same for documentation pages, but link is internal. It return other wiki pages (without file extension, `.md`)
```markdown
[Wiki page](write_documentation)
```
[Wiki page](write_documentation)



