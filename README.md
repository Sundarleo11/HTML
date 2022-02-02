```   
              Introduction to HTML 
```
# WHAT IS HTML?
● HTML stands for Hyper Text Markup Language.

● HTML describes the structure of web pages using markup.
● HTML is used to provide the content(words, images, 
audio, video, and so on) to the web
pages.

● HTML is a tag based language. They are defined within the angle brackets.

● HTML file can be created using a text editor.


# COMMENTS IN HTML

The comment tag ``` <!--...--> ``` is used to insert comments in the source code. Comments are not
displayed in the browsers.
You can use comments to explain your code, which can help you when you edit the source
code at a later date. This is especially useful if you have a lot of code

# TAGS

Tags define all elements of the document,
 i.e. they give meaning to the plain text of HTML.

● HTML tags are surrounded by the two characters < and > (They are called angle brackets).

● The tag name can either start from an alphabet or an underscore(_).

● The text between the start and end tags is the element content.

● Tags with an opening and closing can have any number of tags within itself.

● HTML tags are not case sensitive,``` <p> means the same as <P>.```

● HTML tags normally comes in pairs(container tags), i.e. both opening and closing(it is
same, just the name of the tag with character '/ ' in the beginning) tag.

● Eg: ``` <html> and </html> ``` is a tag that comes in pair.

● Eg: ```<br> ```does not have a closing tag.


# Description of tags used till now
● ``` <!DOCTYPE html> ``` tells the browser that the file being displayed is HTML5 page.

● ``` <html> </html>``` meant to contain all the html data and is the start of an HTML document.

●```  <head> </head> ```provides information about the document. It is not displayed in the browser window.

● ``` <title> </title>``` provides a title for the document.

● ``` <body> </body>```  contains all the things visible on the web page.

NOTE: You might come across "self-closing" tags, whereby a br tag, for eg., will look like
``` "<br/>" instead of simply "<br>  ```

# DOCTYPE
The DOCTYPE declaration describes what version of HTML the page is written in. It is the
very first thing in your HTML document that you see in every web page. It is written at the
top of every page before the ```<html> ```tag.
The doctype declaration is not an HTML tag. It is the one recommended by HTML5.
The syntax for doctype is: ```<!DOCTYPE html> ```

# HTML ELEMENTS

Elements are the things that actually make up the web page. Tags just define the beginning
and end of the elements. Everything that a web page includes is an HTML element.

Eg: this is an HTML element: ```<b>This text is bold</b>```

➢ The HTML element starts with a opening tag:``` <b>```

➢ The content of the HTML element is: This text is bold
➢ The HTML element ends with an closing tag: ``` </b> ```

# Paragraphs
Paragraphs are blocks of text separated from each other by some space. 
They are defined using the ``` <p> and </p> ```tags.
 When p element ends, the next element
appears in next line.

# Headings
These are tags in HTML to mark some content as headings. In fact, there are six
different levels of headings h1, h2, h3, h4, h5 and h6. Among them h1 defines the
largest heading and h6 defines the smallest level heading.

# BR Tag
``` <br> ``` tag is used to introduce a single line break between the contents. This means
that when this tag is used in between a single line, the content after this tag will
move to the next line. Do not use it to provide space between block of
elements( eg., paragraph and heading).

# LISTS
Lists are used to group together related pieces of information so they are clearly associated
with each other and easy to read. Lists are good from a structural point of view as they help
create a well-structured, more accessible, easy to maintain document.
HTML supports ordered, unordered and definition lists.

# Unordered Lists
It is used to group a set of related items in no particular order. Unordered lists are
used when the numbering of items is not required. By default the items are
followed by bullets.
They are defined using the ``` <ul> ``` tag.

HTML provides an interesting feature to change the style of the list item marker.

There are 4 types of style in unordered lists

● type="disc" - sets the list item marker to a bullet (default)

○ type="circle" - sets the list item marker to a circle

■ type="square" - sets the list item marker to a square

