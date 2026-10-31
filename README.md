# Aviation Data Scrapper
This repository is used to fetch data from opensky-network.

## Tech Stack
Python + Docker

## Core Logic
1. Get data from https://opensky-network.org/api/states/all?amin=-11&lamax=21&lomin=92&lomax=141
2. Use the epoch time from JSON as the file name with query parameters to keep the as much as information as possible.
