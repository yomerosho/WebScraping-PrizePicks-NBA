# PrizePicks_NBA
Make Better NBA PrizePick Selections & Webscraping With Selenium

This exercise was to figure out a way to use python to scrape data and present in a visually friendly way so
that one can quickly make PrizePick selections

### Background

I'm an avid sports fan and play daily fantasy a lot (Fanduel, Draftkings, Prizepicks, etc). I had most of my succes with PrizePicks (particularly during the NBA season)
My initial tedious process involved the following steps:

<ol type="1">
  <li>Go to Prizepick and write down the players and their projected fantasy points</li>
  <li>Go to ESPN, search for each player and calculate their project fantasy score based on their last 10 game average using Excel</li>
  <li> Identify the players that have large disparities between their PrizePicks projections and ESPN projections</li>
  <li> Based on the disparities, make the Over/Under selection and win up to 10x your of whatever you gambled</li>
</ol>

Techniques used for this exercise include:

<ul>
  <li>Web Scraping With Selenium</li>
  <li>Using Dictionaries </li>
  <li>Looping over a list </li>
  <li>Looping over a dataframe </li>
  <li>Slicing a dataframe </li>
</ul>

Note: It typically scrapes the PrizePick site relatively fast. Make sure you give it some time and leave the browser open (and untouched) while it is scraping the NBA players' data on ESPN. This can take (3-5 minutes) depending on the number of players you scraped from ESPN.
