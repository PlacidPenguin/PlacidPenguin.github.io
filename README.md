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
author: Your name
date: Jan 8 2020
---
  YourAwesomeBookReview 
```
5. Leave ```Layout: page``` untouched and fill in the rest. Which gives us:
```
---
layout: page
title: The Great Gatsby
author: Jane Doe
date: Aug 5 2050
---
  This book really stood up against the test of time... 
```
6. Scroll to the bottom of the page and click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.


# How to make a book series review
1. Navigate to the [content](content/) folder.
2. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/create_new_file_btn.PNG) button towards the top right.
3. Your going to make a new folder and file, like so: Give your folder a name i.e., ```harry_potter_series``` then press the ``` / ``` (forward slash) and name your file i.e., ```harry_potter_and_the_sorcerers_stone.md```
4. Follow steps 4 - 6 from the section [Review](#review). Then, do steps 2 - 6 from [Review](#review) for each book in the series your reviewing.
5. Create another file in the [content](content/) folder and name it i.e., ```harry_potter.md```.
6. Copy and paste the following into your newly create file: 
```
---
layout: default
---
<div class="container text-center card text-white bg-secondary mb-3" style="max-width: 40rem; font-weight: normal;" markdown="1">
  <h1>Name of Series</h1>
-  [<span markdown="1" class="text-white">cool book1</span>](name_of_series/book1.md)
-  [<span markdown="1" class="text-white">cool book2</span>](name_of_series/book2.md)
</div>
```
7. Change the contents enclosed by the ```<h1> </h1>``` in the ```<h1>Name of Series</h1>``` line to the name of your series.
8. Chanage contents in the part ```[<span markdown="1" class="text-white">cool book1</span>]``` from "cool book1" to the name of your book.
9. Change the contents in the part ```(name_of_series/book1.md)``` from ```name_of_series``` to the name of the folder you created in step 3 i.e., ```harry_potter_series``` and change ```book1.md``` to the name of the file your created in step 3 as well i.e., ```harry_potter_and_the_sorcerers_stone.md```. Which gives us:
```
---
layout: default
---
<div class="container text-center card text-white bg-secondary mb-3" style="max-width: 40rem; font-weight: normal;" markdown="1">
  <h1>The Harry Potter Series</h1>
-  [<span markdown="1" class="text-white">Harry Potter and the sorcerers's stone</span>](harry_potter_series/harry_potter_and_the_sorcerers_stone.md)
-  [<span markdown="1" class="text-white">Second Harry Potter Book</span>](harry_potter_series/second_harry_potter.md)
</div>
```
10. Copy and paste ```-  [<span markdown="1" class="text-white">cool book2</span>](name_of_series/book2.md)``` and follow steps 8 - 9 for each book in the series your reviewing.
11. Scroll to the bottom of the page and click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/commit_btn.PNG) button when your finished.

## How to create the link to your book review
1. Click on the [```index.md```](index.md) file in the root of the repository.
2. Click the ![](https://github.com/PlacidPenguin/PlacidPenguin.github.io/blob/master/resources/edit_btn.PNG) toward the top right.
3. Copy and paste:
``` ```

## Resources for styling
[Bootswatch](https://bootswatch.com/sketchy/)
