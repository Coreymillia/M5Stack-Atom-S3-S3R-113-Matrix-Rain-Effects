# 🌧️ AtomMatrix113 - Matrix Rain Screensaver for M5Stack Atom S3

**113 Stunning Matrix Rain Effects** optimized for the M5Stack Atom S3's 128x128 LCD display! 

This is a port of the successful Core2Matrix113 project, adapted specifically for the compact Atom S3 device with auto scroll, no controls. 

## 🚀 **Features**

- **113 Matrix Rain Variations** - Complete collection of matrix screensaver effects
- **128x128 LCD Optimized** - Perfect scaling for the Atom S3's compact display
- **Boot Button Control** - Simple one-button interface
- **Auto-scroll Mode** - Automatic cycling through all effects
- **Memory Efficient** - Optimized for the Atom S3's hardware constraints
- **Professional Code** - Clean, modular architecture

## 🎯 **Hardware Requirements**

- **M5Stack Atom S3** with 128x128 LCD display
- USB-C cable for programming and power
- Optional: 3D printed case or mounting solution

## 🎮 **Controls**

Unable to get any controls. 

### **Auto-Scroll Mode**:
- When enabled: Automatically cycles through all 113 effects
- **30 seconds per effect** - perfect for ambient display
- Visual feedback shows when mode is toggled

## 🎨 **Effect Categories**

Our **113 effects** include these amazing categories:

### **🌊 Basic Matrix Family** (22 effects)
- Classic matrix rain, fire, ice, storm variations
- Glitch effects, pulse patterns, speed bursts
- Neon gradients, retro terminal styles

### **👻 Advanced Effects** (25 effects) 
- Phantom trails, echo effects, wind sway
- Ripple distortions, depth fog, heavy storms
- Tidal waves, vibration patterns

### **💧 Liquid Physics** (12 effects)
- Blood, honey, acid, mercury, water drips
- Viscosity simulation with realistic flow

### **💥 Fracture Effects** (15 effects)
- Binary splits, triple fractures, cascading breaks
- Organic tree-like splits, explosive shattering
- Molten cycles, crystalline fractures

### **⚡ Energy Systems** (20 effects)
- Plasma fields with fire, ice, toxic, storm variants
- Gravity wells, resonance patterns
- Multi-zone biomes with complex interactions

### **🎆 Firework Effects** (12 effects)
- Pressure release bursts, fan-shaped explosions
- Chain reaction cascades, slow-motion effects
- Ice crystal shards, particle trails

### **🔬 Microfont Family** (7 effects)
- Ultra-dense matrix with 3x3 pixel characters
- Fire, ice, storm, toxic variations
- Micro-tsunami effects with ripple waves

## ⚡ **Performance Statistics**

### **Memory Usage**:
- **RAM**: 11.5% (37.8KB / 320KB) - Excellent efficiency!
- **Flash**: 14.7% (490KB / 3.3MB) - Plenty of room for expansion
- **Performance**: Smooth rendering at 20Hz on 128x128 display

### **Optimization Techniques**:
- **Smart scaling** from 320x240 → 128x128 resolution
- **Efficient matrix grid** (16x16 vs original 40x30)
- **Memory pooling** for complex effects
- **M5GFX optimization** using native font system

## 🛠️ **Installation**

### **Option 1: M5Burner (Recommended)**
1. Download M5Burner from M5Stack official website
2. Connect your Atom S3 via USB-C
3. Load `AtomMatrix113-v1.0-MERGED.bin`
4. Flash to device
5. Enjoy 113 matrix effects!

### **Option 2: PlatformIO Development**
```bash
# Clone or copy project files
cd AtomMatrix113/
pio run -t upload
```

## 🎯 **Quick Start Guide**

1. **Power On**: Atom S3 starts with auto-scroll enabled
2. **Watch**: Effects change automatically every 30 seconds  
3. **Interact**: Press boot button to manually advance effects
4. **Customize**: Hold boot button to disable auto-scroll for manual control

