Mars Photos
==================================

Mars Photos app is a demo app that shows actual images of Mars' surface. These images are
real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server
as a REST web service.

This app demonstrated the use of [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) to
handle the deserialization of the returned JSON to Kotlin data objects, and [Coil](https://coil-kt.github.io/coil/) to load images by URL.

Things Learnt
---------------
* What a REST web service is.
* How to use the Retrofit library to connect to a REST web service on the internet and get a response.
* How to use the Serialization (kotlinx.serialization) library to parse the JSON response into a data object.
* Repository pattern 
* Dependency injection 
* How to use the Coil library to load and display an image from a web URL. 
* How to use a LazyVerticalGrid to display a grid of images. 
* How to handle potential errors as the images download and display.

Screenshots
---------------
![image](https://github.com/user-attachments/assets/5c830e54-a9fe-4d86-8a46-766a721e2aa6)
