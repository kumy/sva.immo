# Optimize images

```
jpegoptim --size=150k *.jpg

for i in *.jpg; do convert $i -gravity SouthEast -pointsize 16 -font Helvetica -fill "#fffdc3" -annotate +10+10 "Photo M. Vercellino" $i; convert $i -gravity SouthWest -pointsize 16 -font Helvetica -fill "#fffdc3" -annotate +10+10 "https://sva.immo" $i; done
```
