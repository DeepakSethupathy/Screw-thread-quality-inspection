# Screw-thread-quality-inspection
Screw thread quality inspection using image processing. This can be used for automating the quality check of screws which would improve the 
outgoing quality level.

Parameters measured: Pitch, major diameter, minor diameter, depth of thread, length of screw, collor diameter, head length

## Output Images

![screw11](https://user-images.githubusercontent.com/60769429/86892667-2dcfe380-c11e-11ea-9db8-059fde62c40b.jpg)
Bolt's pic caught by phone camera


![canny extracted](https://user-images.githubusercontent.com/60769429/86892828-653e9000-c11e-11ea-84a8-21b69ed6fe50.jpg)

Outline of the screw extracted using canny edge detection algorithm and extracting only the outline pixels


![midp](https://user-images.githubusercontent.com/60769429/86893046-af277600-c11e-11ea-9970-80926a880b3b.jpg)

Midpoint line between upper and lower profile

![root crests](https://user-images.githubusercontent.com/60769429/86893121-cc5c4480-c11e-11ea-9821-23918b112ade.jpg)

Extracting the roots and crest based on direction change

![acrflt](https://user-images.githubusercontent.com/60769429/86893207-e6962280-c11e-11ea-875b-6026ebe41d0d.jpg)

Bolt head measurements





