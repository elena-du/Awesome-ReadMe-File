# All sintax you need for an awesome README.md

In essence, this is a *Markdown* **language**. 

Let's start with a pretty cat to illustrate how to open and close issues in a GitHub. You can use the word 'fixes' inside a particular commit message.

![kitten-4814553_640](https://user-images.githubusercontent.com/39673440/104966825-e15c3f00-59af-11eb-9f34-3b92d4ea0d6d.jpg)

Image by <a href="https://pixabay.com/users/jfranklin101-8627525/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=4814553">Joanna Franklin</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=4814553">Pixabay</a>

Insert picture **Option 1**

![I'm a pricture from the link](https://commonmark.org/help/images/favicon.png)

Insert picture **Option 2** 

![Logo][2]

[2]: https://commonmark.org/help/images/favicon.png "I'm text"

Want to post a link? 

This is how to display plain clicable link: <https://data.gov>

This is how to display give a name to a link: [Depository of US Government Data](https://data.gov)

[My Code](doc/test_hello.Rmd)

This is*

\* to test asterics.

Here I am\
breaking the line\
It's not a poem\
But works just fine

# Level 1 
bla
## Level 2
bla-bla
### Level 3
bla-bla-bla
#### Level 4
bla-bla-bla-bla

The quote

> Luck is what happens when preparation meets opportunity
>
>                                                  Seneca

> The noblest pleasure is the joy of understanding
> 
>                                                  Leonardo da Vinchi


This is a list:
* first item
  * this is semi-item 1
  * this is semi-item 2
* second item
  * this is semi-item 1
  * this is semi-item 2

This is an ordered list:
1. first item
    * this is semi-item 1
    * this is semi-item 2
2. second item
  * this is semi-item 1
  * this is semi-item 2

Yet, another list:
1. Ingredients 
    - spaghetti
    - marinara sauce
    - salt

2. Cooking

     Bring water to boil, add a pinch of salt and spaghetti. Cook until pasta is **tender**.

3. Serve

   Drain the pasta on a plate. Add heated sauce. 

   > No man is lonely eating spaghetti; it requires so much attention.

   Bon appetit!

And this is NOT a list item, just text:
1\.Think of the way you want to use this format. 2\.Let me know as I didn't find a good example yet.  

Want to showcase some **code**?

**Inline**: 
When `x = 3`, that means `x + 2 = 5`

**or**

**Chunk**:

A loop in JavaScript:

```
var i;
for (i=0; i<5; i++) {
  console.log(i);
}
```
And some plain text to comment on it!

And add some a formula? Standard Markdown is not supported: $$\frac{n!}{k!(n-k)!}$$
But you can use this heuristics: adding image with source equals "https://render.githubusercontent.com/render/math?math=MY MARKDOWN MATH EQUATION GOES HERE>, so you get:

<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">

<img src="https://render.githubusercontent.com/render/math?math=e^{i %2B\pi} =x%2B1">