type="none" - the lists items will not be marked
NOTE: The above styles can be produced by using the 'type' attribute. However, this
attribute is now not supported in HTML5 and you now need to change the
style using CSS(we will learn later about it).

# Ordered Lists
It is used to group a set of related items in a specific order. Ordered lists are used
when the numbering of items is required. By default the items are followed by
numerical numbering.
They are defined using the ``` <ul> ``` tag

Similarly, like the unordered lists, there are also different types of ways to number
the ordered lists using the 'type' attribute:
1. type="1" - The list items will be numbered with numbers (default)

A. type="A" - The list items will be numbered with uppercase letters

a. type="a" - The list items will be numbered with lowercase letters

I. type="I" - The list items will be numbered with uppercase roman numbers

i. type="i" - The list items will be numbered with lowercase roman numbers

Now, what if you want to change the starting numbering of the lists?
HTML has got the solution for it: the 'start' attribute.
``` So, if we change <ol> to <ol start="7" >, you will now see the output  ```

# Description Lists
A definition list is not a list of items. This is a list of terms and explanation of the
terms.
A definition list starts with the ``` <dl> ``` tag. Each definition - list term starts with the
``` <dt> ``` tag. Each definition - list definition starts with the ```<dd> ```tag.
Description lists are very specific in use as compared to ordered and unordered lists
and hence are very less used. But whenever, a structure like a list of terms and their
description is required, the description lists are the the perfect elements.

# IMAGES IN HTML
With HTML you can also display images in a document. In HTML, images are defined with the
``` <img> ``` tag.
To display an image on a page, you need to use the src attribute. Src stands for "source". The
value of the src attribute is the URL of image you want to display on your page.
The syntax of defining an image:
```
<img src="images/logo.png"> 
```

Some points you need to know

● ``` <img> ``` tag is a self closing tag which means that it doesn't contain the closing tag.

● The src tag can contain both relative and absolute paths, as well as internet image links

# The ALT Attribute
The alt attribute or alternate text tells the reader what he or she is missing on a
page if the browser can't load images. The browser will then display the alternate
text instead of the image.
Now, we can use the alt attribute as:
``` 
<img src="images/logo.png" alt="logo image">
```
NOTE: It is a good practice to include the "alt" attribute for each image on a page.

# ANCHOR TAG

The ```<a> ``` tag defines a hyperlink, which is used to link from one page to another.
You have seen that clicking on a link opens a new page may be on the same page or another.
These web pages are connected using links. They give us the ability to go to a different web
page without each time entering its URL. This kind of links are external links

 i.e. they help in
connecting to external web pages.
Links can also be internal which means that they will be linking the content within the same
page.

Eg: link to the top of the page or any link to any specific content on the page.

By default, links will appear as follows in all browsers

● An unvisited link is underlined and blue

● A visited link is underlined and purple

● An active link is underlined and red

# href Attribute
The most important attribute of the```  <a> ``` element is the href attribute, which
indicates the link's destination. In other words, the href attribute is used to address
the document to link to.

An anchor can point to any resource on the Web: an HTML page, an image, a sound
file, a movie, etc. These all are known as external links.

NOTE: You need to remember that here also, we can provide relative url of a file as
a value to href attribute. Eg: href="/home/myPC/Documents/test.html

# Relative and Absolute Linking

Relative linking is used to specify local links, i.e. link to files inside the root folder.

Absolute linking is used to specify outside links, i.e. URL of the web pages.

Relative links works relative to the page. So, when a user clicks a relative link, the
browser looks for the location of the file relative to the current page.

Four situation arises in this case:-

● File is present in the same folder - In this case, the name of the file is provided.
Eg: ``` <a href="relativeFile.html">Click Me</a> ``` will look for the file inside
the same folder.

● File is present in the subfolder - In this case, the name of the file provided is
preceded with the folder names according to hierarchy.
 Eg: ``` <a
href="subfolder/down/relativeFile.html">Click Me</a> ```, will move to the
'subfolder' folder, then to 'down' folder and look for the file inside it.


