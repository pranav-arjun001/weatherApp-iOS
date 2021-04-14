#  Clima

## Goal

Introducing you to the wonderful world of Application Programming Interfaces (APIs) to grab live data from the internet.


## What I have created

A beautiful, dark-mode enabled weather app. You'll be able to check the weather for the current location based on the GPS data from the iPhone as well as by searching for a city manually. 

## What I have learned

* How to create a dark-mode enabled app.
* How to use vector images as image assets.
* Learnt to use the UITextField to get user input. 
* Learnt about the delegate pattern.
* Swift protocols and extensions. 
* Swift guard keyword. 
* Swift computed properties.
* Swift closures and completion handlers.
* Learnt to use URLSession to network and make HTTP requests.
* Parsed JSON with the native Encodable and Decodable protocols. 
* Learnt to use Grand Central Dispatch to fetch the main thread.
* Learnt to use Core Location to get the current location from the phone GPS. 


### Condition Codes
```
switch conditionID {
        case 200...232:
            return "cloud.bolt"
        case 300...321:
            return "cloud.drizzle"
        case 500...531:
            return "cloud.rain"
        case 600...622:
            return "cloud.snow"
        case 701...781:
            return "cloud.fog"
        case 800:
            return "sun.max"
        case 801...804:
            return "cloud.bolt"
        default:
            return "cloud"
        }
```
## Sample JSON Response
```
{
"coord": {
"lon": 13.4105,
"lat": 52.5244
},
"weather": [
{
"id": 803,
"main": "Clouds",
"description": "broken clouds",
"icon": "04d"
} ],
"base": "stations",
"main": {
"temp": 3.85,
"feels_like": -1.23,
"temp_min": 2.78,
"temp_max": 5,
"pressure": 1005,
"humidity": 70
},
"visibility": 10000,
"wind": {
"speed": 7.72,
"deg": 270
},
"clouds": {
"all": 75
},
"dt": 1617702451,
"sys": {
"type": 1,
"id": 1262,
"country": "DE",
"sunrise": 1617683323,
"sunset": 1617731303
},
"timezone": 7200,
"id": 2950159,
"name": "Berlin",
"cod": 200
}
```