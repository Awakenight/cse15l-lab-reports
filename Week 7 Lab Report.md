# Week 7 Lab Report

---

## Part 1: Editing from the Command Line

Here are the instructions on how I changed the name of the **start** parameter and its uses to **base** 
within the method **getFiles**, under the file **DocSearchSever.java**, using vim.

Enter the command `vim DocSearchServer.java` and have your cursor start at top, before the method,
**getFiles**. You should start in normal mode, however, press `<Esc>` to make sure that you're in normal mode. 
Below is the list of keys to press to chang the name of the **start** parameter and its uses to **base**. 
Along with images of what the method looks like before and after. 

`/start<Enter>cebase<Esc>n.n.:w<Enter>`

Before: 
![Image](Screenshot 2022-11-13 205859.png)

After:
![Image](Screenshot 2022-11-13 210911.png)

Here is an explaination on changing the first occurrence of the word “apple” to “banana” in a file containing 
**blueberry apple sauce**, using vim with the following keys: 

`/apple<Enter>cebanana<Esc>:w<Enter>`

**/apple<Enter>** allows for you to search for text after **/**, which moves your cursor in front
of the first instance of the text:

![Image](Screenshot 2022-11-13 211157.png)

**ce**  allows for your to delete the text and switch to insert mode:

![Image](Screenshot 2022-11-13 212633.png)

**banana<Esc>** replaces the text by inputing the word **banana**, and 
**<Esc>** returns you back to normal mode:

![Image](Screenshot 2022-11-13 213310.png)

**:w<Enter** saves the changes made to the file:

![Image](Screenshot 2022-11-13 213447.png)

## Part 2: Editing from the Command Line