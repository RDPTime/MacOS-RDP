# MacOS-RDP
macOS-SSH
SSH into macOS Big Sur running in GitHub Actions

Preparation
Fork This Repo
Add your ngrok authtoken as NGROK_TOKEN in the Repository Secrets
You can find this token here: https://dashboard.ngrok.com/auth/your-authtoken

Add a shell login password as SSH_PASSWORD in the Repository Secrets
To get Session Link in Telegram [Optional, but Recommended]
Add your bot token as TELEGRAM_BOT_TOKEN and group chat id as TELEGRAM_CHAT_ID in the Repository Secrets
Go to Actions tab, select the workflow name, and run it through workflow_dispatch method
That's it!
Default username of macOS VM in ngrok mode is root. If you want to change to normal user, after login, run su - runner and continue work

Where To Go Next
Experiment anything in your own remote macOS Big Sur machine.

What's inside the beast?! Run system_profiler SPHardwareDataType inside the session or use pip3 install bpytop && bpytop

Good Luck.
