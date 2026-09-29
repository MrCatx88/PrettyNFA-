# Update notes

## v1.0.4

- Check for updates always works; the Update button only appears when a newer version is out.

## v1.0.3

- Cached Accounts: every saved login has its own Restore login button again, no need to select it first.

## v1.0.2

- Deleting an account now removes every trace of it: its token, avatar, stats, backup copy and log entries.
- Steam on this PC forgets deleted accounts too. If Steam is open, this finishes the next time you sign in through PrettyNFA.
- Removing a saved login on Cached Accounts also makes Steam forget it, so it cannot come back.
- Clearer delete confirmations that say exactly what gets removed.

## v1.0.1

- Deleted cached accounts now stay deleted, also after a restart or a new sign-in.
- Accounts are safer: if the accounts file is ever damaged, PrettyNFA loads your accounts from its backup.
- Saves can no longer overwrite each other, so accounts never disappear from the list.
- Signing in keeps working even if the saved logins file is briefly locked.

## v1.0.0

First release of PrettyNFA.

- **Accounts:** add an account by pasting its Steam token. Every account shows whether it still works, and its details: last online, last played CS2, hours, account age, bans, inventory value, Premier rating, level and cooldown.
- **Cached Accounts:** move logins Steam remembers into Accounts, delete the ones that no longer work, or clear them all.
- **Ingame Settings:** set your loadout, keybinds, sensitivity, crosshair (share codes supported) and audio once, or copy them from another account.
- **Auto deploy:** apply Ingame Settings, loadout, profile and workshop cleanup automatically on every sign-in.
- **Security:** saved accounts are encrypted to your Windows user.
- **Updates:** PrettyNFA checks this page for new versions and updates itself.
