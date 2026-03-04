# ⚙️ iv-surface-engine - Fast Implied Volatility Analysis Tool

[![Download iv-surface-engine](https://img.shields.io/badge/Download-iv--surface--engine-green?style=for-the-badge)](https://github.com/milha9089/iv-surface-engine)

## 📋 About iv-surface-engine

iv-surface-engine is a tool designed to analyze implied volatility surfaces quickly and reliably. It uses advanced mathematical models like SABR, SSVI, and eSSVI to provide accurate volatility data. This helps you understand option pricing and risk better. The software offers:

- Strong checks to prevent calculation errors (arbitrage enforcement)
- A way to adjust model parameters focused on key sensitivities (vega-weighted calibration)
- Limits based on statistical moments (Lee moment bounds)
- A thorough record of all calculations (full audit trail)
- Over 300 tests passed to ensure accuracy

The software includes a C++ engine and a simple dashboard made in Python using Streamlit. The dashboard lets you interact with the data without coding.

## 🖥️ System Requirements

To run iv-surface-engine smoothly on your Windows PC, make sure your system meets the following:

- Operating System: Windows 10 or later (64-bit)
- Processor: Intel Core i3 or equivalent
- Memory: 8 GB RAM or more
- Disk space: At least 500 MB free
- Python 3.8 or newer installed (for dashboard use)
- Internet connection for initial download and updates

You don’t need programming skills to use the dashboard. The setup steps cover everything you need.

## 🚀 Getting Started: Download and Run iv-surface-engine

Start by downloading the latest version. Visit the iv-surface-engine repository page to get the software.

[![Download iv-surface-engine](https://img.shields.io/badge/Download-iv--surface--engine-blue?style=for-the-badge)](https://github.com/milha9089/iv-surface-engine)

### Step 1: Visit the Download Page

Go to the official iv-surface-engine page here:

https://github.com/milha9089/iv-surface-engine

Once there, look for the "Releases" or "Downloads" section on the page. This is where you will find the latest version of the software.

### Step 2: Choose Your File

Download the version marked for Windows. This file usually has `.exe` or `.zip` at the end. If it’s a zip file, you will need to unzip it after downloading.

### Step 3: Run the Installer or Unzip the Package

- If you downloaded an installer (`.exe`), double-click the file and follow the on-screen instructions.
- If you downloaded a zip file, right-click it and select "Extract All," then choose a folder to save the contents.

### Step 4: Open the Dashboard

The dashboard lets you view and interact with the data easily.

- If the dashboard is included in the package, find the file named `dashboard.py` or follow the included instructions.
- To start the dashboard, open the Windows Command Prompt.
- Navigate to the folder where the software is saved using the `cd` command. For example:
  
  ``` 
  cd C:\Users\YourName\Downloads\iv-surface-engine
  ```

- Run the dashboard by typing:

  ``` 
  streamlit run dashboard.py
  ```

- A browser window will open automatically with the dashboard.

### Step 5: Use the Dashboard

On the dashboard, you’ll find options to:

- Load sample volatility data
- Choose different models (SABR, SSVI, eSSVI)
- Run analyses with simple buttons
- View charts and tables of results

The interface uses plain language to help you understand results without extra tools.

## 🔧 Installation Details

This section helps if you want to install additional components or fix issues.

- Python: The dashboard needs Python 3.8 or later.
- Streamlit: Install Streamlit if you don’t have it already. Open Command Prompt and type:

  ```
  pip install streamlit
  ```

- C++ Engine: The main engine runs in C++. The package includes files ready to use. No compilation needed for general use.

If you face errors running the dashboard, check that Python and Streamlit are installed correctly. Also, ensure the downloaded files are unzipped without changes.

## 🛠️ Features and Tools

iv-surface-engine includes:

- **Arbitrage enforcement**: Stops invalid results where price checks fail.
- **Vega-weighted calibration**: Adjusts model parameters focusing on option sensitivity.
- **Lee moment bounds**: Limits volatility values based on statistical rules.
- **Audit trail**: Keeps a full list of all actions and data changes.
- **Extensive testing**: Over 300 tests ensure software reliability.

The dashboard lets you apply these features with no programming required.

## 🧑‍💻 Common Questions

### Q: Do I need to code to use iv-surface-engine?

No. The dashboard lets you run analyses using buttons and menus.

### Q: Can I run this on Mac or Linux?

This version targets Windows. Support for other systems may come later.

### Q: How do I update iv-surface-engine?

Visit the download page regularly to get new releases and follow the same instructions to replace your files.

### Q: What if I need help?

Check the README and documentation on the GitHub page or contact through the repository issues section.

## 🔗 Useful Links

- Repository Home: https://github.com/milha9089/iv-surface-engine
- Download Page: https://github.com/milha9089/iv-surface-engine/releases  
- Python Download: https://www.python.org/downloads/
- Streamlit Info: https://streamlit.io/

[![Download iv-surface-engine](https://img.shields.io/badge/Download-iv--surface--engine-green?style=for-the-badge)](https://github.com/milha9089/iv-surface-engine)