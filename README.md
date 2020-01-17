# cloudynights
Script to analyze airport weather data to visualize changes over time in cloudy nights for a given location.

This Jupyter notebook was created for the purpose of analyzing trends in astronomical observing conditions for a given location.

Local data for cloudiness is hard to find, but airports have it! It queries the Iowa Environmental Mesoset hosted by
Iowa State University for historical hourly METAR weather reports, filters them for nighttime observations, categorizes
them into clear and not-clear observations, and aggregates them to the time periods of your choice. Finally it produces
a pretty graph that will unveil local climate changes that affect astronomical observing.

Disclaimer: I am not a climate scientist nor a professional astronomer. No warranty that this data is correct, although I
think it is.

See the comments in the notebook for further guidance.