● File is present somewhere in the parent folder - In this case, to move one
folder above use '../'. Eg:``` <a href="../relativeFile.html">Click Me</a> ```, will
move to the parent folder and look for the file inside it.

● File is present in another subfolder of parent folder - This case covers above
two cases. Eg: ``` <a href="../subfolder/relativeFile.html">Click Me</a> ```  will
move to the parent folder, then to folder named 'subfolder' and look for the
file inside it.
Absolute links provides complete web address of the web page where you want to
go. Eg: ``` <a href="https://www.codingninjas.in/">Click Me</a> ```, will make the
browser directly go to the specified URL

# target Attribute
With the target attribute, you can define where the linked document will be

opened. The target attribute has the following values:
● _self: load the URL into the current tab itself. This is the default.

● _blank: load the URL into a new tab or browser window.

● _parent: load the URL into the parent browsing context. If there is no parent,
this behaves same as _self.

● _top: load the URL into the top-level browsing context. If there is no parent,
this behaves same as _self.

The line below will open the document in a new browser window:

 ``` <a href="http://www.google.in/students/assignments" target="_blank">google</a> ```


NOTE: By default, linked page will be displayed in the current browser window.

``` 
                      More on HTML 
```

 # DIV TAG
The ``` <div>  ```tag defines a block-level section or a division in an HTML document.
The ``` <div>  ```tag is a block element. It is often used as a container for other HTML elements.
The``` <div>  ``` element has no required attributes.
The``` <div>  ```element is very often used together with CSS, to layout a web page. By default,
browsers always place a line break before and after the``` <div>  ``` element.

# SEMANTIC ELEMENTS
Semantic HTML or semantic markup is HTML that introduces meaning to the web page
rather than just presentation. For eg., a ``` <p> ``` tag indicates that the enclosed text is a
paragraph.
Semantic HTML tags provide information about the contents of those tags that goes beyond
just how they look on a page. For eg., text that is enclosed in the ```<code> ``` tag is immediately
recognized by the browser as some type of coding language.
Examples of non-semantic elements:``` <div>``` and ```<span> ``` - tells nothing about its content.
Examples of semantic elements:``` <h1> to <h6>, <p>, and <ul> ``` - clearly defines its content.
Now, here is an example of how some of the common semantic tags are used to construct a
page:









# INTERNAL LINKS
Instead of having to resort to the task of scrolling down long pages, you can make your
readers very happy by offering them page jumps as an alternative mode of transport around
your site. Basically, page jumps are just links (they use the same ```<a> ``` element as all links), but
links that point to a certain part of the same document, i.e. internal links.
You simply add a unique id value to an existing element. Now, you will know about id
attribute afterwards in CSS, so don't stress too much on it for now.
For eg., here's how you set up a link:
``` <h2 id="heading">This is the top</h2> ```

``` <a href="#heading">Go to top</a> ```

Explanation: In the href attribute, heading is the id of the heading of this page. id of an html element is an attribute and it can have any value. While referring to an id, '#' is
used in the beginning of its name. Clicking on the link shown below will scroll
you to the heading such that it is the first line of the display.

# BLOCK VS INLINE ELEMENTS
Block elements are those that take up the full width available on a web page, effectively
blocking out any other elements from sitting next to it on the left or right.
Inline elements are those who only take up as much width as much needed to display the
contents of the element, thereby allowing other elements to be in line with the inline
element.
Block elements always start on a new line.
Inline elements does not start from a new line.
Examples of block elements are ```  <div>, <p>, <h1> to <h6>, <nav>, ``` etc.
Examples of inline elements are ``` <b>, <i>, <span>, <img> ```, etc.
NOTE: You can also check which elements are block and which are inline by inspecting them
using chrome dev tools

