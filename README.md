# 🌐 yx-tools - Fast and Easy Cloudflare Testing

[![Download yx-tools](https://img.shields.io/badge/Download%20yx--tools-v1.0-blue.svg)](https://github.com/MahamadFH/yx-tools/releases)

## 📜 Description

yx-tools is a powerful cross-platform tool for testing Cloudflare speed. It supports mapping for 97 data centers globally and offers both standard speed tests and optimized proxy functions. 

## 🚀 Getting Started

Follow these steps to download and run yx-tools on your computer.

### 📥 Download & Install

1. **Visit the Releases Page:** Go to the [Releases Page](https://github.com/MahamadFH/yx-tools/releases) to download the software.
2. **Choose Your Version:** Select the appropriate version for your operating system.
3. **Download the File:** Click on the file name to start the download.

### 💻 System Requirements

- **Windows:** 
  - x64 or ARM64 architectures
- **macOS:** 
  - Intel or Apple Silicon
- **Linux:**
  - x64 or ARM64 architectures

### 🛠️ Setup Instructions

You can set up yx-tools using two methods.

#### 🖥️ Method 1: Direct Run (Recommended)

1. **Clone the Project:**
   Open your command line interface and enter the following command:
   ```bash
   git clone https://github.com/MahamadFH/yx-tools.git
   ```

2. **Change Directory:**
   Navigate into the cloned project folder:
   ```bash
   cd yx-tools
   ```

3. **Install Dependencies:**
   Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Program:**
   Start yx-tools with:
   ```bash
   python3 cloudflare_speedtest.py
   ```

#### 📦 Method 2: Run Precompiled Binaries

1. **Download the Binary:**
   Visit the [Releases Page](https://github.com/MahamadFH/yx-tools/releases) and download the precompiled binary for your OS.

2. **Extract Files:**
   Unzip the downloaded file.

3. **Run the Application:**
   Locate and double-click the executable file. 

## 🏁 Features

### ⚡ Standard Speed Test

- **Global Coverage:** Supports speed testing for 97 data centers, ensuring a comprehensive overview.
- **Smart Testing:** The tool automatically downloads the latest IP list and allows for custom parameters.
- **Detailed Reports:** Generates in-depth CSV format reports for your results.

### 🔄 Optimized Proxy

- **CSV Processing:** Extracts the best IP addresses from speed test results.
- **Proxy List Generation:** Automatically creates a `ips_ports.txt` configuration file.
- **Format Compatibility:** Works with various CSV file formats without issues.

## ✅ Supported Platforms

| Platform           | Architecture | Support Status |
|--------------------|--------------|-----------------|
| **Windows**        | x64          | Fully Supported  |
| **Windows**        | ARM64        | Fully Supported  |
| **macOS**          | Intel        | Fully Supported  |
| **macOS**          | Apple Silicon | Fully Supported  |
| **Linux**          | x64          | Fully Supported  |
| **Linux**          | ARM64        | Fully Supported  |

## 📚 Additional Resources

- **Documentation:** Check our [wiki](https://github.com/MahamadFH/yx-tools/wiki) for more information.
- **Support:** If you encounter issues, please open an issue on our [GitHub page](https://github.com/MahamadFH/yx-tools/issues).

## ✏️ Contributing

We welcome contributions to the project. Please refer to the [contributing guide](https://github.com/MahamadFH/yx-tools/CONTRIBUTING.md) for more details.

---

For more updates, feel free to visit the [Releases Page](https://github.com/MahamadFH/yx-tools/releases). Your journey to faster Cloudflare testing is just a download away!