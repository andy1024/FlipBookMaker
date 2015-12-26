FlipBookMaker
=============

Flip book making tool


combine movie frames into a series of matrices of pictures

it can be used to make flip book animations

optionally draws a separator line
```
youtube-dl.exe https://www.youtube.com/watch?v=nPrWo5pEvyk
ffmpeg.exe -i "High Diving Giraffes-nPrWo5pEvyk.mp4" -r 1 -f image2 -s 192x108 exp2\image-%05d.png
javac FlipBookMaker.java
java FlipBookMaker
```

(Still unfinished, because of unimpressive results produced by monochrome laser printer)
