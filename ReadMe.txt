Python 3

Libraries:
datetime
pytz
requests
json
pandas

Purpose:
Downloading data from API as json file. 

After running the script, function ticketmaster_info() must be called
 - with parameters:
* api key, 
* start date 
* end date 

Example:
ticketmaster_info(api_key="enteryourapikey",start_date="2019-07-13T14:00:00Z", end_date="2019-07-15T14:00:00Z")

Above example is showing correct formatting for dates. None of the parameters are optional - all are required to run the function.
