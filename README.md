# WeChat



Type  | Value
----------- | -------------
Source | https://twitter.com/0xDUDE/status/1107793510881742848
Description | 1.081.231.257 captured WeChat dialogues containing 3.784.309.399 messages dated 18 March 2019 were automatically selected for review based on a keyword trigger. Not all the dialogues were in Chinese or only had GPS coordinates in China.

## Project files:
 * MongoDB db.stats() `db.tencent.stats()`
 * MongoDB db.collection.stats() `db.tencent.wxmsg_20190318.stats()` 
 * MongoDB export `mongoexport --db tencent --collection wxmsg_20190318 --out wxmsg_20190318.json`
 * Grep [output](https://drive.google.com/open?id=19ce7MhhDqmOkwIP9cI0nijbNpA_ojzzK)
 * Recovered [Jupyter notebook files]()
 * [Keywords](https://github.com/GDI-foundation/WeChat/blob/master/keywords.txt) used and found in the [wxmsg_20190318.json]() export file. 

## JSON tools
 * [JQ](https://stedolan.github.io/jq/)
 
