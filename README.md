<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title: Value of Retro Video Games - Fair Pricing based on pictures and videos of objects and available data on game (barcode, SKU, edition, # of copies sold, completeness, etc.)

Final project for the Building AI course

## Summary

This project is intended to value retro video games and put a fair price sticker on beloved games in one's collection. 
It is not only for the purpose of selling or buying games at fair prices.
It is also intended to give a fair and (freely) accessible true alternative to "grading games" operations. Or just trial and error via ebay etc.

## Background

I personally own a lot (well not too many compared to huge collections, maybe somewhere between in the 400+ games range) and fail to determine a fair value for each item. Personal memories and individual perception may vary widely from fair value and price of objects (same with used cars, used Mac computers, etc...). Therefore and before trying any activities in terms of selling, I want to create a simple way to put a sticker price on the items in my games collection so as to see where I maybe have add some extra attention when storing or where I can hardly get a movie ticket in exchange when selling a game. With so many people playing and collecting games, especially retro games I expect this to be a relevant project and very useful to many people.

This is how you make a list, if you need one:
* problem 1: gather as many data and information on games as possible (e.g. barcodes, SKU info, identifier for exact item, data on production volume, original price sold, areas sold, editions available, copies sold, history of ebay sales, etc.)
* problem 2: setup picture and video identification and classification concept and put reliable determination for estimated conditions and resulting prices
* problem 3: build slick neuronal network with self-improving algorithm to determine results
* problem 4: compare determined results with real world prices etc.
* problem 5: build, test, run decent code and in the end put everything into a nice app for Android / iOS...
* problem 6: find time and resources for project and tenacity to run project to the end
* problem 7: monetize / raise donations for use of project to ensure future releases

## More details to be added later

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
