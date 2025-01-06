# MobaXterm License Generator
A simple MobaXterm license generator that supports dark and light themes and Chinese (Simplified, Traditional), English and Japanese interfaces.

[简体中文](./README.md) | English

## Features
- 🎨 Modern dark and light themes
- 🌏 Supports multi-language switching (Simplified Chinese, Traditional Chinese, English, Japanese)
- 🔑 Supports generating professional, educational, and personal license types
- 📱 Responsive design, supports mobile access
- 🛡️ Pure front-end implementation, no backend service required

## Environment Requirements

### Supported Browsers
- Chrome 80+
- Firefox 75+
- Safari 13.1+
- Edge 80+

### Local Server (Choose one of the following)
- [Node.js](https://nodejs.org/en/)
- [Python](https://www.python.org/)
- [PHP](https://www.php.net/)

## Usage

### 1. Clone the project
```bash
git clone https://github.com/houyuxi/MobaXterm_License_Generator.git
```

### 2. Install dependencies

#### Using Python(Python 3):
```bash
python -m http.server 8080
```

#### Using Node.js:
```bash
# Install http-server
npm install -g http-server
# Start Service
http-server -p 8080
```

#### Using PHP:
```bash
php -S localhost:8080
```

## Function Usage Instructions

1. Select license type (Professional Edition/Education Edition/Personal Edition)
2. Enter username (only supports English letters)
3. Enter the version number (such as 24.00 or 24.1)
4. Enter the number of users (default is 1)
5. Click the "Generate License" button
6. Download the generated Custom. mmtpro file
7. Import the file into MobaXterm (1. Copy Custom. mmtpro from the installation version to C:\Program Files(x86)\Mobatek\MobaXterm; 2. Copy Custom. mmtpro to the root directory of MobaXterm for the installation free version to use）

## precautions
-The username only supports English letters
-The version number format is x.x and supports up to one decimal place
-The number of users must be a positive integer
-Recommend using the latest version of modern browsers
-Need a local web server environment

##Author

- **HouYuXi**
- Email:  houyuxi123@gmail.com
- GitHub:  https://github.com/houyuxi012

##License

This project is open sourced under the MIT license - please refer to the [LICENSE] document for details

Copyright (c) 2023 HouYuXi

Disclaimers

This project is for learning and research purposes only, please do not use it for commercial purposes. All consequences arising from the use of this project shall be borne by the user themselves.

##Contribution

Welcome to submit Issue and Pull Requests to help improve this project.

1. Fork this project
2. Create your feature branch (` git checkout - b feature/AmazingFeature `)
3. Submit your changes (` git commit - m 'Add some Amazing Features' `)
4. Push to Branch (` git push origin feature/AmatzingFeature `)
5. Open a Pull Request