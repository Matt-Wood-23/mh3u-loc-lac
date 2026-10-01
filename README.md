# Loc Lac City for Monster Hunter 3 Ultimate

Loc Lac City from Monster Hunter Tri, brought into Monster Hunter 3 Ultimate on Cemu. It takes
the place of Port Tanzia: go to the port the way you always do and you arrive in Loc Lac.

Version 0.1.0-beta. Made by Matt.

## What's in it

- **The city:** the gate, the streets, the market and the tavern, with its animated airship,
  balloons, gears and torches. The camera works like it did in Tri.
- **People and shops:** the city's stalls and vendors, the farm and trade menus, and a City
  Greeter with a few new things to say.
- **The tavern:** seats (with food), the item box, the quest board, departures and arm wrestling.
- **A room to decorate,** with Chamberlyne and a Poogie.
- **Tri's music,** with Loc Lac's own day and night themes.
- **Day and night,** swapping every real hour like in Tri.
- **The Jhen Mohran sandstorm:** sand in the sky and on the wind, with its own music. Switch it on
  whenever you like.

Everything is inside one Cemu graphic pack. Your game files are never changed, and turning the
pack off brings Port Tanzia back.

## What you need

- **Cemu** (a recent 2.x version).
- **Monster Hunter 3 Ultimate, US or EU, with the v1.3 update installed.** In Cemu's game list
  the game should show version **v32**. Without the update the pack can't work: the town files
  load but the rest doesn't.
- The Japanese version (MH3G HD Ver.) isn't supported yet. See the end of this page.

## Install

1. Download `LocLacCity_0.1.0-beta.zip` from the Releases page.
2. In Cemu, open **File → Open Cemu folder**, then open the `graphicPacks` folder.
3. Copy the `MH3U_LocLac` folder from the zip into `graphicPacks`. You should end up with
   `graphicPacks/MH3U_LocLac/rules.txt`, not `MH3U_LocLac/MH3U_LocLac/...`.
   - Don't put it inside `downloadedGraphicPacks`. Cemu empties that folder whenever it
     downloads the community packs.
4. Open **Options → Graphic packs** and go to **Monster Hunter 3 Ultimate → Mods → Loc Lac
   City**. Tick it.
5. Start the game and head to Port Tanzia. You'll arrive in Loc Lac.

## Settings

Choose these in the Graphic packs window when you tick the pack. If the game is already running,
restart it after changing them.

| Setting | Choices |
| --- | --- |
| Day and night | **Hourly** (like Tri: day and night swap every real hour), **Half-hourly** (night from :30 to :59), **Always day**, **Always night** |
| Sandstorm (Jhen Mohran event) | **Off**, **On** |

## Playing online

The pack works in online rooms, for example with the
[MH3U Revival](https://github.com/Matt-Wood-23/mh3u-revival) server. Everyone in the room should
use the pack, and the same version of it. A player without the pack can still join you on
quests, but in town you'll see each other in odd places, because their Port Tanzia and your Loc
Lac are laid out differently.

## Updating and removing

- **To update:** delete the old `MH3U_LocLac` folder first, then copy in the new one.
- **To remove:** untick the pack in the Graphic packs window, or delete the `MH3U_LocLac` folder.
  Port Tanzia comes back.
- **Your save** keeps working either way: a save played with the pack loads fine without it.

## Known issues

- The room's furniture layout isn't saved. It resets the next time you play.
- The City Greeter speaks English in every language.
- Changing a setting needs a game restart.
- In a room where some players don't use the pack, the town looks odd for everyone (see above).

## Problems and feedback

Please open an issue on this project's GitHub page:
<https://github.com/Matt-Wood-23/mh3u-loc-lac/issues>.

If the town doesn't work, include Cemu's `log.txt` (it's in the Cemu folder). A working setup
lists four lines starting `Applying patch group 'MH3U_LocLac_`.

## 日本のプレイヤーの皆さまへ

申し訳ありません。このMODは現在、北米版と欧州版の『MONSTER HUNTER 3 ULTIMATE』（v1.3）にのみ対応しており、
日本版『モンスターハンター3（トライ）G HD Ver.』では動作しません。日本版はゲームのプログラムが大きく異なるため、
対応にはかなりの作業が必要です。

日本版での対応を希望される方は、GitHubの Issues でお知らせください（日本語で大丈夫です）。
希望が多ければ、対応に挑戦します。

## Credits

Loc Lac City, its music and Monster Hunter are © Capcom. This is an unofficial fan project, not
made or endorsed by Capcom. You need your own copy of Monster Hunter 3 Ultimate to use it.
