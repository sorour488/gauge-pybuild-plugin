# 🚀 gauge-pybuild-plugin - Simplifying Python Builds for Testing

[![Download Latest Release](https://img.shields.io/github/v/release/sorour488/gauge-pybuild-plugin?label=Download&style=for-the-badge)](https://github.com/sorour488/gauge-pybuild-plugin/releases)

## 🛠️ Overview

gauge-pybuild-plugin is a Python build plugin designed to enhance the Gauge testing framework. With support for UV, Poetry, and setuptools, it streamlines your testing process and improves your development workflow.

## 🌍 Features

- **Support for Gauge**: Integrates seamlessly with Gauge, boosting your testing capabilities.
- **UV Support**: Leverage the power of UV for improved performance.
- **Poetry Integration**: Utilize Poetry for managing dependencies efficiently.
- **Setuptools Compatibility**: Works with setuptools to standardize your build process.
- **Easy to Use**: Designed for non-technical users with straightforward instructions.

## 📦 System Requirements

Before you download gauge-pybuild-plugin, make sure your system meets the following requirements:

- **Operating System**: Windows, macOS, or Linux
- **Python Version**: Python 3.7 or higher
- **Gauge Version**: Gauge 0.0.0 or higher

## 🚀 Getting Started

To use gauge-pybuild-plugin for your projects, follow the steps below to download and set it up.

## 📥 Download & Install

1. **Visit this page to download**: [Download Latest Release](https://github.com/sorour488/gauge-pybuild-plugin/releases)
   
   Here, you will find the latest version of the gauge-pybuild-plugin. Click on the link and choose the version suitable for your operating system.

2. **Extract the Downloaded File**:
   - Once the file finishes downloading, navigate to the folder where it was downloaded.
   - Right-click on the file and select "Extract All." Follow the prompts to extract the files.

3. **Install the Plugin**:
   - Open your command line interface (Terminal on macOS/Linux, Command Prompt on Windows).
   - Navigate to the folder where you extracted the plugin:
     - For Windows: `cd path\to\gauge-pybuild-plugin`
     - For macOS/Linux: `cd path/to/gauge-pybuild-plugin`
   - Run the installation command:
     ```
     pip install . 
     ```
   This command will install the gauge-pybuild-plugin on your system.

4. **Verify Installation**: 
   - To ensure the installation was successful, run the command:
     ```
     gauge run
     ```
   If the installation is correct, you will see a confirmation message.

## 🔧 Configuration

To set up gauge-pybuild-plugin for your projects:

1. **Configure Your Project**: Go to your project folder and create a `gauge.json` file, if it doesn’t already exist. Include the following configuration:

   ```json
   {
     "plugins": {
       "gauge-pybuild-plugin": {
         "enabled": true
       }
     }
   }
   ```

2. **Set Up Poetry** (Optional): If you want to use Poetry for dependency management, run the following command:

   ```
   poetry init
   ```

   Follow the prompts to set up your project's configuration.

3. **Add Dependencies**: You can add any required Python packages to your `pyproject.toml` file.

## 🔍 Usage

Now that you have installed and configured gauge-pybuild-plugin, here’s how to use it in your project:

1. **Create Your Test Files**: In your project folder, create a folder named `tests`. Inside this folder, create test files with the `.py` extension.

2. **Run Your Tests**: Use the following command in your terminal:

   ```
   gauge run
   ```

   This command will execute all tests found in the `tests` folder.

## ⚙️ Troubleshooting

If you encounter issues while using gauge-pybuild-plugin, consider these troubleshooting steps:

- **Check Python Version**: Ensure you are using Python 3.7 or higher.
- **Reinstall the Plugin**: Sometimes, reinstalling can fix conflicts or issues.
- **Dependencies**: Verify all dependencies are correctly listed in your `pyproject.toml` if using Poetry.

## 🌟 Community Support

For further help and discussions, you can join our community:

- Visit the [Gauge Community](https://gauge.org/community).
- Check the [GitHub Issues](https://github.com/sorour488/gauge-pybuild-plugin/issues) page for known issues and solutions.

## 📅 Release Notes

Stay updated with the latest changes in gauge-pybuild-plugin by checking the release notes on the [Releases page](https://github.com/sorour488/gauge-pybuild-plugin/releases). New features, fixes, and updates will be documented here.

## 📦 License

gauge-pybuild-plugin is licensed under the MIT License. You can freely use and modify the software but ensure to provide attribution.

## 📢 Acknowledgments

We appreciate the contributions from the community and the creators of Gauge. Your support helps improve testing for everyone.