# TEXT FORMATTING TAGS
HTML provides us with the ability for formatting text just like we do it in MS Word or any
text editing software.
The following HTML tags are used to format the appearance of the text on your web page.
This can jazz up the look of the web page, however, too much variety in the text formatting
can also look displeasing.HTML also defines special elements for defining text with a special
meaning.
HTML uses elements like ``` <b> and <i> ``` for formatting output, like bold or italic text.
Formatting elements were designed to display special types of text:
 
 ```
● <b>  - defines bold text
● <em> - defines emphasized text
● <i> - defines italic text
● <small> - defines smaller text
● <strong> - defines important text
● <sub> - defines subscripted text
● <sup> - defines superscripted text
● <u> - defines underlined text
● <ins> - defines inserted text by underlying the text
● <del> - defines deleted text by striking through the text
● <s> - defines text that is no longer correct, accurate or relevant by striking through
it
● <mark> - defines marked/highlighted text
● <pre> - defines preformatted text which is presented exactly as written in HTML
● <tt> - defines text appears as typed by a typewriter
● <code> - defines piece of computer code
● <q> - defines short quoted text
● <cite> - defines reference to a cited work
● <abbr> - defines an abbreviation or acronym
● <var> - defines a variable name
● <kbd> - defines keyboard input
● <samp> - defines sample output from a computer program

```
# SPECIAL CHARACTERS
In HTML, we have some characters that are reserved, e.g. less than (<) and greater than (>)
signs, known as angle brackets , that are used to define a tag. Using them as symbols for the
page, the browser could mistake them for markup.
While there are some characters that are not present on the keyboard.
These characters are called special characters or HTML entity, that either cannot be used or
not available on the keyboard. So, to display these special characters, they must be replaced
with the character entities.
An HTML entity is a piece of text that begins with an ampersand (&) and ends with a
semicolon(;) and between is the hex code or entity name. These entities are used to display
the reserved characters.
Eg., these are some html entities with how they will look on browser:
```
● some useful character entities - &nbsp;(single space), &lt;(<), &apos;('), &copy;(©)

● diacritical marks - a&#768;(􀄃), O&#770;(􀁎)

● mathematical symbols - &#8704; or &forall; for(∀), &#8721; or &sum; for(Σ)

● some other entities - &larr;(←), &hearts;(♥), &trade;(™)

```
# TABLES
Tables are used to show the tabular data. To achieve this many tags are used. All the tabledata
is enclosed within the ```<table>``` tags.
A table is divided into rows (with the ```<tr>``` tag), and each row is divided into data cells (with
the ```<td>```  tag). tr stands for table row, which represents the row of a table and td stands for
table-data, which is the content of a data cell.
A data cell can contain text, images, lists, paragraphs, forms, horizontal rules, tables

# border Attribute
The border attribute is used for mentioning the thickness of the borders. If you do
not specify a border attribute the table will be displayed without any borders.
Sometimes this can be useful, but most of the time, you want the borders to show.

# Headings in a Table
If you want to add column names, then HTML provides a separate tag for that.
Headings in a table are defined with the <th> tag.

``` <thead> <tbody>, <tfoot> ```

The ``` <thead> ``` tag is used to group header content in an HTML table.
The ```<tbody> ``` tag is used to group the body content in an HTML table.
The ```<tfoot>``` tag is used to group footer content in an HTML table.
These are the semantic tags that not only provide meaning to the elements but also
have some other useful functionality as well.
Browsers can use these elements to enable scrolling of the table body
independently of the header and footer. Also, when printing a large table that spans multiple pages, these elements can enable the table header and footer to be
printed at the top and bottom of each page.

# caption Tag
The ```<caption>``` tag defines a table caption.
The ```<caption>``` tag must be inserted immediately after the ```<table>``` tag.
Eg: If you add ```<caption>Table Example</caption>``` just after the``` <table>``` tag,

