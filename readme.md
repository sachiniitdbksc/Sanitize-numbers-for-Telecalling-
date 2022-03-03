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
