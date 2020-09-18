# Markdown Tutorial

* This is a property of the half blood prince.

Here we'll learn about markdown in Jupyter. Here we will discuss about some specific topic:

## Markdown styling
* " # ": for header element.
<br>Example: "#" : For biggest header
             "##":For second biggest header and so on
<br />

* Example for bold text: **This is a bold text**, okay?
<br />

* Example for italicized text: *This is italized*, na?
<br />

* Example for strikethrough text: ~~Now strikethrough~~
<br />

* Underlined text: <u> Enough, man!!! </u>
<br />

* Example for backlash escape: \# Hi, I'm here.
<br />

* Example of paragraphs:
<br />
<p>Hello World!</p>
<p>We are learning Markdown.</p>
<br />

* Blockquotes:<br />
Blockquotes can hold the large chunk of text and are generally indented.
> The main challenge of many body physics is while we know all relevant laws of nature for describing system, the number of degrees of freedom in such system is typically much too large to allow a direct solution based on these laws.In this context, renormalization and scaling idea come which have led to classification of microscopically very different systems.
 In our project, we're studying on light-matter interaction by Jaynes-Cummings model with similarity renormalization group technique.

<br />

* Nested block quoting: <br />
> The main challenge of many body physics is while we know all relevant laws of nature for describing system, the number of degrees of freedom in such system is typically much too large to allow a direct solution based on these laws.
>>In this context, renormalization and scaling idea come which have led to classification of microscopically very different systems.
>>>In our project, we're studying on light-matter interaction by Jaynes-Cummings model with similarity renormalization group technique.

<br />




## List

See:
1.  it is a numbered list.
2.  it's also.
<br>

Again we can use a bullet list.
* Like this.
* Like this.(2) 
    * This is a sublist.
    * Fun done.
    
<br />

## Hyperlink
Please have a look here: <a href="https://www.youtube.com/watch?v=HW29067qVWk" target="_blank">Jupyter notebook tutorial by Corey Schafer</a>. 
<br />
or you do an autometic link also: https://www.youtube.com/watch?v=HW29067qVWk
<br />
or in this way (Markdown way): [Jupyter notebook tutorial by Corey Schafer](https://www.youtube.com/watch?v=HW29067qVWk)

<br />
 

## Images
We can also create a link for images from web:
<figure>
   <a href="https://img3.goodfon.com/original/1366x768/a/73/bazinga-sheldon-cooper-the.jpg">
   <img src="https://img3.goodfon.com/original/1366x768/a/73/bazinga-sheldon-cooper-the.jpg" alt="You can use Markdown to add images to Jupyter Notebook files."></a>
   <figcaption> You can use Markdown to add images to Jupyter Notebook.
   </figcaption>
</figure>

#### other way:

![][some-id]

[some-id]: https://www.python.org/static/community_logos/python-logo-master-v3-TM.png 

<br />

## Task lists

This is awesome !!!<br />
- [x] Some task.
- [ ] Some more task. 
<br />

With html we can do even better. See:<br />
<input type=”checkbox” > Some task
<br />

<input type=”checkbox” disabled> Some more task

<br />

## Code section

So lovely !! **code script:**
```python
s = "You're in my spot."
print s
```
<br >

Here some inline codes:

`How you doin?`
```
What doesn’t kill you, simply makes you stranger!
```
<br />


## Table 
It is getting more fun. Now we'll make a table. Just think of that:

|Header|Header|Header|
|:----:|:----:|:----:|
|A     |B     |C     |
|X     |Y     |Z     |
<br />

We can allign in other way also:
* right allign: :---- or ----
* left allign:  -----:
* centered allign:  :-----:
<br /> 

## Inline HTML
Now we'll start to make our document more beautiful.

#### Text color
Roses are <span style="color:red">red</span>.

#### Text font
Now play with font size: <font size="5"> This is my text.</font>

#### Text font style
Change font style also: <span style="font-family:Arial Rounded MT Bold">This is a text</span> 

#### Colored box
Hey, one of the most exciting tool: <br />
<div class="alert alert-block alert-info">
<b>Tip:</b> Use blue boxes (alert-info) for tips and notes.</div>

<br />
<div class="alert alert-block alert-warning">
<b>Example:</b> Use yellow boxes for examples that are not inside code cells, or use for mathematical formulas if needed. Typically also used to display warning messages.
</div>
<br />
<div class="alert alert-block alert-danger">
<b>Danger:</b> This alert box indicates a dangerous or potentially negative action.
</div>
<br />
<div class="alert alert-block alert-success">
<b>Success:</b> This alert box indicates a successful or positive action.
</div>

#### Highlighted text
I've so much waited for this: <br />
<code style="background:yellow;color:black">Everything is connected.</code>

#### Mark tag
Sometimes we need to highlight some particular word. So I'm here: <br />

Everybody is a <mark>whore</mark>, Grace.

#### LaTeX Math
We even use LaTeX here. Now you can understand why as an interactive interface, Jupyter is so much popular. There is a small example:<br /> 
$\sqrt{k}$ 

#### Geometric shapes
We can also use geometric shapes. But it's some tough. Here is a link for reference number:[UTF-8 Geometric Shapes](https://www.w3schools.com/charsets/ref_utf_geometric.asp) 
 




