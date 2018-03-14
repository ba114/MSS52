# MSS52
Development of RomRaider definitions for MSS52 variant 1701.

Only 1701 (Hardware ID 7843317) will officially be supported by these definitions.

Requests to merge definitions for any other variants will be rejected.

To determine both the DME variant by the 16-byte version ASCII string located at offsets 0x7FB8. This will contain a series of characters such as ‘xxxxxxxx1701xxxx’ and should be repeated in triplicate, though technically only bytes 8 to 12 are necessary to make the proper determination.

