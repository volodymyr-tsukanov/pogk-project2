# Etap3 animation render steps
## Sections
### Global
_Render preferences_:
- Max Samples **512**
- Min Samples **32**
- Persistent Data **on**
- Pixel Filter **1px**
- Use Spatial Splits **on**
- Denoise **OpenImage Fast**

### Above the Ocean
_Frames_: 1-100
_Render preferences_:
- Noise Threshold **0.3**
- Light Paths **8**
- Look **High Contrast**

### Near the Surface
_Frames_: 101-300
_Render preferences_:
- Noise Threshold **0.4**
- Light Paths **10**
- Look **Medium High Contrast**

### The Sinking Ship
_Frames_: 301-574
_Render preferences_:
- Noise Threshold **0.25**
- Light Paths **12**
- Look **High Contrast**

### Backwards
_Frames_: 575-700
_Render preferences_:
- Noise Threshold **0.25**
- Light Paths **12**
- Look **Medium Low Contrast**
