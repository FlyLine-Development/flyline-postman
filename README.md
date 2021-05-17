# flyline-postman
Postman collection for the Flyline API


## Getting Started
Follow these steps to quickly get started with the [Flyline API](https://staging.flyline.io/api-ref/welcome/):
1. [Sign up](https://flyline.io/signup) with Flyline to get a API key that is required for interacting with the API.
2. Download and install the [Postman app](https://www.getpostman.com/downloads/)
3. Install the Flyline Postman Collection. Click the "Run in Postman" button below to install the Flyline collection!

    [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/7566436-a0f8d2e8-5b4f-4ec9-93bc-093d6a352910?action=collection%2Ffork&collection-url=entityId%3D7566436-a0f8d2e8-5b4f-4ec9-93bc-093d6a352910%26entityType%3Dcollection#?env%5BFlyline%5D=W3sia2V5IjoiQkFTRV9VUkwiLCJ2YWx1ZSI6Imh0dHBzOi8vYXBpLmZseWxpbmUuaW8iLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkZUb2tlbiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJBaXJjcmFmdElhdGFDb2RlIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkFpcmxpbmVJYXRhQ29kZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJBaXJwb3J0SWF0YUNvZGUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiQ2l0eUlhdGFDb2RlIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImRlcGFydHVyZURhdGUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoicmV0dXJuRGF0ZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJkZXBhcnR1cmVUaW1lIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImFycml2YWxUaW1lIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImZsaWdodG5vIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfV0=)
4. Once both the collection and the environment variables are imported into Postman, see the [Configuration](https://github.com/FlyLine-Development/flyline-postman#configuration) section on how to correctly configure the API key with the collection.

### Configuration
The Flyline Postman collection uses [Postman environment variables](https://learning.getpostman.com/docs/postman/environments_and_globals/intro_to_environments_and_globals/) to simplify each API request. More information on managing Postman environments can be found at [Setting up an environment with variables](https://learning.getpostman.com/docs/postman/environments_and_globals/manage_environments/).

![flyline-postman-configuration](/images/postman-config.png)

1. Select the `Flyline` environment in the top right corner
2. Click the `eye` icon to open the environment settings
3. Copy in your [Flyline API key from your Flyline Dashboard](https://flyline.io/dashboard/access-tokens), into `FToken` field.
4. Save your changes and start making Flyline API requests!
## Collection endpoints
The following collection is a fully-featured set of pre-filled requests that allow you to test the [Flyline API](https://staging.flyline.io/api-ref/welcome/), and visualize the responses in a friendly format.
### Airfare API

### Data API
* **Aircraft Data API**
    * **List Aircraft** - Retrieves a paginated list of all supported aircraft
    * **Get Aircraft** - Retrieves information of an aircraft by its iata code


* **Airline Data API**
    * **List Airlines** - Retrieves a paginated list of all supported airlines
    * **Get Airline** - Retrieves information of an airline by its iata code


* **Airport Data API**
    * **List Airports** - Retrieves a paginated list of all supported airports
    * **Get Airport** - Retrieves information of an airport by its iata code
    * **Get Airports By City** - Retrieves a list of airports in a city specified city iata code

* **City Data API**
    * **List Aircraft** - Retrieves a paginated list of all supported cities
    * **Get Aircraft** - Retrieves information of a city by its iata code


* **Cabin Class Mapping Data API**
    * **Get Cabin Class Mapping** - Retrieves cabin class and booking class mapping


* **Air Amenities Data API**
    * **List Seats** - Retrieves a paginated list of all supported seat
    * **List Seat Layouts** - Retrieves a paginated list of all supported seat layout
    * **List Foods** - Retrieves a paginated list of all supported foods
    * **List Beverages** - Retrieves a paginated list of all supported beverages
    * **List Entertainments** - Retrieves a paginated list of all supported entertainments
    * **List Wifis** - Retrieves a paginated list of all supported wifis
    * **List Powers** - Retrieves a paginated list of all supported powers
