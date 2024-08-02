# Enhanced GWToolbox
GWToolbox for GuildWars with extra features

## Extra features
- **Allow target everything**: allow Toolbox to target any NPC (deads, minipets, invisibles, ...) from the minimap or with an hotkey.
- **Open chest from distance**: allow Toolbox to open a chest further away than close contact.
- **Current work in progress**:
    - Enhanced dialog window with reward / quest taking without delay.

## Version list
<table>
<thead>
  <tr>
    <th align="left">Official Toolbox</th>
    <th>6.16</th>
    <th>6.17</th>
    <th>6.18</th>
    <th>6.20</th>
    <th>6.21</th>
    <th>6.22</th>
  </tr>
</thead>
<tbody>

  <tr>
    <td align="left"><b>Plugin AllowTargetEverything<sup>(2)</sup></td>
    <td align="center"> - </td>
    <td align="center" colspan="5"><a href="/plugins/AllowTargetEverything/2024-05-06_6.17-build/AllowTargetEverything.dll">06/05/24 build</a></td>
  </tr>
  <tr>
    <td align="left"><b>Plugin OpenChestFromDistance<sup>(2)</sup></b><br><i>/openchest</i> chat command</td>
    <td align="center" colspan="6"><a href="/plugins/OpenChestFromDistance/2024-04-23_6.16-build/OpenChestFromDistance.dll">23/04/24 build</a></td>
  </tr>
  <tr>
    <td align="left"Modified Toolbox<br>Modified Toolbox<br><b>target everything directly enable<sup>(1)</sup></b></td>
    <td align="center"><a href="/maindll/6.16/GWToolboxdll.dll">6.16</a></td>
    <td align="center"><a href="/maindll/6.17/GWToolboxdll.dll">6.17</a></td>
    <td align="center">-</td>
    <td align="center">-</td>
    <td align="center">-</td>
    <td align="center">-</td>
  </tr
</tbody>
</table>

- (1) : To use the modified main dll file, simply replace the file <i>GWToolboxdll.dll</i> by the given file in your main <i>GWToolboxpp</i> folder.
- (2) : To use a plugin, add the given <i>.dll</i> file in the <i>computer-name/plugins</i> folder in your main <i>GWToolboxpp</i> folder. Then, in GuildWars, open Toolbox settings and go to the <i>plugins</i> section to load the one you want. Usually a chat message shows that the plugin was successfully loaded.

For last TB versions, the main TB folder is located in your Windows user <i>Documents</i> folder.


## Known issues in last versions
- With GWLauncher and with some plugins enables, a crash message can occurs on GW or TB closure.


## Disclaimer
All these features were at some point removed from the official GuildWars Toolbox because either considered outside of the usual GW bounds, or to comply Toolbox maintainers view about the tool. Some of them were never in the main tool.

Thus, some of these extra features could be considered as *unsafe* to use and could eventually lead to a ban, even if no such ban has been recorded so far.

The OpenChestFromDistance plugin is using ctos hooks, apparently known to flag your account.
