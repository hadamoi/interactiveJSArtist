# 💿 mousemove ver.1
The image on the screen is affected by the movement of the user's mouse, causing the image to move in the opposite direction. 

#### ✔️ Things to remember
```
requestAnimationFrame(loop)
```
* When you call the `requestAnimationFrame()` function, the browser receives a callback function that will run just before the animation frame is rendered.
* This callback function is usually used to calculate the next frame of the animation and update the screen.
To provide a smooth and natural animation effect, the browser sets the optimal frame rate based on the monitor's refresh rate.
* Typically, the refresh rate of a monitor is 60 frames per second, so using `requestAnimationFrame()` will result in 60 updates per second. This helps improve the performance of your web animations and improves the user experience.
