# Infinite Scroll Example Code

Article utilizing this code can be found here: http://www.thegoodlab.com/articles/infinite-scroll-with-ee

## Setup

* Move templates/default_site/scroll.group into your EE templates directory
* Move the scripts and images located in the assets/js and assets/images directory into corresponding folders on your EE site
* Adjust any script/style tags in the index.html file, to match your locations
* Setup Channel Fields/Channel
* Add some entries

#### Channel Field: News
#### Channel: News
#### Fields: 

* news_image: image field
* news_content: text area field

## Note

Old versions of jQuery may not support the implementation of the .data() method our example uses.  Please use a modern version if you are not using the one provided in this example.