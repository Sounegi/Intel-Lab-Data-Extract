# Intel-Lab-Data-Extract
project to extract the data from Intel Lab Data, for easy search and use in the future.

## Main Aims
This project aims to
1. provide search function from available information in each row.
2. show trend by plotting filtered data.
3. extract the filtered data into csv. format for further usage.

## Raw Data Format
---
| date (yyyy-mm-dd) | time (hh:mm:ss.xxx) | epoch (int) | mote (int) | tempurature (real) | humidity (real) | light (real) | voltage (real} |
---
## Data Collection Information
Sensor: Mica2Dot sensors with weather boards.
Information Collected: topology information, along with humidity, temperature, light and voltage values.
Data Collection Inteval: once every 31 seconds.
Database System for Data Collection:  TinyDB in-network query processing system, built on the TinyOS platform.
