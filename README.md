#Hello World!

###This tutorial will show you how to easily get started making your own website with completely free hosting.

##Joining GitHub Pages
We will be using something called GitHub Pages to host our code. GitHub is the most popular way people share and collaborate on code so it's good to have an account and be familair with it.

There are a decent amount of steps but they are all easy enough. Some steps will probably look complicated sometimes but this guide will help you avoid all the fancy stuff you don't need yet. This is what the real software professionals use every single day so if you decide to keep coding, you will already have a great headstart!

The first thing you want to do is create your Github account. It's free to join. 

https://github.com/join

Note that the username you pick will be part of the URL for your website so pick something you won't mind sharing.

After clicking "Create Account" and then "Finish Sign Up" (the free plan is fine), you'll have to verify your email addess. 

Click the button in the email they sent you and it will take you to your main page. Cool!

![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub1.jpg "Github after logging in")

Click the "New Repository" button or the "Create New Repository" link.

Once at the new repository screen, give your repository a name. A repository is where you put code and other files (like pictures) for a particular site. You can think about it like a folder on your computer. You can have as many repositories on your account as you wish, just like you have folders on your computer. Give your repository a name.

IMPORTANT: Click the checkbox that says "Initialize this repository with a README"

![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub2.jpg "New Repo")

Click on where it says "Branch: Master" and type in "gh-pages" exactly like that. Then click below where it says "Create Branch" in blue.
![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub3.jpg "new branch")
![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub4.jpg "gh-pages branch")

We're almost done!

Next, click the "Settings" tab, then "Branches" on the left menu.
![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub5.jpg "Settings tab")

The first heading is for the default branch, this is what we want to change. It currently says "Master", go ahead and click the button and it will create a dropdown. Select "gh-pages". 
![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub6.jpg "Setting default")

Now that you have selected "gh-pages", we'll click "Update". It will pop up with a scary looking message, just click "I understand ..".
![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub7.jpg "Scary message")

Phew! The hard stuff is pretty much done!

##Creating Files

We can now start creating whatever files we like. Click "New File" in the middle of the screen. 

You're now on the screen to create a new file. The easiest thing will be is to use a text editor like Notepad++ or Brackets to write your code and then copy it over to the big textbox on Github. To start with, name your file "index.html". We use "index.html" becuase when you go to a website, that's the page that always shows up by default. For example, if you go to "http://www.shaunvanweelden.com", it'd be the same as going to "http://www.shaunvanweelden.com/index.html". If you don't specify a particular web page, it will try and show "index.html". 

![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub8.jpg "new file")

Anyways! After naming your file "index.html", go ahead and copy this code into your editor on GitHub:

```
<!-- This is how you write a comment in an ".html" file, with <!-- and -->
<html>
    <head>
        <style>
            <!-- If you write any CSS code or styling, you can put it here -->
        </style>
        <script>
            <!-- If you write any Javascript code, you can put it here -->
        </script>
    </head>
    <body>
        <!-- Your web page code or HTML code will go here in the "Body" section -->
        <h3>Check out these links to get started coding in HTML:</h3>
        <a href="https://www.codecademy.com/skills/make-a-website">CodeCademy's "How to Make a Website" guide</a><br>
        <a href="http://www.w3schools.com/html/html_intro.asp">W3School's guide and reference document</a>
        <h3>Congrats on having your first webpage up!</h3>
    </body>
</html>
```

![alt text](https://github.com/OutreachHelper/GetCoding/blob/gh-pages/Images/GItHub9.jpg "finished file")

After copying the code into the editor, scroll down a bit to where it says "Commit New File". Feel free to add a little message about what you did, then click the green "Commit New File" button.

##Checking out your site on the web
Ready to see your code on the World Wide Web? Go to http://<< USERNAME >>.github.io/<< REPOSITORYNAME >>/ where you would substitute your username and repository name. Pretty cool, huh?! Feel free to change the words between the < body > </ body > tags and then commit again, you'll be able to see your changes live. Anyone in the world can see stuff at this link so feel free to show your parents, friends, whomever.

##Next Steps
As you learn things about HTML, I'd recommend updating your index.html file with what you find! Websites come together by piecing different components over time to make a great looking site.

##Advanced Stuff:
###Editing Readme
You can edit your README file to make it look more pretty by following this website's guidelines: 
Your README is what people see if they go to your GitHub account and check out what you have. This is different than your website.

###Bootstrap Website Styling
As you do more research about developing websites, you'll probably start to see something called "Bootstrap". Bootstrap is what we call a CSS framework, you can use this framework to make your website look great without doing a bunch of work. A "CSS framework" is a set of files you can add to your website that make styling components a lot easier. The main website is: http://getbootstrap.com/ and they have some great examples of how it is used here: http://getbootstrap.com/getting-started/#examples. I've also included in this repo an example you can copy to get a jumpstart using bootstrap. You can look through the "CSS" section of Bootstrap's website to start using their components. Just copy and paste them into your index.html file to practice.



