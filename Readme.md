The symbols in Crochet Charts are treated in several different ways depending on whether they are replacements or new symbols.
Internal and new symbols are stored in different ways. This makes updating slightly difficult. So we have a set of procedures below for you to follow.

Within Crochet charts you can import a **set** of new symbols, or update an icon(symbol) from within the Stitch Library (ctrl-L).
We will be using a mechanism that loads new stitches whenever Crochet Charts is opened.
To do this we will be adding stitches into the configuraton directory. This directory has not been used by users before.

# Procedure: #
The insructions below may seem daunting and lengthy. There is a **concise set of instructions in the file** 'concise instructions.md' which is very short and concise but relies on you knowing something about Windows operating system and configuration folders. If you are not comfortable with these concise instructons then use the long winded ones below. They will lead you safely step by step through the procedure.

### Preparation
#### 1. Find your configuration directory.

Crochet Charts stores user data in a special place. You need to find this location because that's where most of the files will need to go.
On Windows its found in a folder like this:
   - C:\Users\userloginname\AppData\Local\Stitch Works Software\Crochet Charts
   - where userloginname is the name of your user.
   - you can find userloginname by finding the appdata folder on your machine and noting the name.
      - do this by opening a file Browser and typing %localappdata% into the address bar
      - you should end up in a folder like this:
         - C:\Users\userloginname\AppData\Local\Stitch Works Software\Crochet Charts
   - Make a note of this location and leave your file browser open here.
   - We will be downloading files into here.

On the Mac look in here:
   - ??
   
#### 2. Backup your current changes.

If you have never imported sets or used 'Manage Icons' to change icons and add new stitches then you can skip this step.
Otherwise you should backup your data - at the end of installing the new stitches we will explain how to get your personal ones back in.
   - The configuration directory, discovered in Step 1, is called 'Crochet Charts'.
   - Rename it to "Crochet Charts original".
       - as long as is not called "Crochet Charts" the system will not find it and so it will rebuild a fresh empty folder.
   - We will temporarily keep your old directory until you have loaded in any of your own stitches you wish to keep.
   - Alternatively - **you can undo all the steps that follow**, and get back to where you started by:
       - Make sure the program "Crochet Charts" is not running.
       - Deleting the directory that Crochet Charts is about to build next time its starts (named 'Crochet Charts').
       - Rename your original renamed directory back to "Crochet Charts". Thereby restoring your data back to its original state.
       - Then restart the program. Your old stitches will be back.

### Installing new stitches
#### 3. Updating current Tunisian symbols.

We do this first because it is the least difficult process.
The Tunisian symbols are unchanged. We add a new category so they can be sorted in the Stitch Library more easily.

    1. Close Crochet Charts if it's open.
    2. Download the Tunisian.xml file and save it into the configuration directory.
    3. Start Crochet Charts.
    4. Navigate to the Stitch Library (ctr-L) or 'Tools/Stitch Library'
    5. Select 'Stitch Source:' Tunisian (It defaults to 'Default Stitches')
    6. You will see the existing Tunisian stitches but 'Category' is filled in and says 'Tunisian'.
    7. Select each one until all are selected (tick in checkbox)
    8. Click on 'Add To List' to swap these for the ones in Default.
        - You will be prompted to replace the existing stitch for each of them. Replace them (first choice).
    9. At the top of the Stitch library - Select 'Stitch source' = Default
    10. You can now see the Tunisian stitches.
        - by clicking on the category column header you can sort Tunisian stitches to the top or bottom.
    11. You can only see the category here for now.
    12. Close the Stitch Library and select stitches as normal.
      
#### 4. Installing Directions symbols.

This is a small set of symbols. Once again to practise the update procedure.
These symbols include: start, end, blo, flo, and 8 arrows to be used between rows.

    1. Close Crochet Charts if it's open.
    2. Download the following files into your configuration directory.
       - far.bat         - internal tool - finds and replaces config directory
       - directions.xml  - description of new stitches
       - directions.bat  - will rename directory in xml file
       - directions.png  - just to look at
       - directions.zip  - the new stitch symbols
    3. Create a new subdirectory here called /newstitches. We will be putting all of our stitches in here.
    4. Move the directions.zip file into the newstitches directory.
    5. Go into the newstitches directory and unzip the files so they all appear in there as a long list.
       - You will see a number of new stitch symbols as svg files in the newstitches directory.
    6. Double click on the directions.bat file.
       - A text window will open for a few seconds and then close.
       - This will edit the xml file and get the config directory properly connected so the new stitches can be found.
    7. Start Crochet Charts.
    8. Navigate to the Stitch Library (ctr-L) or 'Tools/Stitch Library'
    9. Select 'Stitch Source:' Direction stitches (It defaults to 'Default Stitches')
    10. You will see 12 or so stitches with 'Category' saying 'directions'.
    11. Select each stitch (tick in checkbox) until all are selected.
    12. Click on 'Add To List' to set/swap these stitches for the ones in Default.
        - You will be prompted to replace any existing stitches just like with the Tunisians above.
    13. Select 'Stitch source' = Default
    14. You can now see the directions stitches along with with all of the others.
        - by clicking on the category column header you can sort stitches to the top or bottom (click twice).
    15. Close the Stitch Library and select stitches as normal.
    

#### 5. Installing sc (single crochet) symbols.

This is a set of symbols replacing the existing sc symbols and adding a couple of new ones.

    1. Close Crochet Charts if it's open.
    2. Download the following files into your configuration directory.
       - far.bat         - internal tool - finds and replaces config directory (you should already have this now)
       - sc.xml  - description of new stitches
       - sc.bat  - will rename directory in xml file
       - sc.png  - just to look at
       - sc.zip  - the new stitch symbols
    3. Move the sc.zip file into the newstitches directory.
    4. Go into the newstitches directory and unzip the files so they all appear in there as a long list.
       - You will see a number of new stitch symbols as svg files in the newstitches directory.
    5. Double click on the sc.bat file.
       - A text window will open for a few seconds and then close.
       - This will edit the xml file and get the config directory properly connected so the new stitches can be found.
    6. Start Crochet Charts.
    7. Navigate to the Stitch Library (ctr-L) or 'Tools/Stitch Library'
    8. Select 'Stitch Source:' sc stitches (It defaults to 'Default Stitches')
    9. You will see stitches with 'Category' saying 'single crochet'.
    10. Select each stitch (tick in checkbox) until all are selected.
    11. Click on 'Add To List' to set/swap these stitches for the ones in Default.
        - You will be prompted to replace any existing stitches just like as above.
    12. Select 'Stitch source' = Default
    13. You can now see the sc stitches along with with all of the others.
        - by clicking on the category column header you can sort stitches to the top or bottom (click twice).
    14. Close the Stitch Library and select stitches as normal.
    
