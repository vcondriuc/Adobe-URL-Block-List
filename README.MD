# Adobe-Block-Hosts-List

Adobe Block Hosts List to block Adobe activation. Prevent Adobe software from connecting to its activation servers by adding these entries to your system's hosts file.

## Introduction

This repository contains a list of host entries designed to block Adobe activation servers. By adding these entries to your system's hosts file, you can prevent Adobe software from connecting to its activation servers, which can be useful for various reasons including privacy and offline use.


## How to Use the Hosts File

### Windows

1. Open Notepad as an administrator. To do this, search for Notepad in the Start menu, right-click on it, and select "Run as administrator".
2. In Notepad, open the hosts file located at `C:\Windows\System32\drivers\etc\hosts`.
3. Add the above entries to the end of the hosts file.
4. Save the file. If you encounter a permissions error, ensure you are running Notepad as an administrator.
5. Flush the DNS cache by opening Command Prompt as an administrator and running the command: `ipconfig /flushdns`.

### Mac

1. Open Terminal. You can find Terminal in the Applications > Utilities folder or by searching for it using Spotlight.
2. Open the hosts file by running the command: `sudo nano /etc/hosts`.
3. Enter your password when prompted.
4. Use the arrow keys to navigate to the end of the file and add the above entries.
5. Save the changes by pressing `Control + O`, then press `Enter` to confirm. Exit by pressing `Control + X`.
6. Flush the DNS cache by running the command: `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`.

## Notes

- Blocking Adobe activation servers may prevent some software features from functioning properly.
- Make sure to back up your original hosts file before making any changes.
- This method does not guarantee permanent offline use or bypassing of Adobe's activation process.

## Disclaimer

This project is intended for educational and informational purposes only. Use it at your own risk. The author is not responsible for any misuse or damage caused by following these instructions.

## Contributing

Feel free to submit a pull request or open an issue if you have any suggestions or improvements.

<a href="https://www.buymeacoffee.com/vadc" target="_blank">
 <img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174">
</a>
