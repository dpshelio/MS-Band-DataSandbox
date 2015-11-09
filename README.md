# MS-Band-DataSandbox
Simple WPF app which uses the MS Health Cloud API to download user-specified data sets acquired with the Microsoft Band. 

If you're only interested in the executable (updated 2015/11/06), it is here:
https://github.com/dendriticspine/MS-Band-DataSandbox/raw/master/BandSandbox-current.zip

Information on using the Microsoft Health Cloud API:
https://developer.microsoftband.com/cloudAPI

Note: The code is ugly. I mean, really, really ugly.

Time for requesting 1 year+5 days (572 activities) worth of...
Hourly Summary Data: 8 min, 31 sec
Daily Summary Data: 28 sec
All Activities: Basic Activity Summary Data: 19 sec
All Activities: GPS Data & Segment Details: 6 min, 34 sec
All Activities: Minute Interval Summaries: 18 min, 42 sec <- required additional delays between requests to avoid being throttled for going over the bandwidth limits.

Updates:
- 2015/11/01: The beginnings of some rough Python scripts for plotting Daily Summary, Hourly Summary, and Activity Summary data are here: https://github.com/dendriticspine/HealthData-Analysis
- 2015/11/06: Added rate limiting to avoid being throttled by MS health cloud for too many requests/too much bandwidth.

If you have any questions or problems: apps@dendriticspine.com
