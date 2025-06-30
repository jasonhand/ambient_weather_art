# Weather Art Installation

A dynamic, interactive art installation that transforms weather data into a mesmerizing visual experience. This web-based application creates a grid of animated discs that respond to real-time weather conditions and can integrate live camera feeds to create silhouette effects.

## 🌤️ Features

### **Weather-Driven Visual Art**
- **Dynamic Disc Grid**: Hundreds of small discs that flip and change colors based on weather conditions
- **Real-time Weather Integration**: Connects to Ambient Weather Network API for live weather data
- **Multi-factor Response**: Temperature, humidity, pressure, wind speed, and solar radiation all influence the visual patterns
- **Chaos Indicator**: Visual representation of weather instability
- **Day/Night Cycles**: Automatic color scheme adjustments based on time of day

### **Camera Integration**
- **Silhouette Detection**: Advanced motion detection creates negative space effects from camera feed
- **Video Mosaic**: Each disc can display a section of the live camera feed
- **Multiple Blend Modes**: Overlay, replace, mix, and silhouette modes for different effects
- **Real-time Processing**: Live camera feed processing with adjustable sensitivity
- **Preview Windows**: Camera and silhouette preview options

### **Interactive Controls**
- **Manual Weather Simulation**: Test different weather scenarios without live data
- **Animation Controls**: Adjust animation speed and trigger random effects
- **Camera Settings**: Sensitivity, opacity, scale, and blend mode controls
- **Auto-hide Interface**: Clean full-screen experience with easy control access

## 🎨 Visual Effects

### **Color System**
- **Temperature Mapping**: Cold (blues) → Warm (yellows) → Hot (reds)
- **Weather Patterns**: Complex mathematical patterns based on multiple weather factors
- **Dynamic Gradients**: Smooth color transitions that respond to real-time changes
- **Atmospheric Background**: Background colors that change with weather conditions

### **Animation System**
- **Automatic Flipping**: Discs flip based on weather chaos and wind conditions
- **Pattern Generation**: Wave, spiral, humidity, pressure, and wind patterns
- **Time-based Evolution**: Continuous pattern changes over time
- **Weather Responsiveness**: Animation speed and frequency tied to weather data

### **Silhouette Effects**
- **Motion Detection**: Background subtraction identifies moving subjects
- **Negative Space**: Silhouettes appear as dark/transparent areas in the disc grid
- **Adaptive Background**: Automatically adjusts to lighting changes
- **Smooth Outlines**: Noise reduction creates clean silhouette shapes

## 🚀 Getting Started

### **Prerequisites**
- Modern web browser with camera support
- HTTPS connection (required for camera access)
- Optional: Ambient Weather Network API credentials

### **Quick Start**
1. **Open the HTML file** in a web browser
2. **Camera will auto-start** after 2 seconds (if enabled)
3. **See the effect immediately** - discs will show camera silhouettes
4. **Adjust settings** using the controls panel
5. **Hide controls** for full-screen experience

