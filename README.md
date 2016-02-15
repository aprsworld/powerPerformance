# powerPerformance

## validUpdate
validUpdate sets the valid flag on each measurement where valid is null. Site criteria is coded into the program for things like DAS run time, wind direction sector, anemometer comparion.

This script will need to be run before analysis is done on the data. It can be run once a minute using the following crontab entry:
'''* * * * * /home/aprs/powerPerformance/validUpdate'''
