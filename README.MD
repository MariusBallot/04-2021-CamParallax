# :video_camera: Floating Cam :boat:
A simple class to quickly make your camera float arround the screen according to your mouse

## Usage
```
floatingCam = new FloatingCame(THREE.camera)
document.addEventListener('mousemove', floatingCamera.moveCam)

function update(){
    floatingCam.update()
}
```