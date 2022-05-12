# NetCreator v1.3.1
Updated to work with Cinema 4D release 26. (Tested on R26.014 Macintosh.)

https://storage.googleapis.com/charlierobin-1245.appspot.com/videos/work/NetCreatorDemo.mp4

## Better README from v1.3 source code

NetCreator V1.3.0

Copyright: Lewis Orton, https://www.behance.net/gallery/38292207/NetCreator-v11-Cinema-4D-plugin
Author:    Lewis Orton
License:   GPL-3.0 License

Name-US: NetCreator
Description-US: Cinema 4D plugin for creating linking-splines effect.

Description:

- NetCreator is an open-source Cinema 4D plugin, working as a Generator Object inside C4D. it can generate splines based on different kinds of objects. 
- NetCreator’s user interface should be very self-explanatory, all parameters would be available only when they’re allowed to. 

Features:

1. Two modes. You can choose to generate splines on one object or between two objects.
2. Supports polygonal object, Thinking Particles, MoGraph objects (including Cloner Object, Matrix Object, Fracture Object, MoText Object). For MoGraph Object, NetCreator uses MoGraph Object’s elements’ positions to generate splines. And you can use effector to control Matrix points’ visibility, which opens lots of possibilities.
3. VertexMap support for polygonal object. NetCreator will only generating splines on points that have weights larger than 0.5 in assigned VertexMap.
4. Distance and Visibility control. You can randomly remove points that are used to generate splines, or animating this process.
5. Propagation for VertexMap. You can paint on part of VertexMap, and with this feature turned on, NetCreator will automatically create propagation effect for vertexmap, with fast algorithm. You can also use this feature alone to get an animating vertex map for other purposes in Cinema 4D.


Tutorial:

V1.0-V1.2: https://www.behance.net/gallery/38292207/NetCreator-v11-Cinema-4D-plugin

V1.3: http://www.wise4d.com/netcreator-v1-3-plugin-is-now-compatible-with-cinema-4d-r23/

ChangeLog:

Jan/1/2016 V1.0 (by Lewis Orton)
- Release Version

Nov/22/2016 V1.1.1 (by Lewis Orton)
- Fixed issue where selection was scaled down

Oct/21/2020 V1.3 (by Dr. Aaron Feng)
- Fixed runtime issue in R19 R20 R21 R22: there is an error information when parameter “Propagation” be available: AttributeError: type object ‘c4d.plugins.NodeData’ has no attribute ‘GetDEnabling’Traceback (most recent call last).
- Fixed Issue where parameter “Strength” and “Size” could not coordinate unavailable as parameter “Turbulence” is unchecked.
- Fixed Issues of the plugin can not work in R23: now NetCreator could perfectly compatibility with Cinema 4D R23.
- Increase parameter “Factor” in order to accurate adjustment the speed of Propagation for VertexMap if the propagation process is too fast. 

Compatible:

- Win / Mac
- R13, R14, R15, R16, R17, R18, R19, R20, R21, R22, R23


## NetCreator v1.3
Cinema 4D plugin for creating linking-splines effect.

For more information please check:

V1.0-V1.2: https://www.behance.net/gallery/38292207/NetCreator-v11-Cinema-4D-plugin
V1.3:      http://www.wise4d.com/netcreator-v1-3-plugin-is-now-compatible-with-cinema-4d-r23/

## NetCreator v1.1.1
Cinema 4D plugin for creating linking-splines effect.

For more information please check https://www.behance.net/gallery/38292207/NetCreator-v11-Cinema-4D-plugin
