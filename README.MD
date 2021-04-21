# 📹 Three CamParallax 🚤
A classic parallax movement handler for your ```THREE.Camera``` according to your mouse position

## Usage
```
import CamParallax from "PATH/CamParallax"

CamParallax.init(THREE.Camera)

renderLoop(){
    CamParallax.update()
}
```

## Doc
### CamParallax.isActive : Boolean
Enables/Disables the CamParallax
```Default : true```