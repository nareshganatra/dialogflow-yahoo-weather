# Dialogflow - sample webhook implementation in Python

This is a really simple webhook implementation that gets dialogflow classification JSON (i.e. a JSON output of Api.ai /query endpoint) and returns a fulfillment response.

More info about dialogflow webhooks could be found here:
https://dialogflow.com/docs/fulfillment

# What does the service do?
It's a weather information fulfillment service that uses [Yahoo! Weather API](https://developer.yahoo.com/weather/).
The services takes the `geo-city` parameter from the action, performs geolocation for the city and requests weather information from Yahoo! Weather public API. 

The service packs the result in the Api.ai webhook-compatible response JSON and returns it to Api.ai.

app.py is for Dialogflow v1 

app_v2.py is for Dialogflow v2



## License
See [LICENSE](LICENSE).

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/).

## Orignal github source
api.ai yahoo weather example fro Github

This is not an official Google product
