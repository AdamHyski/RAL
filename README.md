# RAL
Ral colour plate
with multiple language colour names


done by this regex
```regex
RAL\s(\d{4})\n([\d-]*)\s(\#.{6})\s\n(.*)\n(.*)\n(.*)\n(.*)\n(.*)\n(.*)
"$1":{"rbg":"$2","hex":"$3","de":"$4","en":"$5","fr":"$6","es":"$7","it":"$8","nl":"$9"},
```
