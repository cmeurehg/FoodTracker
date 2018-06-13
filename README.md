# FoodTracker

Perfect Pair - Your Wine and Food Pairing App

This first group project is the result of a strong shared interest in food and wine, but also a desire to have information about the nutritional profile of a certain meal that the user may have in mind.  We designed this web application with the intention to offer a tool for entertaining, dining out, or simply deciding on which recipe to prepare according to the nutritional expectations at a moment in time... and pairing it with some wonderful wines.

An important advantage of our web application is that the resulting wine pairings are with specific lables that are currently available for purchase at the LCBO.

If you feel like pasta, or pizza, or maybe a hamburger, the app will allow you to search for choice, will present you with a beautiful photo of the finished dish, and will suggest two or three bottles of wine that can pair beautifully with your choice.  If, however, you lean towards something more complex like a Paella, the suggested bottles will complement and enhance the experience.  And to cater to the sweet side of things, you can also search for desserts and obtain delicious wine pairing suggestions!  Cheers.

Technical aspects

The app uses the Spoonacular API through Ajax calls to retrieve nutritional information, while also using the LCBO API to obtain wine pairing suggestions, real bottle images and price points that are presented to the user.  The information is stored in the Firebase database and also in Local Storage to improve performance in case the recipe has already been searched before.  On the front-end, we chose the Materialize framework to design the app and we obtain the food images from Pixabay.

Please visit the deployed web application at:  https://cmeurehg.github.io/FoodTracker