### **Weather Station Setup**
1. **Get API credentials** from [Ambient Weather Network](https://ambientweather.net/)
2. **Enter API Key and Application Key** in the controls
3. **Click "Connect to Weather Station"**
4. **Controls will auto-hide** on successful connection
5. **Enjoy live weather-driven art!**

## 🎛️ Controls Guide

### **API Configuration**
- **API Key**: Your Ambient Weather Network API key
- **Application Key**: Your Ambient Weather Network application key
- **MAC Address**: Optional device-specific identifier
- **Save Credentials**: Automatically save for future sessions

### **Manual Controls**
- **Temperature**: -20°F to 120°F range
- **Humidity**: 0% to 100%
- **Pressure**: 28" to 32" Hg
- **Wind Speed**: 0 to 100 mph
- **Solar Radiation**: 0 to 1200 W/m²
- **Time of Day**: Auto, Day, or Night modes

### **Camera Controls**
- **Enable Webcam**: Toggle camera integration
- **Blend Mode**: Silhouette, Mosaic, Overlay, Replace, or Mix
- **Motion Sensitivity**: Adjust silhouette detection (10-100)
- **Camera Opacity**: Control camera influence (0.1-1.0)
- **Camera Scale**: Zoom camera sections (0.5x-3x)

### **Animation Controls**
- **Animation Speed**: Control overall animation rate
- **Trigger Random Flips**: Manual animation trigger
- **Reset All Discs**: Return all discs to default state

## 🔧 Technical Details

### **Weather Data Processing**
- **Chaos Calculation**: Combines temperature, humidity, pressure, and wind deviations
- **Color Mapping**: HSL color space with temperature-based hue selection
- **Pattern Generation**: Multiple sine wave combinations for organic movement
- **Real-time Updates**: 5-minute API refresh rate (per Ambient Weather limits)

### **Camera Processing**
- **Frame Analysis**: Real-time background subtraction
- **Motion Detection**: Pixel-level difference calculation
- **Noise Reduction**: Gaussian smoothing for clean silhouettes
- **Adaptive Background**: Gradual background updates for lighting changes

### **Performance Optimization**
- **Canvas-based Rendering**: Efficient 2D graphics processing
- **RequestAnimationFrame**: Smooth 60fps animations
- **Memory Management**: Automatic cleanup of video streams
- **Responsive Design**: Adapts to different screen sizes

## 🎯 Use Cases

### **Art Installations**
- **Gallery Displays**: Interactive weather-responsive art
- **Public Spaces**: Dynamic environmental awareness installations
- **Educational**: Weather science visualization
- **Therapeutic**: Calming, nature-connected experiences

### **Personal Use**
- **Home Decor**: Beautiful, dynamic wall art
- **Weather Monitoring**: Visual weather station interface
- **Camera Art**: Creative silhouette and mosaic effects
- **Meditation**: Peaceful, nature-inspired visuals

### **Development**
- **API Integration**: Example of weather data visualization
- **Camera Processing**: Real-time video analysis techniques
- **Interactive Art**: Web-based creative coding examples
- **Responsive Design**: Modern web application patterns

## 🌟 Advanced Features

### **Silhouette Detection**
- **Background Subtraction**: Compares current frame with stored background
- **Motion Thresholding**: Adjustable sensitivity for different environments
- **Smoothing Algorithm**: Reduces noise and fills gaps in silhouettes
- **Adaptive Learning**: Background gradually updates to handle lighting changes

### **Weather Chaos System**
- **Multi-factor Analysis**: Temperature, humidity, pressure, and wind combined
- **Deviation Calculation**: Measures how "unstable" current conditions are
- **Visual Representation**: Chaos level shown as vertical indicator
- **Animation Influence**: Higher chaos = more dynamic disc movement

### **Camera Mosaic Effect**
- **Grid Sampling**: Each disc samples a specific section of camera feed
- **Dynamic Mapping**: Time-based variations create organic movement
- **Scale Control**: Zoom in/out of camera sections
- **Real-time Updates**: Immediate response to camera movement

## 🔒 Privacy & Security

### **Camera Access**
- **Local Processing**: All camera data processed locally in browser
- **No Upload**: Camera feed never leaves your device
- **Permission Required**: Browser will request camera access
- **Easy Disable**: Simple toggle to turn off camera features

### **Weather Data**
- **API Credentials**: Stored locally in browser (optional)
- **Secure Connection**: HTTPS required for camera access
- **No Tracking**: No analytics or data collection
- **Open Source**: Transparent code for security review

## 🛠️ Troubleshooting

### **Camera Issues**
- **Permission Denied**: Check browser camera permissions
- **No Camera Found**: Verify camera hardware and drivers
- **Poor Detection**: Adjust motion sensitivity and lighting
- **Performance Issues**: Reduce camera resolution or disable features

### **Weather API Issues**
- **Connection Failed**: Verify API credentials and internet connection
- **No Data**: Check if weather station is online and reporting
- **Rate Limits**: API updates every 5 minutes maximum
- **Invalid Data**: Some weather stations may not report all parameters

### **Visual Issues**
- **Slow Animation**: Reduce animation speed or number of discs
- **Color Problems**: Check browser color support and settings
- **Layout Issues**: Ensure browser window is large enough
- **Performance**: Close other browser tabs to free memory

## 📱 Browser Compatibility

### **Supported Browsers**
- **Chrome**: Full support (recommended)
- **Firefox**: Full support
- **Safari**: Full support (macOS/iOS)
- **Edge**: Full support

### **Required Features**
- **getUserMedia API**: For camera access
- **Canvas API**: For graphics processing
- **ES6+ Support**: For modern JavaScript features
- **HTTPS**: Required for camera access (except localhost)

## 🎨 Customization

### **Visual Customization**
- **Disc Size**: Adjustable via CSS grid settings
- **Color Schemes**: Modify temperature color mapping
- **Animation Patterns**: Customize pattern generation algorithms
- **Background Effects**: Enhance atmospheric background system

### **Weather Integration**
- **Additional Sensors**: Extend to support more weather parameters
- **Multiple Stations**: Support for multiple weather stations
- **Historical Data**: Add historical weather visualization
- **Forecast Integration**: Include weather prediction data

### **Camera Effects**
- **Advanced Detection**: Implement more sophisticated motion detection
- **Object Recognition**: Add specific object detection capabilities
- **Multiple Cameras**: Support for multiple camera feeds
- **Recording**: Add ability to record and replay effects

## 📄 License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute according to the license terms.
