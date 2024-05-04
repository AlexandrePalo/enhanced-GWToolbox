# Enhanced GWToolbox
GWToolbox for GuildWars with extra features

## Extra features
- **Target everything**: allow Toolbox to target any NPC (deads, minipets, invisibles, ...) from the minimap or with an hotkey.
- **Open chest from distance**: allow Toolbox to open a chest further away than close contact.
- **Current work in progress**:
    - Plugin for TargetEverything rather than the maindll file.
    - Enhanced dialog window with reward / quest taking without delay.

## Version list
<table>
<thead>
  <tr>
    <th align="left">Official Toolbox</th>
    <th><a href="https://github.com/gwdevhub/GWToolboxpp/releases/tag/6.16_Release">6.16</a></th>
    <th><a href="https://github.com/gwdevhub/GWToolboxpp/releases/tag/6.17_Release">6.17</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="left"Modified Toolbox<br>Modified Toolbox<br><b>TargetEverything enable<sup>(1)</sup></b></td>
    <td align="center"><a href="/maindll/6.16/GWToolboxdll.dll">6.16</a></td>
    <td align="center"><a href="/maindll/6.17/GWToolboxdll.dll">6.17</a></td>
  </tr>
  <tr>
    <td align="left"><b>Plugin OpenChestFromDistance<sup>(2)</sup></b><br><i>/openchest</i> chat command</td>
    <td align="center" colspan="2"><a href="/plugins/OpenChestFromDistance/2024-04-23_6.16-build/OpenChestFromDistance.dll">23/04/24 build</a></td>
  </tr>
</tbody>
</table>

- (1) : To use the modified main dll file, simply replace the file <i>GWToolboxdll.dll</i> by the given file in your main <i>GWToolboxpp</i> folder.
- (2) : To use a plugin, add the given <i>.dll</i> file in the <i>computer-name/plugins</i> folder in your main <i>GWToolboxpp</i> folder. Then, in GuildWars, open Toolbox settings and go to the <i>plugins</i> section to load the one you want. Usually a chat message shows that the plugin was successfully loaded.

For last TB versions, the main TB folder is located in your Windows user <i>Documents</i> folder.


## Known issues in last versions
- Unloading the OpenChestFromDistance plugin from GWToolbox settings sometimes leads to a crash.

## Remarks
- When possible, each extra feature is added with a plugin. They are easier to maintain and can be loaded / unloaded when you really need them.
- If not possible, the feature is directly added to the main GWToolbox.dll file but needs to be updated for every Toolbox updated.

## Disclaimer
All these features were at some point removed from the official GuildWars Toolbox because either considered outside of the usual GW bounds, or to comply Toolbox maintainers view about the tool. Some of them were never in the main tool.

Thus, some of these extra features could be considered as *unsafe* to use and could eventually lead to a ban, even if no such ban has been recorded so far.
