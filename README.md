# ios_scripts
Scripts for IOS widgets to display data from Thingspeak

Please read the PDF file, here you will find the description for the setup.

In the file test_more.js two more parameters have to be passed for drawing the graph. Between the parameters min and max the graph will be drawn. In the original file starter_original.js the values for scaling were obtained from the supplied data. This is not advantageous for a meaningful representation.

These parameters are passed separately with "|".

Example:   1278463|1|results=30|0|100

* Channel ID
* Field
* Number of records
* Bottom line
* top line

The example represents all values in the scaling 0 to 100.
The color of the graph can be changed in line 54.