# colspan and rowspan Attribute
To manage the layout of the the tables, two attributes are used, rowspan and
colspan.
Attribute rowspan is used to mention the number of rows that a particular cell will
be occupying. Attribute colspan is used to mention the number of columns that a
particular cell will be occupying.
They both are used with the td tag and can also be used with the th tag.
``` 
<th colspan="2">Column 2 and 3 heading</th>
```

```  
             HTML Forms and Media Tags

```

# FORMS
HTML Forms are used to collect different kinds of user input. Through these forms, a user
enters the data which is either processed by the browser itself (using Javascript) or the data
goes to the servers where it gets processed.
A form is an area that can contain form elements. A form is defined with the ```<form>``` tag.
Form elements are elements that allow the user to enter information (like text fields,
textarea fields, drop- down menus, radio buttons, checkboxes, etc.) in a form.
An HTML form may contain a lot of elements like text fields (single line or multiline), select
boxes, buttons, checkboxes, or radio buttons. Let us start with just a basic form without any
elements

# input Tag
The ```<input>``` tag specifies an input field where the user can enter data.
```<input>``` elements are used within a ```<form>``` element to declare input controls that
allow users to input data.
This is an inline tag

# type Attribute
HTML provides different types of input that you can use for different types
of entries. By default the value of type is "text", which specifies that we
want single line text input.
Some more values for type attribute type="submit" represents a button that when selected will submit the
form. You can control the text that appears on the submit button with the
value attribute. Eg: ```<input type="submit" value="Submit">```

# value Attribute
Value is not a compulsory attribute to add to input element, but it is very
useful. The value attribute is used differently for different input types:

● For "button", "reset", and "submit" - it defines the text on the button

● For "text", "password", and "hidden" - it defines the initial (default)
value of the input field

● For "checkbox", "radio", "image" - it defines the value associated
with the input (this is also the value that is sent on submit)

Eg. to display country as default initial value in an input field, the code will
be like this:
```<input type="text" value="India" />```

# name Attribute
The name attribute is a compulsory attribute for input tag in a form.
Without this attribute, this form element won't be submitted or in other
words would not be send to the server.
The name attribute also uniquely identifies that piece of data. The value of
the input is accessed using the name attribute.

# label Tag
Use of labels to describe the kind of input in a form is not compulsory. You can do
that without the use of label tag, as also shown in above example.
But it is best to use ``` <label>``` tag to describe the kind of input for form element. It not
only is semantically correct but it can also be tied to their form elements like
```<input>, <textarea>``` etc

This is also an inline tag.
Like what we have done in the above example is:
```<label for="fname">First name:</label><br/>```
```<input type="text" id="fname" name="firstname" /> ```
The label is tied to this input element by giving "id" attribute of input element the
same value as the label's "for" attribute.

NOTE: It is possible for the value of id and name to be same and most of the time
this will be the case

# required Attribute
When present, it specifies that an input field must be filled out before submitting
the form. Else, it shows a pop up to fill out the required field.
The required attribute is a boolean attribute.
Eg. applying required attribute to an input field like
```
<form> <input type="text" required>
<input type="submit" value="Submit" />
</form>
```

# placeholder Attribute
The placeholder attribute is used with input element. It describes a sample value or
a short description of the expected format.
The value of the placeholder attribute specifies a short hint that describes the
expected value of an input field.
Eg. adding placeholder to the input
```
 <input type="text" name="fname" placeholder="First name"><br>
<input type="text" name="lname" placeholder="Last name"> 
```

# disabled Attribute
The disabled attribute specifies that the ```<input> ```element should be disabled. If the
input is disabled, it becomes un-editable and un-clickable, although it might already
contain a default value in it.
This is also a boolean attribute.
Eg. adding disabled attribute to an input element
```<input type="text" name="country" value="India" disabled><br>```

NOTE: Disabled ```<input> ```elements in a form will not be submitted


# Checkboxes
checkbox is a value of type attribute of input element. Check boxes are used when
more than one option may need to be checked or you can also use it to enable or
disable something.
The checkbox is shown as a square box that is ticked (checked) when activated.
There is also a attribute named checked, that when present makes the checkbox
selected by default when page loads.

