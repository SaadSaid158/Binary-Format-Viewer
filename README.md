# Simple Binary Format Viewer 

A client-side binary analysis tool with basic malware detection capabilities.

## Features

### 🔍 **Binary Detection**
- **50+ file format signatures** including executables, archives, images, documents, media files, databases, and system files
- **Magic byte detection** with offset support for complex formats
- **Risk assessment** for different file types

### 🛡️ **Simple Malware Detection**
- **Multi-layered threat analysis** using entropy, pattern matching, and behavioral indicators
- **40+ malware patterns** including command execution, process injection, persistence mechanisms
- **Threat categorization** (execution, injection, persistence, network, malware, evasion)
- **Risk scoring system** with detailed threat level assessment

### 📊 **Professional Analytics**
- **Shannon entropy calculation** with visual indicators
- **Section-based analysis** for PE and ELF files
- **Sliding window entropy** visualization
- **Byte frequency analysis** with interactive charts

### 🎨 **Modern UI/UX**
- **Glassmorphism design** with gradient backgrounds
- **Tabbed interface** (Overview, Hex Dump, Security, Structure, Visualization)
- **Interactive charts** using Chart.js
- **Responsive design** for desktop and mobile
- **PDF export functionality** for detailed reports

### 🔒 **Security Features**
- **Real-time threat indicators** with color-coded badges
- **Detailed security analysis** with specific threat categories
- **Comprehensive reporting** with recommendations
- **Pattern detection** for known malware families

## Usage

1. Open `advanced-binary-viewer-pro-pdf.html` in any modern web browser
2. Drag and drop a binary file or use the "Browse Files" button
3. View comprehensive analysis across multiple tabs
4. Export detailed PDF reports using the floating action button

## Technical Details

- **Client-side only** - No backend required, no data uploaded
- **Supports files up to 10MB+** without performance issues
- **Vanilla JavaScript** with Tailwind CSS and Chart.js
- **Zero dependencies** beyond CDN resources
- **Cross-platform compatibility**

## Security Notice

This tool performs static analysis only. Always exercise caution with suspicious files and consider dynamic analysis in isolated environments for comprehensive security assessment.

## License

Open source - feel free to modify and distribute.

