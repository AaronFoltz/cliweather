You must have a recent version of Python installed (2.6-3.0)

To use this system-wide, make this application executable by doing:

	chmod +x weather

Then move this application to /usr/bin

	mv weather /usr/bin


This utility offers two views, one of the current conditions, and another of the forecast

For either view, you can choose to leave out your zip code, and a geolocation service will try to pinpoint it.

To see the forecast, add the "-f" flag like:

	weather -f

If you want to include your zip code:

	weather -f 20171

To see the current conditions, no flag is needed:

	weather

If you want to include your zip code:

	weather 20171

If you want to set a default location:

  echo "20171" > ~/.cliweather

