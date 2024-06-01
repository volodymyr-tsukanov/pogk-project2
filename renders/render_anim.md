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

### Above the Ocean
_Frames_: 1-100
_Render preferences_:
- Noise Threshold **0.6**
- Max Samples **80**
- Min Samples **16**
- Light Paths **6**
- Denoise **OpenImage Fast**

### Near the Surface
_Frames_: 101-300
_Render preferences_:
- Noise Threshold **0.5**
- Max Samples **128**
- Min Samples **18**
- Light Paths **8**
- Denoise **OpenImage Fast**

### The Sinking Ship
_Frames_: 301-574
_Render preferences_:
- Noise Threshold **0.4**
- Light Paths **10**

### Backwards
_Frames_: 575-700
_Render preferences_:
- Noise Threshold **0.4**
- Light Paths **12**
