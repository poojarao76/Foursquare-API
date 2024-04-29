# Foursquare-API

## Introduction:

In this lab, you will learn in detail how to make calls to the Foursquare API for various purposes. You will learn how to construct a URL to send a request to the API to search for specific types of venues and explore particular venues.

## Prerequisites:

Before getting started, ensure you have installed the following packages:

* **python-dotenv:** This package allows you to load environment variables from a .env file into your Python script.
  
* **geopy:** This package provides an easy-to-use interface to geocoding services like Nominatim.

## Setting Up Environment Variables:

To securely store your Foursquare API credentials, you can create a .env file and add them there. This helps to keep sensitive information out of your codebase.

## Loading Environment Variables:

After creating the .env file, you can load the environment variables into your Python script using the load_dotenv() function from the dotenv module.

## Getting Location Coordinates:

Before making requests to the Foursquare API, you often need to convert an address into latitude and longitude coordinates. The Geopy library provides a convenient way to do this using various geocoding services.

**1. Search for a Specific Venue Category:**

To search for venues of a specific category (e.g., Italian food), you construct a URL with the appropriate parameters and send a GET request to the Foursquare API. The response contains information about the venues matching your search criteria.

After receiving the response, you can extract the relevant information and transform it into a structured format, such as a pandas DataFrame.

**2. Explore a Given Venue:**

Once you have identified a specific venue you're interested in, you can explore it further by sending a request to the API with the venue's unique identifier (venue ID). This allows you to retrieve additional details about the venue, such as its rating, contact information, and user reviews.

## Libraries Used:

* **python-dotenv:** For loading environment variables from a .env file.
  
* **geopy:** For converting addresses into latitude and longitude coordinates.
  
* **requests:** For making HTTP requests to the Foursquare API.
  
* **pandas:** For data manipulation and analysis.
  
* **json_normalize:** For flattening JSON data into a pandas DataFrame.

## Foursquare API Documentation:

For more information about the Foursquare API and its capabilities, visit the official Foursquare Developers website: [Foursquare Developers](https://foursquare.com/developers/orgs/662ca6b22bdfc50520afbefa/projects/662ca6b32bdfc50520afbf0a/settings)

By leveraging these libraries and the Foursquare API, you can efficiently interact with location-based data and extract valuable insights for various applications.

## Author

**Pooja Rao**
