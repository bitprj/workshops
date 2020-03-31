# Bit Project - Workshops
All of our workshop materials - open for everyone to use!

Our workshops are first written in Markdown, with one .md file corresponding to a slide. Each card must have the type of slide (please consult our Bit brand template) and appropriate labelings of content to be placed on the slide. 

# **Developing Markdown Cards --> PPT That Fits Inside Of Slide Template**

As we are also presenting and teaching our cards in a classroom, we want to make the cards we already had into slides.

Each .md file should correspond to one slide, and the basic format to represent a slide in a markdown file is as shown below.

**Type:** _insert type here_

**Title:** _insert slide title here_

_insert slide content here_

---

_insert any explanations_ (will be in speaker notes)



We are specifying these details to help the design team when they put the information into the actual PPT.

First, you need to specify the type -- what slide template you would like to use. Our design team has made many good BitProject templates, and you can find all of them [here](https://docs.google.com/presentation/d/1F5_Qcf_0IduoNKzRUT4owPlE5t5Ab8utmGHUMwZCM_g/edit#slide=id.p). You can make a copy of it and see the details of all templates by adding empty slides. 



For almost all the templates, they have a block for title. So simply put the title of the slide after "**Title:**". You can use the corresponding title of the card, or be more specific.



Once you chose the template and finished the title, you should write the content of the slide. You need to specifically point out what content should be in which text/image box in the template. For example, there are 2 text boxes in the "small code snipet" template, so you need to specify what are in the upper text box, and what are in the lower text box. 



Since the slides are to help people visualize the ideas better and be like a summary, you should simplify and extract the content from the cards instead of copying it. There should not be long sentences or paragraphs on the slides. 



After that, you can use the cards or your own words to write the notes for the speaker to understand what they need to cover for the slide.



Often, one card contains too much information to be covered in one slide. So you should split them up and make sure the slides are reasonable and understandable.



Here is a full example of what a slide should be like in a markdown file.

**Type:** Small code snipet

**Title:** *Installing React*

upper-right text box

* Node.js
* Terminal

lower-right text box

```bash
$ npm install --save-dev react
$ npm install --save-dev react-dom
```

------

*Speaker notes: 

First, you need to download the latest version of Node.js

Now let's nevigate to the terminal. Every operating system is differen, and here we are demostrating with Apple terminal.

Install react using npm

