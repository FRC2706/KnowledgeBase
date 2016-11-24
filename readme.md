# Welcome to the Team 2706 Merge Robotics Knowledge Base!

This is intended to be a collection of notes, lists, tips, and things that we want to remember about all our various projects.

## How to edit a file

First, make sure you're logged in to your github account, and make sure your account is a member of the FRC2706 github organization. Everyone in FRC2706 should have write access.

To edit an existing page, click on the file you want to edit (ex. readme.md) and there is an edit icon (pencil). To save your changes, you need to scroll to the bottom and click "Commit changes".

If you're a git wizard and want to do the clone, commit, push thing instead, go for it!

## How to create a new file

To create a new file in the wiki, click "Create new file" or "Upload files".

## How to create a new folder

Github is is quirky in that you can't have empty folders, but if you go to "Create a new file" and you type a folder as part of the name, for example "folder/newFile.md", a new folder will be created.

## Formatting

Github uses a formatting syntax called MarkDown (`.md`). If you google "github markdown syntax" you will get lots of great guides, but here's the basics: with markdown, you type certain symbols into the Edit window, and github will automatically turn them into formatting in the Preview window. Here are some of the basics:

Section Headers:

    # Title
    ## Section Heading
    ### Subsuction Heading
    #### Subsubsection heading
    ##### ...
    
Bold, italics, strikethrough:

    Emphasis, aka italics, with *asterisks* or _underscores_.
    Strong emphasis, aka bold, with **asterisks** or __underscores__.
    Combined emphasis with **asterisks and _underscores_**.
    Strikethrough uses two tildes. ~~Scratch this.~~
       
>Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~
    
    
Numbered lists:

    1. First item
    2. Second Item
    
> 1. First item
2. Second Item

Bullets:

    - First item
    - Second item
       
>- First item
- Second item

Code:

    For things like filenames, urls, or variable names, use `single back-quotes`, or indent 4 spaces.
    
For code snippits that you would like syntax highlighting on, surround them with tripple backquotes (on their own line), and tell it the language:

    ```java
    public static void main(String args){
    float likeAButterfly;
    String likeABee;
    }
    ```
    
```java
public static void main(String args){
    float likeAButterfly;
    String likeABee;
}
```

## Misc

By default, github will display the `readme.md` for each folder. By all means, make other files (`.md` or otherwise), or upload whatever you want!, but unlike the `readme.md`, people will have to click on them to see them.

Version control: anyone who's used git before will know that everything is versions controlled, so we'll never lose anything, and can always look back at a previous version of something!
