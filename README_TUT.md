# Mastering MarkDown tutorial

# Heading 1 
This is a paragraph. Use hash for heading one hash for heading 1.

## Heading 2
This is another paragraph.
This is in same paragraph.

### Heading 3
This is a 3rd paragraph. Keep one line break to make new paragraph.


This word is formatted as **bold** use double star or double underscore for __bold__.

This word is formatted as *italics* use single star or single underscore for _italics_.

This word is ~~cross through~~ use double Tilda for cross through.


# Links in Markdown
<https://github.com/pawansa3>

[My GitHub Account](https://github.com/pawansa3)

[My Facebook Account](https://facebook.com/sa3.pawan "This the link title for facebook a/c")

If you want to insert link to all place where [Pawan][1] is written then we can insert link like this as [Pawan][1] and this is my [facebook a/c][fb] link.


[1]: https://github.com/pawansa3
[fb]: https://facebook.com/sa3.pawan 


# Markdown Images

"![]()" is used for images as "!" means **Images**, "[]" contain **alternate image text** and "()" contain **Image Url/Src**

## Images Examples

![Wow great Pict!!!](http://unsplash.it/500/500?random)

![Another Pict!!!](http://unsplash.it/500/500?random "this is the title")

![Nice Pict][pic]

### Image link As nested inside link
[![](http://unsplash.it/50/50?image=900)](http://unsplash.it/500/500?image=900)


we can also write html tags or style in MD work fine in github.

[pic]: http://unsplash.it/500/500?image=900


# Lists -- Ordered & Unordered, Bullets & Nesting

## Unordered Lists using "* or + or -" As Ingredients

+ milk
+ eggs
+ bread

## Ordered Lists using "1.(auto increment) or 1. 2. ..." As Steps

1. Mix all Ingredients.
	* Mix until homogeneous mixture.
		* Leave it for 2-3 minutes.
1. Gently Stir Together.
1. Bake at 350 for 20 minutes.


## Line break
Hi, I am pawan.<br>
What's your name?

## Horizontal Rules

this is a horizontal rules using "--- or ===" after a line break.

---

## Block Quotes
> With the Great Power, Comes the Responsibility.
> 
> -From **Spiderman**
> 
> This is a block quotes using ">".


## Code Blocks

Here is my code:

	var x = 100;
	const name = "Pawan";

We can use 3 Tilda "```name_of_language" as

```php
$a = 100;
$name = "pawan";
echo strtoupper($name);
```

```
echo "hello"
```

hey, we can use single Tilda in a paragraph for code as `var x = 100`?

```diff
var x = 200;
- var y = 300;
+ var y = 400;
```


# Tables in Markdown
| Name | Super Hero | Real Name |
|:----:|:----------:|:---------:|
|Bruce Wayne|Batman|Christian Bale|
|Clark Kent|Superman|Henry Cavill|
| Tony Stark|Ironman|Robert Downey Jr.|
|Peter Parker|Spiderman|Andrew Garfield|

In table colon control text- left/right/center as put colon both side of center and in left for left-align & vice-versa. 


# Github treats

Checkbox using "[ ]" as

* [x] Get Milk
* [ ] Crack Eggs
* [ ] Cook Bacon

### Fork to issues in Github using "# (to reference to problem) or @ (to add people)"
I have same problem at #51 but fixed #86 @pawansa3@


