🚀 Ip-ScannerV1.2  Advanced IP Lookup Tool

🌍 Overview
**Ip-ScannerV1.2** is a powerful and efficient Python script designed to retrieve detailed information about IP addresses associated with a given domain or URL. This tool provides valuable insights such as resolved IP addresses, forwarded IPs (X-Forwarded-For, X-Real-IP), and additional geolocation details from `ipinfo.io`.

✨Key Features
🔍 **Resolve Domain to IP:** Retrieve all resolved IP addresses of a given domain.
🌎 **Geolocation Information:** Obtain details about an IP address, including country, region, and ISP.
🛡 **Header Analysis:** Extract X-Forwarded-For and X-Real-IP headers for additional insights.
📊 **Formatted Output:** Present results in a well-structured tabular format for better readability.
🏗 **Cross-Platform Compatibility:** Works seamlessly on Windows, Linux, macOS, and Termux (Android).

   📥 Installation Guide

🐧 Linux & 🍏 macOS
1. Ensure Python 3 is installed:

      python3 --version

3. Install required dependencies:

      pip3 install requests tabulate

5. Run the script:

      python3 Ip-ScannerV1.2.py

🪟 Windows
1. Verify Python 3 installation. If missing, download it from [python.org](https://www.python.org/downloads/).  
2. Install dependencies using Command Prompt:

      pip install requests tabulate

4. Execute the script:

      python Ip-ScannerV1.2.py

📱 Termux (Android)
1. Install Python in Termux:

      pkg install python -y

3. Install dependencies:

      pip install requests tabulate

5. Run the script:

      python3 Ip-ScannerV1.2.py

🎯 Usage Instructions
1. Execute the script using the appropriate command for your operating system.
2. Input a valid URL or domain when prompted.
3. The script will analyze and display relevant IP information in a structured format.

📌 Example Usage:

    Enter URL (http/https): example.com

💡 The output will include resolved IP addresses, forwarded IP headers, and geolocation details presented in a structured table.

⚠ Important Notes
  ✅ Ensure an active internet connection, as the script relies on `ipinfo.io` for detailed IP data.
  ✅ This tool is intended for educational and ethical purposes only. Misuse of this tool is strictly discouraged.

👤Author & Version

  👾 **Developer:** EAST TIMOR GHOST SECURITY
  📌 **Current Version:** 1.2


