# Road Safety Data - Accidents 2018

## Description

Road accidents and their causes are of particular importance to road safety experts looking to prevent them. Data contains 768 observations of 31 variables.

## Variables

* `id` - Accident ID

* `easting` - Easting of accident location

* `northing` - Northing of accident location

* `longitude` -  Longitude of accident location

* `latitude`- Latitude of accident location

* `police_force`- Police force

* `severity`- Accident severity: Fatal, Serious, Slight

* `vehicles` - Number of vehicles involved in accident

* `casualties` - Number of people injured in the accident

* `date` - Date of the accident

* `day_of_week` - Day of the week of the accident

* `time` - Time of the accident on the 24h clock

* `district` - Local authority district

* `highway` - Local authority highway

* `first_road_class` - Class of 1st road involved in accident: Motorway, A(M) road (A-road with motorway restrictions), A-road, B-road, C-road, Unclassified

* `first_road_number` - ID of 1st road (0 if unclassified)

* `road_type` - Type of road: Roundabout, One way street, Dual carriageway, Single carriageway, Slip road

* `speed_limit` - Speed limit on the road in mph

* `junction_detail` - Detail on junction where accident occurred: Crossroads, Mini-roundabout, More than 4 arms, Not within 20 meters of junction, Other junction, Private drive or entrance, Roundabout, Slip road, T or staggered junction

* `junction_control` - How junction was controlled: authorized person, Auto traffic signal, Give way or uncontrolled, Missing / Out of range, Stop sign

* `second_road_class` - Class of 2st road involved in accident: A-road, B-road, C-road, Missing / Out of range, Motorway, Unclassified

* `second_road_number` - ID of 2nd road (0 if unclassified)

* `ped_cross_human` - Level of human control at a pedestrian crossing: Control by other authorized person, Control by school crossing patrol, None within 50 meters

* `ped_cross_physical` - Level of facilities controlling a pedestrian crossing: Central refuge, No physical crossing facilities within 50 meters, Non-junction crossing (pelican, puffin, toucan or similar light crossing), Pedestrian phase at traffic signal junction, Zebra crossing

* `light` - Light condition at the time of accident: Daylight, Darkness - lights lit, Darkness - lights unlit, Darkness - no lighting, Darkness - lighting unknown

* `weather` - Weather condition at the time of accident: Fine + no high winds, Raining + no high winds, Snowing + no high winds, Fine + high winds, Raining + high winds, Snowing + high winds, Fog or mist, Other, Unknown

* `road_surface` - Road surface conditions at the time of the accident: Dry, Wet or damp, Snow, Frost or ice, Flood over 3cm deep

* `special_condition` - Special condition at the site of the accident: None, Road sign or marking defective or obscured, Roadworks, Road surface defective

* `hazard` - Carriageway hazards: None, Other object on road, Previous accident, Pedestrian in carriageway - not injured

* `urban_rural` - Type of area the accident occurred in: 1 - urban, 2 - rural

* `police` - Did police officer attend the scene of the accident: No, No + accident self reported (using a self completion form), Yes

## Details

The data come from the UK Government at roadtraffic.dft.gov.uk. It's been modified to better serve the goals of introductory data science education.

Source - https://roadtraffic.dft.gov.uk/custom-downloads/road-accidents