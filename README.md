# GeoTools
 set of dockerized and fast deployable tools for the digital cartographer.
 
 You need vagrant and virtual box installed. If windows host, you need rsync as well. You can install sygwin which provides rsync among other unix tools.<br>
 Just git clone, or download as zip. Then, run "vagrant up" inside the vagrant folder.
 That's it! 
 
 You tilehut server is running on <br>
 http://localhost:80000<br>
 To access demo maps, try:
 http://localhost:8000/tiles-world-simple/map/<br>
 http://localhost:8000/tiles-world-vector/map/<br>
 http://localhost:8000/tiles-world-utfgrid/map/<br>
 
  You can put .MBTiles maps on the "TilehutMaps" folder in order to see them in tilehut.
 
 Your timemill server is running on <br>
 http://localhost:20008<br>
 http://localhost:20009<br>
 You can put files in "TilemillMaps" in order to access them from tilemill.
 
 #Sources
 Tilehut source: https://github.com/b-g/tilehut<br>
 Tilemill source: https://github.com/mapbox/tilemill
 
 Hope you enjoy!