## 🔍 **Technical Details**

### **Display Adaptation**:
- Original: 320x240 (40x30 matrix grid)
- Atom S3: 128x128 (16x16 matrix grid)
- Character size: 8x8 pixels maintained
- All effects proportionally scaled

### **Control System**:
- Replaced Core2's three touch buttons with single boot button
- Long press detection for mode switching
- Visual feedback optimized for small screen

### **Font System**:
- Adapted to M5GFX font system
- Reduced font count from 22 to 7 optimized fonts
- Maintained font variety for different effects

## 🔧 **Development Notes**

### **Porting Changes Made**:
1. **Library Update**: M5Core2 → M5Unified
2. **Display Scale**: 320x240 → 128x128 resolution
3. **Control System**: Touch buttons → Boot button with long press
4. **Font System**: Adafruit GFX fonts → M5GFX native fonts
5. **Memory Optimization**: Reduced grid size and effect complexity

### **Key Technical Adaptations**:
- Matrix grid: `MATRIX_COLS 40→16`, `MATRIX_ROWS 30→16`
- Microfont grid: `MICRO_COLS 106→42`, `MICRO_ROWS 60→32`
- Heatmap system: Reduced from 40x30 to 16x16 grid
- Visual feedback: Adapted for 128x128 display constraints

## 🎨 **Effect Showcase**

The Atom S3's compact 128x128 display showcases these effects beautifully:

- **Matrix Custom**: Classic green rain with authentic character set
- **Matrix Fire**: Blazing red/orange cascading characters  
- **Matrix Storm**: Electric blue with lightning flickers
- **Matrix Fracture**: Characters split and cascade in complex patterns
- **Matrix Plasma**: Energy fields bend character trajectories
- **Matrix Fireworks**: Explosive character bursts with particle trails
- **Matrix Microfont**: Ultra-dense rain with tiny 3x3 characters

## 📊 **Project Statistics**

- **Total Effects**: 113 unique matrix variations
- **Code Size**: ~490KB optimized for Atom S3
- **Display**: 128x128 LCD perfectly utilized
- **Control**: Simple one-button interface
- **Performance**: Consistent 20Hz rendering
- **Memory**: Efficient 16x16 matrix grid

## 🚀 **Future Enhancements**

Potential additions for future versions:

- **IMU Integration**: Shake to change effects (if Atom S3 has IMU)
- **Sound Reactive**: Audio-reactive matrix effects
- **Network Features**: WiFi-based remote control
- **Custom Patterns**: User-defined matrix sequences
- **Color Themes**: Additional color palette options

## 📄 **License & Credits**

- **License**: MIT License (see LICENSE file)
- **Original Effects**: Based on XScreensaver matrix algorithms by Jamie Zawinski
- **ESP32 Port**: Core1/Core2 implementation by Coreymillia  
- **Atom S3 Port**: Adapted and optimized for M5Stack Atom S3
- **M5Stack**: Hardware platform and M5Unified library

## 🔗 **Related Projects**

- **Core1Matrix113**: Original 128x160 ST7735 version
- **Core2Matrix113**: 320x240 ILI9341 version  
- **AtomMatrix113**: This 128x128 Atom S3 version
- **XScreensaver**: Original screensaver collection

---

## 🌟 **Final Words**

The AtomMatrix113 brings the mesmerizing world of matrix rain effects to the ultra-compact M5Stack Atom S3. With 113 variations, simple one-button control, and perfect 128x128 optimization, it's the ultimate pocket-sized matrix screensaver.

Whether you're a developer, maker, or just love the aesthetic of digital rain, this collection transforms your Atom S3 into a captivating display piece.

**Welcome to the Matrix... in your pocket!** 🌧️✨

---

### 📧 **Support & Contact**

- **GitHub**: Your projects and repos
- **Email**: Coreymillia@gmail.com
- **M5Stack Community**: Share your Atom S3 matrix photos!

**Enjoy the endless digital rain!** 🎆🔋
