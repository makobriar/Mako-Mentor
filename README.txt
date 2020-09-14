 /$$      /$$  /$$$$$$  /$$   /$$  /$$$$$$        /$$      /$$ /$$$$$$$$ /$$   /$$ /$$$$$$$$ /$$$$$$  /$$$$$$$ 
| $$$    /$$$ /$$__  $$| $$  /$$/ /$$__  $$      | $$$    /$$$| $$_____/| $$$ | $$|__  $$__//$$__  $$| $$__  $$
| $$$$  /$$$$| $$  \ $$| $$ /$$/ | $$  \ $$      | $$$$  /$$$$| $$      | $$$$| $$   | $$  | $$  \ $$| $$  \ $$
| $$ $$/$$ $$| $$$$$$$$| $$$$$/  | $$  | $$      | $$ $$/$$ $$| $$$$$   | $$ $$ $$   | $$  | $$  | $$| $$$$$$$/
| $$  $$$| $$| $$__  $$| $$  $$  | $$  | $$      | $$  $$$| $$| $$__/   | $$  $$$$   | $$  | $$  | $$| $$__  $$
| $$\  $ | $$| $$  | $$| $$\  $$ | $$  | $$      | $$\  $ | $$| $$      | $$\  $$$   | $$  | $$  | $$| $$  \ $$
| $$ \/  | $$| $$  | $$| $$ \  $$|  $$$$$$/      | $$ \/  | $$| $$$$$$$$| $$ \  $$   | $$  |  $$$$$$/| $$  | $$
|__/     |__/|__/  |__/|__/  \__/ \______/       |__/     |__/|________/|__/  \__/   |__/   \______/ |__/  |__/
                                                                                                               
                                                                                                               
                                                                                                               
_______________________________________________________________________________________________________________
Author: Mako Briar
Git Repo: https://github.com/makobriar/Mako-Mentor.git
Server: Crystal -- Zalera
_______________________________________________________________________________________________________________

HOW TO EDIT DUTY JOURNALS
`````````````````````````````````
    1. Open the 'data' folder and search for the dungeon you need.
        1a. If it doesn't exist, create a new folder under the proper
            type, and copy the format of others.
            AKA: Dungeon Name.html is the general guide, followed by
            all the necessary files for tank, healer, and dps (even
            if they have to be blank.)
    2. Edit it by using HTML. No need to add a <style> tag, that's all
       prepended by the 'default_style.html' file directly in the 
       data folder.
    3. If you need to add an image, add whatever you need in the 'images'
       folder. I'm trying to add minimal icons for boss mechanics, so feel
       free to use those.
    4. When you're finished: that's it! Make sure your files are saved and
       they should pull up in Mako Mentor.


TROUBLESHOOTING
`````````````````````````````````
    Q: A dungeon I added isn't showing up in Mako Mentor. Why??
    A: It must follow the exact same file structure as the others.
       That is, if you were to add an Alliance raid, it would be
       under \data\alliance\<your_alliance>
       It also must have .html files in there, otherwise it will
       be skipped.
       
    Q: I want different colors in my guide!
    A: You can tweak the default_style.html to however you want.
       Frankly, I'm not too savvy in HTML, but it's a light enough
       method of editing your own guides. You can try to overwrite
       those changes in your guide. All my code does is prepend
       'default_style.html' to the dungeon's html.
       
    Q: I'm clicking a dungeon and nothing is changing!
    A: There likely isn't a guide for it yet - or more accurately,
       no HTML files are in that directory. It's going to take awhile
       to get me to fill out these guides, unless I get some help.
