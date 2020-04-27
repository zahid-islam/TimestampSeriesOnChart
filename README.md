# TimestampSeriesOnChart
Importants Note: 
1. In backup DB data available between date range from 26th, April 2019 To 26th July 2019. Total Data 42200.
2. For searching data every field mandatory

Step to run project:
1. After cloning need to install npm package in both side, TimestampSeries is backend folder and TimeStampFrontEnd is front folder.
2. Need to restore backup of time_series Database in mongodb (restore command: mongorestore --db time_series (db downlaoded path))
3. Run the Back-End project by using "nodemon index.js", But firstly need to change direcotry to TimestampSeries
4. Run Front-End project by "ng serve --open", But need to change directory to TimeStampFrontEnd
5. Now search by Building, Object, DataField and Date Range, All these are mandatory to search.

TO DO: 
1. Need to validate date range select option within three month because there is no need to see 1 year data or two year data at a time.


Final screen shot attached above
