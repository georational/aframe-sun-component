# aframe-sun-component
####[A-Frame](https://github.com/aframevr) component wrapper for [three.js](https://github.com/mrdoob/three.js) atmosphere shader
   
   
   
#### Usage
``` <a-sun intensity="1" inclination="23.5" azimuth="0" /> ```
Creates skybox with atmospheric shading and directional lighting   



|Property|Default|Description| 
|---|---|---|
|intensity|1|   | 
|inclination|23.5|   | 
|azimuth| 0 |   | 
|turbidity|   |   | 
|rayleighCoefficient|   |   | 
|mieCoefficient|   |   | 
|mieBias|   |   |   

---
####To do   

* convert attributes to degrees 
* attach shader 
* attach sky sphere
* attach directional light and register with lighting system
* let colour of sun disc drive the directional light colour
* derive cube map from sun component

***
Atmospheric scattering shader for GLSL based on work by Arcot Preetham, [@renderwonk](https://twitter.com/renderwonk?lang=en-gb), [Simon Wallner](https://github.com/SimonWallner), [martinsh](https://github.com/martinsh), [@blurspline](https://github.com/zz85) et al.  

Further reading  
[http://amd-dev.wpengine.netdna-cdn.com/wordpress/media/2012/10/ATI-LightScattering.pdf](http://amd-dev.wpengine.netdna-cdn.com/wordpress/media/2012/10/ATI-LightScattering.pdf)  
[http://http.developer.nvidia.com/GPUGems2/gpugems2_chapter16.html](http://http.developer.nvidia.com/GPUGems2/gpugems2_chapter16.html)  
