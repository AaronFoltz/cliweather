You must have a recent version of Python installed (2.6-3.0)

To use this system-wide, make this application executable by doing:

	chmod +x cliweather

Then move this application to /usr/bin

	mv cliweather /usr/bin


This utility offers two views, one of the current conditions, and another of the forecast

For either view, you can choose to leave out your zip code, and a geolocation service will try to pinpoint it.

To see the forecast, add the "-f" flag like:

	cliweather -f

If you want to include your zip code:

	cliweather -f 20171

To see the current conditions, no flag is needed:

	cliweather

If you want to include your zip code:

	cliweather 20171

If you want to set a default location:

  echo "20171" > ~/.cliweather

