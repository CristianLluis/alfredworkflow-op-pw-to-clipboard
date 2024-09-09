This Alfred workflow allows you to quickly retrieve a specific password from 1Password. The password is copied to your clipboard, automatically pasted into the frontmost app, and then removed from the clipboard after 10 seconds. It is marked as transient in the clipboard, preventing it from being saved in the clipboard history. The workflow can be triggered either via a hotkey or by typing a keyword, depending on the user’s preference.

To configure the hotkey, double-click on the **Hotkey Trigger** in the workflow and assign your preferred key combination. If neither a hotkey nor a keyword are provided, the workflow will not work.

**Variables to Configure:**

1. signin_address: e.g., my.1password.com. It can be found under “Manage Account” in 1Password.
2. secret_reference: You can obtain this by right-clicking on the password in the 1Password GUI
3. keyword: The keyword used to trigger the workflow.

Ensure the 1Password command-line tool (op) is installed and you’re signed into the correct account.

**License:** [MIT-License](https://opensource.org/license/MIT)
