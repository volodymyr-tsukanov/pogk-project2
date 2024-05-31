# Etap3 animation render steps
## Sections
### Global
_Render preferences_:
- Max Samples **512**
- Min Samples **32**
- Persistent Data **on**
- Pixel Filter **1px**
- Use Spatial Splits **on**
- Denoise **OpenImage Accurate**

### Near the Surface
_Frames_: 1-200
_Render preferences_:
- Noise Threshold **0.5**
- Max Samples **128**
- Min Samples **18**
- Light Paths **8**
- Denoise **OpenImage Fast**

### The Sinking Ship
_Frames_: 201-474
_Render preferences_:
- Noise Threshold **0.4**
- Light Paths **10**

### Backwards
_Frames_: 475-600
_Render preferences_:
- Noise Threshold **0.4**
- Light Paths **12**
