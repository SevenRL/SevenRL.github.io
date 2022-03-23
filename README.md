# Hosting A Resume on Github

## Purpose
The purpose of this readme file is to describe how to host and format a resume using various software stacks. This will also include steps that introduce, demonstrate, and relate the principles of Andrew Etter's book Modern Technical Writing

## Prerequisites
Two things will be required before we move on to elaborate on how to host a resume:
  1. [Resume](https://sevenrl.github.io/) to use to host
  2. A decent tutorial to get us started (*linked under **More Resources***)
  3. Github pages
  4. Markdown file editor(such as Atom or VSCode)

## Instructions

A guide that is helpful when hosting a resume would be that of Andrew Etter's Modern Technical Writing. One thing I personally picked up is how writing and hosting are so much simpler in Markdown as compared to something like XML, the comparison  is that in Markdown we would use only 179 characters as compared to XML or some other complex technical writing tool, which could take up to 700+ characters, which is a massive difference. This is why Markdown is a great tool to use when it comes to creating things like these, some other good ones are reStructuredText and AsciiDoc.

Another thing to pick up from Andrew is how he has mentioned the use of distributed version control, this allows for easy changes on the go, especially for things such as a resume. It also allows us to store different versions to go back on. Very useful tool since you can allow yourself to tailor different resumes under different versions. Another helpful tip would be you can get other people such as advisors to look at it for you and make changes accordingly. Personally, I would use something such as git and Github since they are very well documented.

### Guide
1. Click on the '+' icon in the top right and create a new repository
2. Name the repository starting with your username and adding .github.io at the end, all one word, this is the link where the website will be hosted
3. The next step is we need an index.md file, as well as a config file
4. To get the config file, go to the repository's settings on the tab next to Insights
5. Scroll down till you find Github Pages
6. From here, you can choose an appropriate theme to support the resume
7. Once all that is done, simply put your formatted resume into the index.md file
8. If all is good, you will see the following appear as your resume when you go to the .io website


![](https://github.com/SevenRL/SevenRL.github.io/blob/main/GIFResume.gif)


## More resources

Here are some helpful links that will get you started

1. [Link](https://www.goodreads.com/en/book/show/28433138-modern-technical-writing) to getting Etter's Modern Technical Writing. There is some very handy information in this book that I have not touched base on, worth a read to go over things that you can incorporate yourself to help you get started. 
2. [This](https://docs.gitlab.com/ee/user/markdown.html) is a great tutorial for Github Flavored Markdown. I used this to get myself started on this, I would highly recommend this.
3. Another great guide I would check out is on [version control](https://ourcodingclub.github.io/tutorials/git/) to give yourself a wider knowledge  of how to use version control

## Authors and Acknowledgments

1. Thank you to Danny Guo for the Readme [template](https://www.makeareadme.com/)
2. Thanks to my amazing group members
* Winston Lam
* Braden Jonsson
* Joshua Dueck

## FAQs

### Question: Why is Markdown better than a word processor?
Answer: Markdown allows for many different types of customizations when it comes to the field of technical writing, it can be a very powerful tool

### Question: Why is my resume not showing up?
Answer: The resume takes time to update on the backend, it could take a few minutes for the updates to go through
