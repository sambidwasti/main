# [Blog1 site](https://sambidwasti.github.io/blog1/)

# Notes on the modifcation

Need to modify the pages. 
Followed youtube tutorial on girraffee academy to understand the setup, folders and structures of the hugo at base level.

> Goal here is to 
> * Understand the structure.
> * Start modifying it to your needs.
> 
---
#Folders.
* archetypes: Frontmatter/ Tags/ etc
* content : all content, blogs, gallery, webpages..
    * 2 folders
    * Blogs
    * Gallery
    * **Create Test** 
    
* data: no data. 
    * Probably resume stuff goes here. Few Json files go here aswell. Maybe the hinge data go here.
    * SImpleworkout log is a csv file.
    
* layouts: define layouts, complex, header, footer, etc.    
    * example, header, footer. 
* static: important folders for static elements, image, css file, java file, etc.

* themes: pre built theme.

---

#Home Page
> Need to modify 
> * Logos of socials like coder.
>   * successful in coder but it is structured differently.


---
#Archetypes
There are few tags and more frontmatter so added that to translate to the contents.

###Example of the frontmatter.
title: "Placeholder Text"    
date: 2021-04-03T22:41:10+05:30     
draft: false       
github_link: "https://github.com/gurusabarish/hugo-profile"       
author: "Gurusabarish"        
tags:       
  - Placeholder text
  - Sample
  - example
image: /images/post.jpg       
description: ""       
toc:
    
#Layouts

##Homepage
**index.html** at layouts folder.

Index hase three blocks.
###Head
###Title

### main.
* In Main, when commented out about, it did not get removed at the header section but it removed the div with about.
* When everything in main is commented, you still see the Recent Posts and bottom contact options.
* So they must be in base of/ or footer.

## Base of
Has a footer element.

## Java Script

HTML is content of the webpage
Java Script is behaviour of the element when a mouse is hovered.

---
## Socials at footer and at Hero.