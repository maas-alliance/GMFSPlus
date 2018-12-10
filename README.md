# GMFS+ | General Mobility Share Feed Specification Plus
This is a proposal based on GBFS+ to extend the principles of GBFS to all mobility solutions (bikes, cars, station-based, free floating,...).

## Preface
...:

## The standard: GBFS+ 

1. __GBFS__ 
..

2. __Deep links, Add rental_url to free bikes and stations__
... There is already a change-requests (from others) for an extension of the standard, covering exactly our wishes. So we include request #25 in GBFS+, which enables deep links.

3. __Type_of_system__
... We will add type_of_system in the “system info” file. Allowed values are [free_floating, station_based, virtual_station_based]

4. __Type_of_vehicle__
... We add a file “Types_of_bikes” which describes the different bike types (type_id, name, gears, electric, description, img_url)
In free-bike-status file we add the field type_of_bike
(our first proposal on OpenBikeShare Github)  

5. __TTL__
... The time to live (TTL) for real-time data feeds will be at most 30s, so that traveller has always the most actual information about the availability of bicycles.

## Recommendations

 