Eg:
```<form>
<input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
<input type="checkbox" name="vehicle2" value="Car"> I have a car<br>
<input type="checkbox" name="vehicle3" value="Boat" checked> I have a
boat
</form>
```

# Radio Button
Radio button is just like a checkbox, but the difference is that the values of name
attribute are all the same. To define a radio button the value of type attribute is
"radio".
The name attributes are all set to the same value makes these radio buttons part of
the same set, and therefore, you can only select one of them at once.

```
<form action="/action_page.php">
<input type="radio" name="gender" value="male" checked> Male<br>
<input type="radio" name="gender" value="female"> Female<br>
<input type="radio" name="gender" value="other"> Other
</form>
```

# fieldset and legend Elements
The ```<fieldset>``` element is used to provide grouping for a part of an HTML form. The
```<fieldset>``` tag draws a box around the related elements, which makes it more
presentable.
The ```<legend>``` element is used for providing a title or explanatory caption for the
rest of the contents of the legend element's parent element. ```<legend>``` comes just
after the ```<fieldset>``` tag.
Eg, if a fieldset and legend is used
```
<form>
<fieldset>
<legend>SUBSCRIBE:</legend>
Name: <input type="text"><br>
Email: <input type="text"><br>
</fieldset>
</form>
```

# select Element
HTML ```<select>``` tag is used to create drop down list of options. Drop down list
contains many options and the user can choose one of them.
The select tag also contains name attribute, like other form elements, that
represent the associated data submitted to the server.
There are some of the unique attributes of select element

● multiple, which specifies that multiple options can be selected.

● size, which specifies how many options can be shown at once.

``` 
Eg:
<select name="select">
<option value="value1">Value 1</option>
<option value="value2" selected>Value 2</option>
<option value="value3">Value 3</option>
</select>

```

# option Element
The tag used to define the possible options is ```<option>``` tag. This tag is put
inside the ```<select>``` tag. For every option in drop down list, separate
```<option>``` element is used.
The first ```<option>``` element from the options' list is selected by default. To
change this predefined option, use selected attribute with the ```<option>``` tag.
Each option element should have a value attribute, which contains the
data value that will be submitted to the server when that option is selected

# optgroup Element
The ```<optgroup>``` tag is used to group several options together into one
group.
This will create separate groups of options inside the dropdown.
Eg:
```<select>
<optgroup label="Books">
<option value="html">HTML</option>
<option value="css">CSS</option>
</optgroup>
<optgroup label="Snippets">
<option value="git">Git</option>
<option value="java">Java</option>
</optgroup>
</select>

```
# textarea Element
The ```<textarea>``` element is a input element where the user can input multi-line text,
unlike ```<input>``` element where there is only a single line.
A text area can hold unlimited number of characters, and text wrapping is allowed
when the form is submitted.
Eg:
```
<label>Write about yourself:</label>
<textarea rows="10" cols="50"></textarea> 

 ```
 # rows and cols Attribute

These 2 attributes are used to set the size of ```<textarea>```.
The rows attribute specifies the visible height of a text area.
The cols attribute specifies the visible width of a text area.

NOTE: The size of text area can also be specified by CSS height and width
property

# Submit Button
Submit button is a button that when clicked automatically submits the form. The
button is defined at the end of the form. There are 2 different ways to add submit
button to the form:

● via ```<input>``` tag

● via ``` <button>``` tag
Both these ways will work in the same way.

# Audio and Video Element
HTML can embed audios and videos directly in a web page without any external
support. You can add audios and videos in a standard way.
The ```<audio>``` element is used to add audio in web page.
The ```<video>``` element is used to add video in web page.
These elements are not sufficient to add the media. We need to control the media
as well. So, there are several tags and attributes that are required to fully add the
media.
The ```<audio> and <video>``` are same in the way the content is added to it and only
tag name is different.

Eg., to add audio to the web page, we use the following code:

