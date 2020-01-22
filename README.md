### This site serves as the backend for the small book review site that I host for my family and friends.
 

# How to make a book review   

1. Navigate to the [content](content/) folder.
2. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/create_new_file_btn.PNG) button towards the top right.
3. Give your file a name i.e., if you read "The Great Gatsby" name your file ```great_gatsby.md```.  
   *Pro Tip: try to leave of leading "articles" such as, "The" or "A" in file name. Likewise, use "_" instead of spaces and use     
   lower case.*
4. Copy and paste the following into your newly created file:
```
---
layout: page
title: Name of the book you read
bookAuthor: Foo Bar
author: Your name
date: Jan 8 2020
parentalRating: PG
---
  YourAwesomeBookReview 
```
5. Leave ```Layout: page``` untouched and fill in the rest. Which gives us:
```
---
layout: page
title: The Great Gatsby
bookAuthor: F. Scott Fitzgerald
author: Jane Doe
date: Aug 5 2050
parentalRating: PG
---
  This book really stood up against the test of time... 
```
6. Scroll to the bottom of the page and click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.

7. Upate the [index.md file](index.md)

# How to make a book series review
1. Navigate to the [content](content/) folder.
2. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/create_new_file_btn.PNG) button towards the top right.
3. Your going to make a new folder and file, like so: Give your folder a name i.e., ```harry_potter_series``` then press the ``` / ``` (forward slash) and name your file i.e., ```harry_potter_and_the_sorcerers_stone.html```
4. Follow steps 4 - 6 from the section [How to make a book review](#how-to-make-a-book-review). Then, do steps 2 - 6 from [How to make a book review](#how-to-make-a-book-review) for each book in the series your reviewing.
5. Create another file in the [content](content/) folder and name it i.e., ```harry_potter.html```.
6. Copy and paste the following into your newly create file: 
```
---
layout: series
seriesName: Name
folderName: name
book1: Name
fileName1: name 
---
```
7. Fill in the the ```seriesName``` portions with the name of your series, ```folderName``` with the name of your folder (see step 3), ```book1``` with the book name  and ```fileName1``` with the name of your file (see step 3). Which gives us:
```
---
layout: series
seriesName: The Harry Potter Series
folderName: harry_potter_series
book1: Harry Potter and the Sorcerer's Secret
fileName1: harry_potter_and_the_sorcerers_secret.html
---
```
8. For additional books in the series add the tags ```bookN``` and ```fileNameN``` where ```N``` is the number in the series i.e., ```book2: The Second Book``` and ```fileName2: the_second_book.html```
9. Scroll to the bottom of the page and click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.

# How to create the link to your book review
1. Click on the [```index.md```](index.md) file in the root of the repository.
2. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/edit_btn.PNG) toward the top right.
3. Copy and paste: ```-  [<span markdown="1" class="text-white">Name of book or series</span>](content/name_of_file.html)``` right below the ``` <h1>Reviews</h1>``` portion.
4. Change ```Name of book or series``` to the name of the book or series your reviewing i.e., *The Lost World* and change the ```name_of_file.html``` to the name of the file you created in step 3 of the [How to make a book review](#how-to-make-a-book-review) section i,e., ```lost_world.html```. 
   *Or, if you're linking a series then change it to the **filename** you created in step 5 of* 
   [*How to make a book series review*](#how-to-make-a-book-series-review)
5. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.

# How to make a new Rant
1. Navigate down to the year and month that you want from the [content](content/) folder.
 ***Note: if your making a rant for a month that doesn't exist yet. You will create the folder for the month when you make the new file. i.e., follow step 2 below and then name your file ```/newMonth/fileName.md``` for example, ```/may/government_employees_are_lazy.md```
2. Create a new file and name it with the ```.md``` extension.
3. Copy and paste the follow:
```
---
layout: page
title: my title
author: Devin
date: Jan 22 2020
---
```
4. Make sure to create the Link to this file in the coresponding month ```.html``` file in the year folder.
5. Edit the ```title:```,```author:``` and ```date:``` values according to your wishes.
6. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.

### How to make a new month
1. Navigate down to the year you want from the [content](content/) folder
2. Create a new file and name it the month you want with the ```.html``` extension.
3. Copy and paste the following:
```
---
layout: series
seriesName: New Mouth
folderName: year/month

book1: Title of Rant

fileName1: title_of_rant.html
---
```
4. Edit the ```folderName: year/month``` to the name of the month folder for the new rants i.e., it the year is 2020 then, ```folderName: 2020/August```
5. Edit the ```book1: Title of Rant``` to the name of the rant i.e., ```book1: Drivers in Silverdale/Bremerton```
6. Edit the ```fileName1: title_of_rant.html``` to the name of the file for your rant i.e., ```fileName1: stupid_bremerton_drivers.html```
7. Click te Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.

### How to make a new year
1. Edit the [rants.md](rants.md) file by adding a new link to the new year, with the following:
```
book2: 2021
fileName2: 2021.html
```
2. Make sure the ```2021``` and ```2021.html``` values are changed to the year your want i.e., ```book2: 2040``` and ```fileName2: 2040.html```
3. Make a new file with the year you just used i.e., ```2040``` in the (content)[content/] folder and name it ```year.html``` i.e., ```2040.html```.
4. Edit the new file by adding the following:
```
---
layout: series
seriesName: Year
folderName: *see the note below*

book1: month

fileName1: january.html
---
```
5. Note: In order to make a new folder you must make a new file and create the folder you want when you make the new file. It's weird but its just how github.com works.

# Resources for styling
[Bootswatch](https://bootswatch.com/sketchy/)
