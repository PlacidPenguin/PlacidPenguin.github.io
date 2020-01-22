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
1. Navigate down to the year and month that you want.
2. Create a new file and name it withe the ```.md``` extension.
3. Copy and paste the follow:
```
---
layout: page
title: my title
author: Devin
date: Jan 22 2020
---
```
4. Make sure to create the Link in the month corresponding ```.html``` file in the year folder.

### How to make a new month
1. Navigate down to the directory with the year your want.
2. Create a new file and name it month you want with the ```.html``` extension.
3. Copy and paste the follow:
---
layout: series
seriesName: New Mouth
folderName: year/month

book1: Title of Rant

fileName1: title_of_rant.html
---

# Resources for styling
[Bootswatch](https://bootswatch.com/sketchy/)
