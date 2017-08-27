## What
A Python script to read nginx access logs and offer a basic summary on popular cities, countries, and pages.

## Why
I'd like to avoid client-side scripts and trackers. Parsing the nginx logs gives enough information on popular pages and locales.

## How
Dependencies:  
geoip2: https://github.com/maxmind/GeoIP2-python/  
The geoip city database: https://dev.maxmind.com/geoip/geoip2/geolite2/  

Configuration:  
access_file_path: The path to the nginx access log you want to parse  
geoip_file_path: The path to the Geoip mmdb file  
time_period_days: The time period in days you'd like to parse data for  

## License
MIT 
