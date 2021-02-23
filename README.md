# Cobalt Beacon Deobfuscator
This script tries to deobfuscate base64 beacon from Cobalt Strike tool. You have to modes to execute this script. You can provide a base64 to deobfuscate or you can write the base64 string into a file and pass it to the script.

## Usage

#### Option --base64:
```
python3 deobfuscateCobalt_beacon.py --base64 JABzAD0ATgBlAHcALQBPAGIAagBlAGMAdAAgAEkATwAuA...A0AHUAYgB1AHIAOAB1AGYAYQBOAE8AbQBqADIAbQBmAEUAYgBOAFUARQBHAGcAbgBIADcAYgBvAEIAMQB5AEYASQBFADgAMQBjAG0ATwBoAGUAUwBFAGMAUABaADMANABXAEQAVwBDAGoALwBEAFEAQQBBACIAKQApADsASQBFAFgAIAAoAE4AZQB3AC0ATwBiAGoAZQBjAHQAIABJAE8ALgBTAHQAcgBlAGEAbQBSAGUAYQBkAGUAcgAoAE4AZQB3AC0ATwBiAGoAZQBjAHQAIABJAE8ALgBDAG8AbQBwAHIAZQBzAHMAaQBvAG4ALgBHAHoAaQBwAFMAdAByAGUAYQBtACgAJABzACwAWwBJAE8ALgBDAG8AbQBwAHIAZQBzAHMAaQBvAG4ALgBDAG8AbQBwAHIAZQBzAHMAaQBvAG4ATQBvAGQAZQBdADoAOgBEAGUAYwBvAG0AcAByAGUAcwBzACkAKQApAC4AUgBlAGEAZABUAG8ARQBuAGQAKAApADsA
```
#### Return value
```
[2021-02-23 18:10:00,928][INFO]: Possible C2: winappsearch.com
[2021-02-23 18:10:00,929][INFO]: Possible User-Agent:  Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko
[2021-02-23 18:10:00,930][INFO]: Possible endpoints: ['/9u', '/a6uPa', '/5', '/7', '/X']
```

#### Option --file
```
python3 deobfuscateCobalt_beacon.py --file examples/beacons.txt
```
