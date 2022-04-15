# MarebolDB-spwn
MarebolDB API for SPWN

# Usage
```
let MarebolDB = import MarebolDB
let db = MarebolDB("45da8293-13d5-48fe-a691-e4da8e40ce7e")
db.set("Hello", "World!")
$.print(db.get("Hello"))
```
