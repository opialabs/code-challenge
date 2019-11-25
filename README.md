# code-challenge

Using https://openweathermap.org/api or similar API, create a simple web app which supports the following functionality.

* User types in a city name (autocomplete) and it shows the current weather along with next 3/5 days prediction (the more information you show the better) in a structured way.
* Caches the result for searched cities for 24 hours so another API lookup isn't necessary. Needless to say if there is another query for the same city and if there is a cache hit the data should be loaded from cache.
* Stores all searched cities in DB along with the time at which search was done. Based on stored data, show simple graphical stats like most searched cities (along with count) in last 24 hours and last 7 days. Add a separate page/route for displaying this section.
* Wow us if you can by doing something extra. Totally optional ;)

# Notes

* Use your judgement in case you aren't sure about how a prticular thing needs to be shown/implemented.
* No design/styling work needed but would be good if an open source library is used with ready to use design elements/components.
