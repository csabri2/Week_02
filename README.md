# Week_02

## Setup for Development (optional for this assignment)

### Mac
You guys are fine.

### Windows
You have multiple options on how to develop software on Windows. This is just MY   
preferred method and it works very well for CS classes you will take in the  
future.

**Step 1** - Install Windows Subsystem for Linux and install your preferred Linux  
Distribution (you probably want Ubuntu). [Follow this Guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

**Step 2** - Use Atom text editor. Install it [here.](https://atom.io/)

**Step 3** - Install PlatformIO IDE for Atom [here.](https://platformio.org/platformio-ide)  
- Scroll down for the Atom install link.
- This plugin for Atom text editor will let you interface with bash within Atom. This  
is completely optional, but saves you from having to open multiple windows.

## Intro to Git (Part 2)

### Common Git Commands
The "$" is not part of the command. It there to show it's a Bash command.
```
$git clone http://<url>

$git add .

$git commit -m "some commit message"

$git push origin

$git log
```

**Remember**  
If you are not a collaborator on a repository, you should first fork the  
repository before cloning it. And, always use Pull Requests when working in  
teams, so team members can check your work.

## HTML & CSS
**Google what you want to do in HTML/CSS, your question has usually been asked  
before**


### General HTML File Format
```
*index.html*
<html>
  <head>
    <link href="..." />
  </head>
  <body>
    PUT YOUR CONTENT HERE
    <script src="..."/>
  </body>
</html>
```

### Syntax  
```
//  HTML
<tagname property="value" property="value"></tagname>
<tagname property="value" property="value"></tagname>

//  CSS
selector {
  property: value;
  property: value;
}
```

## Assignment
Create a website using Repl.it or within your own filesystem.

It should have the following:
- Some type of Header
- Some type of unordered list or ordered list
- A paragraph
- A picture
- Some CSS Styles

**If you don't know how to do something Google it, or look at [this for reference](https://www.w3schools.com/)**
