# 

A modern, web-based QR code scanner specifically designed for scanning and validating MAC addresses. This tool provides real-time scanning capabilities, data validation, and export functionality for managing MAC address collections.

![QR Code Scanner](https://img.shields.io/badge/Version-1.1-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-blue)

## Features

### Real-time QR Code Scanning
- **Webcam Integration**: Uses device camera for instant QR code detection
- **Live Preview**: Real-time video feed with scanning overlay
- **Auto-focus**: Automatically detects and scans QR codes in view
- **Mobile Optimized**: Works seamlessly on smartphones and tablets

### MAC Address Validation
- **Multiple Formats**: Supports various MAC address formats:
  - `AA:BB:CC:DD:EE:FF` (colon-separated)
  - `AA-BB-CC-DD-EE-FF` (dash-separated)
  - `AABBCCDDEEFF` (no separators)
  - `AAAA:BBBB:CCCC` (IPv6 format)
- **Real-time Validation**: Instant feedback on MAC address validity
- **Visual Indicators**: Clear valid/invalid status with color coding

### Data Management
- **Duplicate Prevention**: Automatically prevents scanning the same MAC address twice
- **Chronological List**: Shows all scanned MAC addresses with timestamps
- **Individual Deletion**: Remove specific entries with trash icon
- **Bulk Operations**: Clear entire list with one click

### Export Capabilities
- **CSV Export**: Download data as CSV file with proper UTF-8 encoding
- **Clipboard Copy**: Copy formatted table data to clipboard
- **Tab-separated Format**: Perfect for pasting into Excel or Google Sheets
- **ISO Timestamps**: Standardized time format for all entries

## Installation & Usage

### Prerequisites
- Modern web browser with camera access
- No installation required - runs entirely in the browser

### Getting Started
1. **Download**: Clone or download this repository
2. **Open**: Open `index.html` in your web browser
3. **Allow Camera**: Grant camera permissions when prompted
4. **Start Scanning**: Click "Start Scanner" and hold QR codes in front of the camera

### Basic Usage
1. **Start Scanner**: Click the green "Start Scanner" button
2. **Scan QR Codes**: Hold QR codes containing MAC addresses in front of the camera
3. **View Results**: Scanned MAC addresses appear in the list below
4. **Export Data**: Use export buttons to save or copy your data
5. **Stop Scanner**: Click "Stop Scanner" when finished

## Supported Devices

- **Desktop**: Windows, macOS, Linux
- **Mobile**: iOS, Android
- **Tablets**: iPad, Android tablets
- **Browsers**: Chrome, Firefox, Safari, Edge

### Browser Compatibility
- **Chrome**: Full support (recommended)
- **Firefox**: Full support
- **Safari**: Full support on iOS 11+
- **Edge**: Full support on Windows 10+


## Technical Details

### Technologies Used
- **HTML5**: Modern web standards
- **CSS3**: Advanced styling with gradients and animations
- **JavaScript (ES6+)**: Modern JavaScript features
- **jsQR Library**: QR code detection and decoding
- **WebRTC**: Camera access and video streaming

## 📋 Data Format

### CSV Export Format
```csv
MAC Address,Status,Timestamp
"AA:BB:CC:DD:EE:FF","Valid","2024-01-15T14:30:45.123Z"
"11:22:33:44:55:66","Invalid","2024-01-15T14:31:12.456Z"
```

### Clipboard Format
```
MAC Address	Status	Timestamp
AA:BB:CC:DD:EE:FF	Valid	2024-01-15T14:30:45.123Z
11:22:33:44:55:66	Invalid	2024-01-15T14:31:12.456Z
```

## 🔒 Privacy & Security

- **Local Processing**: All scanning and processing happens locally in your browser
- **No Data Transmission**: No data is sent to external servers
- **Offline Capable**: Works without internet connection (except for initial library loading)
- **Camera Access**: Only used for QR code scanning, no recording or storage

### Common Issues
- **Camera not working**: Ensure camera permissions are granted
- **QR codes not detected**: Check lighting and QR code quality

## License
This project is licensed under the MIT License

### Development
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

If you encounter any issues or have questions:
- **Issues**: Use GitHub Issues for bug reports
- **Discussions**: Use GitHub Discussions for questions
- **Documentation**: Check this README for common solutions

## 🔄 Version History

- **v1.1**: Enhanced UI design, improved export functionality
- **v1.0**: Initial release with core scanning and export features

---

**Made with ❤️ for efficient MAC address management**