```<audio controls>
<source src="cn.avi" type="audio/avi">
<source src="cn.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio> 
```

Here, multiple source tags are used so that the audio plays if any one of the format
is supported by the browser. Else, the text message will be shown.

# controls Attribute
The controls attribute is necessary to add controls like play, pause, and
volume to the audio/video. This gives you the ability to control the video
and audio content

# source Tag
```<source> ```element is used to serve the same media content in multiple
formats so that different browsers can run any of the file that it supports. It
is an empty element.


# src Attribute
The src attribute is used to specify the URL of the media file that is needed
to be played. This can have absolute or relative path.
##  type Attribute

The type attribute is used to specify the media type of the media resource.
The way we define a type for video is like: video/mp4, etc. and for audio
like: audio/mpeg

# figure Element
The ```<figure> ```is a new tag introduces in HTML5. This element specifies selfcontained
content, like illustrations, diagrams, photos, code listings, etc.

Eg.
``` <figure>
<img src="images/logo.png" alt="The Pulpit Rock" width="304"
height="228">
<figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>
```
## figcaption Element
The ```<figcaption> ``` tag defines a caption for a ```<figure>``` element. This can be
placed anywhere inside the figure element.

# FAVICON
A favicon is a small, iconic image that represents the website. They are most often found in
the address bar of your web browser, but they can also be used in lists of bookmarks in web
browsers and feed aggregators.
You can see an icon beside the title of the page on the tab itself. This is known as favicon

You can add favicon with the following syntax:

```<link rel="icon" href="/favicon.ico" type="image/x-icon" /> ```

The rel defines the relationship with the favicon.

The href defines the location of the favicon.

# META TAGS
Metadata defines information about data. Therefore, under the meta tag, information about
the web page is stored.

Metadata will not be displayed on the page, but will be machine parsable. The meta tag is a
self-closing tag and the data stored in it is known as metadata.

Meta elements are typically used to specify page description, keywords, author of the
document, last modified, and other metadata.

There are 4 attributes that are used in meta tag:

● name

● content

● charset

● http-equiv


Meta tags have been one of the most basic elements of SEO. They are used to provide
details about your site to search engines. Search engine optimization (SEO) is defined as the
process of affecting the online visibility of a website or a web page in a web search engine's
results.
Search engines such as Google often display the meta description in search results where
they can highly affect user visits to website. So, it’s very important to add meta tags to your
web pages.
NOTE: There can be any number of meta tags defined within a page inside head.

# name Attribute
The name attribute is used to specify the name for the metadata. 
The name
attribute is used together with content attribute. This attribute specifies a name for
the information/value of the content attribute.

The name attribute can have one of the 6 values:

● author - specifies the name of the author of the document

● keywords - specifies a comma-separated list of words for SEO purposes

● viewport - specifies the control of the viewport on different devices

● application-name - specifies name of the application that the page represents

● description - specifies a description of the page

● generator - specifies the software packages used to generate the document

The syntax is: ```<meta name="value"> ```

### NOTE: 
If the http-equiv attribute is set, the name attribute should not be set. SEO is
used by the search engines like google and bing to search for the website's
content relevant to the user search. This increases the quality and quantity of
traffic on one's website

## content Attribute
The content attribute gives the value associated with the http-equiv or name
attribute.
The syntax is:
``` <meta http-equiv/content="value" content="text">```

## charset Attribute

The charset attribute is used for declaring the character encoding for the page. It is
a good practice to use UTF-8 encoding. However, this must be taken care of that
the declared character set matches the one on the page and is defined for every
page of the website.
The syntax is:
``` <meta charset="character_set">```

# http-equiv Attribute
The http-equiv attribute provides an HTTP header for the information/value of the
content attribute. The value of this attribute can be used to alter servers and useragents
behavior.

The syntax is:

```<meta http-equiv="content-type|default-style|refresh">```
Eg., the "refresh" value is used to specify the seconds after which the page is going