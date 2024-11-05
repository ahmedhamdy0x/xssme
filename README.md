
# XSSME

![XSSME-Ahmed Hamdy-Gentil Security](https://github.com/user-attachments/assets/89059b99-8de9-4c9c-ab77-b45fd8a75580)

**XSSME** is a powerful and automated XSS vulnerability scanner developed to help security professionals and bug bounty hunters efficiently identify Cross-Site Scripting (XSS) vulnerabilities. The tool is designed to dynamically locate exploitable parameters in web applications and inject a wide range of XSS payloads to detect weaknesses.

## Features:
- **Dynamic Parameter Detection**: Automatically identifies parameters in forms and URLs.
- **Multi-threading Support**: Scans multiple endpoints simultaneously for faster results.
- **Custom Payloads**: Easily add or modify payloads to adapt the tool to different scenarios.
- **Save Results**: Option to save the scan output to a file for further analysis.
- **User-friendly Interface**: Simple command-line arguments for seamless usage.

---

## Requirements

Before you begin, make sure you have the following installed on your system:
- **Python 3.x** 
- **pip** (Python package installer)

---

## Installation

### 1. Create a Virtual Environment (Optional but Recommended)
It's best practice to isolate your tool environment using a virtual environment. This prevents dependency conflicts with other Python projects.

```bash
python3 -m venv ~/xssme-env
source ~/xssme-env/bin/activate
```

### 2. Clone the Repository

Clone the XSSME tool from GitHub and navigate to the project folder:

```bash
git clone https://github.com/ahmedhamdy0x/xssme.git
cd xssme
```

### 3. Install Dependencies

Install the necessary Python libraries required for the tool by running:

```bash
pip install -r requirements.txt
deactivate
```

### 4. Make the Tool Executable

Ensure that the tool is executable by running the following command (if it's not executable already):

```bash
chmod +x xssme
```

### 5. Add XSSME to Your System PATH

To make the tool globally accessible from any directory, move it to `/usr/local/bin/`:

```bash
sudo mv xssme /usr/local/bin/
```

This allows you to run `xssme` from anywhere without needing to specify the path.

---

## Example Usage

Once installed, you can run **XSSME** by specifying the target URL and optional output file for results:

```bash
xssme -v https://target.com -o output.txt
```

### Command-line Arguments:
- `-v` or `--verbose`: Runs the scan in verbose mode, showing detailed results.
- `-o` or `--output`: Save the results to a specified file.

For more options, simply type:

```bash
xssme --help
```

---

## Conclusion

With **XSSME**, you can simplify the process of finding XSS vulnerabilities in your web applications. This tool is designed to be customizable, fast, and effective, making it a valuable asset for penetration testers, bug bounty hunters, and security researchers.

---

### Contact

Developed by [Ahmed Hamdy](https://github.com/ahmedhamdy0x)

Youtube Channel [Gentil Security](https://www.youtube.com/@gentil.security)

Upwork Profile [Ahmed Hamdy](https://www.upwork.com/freelancers/~01955158a82488323f)

For inquiries or support, feel free to contact me at: **info.gentil.academy@gmail.com**

