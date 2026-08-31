# FCGoblin

FFXIV Free Company scanner, in two parts: a Windows app that scans the
Lodestone, and a Dalamud plugin that receives the chosen FCs and tracks
leader online status, right in-game.

Private access, limited to a small group of chosen people. If you're
reading this, you've been invited to use it.

## Installing the plugin in-game

1. Launch the game, type `/xlsettings` in chat, Enter.
2. **Experimental** tab.
3. Scroll down to **Custom Plugin Repositories**.
4. Paste this URL into the empty field at the bottom:

   ```
   https://raw.githubusercontent.com/AerisLifestream/FCGoblin-plugin-repo/main/repo.json
   ```

5. Click **+**, check **Enabled** on the new row, click **Save and
   Close**.
6. Type `/xlplugins`, search for "FCGoblin" in the search bar, click
   **Install**.

The plugin will ask for a password the first time it opens (given to
you separately). Once entered, you won't be asked again.

## Windows app

The `.exe` file is sent to you directly, separately. Like the plugin,
it asks for a password once on first launch.

## Updates

Once you've added the repository above in your Dalamud settings, plugin
updates will show up automatically in the plugin installer - nothing
else to do.
