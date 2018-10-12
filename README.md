# Idea for codefundo++

## What are you planning to build?
>> We are planning to develop a prediction system for Natural Disasters. It will also show the safest path to evacuate the affected area.

## How does it work?

>> We primarily use the datasets of the past occurrences of a Natural Disaster. Each location has two critical parameters here: Distance index from the centre (DI) and Time Period index(TI).  Most calamities have a point of origination. 

>> For example the epicentres of an earthquake. We will use these centres and draw circles from it. The centre will have the maximum value of DI and it will diminish as we move towards the circumference. Each such circle has its own DI. The DI of a location will be the sum of DIs of the circles it lies in.

>> Calamities also have an approximate Time after which they tend to reoccur. The TI of a circle would be maximum at the time of occurrence and will be maximum again when it occurs for another time. TI will be minimum between these two consecutive occurrences. This gives us DI and TI for a location. The probability of the area being affected is a function of these parameters and would vary with time. The evacuation path would lead people from the regions with the least probabilities.

## How can users get started with the project?
>> Users can get introduced to the web app through news channels. Accessing this site would show them the probability of being hit with a calamity and also the safest path to evacuate.

## What dataset(s) are you using?
>> Floods: http://www.gdacs.org/flooddetection/download.aspx

>> Earthquakes: http://opendtect.org/osr/

>> Additional datasets of other calamities as required

## What technologies are you using?
>> JavaScript, jQuery, BootStrap 4

>> Azure Database, Azure AI services
