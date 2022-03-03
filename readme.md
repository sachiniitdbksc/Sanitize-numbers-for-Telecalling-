# Sanitizing numbers copied from Google Maps
The numbers obtained from copying from Google maps are in this format
+91-88888-88888
8888-88-8888
i.e. with spaces and +91 ISD code in front of them

so the inut string is newLine separated numbers of any size
+91-88888-88888
8888-88-8888
8888888888

and we want output 
8888888888
8888888888
8888888888


We want this application to be used by Tech-Dumb "Data extractor workers" to sanitize data which in turn was obtained from the mobile app Clipboard Manager from Google Maps 
https://play.google.com/store/apps/details?id=devdnua.clipboard 

So we created an HTML file which can be sent to these workers and they use this to sanitize data before sending to company. Rather than making a full blown android app
or Desktop app, we found this to be a solution which can be made faster.
