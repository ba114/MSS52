# MSS52
Development of RomRaider definitions for MSS52 variant 1601.

Only variant 1601 (Hardware ID 7843317) will officially be supported by these definitions. If you are running any other version, you will need to upgrade/downgrade as appropriate.

Requests to merge definitions for any other variants will be rejected.

DME variant is determined by the 16-byte ASCII string located at offsets 0x7FB8. This will contain a series of characters such as ‘xxxxxxxx1601xxxx’ and should be repeated in triplicate. Only bytes 8 to 12 of the first occurrence of this string are necessary to make the proper determination.

If my work proves helpful to you, donations are appreciated. I will contribute a percentage of any donations to the ms4x dev team as without them, the ecu definitions would not be at the maturity that they currently are. 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?hosted_button_id=TFWBHH4WEEHAU)
