# Nature Classifier

Based on [this xkcd comic](https://xkcd.com/1425).

![XKCD comic 1425 titled "Tasks"](https://imgs.xkcd.com/comics/tasks.png)


The idea here is to bring this comic to life, allowing the user to perform a GIS* lookup of a photo to check whether it is from a national park and whether there's a bird in it.

I've built an image classifier using a pretrained model from [fast.ai](https://www.fast.ai/) that was trained to identify birds, forests and squirrels.

The app also uses [TomTom search API](https://developer.tomtom.com/search-api/), which accepts an address or geographical coordinates, and returns the points of interest in the location, for example, a national park.


*GIS here stands for Geographic Information System
