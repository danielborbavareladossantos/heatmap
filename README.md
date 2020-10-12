# This project uses the google maps library to work

The idea is to capture data from the TRE and visualize it on a heat map.

For data capture I used a node selenium project which is also here on my github, I also use the Google geolocation api to capture the latitude and longitude of the areas.
https://github.com/danielborbavareladossantos/webScrapingLocaisTre

![alt text](https://github.com/danielborbavareladossantos/heatmap/blob/main/docs/image-1.png?raw=true)
![alt text](https://github.com/danielborbavareladossantos/heatmap/blob/main/docs/image-2.png?raw=true)
![alt text](https://github.com/danielborbavareladossantos/heatmap/blob/main/docs/image-3.png?raw=true)

# Google Maps JavaScript API Sample Application

This sample is generated from @googlemaps/js-samples located at
https://github.com/googlemaps/js-samples.

## Setup

```sh
npm i
npm run dev  # development
npm run build  # production
```

The application is currently using the `.env` file to embed the API key in the
HTML document. This is a temporary key and is not valid for production usage. It
can be replaced by following these instructions to
[get an api key](https://developers.google.com/maps/documentation/javascript/get-api-key).

## Feedback

For feedback related to this sample, please open a new issue on
[GitHub](https://github.com/googlemaps/js-samples/issues).
