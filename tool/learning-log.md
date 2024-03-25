# Tool Learning Log

Tool: **A-Frame**

 Installment- `<script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>`

---
03/2/24
*Step one- using [glitch](https://glitch.com/~aframe-basic-guide) to help myself?*
-watch some of the videos that it has to offer.
-saw some examples of some codes that can be previewd.
-visual learning to see how the code works
-seeing some previews using glitch since i can see the codes without a problem
---
  **-Went back to watch youtube videos step by step**
*Step two?-Learning from videos*
[playlist to A-frame learning basics](https://youtube.com/playlist?list=PL8MkBHej75fJD-HveDzm4xKrciC5VfYuV&si=F18tOmhkw-vy0lCu)
-to install/use
-setting up using `<a-scene>`
-changing up shapes/settin it up using codes like `a-box/a-cylinder`
-shape inside a shape?
-`Size,position,and scale` matters a lot.

   **Texture**
- `<src = "Texture img link.jpg">`
- colors matter in textures too to see how they would look like.
- `<a-assets>` to add for better quality texture results
- [textures-a place to find them would be this link ](https://www.textures.com/searchq=Brick)
- `normal-map,normal-texture-repeat,normal-scale` to make the
texture more apealing.
-scale can change the spes into hallow.
---
*Step three?*

-trying to follow along side the video to make sure I know
what im trying to do.
-trying to create a funky creature
-Finish the whole lesson on the youtube playlist
**thought this was harder then i thought 
but turns out its quite easy, i'm quite confident
I have the hand of this of creating shapes
and textures, with creating visual desgins to my freedom project which can be a great help.**

03/04/24:
*part2*
**continuing on with the video**
Notes
- using primitives to learn about curved images
- Radius of Arc
- Width of Arc - 1 m
- angle subtended by Arc = 90 deg
- Img height (m) = width (m)/IMG width (px) * IMG height (px)

3/16/24
**did some practice in my IDE**
`_https://turbo-waddle-979v9w6gpxq42pgxv-8080.app.github.dev/index.html_`
worked on 
-`<a-plane>`
-`a-image`
-`a-curvedimage`

```
<a-plane material= "src: yoduck.jpeg;
                   repeat: 5 5;
                   normal-map: #floor-NRM;
                   normaltexture-reapeat: 5 5"
roation="-99 0 0"
scale="10 10 1">


</a-plane>```

```<a-image src="yoduck.jpeg"
position="0. 1.5 -3"
width="1"
hieght="0.75"
scale="3 3 1">
 </a-image>
```

```
<a-curvedimage
 src="yoduck.jpeg"
theta-length="130"
theta-start="-90"
radius="0.7"
position="0 1.5 0">
</a-curvedimage>

```
-just made images smaller/stretch/or fitting into the adjustment
-Still have
Next step- learning how to set up a scene. 

![image](https://github.com/XueL6135/sep10-freedom-project/assets/146861517/4edb1120-ac91-4ff0-8cc9-22d25e5153b1)

practicing wiht every shape dimention i have.

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

**3.24.24**

## 360 ##
Codes for me to try out in my next practice.

```
<a-sky src="clear-sunny-sky
        radius="5"
        side="double"
        rotation="0 60 0">
       </a-sky>
```

# Camera primitive #
-the postiion of where your caera can be will be chnaged and can be changed by how you chnage them of how you can view the other elements.
-The object smay look normal to the adults, but to kids its very different considering that they are much shorter. (so thats the reason you need to change 
your camera height).
-You can have multiple cameras and you can choose which one do you want to select.

`<a-camera
  user-height="1.6"
  active="false">
</a-camera>
`

# loading an displaying 3d objects #
-you can use other 3d models that you can use.
-

```
<a-assets-item
  id="something" src="your scene/model" >
you can add more then one model in your assest itdem.
</a-assets-item>

<a-entity gltf-model="model".>
</a-entity

-USE ENTITY FOR IT TO SHOW UP FOR THE 3D MODEL

```
**3.25.24**

# Animating object #

## roatation ##
```
<a-box color="colors"
position="0 80 0">
 `<a-animation attribute="rotation/position"
              to="0 360 0"
              repeat="indefinite"
              dur="5000"
              easing="linear"
              direction="alternate"
              easing="ease-out or ease-out-bounce"
              >
  </a-animation>`
</a-box>
```

## Changing it from a specific color to this ##
```
 `<a-animation attribute="rotation/position/material.color"
              from-="specific color"
              to="specific color"
              repeat="indefinite"
              direction="alternate"
              dur="1500"
              easing="ease-out or ease-out-bounce"
              >
  </a-animation>`
```

# The cursor #
```
<a-entity>
   <a-cursor>
   </a-cursor>
</a-entity>
```
