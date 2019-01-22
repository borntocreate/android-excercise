# Android Excercise

This is a small excercise to test android/kotlin programming skills.

## Task

Develop a basic android app using `Android Studio` with `Kotlin` implementing the following features:

1. Implement a view to display a list of articles loaded from `http://url-following.de`
	- The articles must be displayed in a list
	- Each item in the list consists of an image, title and excerpt.
	- For the images placeholder images can be used but must not be hardcoded.  
2. Implement a detail view which displays the full article with a larger image when selected
3. Implement a comment section which accepts a `name`, `email` and `comment` as input an sends it to the following URL `http://url-following.de`
 	- The comment section must be prefilled with comments for this post retrieved over `http://url-following.de/post/{id}/comment`
 	- Each comment entry must display the `name`, `email` and `comment`.
4. Provide proper user feedback for all interactions with the UI 
