# theFOODIEscript
A script for Zomato [Zomato is an Indian multinational restaurant aggregator and food delivery company founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants as well as food delivery options from partner restaurants in select cities.]. Automates the process of finding the best restaurant nearby, and also finds the restaurants that offer the best deals for a particular dish.

## Install the required modules first.

`pip install -r requirements.txt`

## Usage

`python thefoodie.py <command-line options and arguments>`
### Command line options
* --city -> **Required**. Mention your city
* -c     -> **Optional**. Mention your cookie file. Default is *cookies.json*
* --categories -> **Optional**. Mention the categories of restaurants you want to search for.
* --dishes -> **Optional**. Mention the dishes you want to search for.

### Examples
#### Searching without any categories and dishes (All restaurants around you sorted from "best" to "not too good")
`python thefoodie.py -c "cookies.json" --city "guntur"`
OR
`python thefoodie.py --city "guntur"`

#### Searching with categories
`python thefoodie.py --city "guntur" --categories "lebanese,fast food"`

#### Searching for particular dishes
`python thefoodie.py --city "guntur" --dishes "chicken dum biryani"`

