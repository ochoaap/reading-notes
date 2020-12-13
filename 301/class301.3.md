# Class 3 of 301

## Templates
Templating is a fast & efficient way to render client-side veiw templates. It is created by javascript that uses a jSON data source

### Mustache 
WHat is Mustache?
1. Is a logic less template syntax
1. It can be used for HTML
  * config Files
  * source code
  * anything

It's referred to as *logic-less* because there are no if statements, else, or for loops. There are lonly **tags**

#### Example Given 
```
Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn
```
* Mustache is not a templating system
* it is a sepcification *for* a templating engine


## Flexbox

```
display: flex;

```
#### Flex Direction 
1. Row
  * left to right (ltr) right to left (rtl)
1. Row-reverse
  * left to right (ltr) right to left (rtl)
1. column
  * top to bottom
1. column-reverse
  * bottom to top


#### Flex Wrap
* No wrap - all items will be on one line
* Wrap - items will wrap onto multiple lines - top to bottom
* Wrap - Reverse Items will wrap multiple lines bottom to top

#### Flex Flow
Short hand for Flex-Direction and Flex-wrap properties 
Together flex-direction/flex-wrap define the flex container's main and cross axes 
*Default value of row is nowrap*

### Justify content
Defines the alignment along the main axis and distrubutes extra free-space 