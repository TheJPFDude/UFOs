# UFOs

## Overview of Project

The purpose of this analysis is to create a webpage that uses HTML and JavaScript to dynamically filter UFO sighting data using multiple criteria.

## Results

To use the search criteria in the page, just type the desired element in lowercase (with state abbreviations for states). For example, if you want all sightings in California, just type "ca" in the "Enter State" search bar, as shown in this below image:

![CA Search Results](Resources/ca_search_results.png)

Similarly, if you want all results on a certain date, type the date in the "Enter Date" search bar in the form MM/DD/YYYY (using only one digit for single digit months/days). For example, here are results from January 2nd, 2010:

![1/2/2010 Search Results](Resources/date_search_results.png)

## Summary

One drawback about this new design is that search results are case sensitive. That means that if you typed a city in capitals, it would not work.

One recommendation for further development would be to fix this by converting any input to lowercase before filtering the data -- that way, the search results would not be case sensitive. Another recommendation is to add more filters, possibly for the duration. To do this, we would probably need use Regex or something to make the data more consistent for filtering, as it does not have a standard format within the data table.