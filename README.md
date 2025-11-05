# countryis
API for country.is IP info site
# Example
```nim
import asyncdispatch, countryis, json
let data= waitFor my_ip()
echo data["ip"].getStr()
echo data["country"].getStr()
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
