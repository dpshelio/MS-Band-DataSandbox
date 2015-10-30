# MS-Band-DataSandbox
Simple WPF app which uses the MS Health Cloud API to download user-specified data sets acquired with the Microsoft Band. 

If you're only interested in the executable, it is here:
https://github.com/dendriticspine/MS-Band-DataSandbox/raw/master/BandSandbox1.0.zip

Information on using the Microsoft Health Cloud API:
https://developer.microsoftband.com/cloudAPI

Note: The code is ugly. I mean, really, really ugly. Yes, I feel shame. 

- Daily and Hourly summaries can take a while to download, especially if you're downloading a complete history, but you should be able to see progress being made via the app/URL/data status notifications.
- Downloading activity summaries might have more lag between requests, so it might look like the app is doing nothing -- if you haven't received an error, it's probably still working in the background.
- If you've selected the Details/GPS or Minute Summary options, it will probably be very, very slow between requests. This seems to be the case regardless of how I segment the data received. Downloading a year's worth of Activity Details/GPS Data for all activities took about 30 minutes for me.
- If you receive an error for making too many requests, wait a few minutes before trying again. 

If you have any questions or problems: apps@dendriticspine.com
