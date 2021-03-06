# US Datasets

## presidents

People who have held the position of the President of the United States of America

* General information: https://simple.wikipedia.org/wiki/List_of_Presidents_of_the_United_States
* Executive Orders: http://www.presidency.ucsb.edu/data/orders.php
* Impeachment: https://en.wikipedia.org/wiki/Impeachment_in_the_United_States
* Wars: http://www.american-presidents-history.com/wartime-presidents.html
* Inaugural Addresses:
  * http://avalon.law.yale.edu/subject_menus/inaug.asp
  * http://www.presidency.ucsb.edu/inaugurals.php

## vice_presidents

People who have held the position of the Vice President of the United States of America

* General information: https://en.wikipedia.org/wiki/List_of_Vice_Presidents_of_the_United_States

## states

* General information from wikipedia: https://en.wikipedia.org/wiki/List_of_states_and_territories_of_the_United_States.
* State flowers: https://en.wikipedia.org/wiki/List_of_U.S._state_and_territory_flowers
  * Order of preference: State Flower, State Wildflower
* State birds: https://en.wikipedia.org/wiki/List_of_U.S._state_birds
* Population data from US census:
  * 1900-1909: https://www2.census.gov/programs-surveys/popest/tables/1980-1990/state/asrh/st0009ts.txt
  * 1910-1919: https://www2.census.gov/programs-surveys/popest/tables/1980-1990/state/asrh/st1019ts.txt
  * 1920-1929: https://www2.census.gov/programs-surveys/popest/tables/1980-1990/state/asrh/st2029ts.txt

## cities

* Alabama: https://en.wikipedia.org/wiki/List_of_cities_and_towns_in_Alabama
* Alaska: https://en.wikipedia.org/wiki/List_of_cities_in_Alaska
* Arizona: https://en.wikipedia.org/wiki/List_of_cities_and_towns_in_Arizona
* Arkansas: https://en.wikipedia.org/wiki/List_of_cities_and_towns_in_Arkansas
* California: https://en.wikipedia.org/wiki/List_of_cities_and_towns_in_California

## Notes

Resized images with the following:

    magick mogrify -format jpg *.png
    rm *.png
    magick mogrify -resize 800x1024^ *.jpg
    magick mogrify -gravity north -crop 800x1024+0+0 *.jpg
