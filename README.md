# sq_cruise_ship

# Build

Using tweego to compile .twee files to html file:

`./tweego_win64.exe -o sq_cruise_ship.html src`

# Testing

Use Selenium IDE https://www.selenium.dev/selenium-ide to run the ./selenium_test.side file in chrome. This file runs through a basic playthrough to a certain point.

This does require updating the file to point to the fully qualified local path for the test to run by replacing "path/to/directory" in all locations in the file.

# Plans

Need to get all the heavy files (video, audio, images) off of this repo and store it in a more reasonable way. The total project size is 1.6 GB _compressed_. I'm also sure that Github has issues with adult media hosted on their site. Might need to burn this repo after a while and migrate to a new one.

Will include basic save files within the repo at some point. Might use them for more easy automated testing. Might include a way to skip to later chapters by setting choices later.
