# 残響のダンジョン / Echo Dungeon / 回响地牢

## 日本語

### 概要
残響のダンジョンは、スマートフォンでもPCでも遊べる見下ろし型フィールドダンジョンアクションゲームです。
プレイヤーキャラクターを上下左右に動かしながら、敵を魔法で攻撃して、鍵や宝箱を集め、出口を目指すゲームです。

タイトルは index.html として保存されている前提です。

### 対応言語
このゲームとREADMEは、以下の言語に対応しています。

- 日本語
- English
- 简体中文

ゲーム中の言語は、タイトル画面の言語選択、または上部の言語切り替えボタンで変更できます。

### 遊び方
1. README.md と同じフォルダ、または任意のフォルダに index.html を保存してください。
2. index.html をブラウザで開いてください。
3. タイトル画面で ゲーム開始 を押すと遊べます。
4. 途中でセーブデータが残っていれば、続きからを選ぶことができます。

### PCでの操作方法
移動:
- WASD
- 方向キー

攻撃:
- Space
- J
- X

一時停止:
- Esc
- 上部の一時停止ボタン

言語切り替え:
- 上部の言語ボタン
- タイトル画面または一時停止画面の言語選択

サウンド切り替え:
- 上部のサウンドボタン

### スマートフォンでの操作方法
移動:
- 左下の仮想スティック

攻撃:
- 右下の攻撃ボタン

一時停止:
- 上部の一時停止ボタン

言語切り替え:
- 上部の言語ボタン
- タイトル画面または一時停止画面の言語選択

サウンド切り替え:
- 上部のサウンドボタン

### ゲームのルール
- 敵を倒しながら進む見下ろし型アクションゲームです。
- 鍵を集めると、次の目標が解放されます。
- 宝箱を開けると、回復アイテム、追加コイン、上位武器などが入ることがあります。
- 一定数の鍵を集めたうえでボスを倒すと、出口が有効になります。
- 出口に到達するとステージクリアです。
- 複数のステージを連続して遊ぶことができます。
- 1ステージは、目安として3分から5分程度でクリアできるように設計されています。

### 主な機能
- 縦長画面対応
- スマートフォン向けタッチ操作
- PCキーボード操作
- サウンドON / OFF
- 多言語表示
- ローカルセーブデータ保存
- ステージ選択
- 敵の種類を多く用意
- ボス戦
- 武器強化
- 宝箱、鍵、回復、コインなどのアイテム
- 攻撃エフェクト、被弾演出、カメラ処理、パーティクル演出

### ステージについて
このゲームには、多数のステージが含まれています。
ゲーム開始時点では、最初のステージのみが選択可能です。
ステージクリアを進めると、次のステージが順次解放されます。
ステージ選択画面では、遊べるステージから選んで再開できます。

### 敵について
ステージが進むと、より強い敵や行動パターンの異なる敵が出現します。
主な敵の種類には、素早い敵、遠距離攻撃を行う敵、壁を通過する幽霊系の敵、大型の耐久型、ボス系などがあります。

### ボスについて
一部のステージにはボスが配置されます。
ボスを倒すと、ボスバーが表示され、攻撃パターンに応じてリング弾、貫通弾、突進、敵の追加召喚などの行動を行います。
ボスを倒したうえで鍵を集めると出口が解放されます。

### 保存データについて
このゲームは、保存データをブラウザのローカルストレージに保存します。
保存される主な項目は、解放済みステージ、記録時間、言語設定、サウンドON / OFF設定です。

ブラウザの履歴やサイトを削除すると、セーブデータも消えることがあります。
別端末や別ブラウザでは、自動的にセーブデータは引き継がれません。

### サウンドについて
ゲーム内の音は、タイトル画面や一時停止画面の言語選択付近、または上部のサウンドボタンからON / OFFできます。
スマートフォンのマナーモードやブラウザの自動音声規制により、最初から音が出ない場合があります。
その場合は、画面のボタンやキーを一度押して、ユーザー操作を開始してください。

### 推奨環境
- 最新バージョンのブラウザ
- 縦長レイアウト対応のPCまたはスマートフォンブラウザ
- JavaScript実行可能
- ローカルストレージ利用可能

### トラブル対処
音が出ない場合:
- サウンドボタンがOFFになっていないか確認してください。
- ブラウザの音声許可設定を確認してください。
- 一度画面操作を押して、オーディオを有効化してください。

セーブできない場合:
- ブラウザがローカルストレージを許可しているか確認してください。
- 秘密ウィンドウやシークレットモードでは、保存できないことがあります。
- 画面下部の初期化ボタンでセーブデータがリセットされていないか確認してください。

表示が崩れる場合:
- 画面回転を許可している場合は、縦表示を固定して確認してください。
- 古いブラウザや一部のWebViewアプリでは、Canvas描画や音声再生が制限されることがあります。

### 再配布について
このREADMEは、同梱ゲームの説明用として作成されています。
index.html を削除したり、README.md と index.html の相対的な位置関係が大きく変わらない限り、そのまま開いて動作させることができます。

---

## English

### Overview
Echo Dungeon is a top-down dungeon action game playable on both smartphones and PCs.
The player moves a character in four directions, magic attacks enemies, collects keys and chests, and reaches the exit after clearing objectives.

This document assumes the game file is saved as index.html.

### Supported Languages
This game and this README support the following languages:

- Japanese
- English
- Simplified Chinese

The in-game language can be changed from the language select on the title screen, or from the language button at the top of the game screen.

### How to Play
1. Save index.html in any folder, preferably the same folder as README.md.
2. Open index.html in a modern browser.
3. Press Start on the title screen.
4. If local save data exists, you can choose Continue.

### PC Controls
Move:
- WASD
- Arrow keys

Attack:
- Space
- J
- X

Pause:
- Esc
- Pause button at the top of the screen

Change language:
- Language button at the top
- Language selector on the title or pause screen

Toggle sound:
- Sound button at the top

### Mobile Controls
Move:
- Virtual joystick in the lower-left

Attack:
- Attack button in the lower-right

Pause:
- Pause button at the top

Change language:
- Language button at the top
- Language selector on the title or pause screen

Toggle sound:
- Sound button at the top

### Game Rules
- Defeat enemies while exploring a dungeon.
- Collect keys to unlock the next objective.
- Open chests to find recovery items, coins, or better weapons.
- After collecting the required keys and defeating the boss, the exit becomes active.
- Reach the exit to clear the stage.
- The game contains many stages.
- Each stage is designed to take roughly 3 to 5 minutes.

### Main Features
- Portrait screen layout
- Touch controls for smartphones
- Keyboard controls for PCs
- Sound on / off
- Multilingual UI
- Local save data
- Stage selection
- Many enemy types
- Boss battles
- Weapon upgrades
- Chests, keys, recovery, coins, and other items
- Attack effects, hit effects, camera behavior, and particle effects

### Stages
The game contains many stages.
At the beginning, only the first stage is available.
Clearing a stage unlocks the next one.
In the stage select screen, you can start from an unlocked stage.

### Enemies
More advanced stages introduce enemies with stronger stats and different behavior patterns.
Enemy types include fast enemies, ranged attackers, wall-passing ghost-like enemies, large durable enemies, and boss-type enemies.

### Bosses
Some stages contain bosses.
After a boss is engaged, a boss health bar is shown. Bosses may attack with ring bullets, aimed bullets, charges, or enemy summons.
After collecting the required keys and defeating the boss, the exit becomes available.

### Save Data
The game saves data to the browser's local storage.
Saved data includes unlocked stages, best times, language settings, and sound settings.

Clearing browser history or site data may delete the save.
Save data is not automatically carried over to another device or another browser.

### Sound
Sound can be turned on or off from the top sound button or the sound selector on the title and pause screens.
On some smartphones or browsers, audio may be blocked until a user interaction occurs.
Press a button or key once to enable audio.

### Recommended Environment
- A modern browser
- A browser that supports portrait layout
- JavaScript enabled
- Local storage enabled

### Troubleshooting
If sound does not play:
- Make sure the sound setting is not off.
- Check the browser's audio permission.
- Press a button or key once to resume audio.

If saving does not work:
- Check that the browser allows local storage.
- Private or incognito mode may not keep save data.
- Check whether the save data was reset from the title screen.

If the layout appears broken:
- Try keeping the device in portrait mode.
- Some older browsers or WebView apps may restrict canvas rendering or audio playback.

### Redistribution
This README is written to document the bundled game.
It should remain usable as long as index.html is not deleted and the file remains openable in a browser.

---

## 简体中文

### 概述
回响地牢是一款可在智能手机和PC上游玩的俯视角地牢动作游戏。
玩家控制角色上下左右移动，用魔法攻击敌人，收集钥匙和宝箱，在完成目标后前往出口。

本文档默认游戏文件已保存为 index.html。

### 支持语言
本游戏和本README支持以下语言：

- 日本語
- English
- 简体中文

游戏内语言可以通过标题界面的语言选择，或游戏界面上方的语言切换按钮进行修改。

### 玩法
1. 将 index.html 保存到任意文件夹，最好和 README.md 放在同一文件夹。
2. 用浏览器打开 index.html。
3. 在标题界面点击开始游戏即可游玩。
4. 如果存在本地存档，可以选择继续游戏。

### PC操作
移动：
- WASD
- 方向键

攻击：
- Space
- J
- X

暂停：
- Esc
- 界面上方的暂停按钮

切换语言：
- 上方语言按钮
- 标题界面或暂停界面的语言选择

切换声音：
- 上方声音按钮

### 智能手机操作
移动：
- 左下方虚拟摇杆

攻击：
- 右下方攻击按钮

暂停：
- 上方暂停按钮

切换语言：
- 上方语言按钮
- 标题界面或暂停界面的语言选择

切换声音：
- 上方声音按钮

### 游戏规则
- 一边击破敌人一边前进的地牢动作游戏。
- 收集钥匙可解锁后续目标。
- 打开宝箱可能获得回复道具、金币或更好的武器。
- 收集足够钥匙并击败Boss后，出口会开启。
- 到达出口即可通关。
- 游戏包含大量关卡。
- 每个关卡的通关时间大约为3到5分钟。

### 主要功能
- 竖屏画面适配
- 智能手机触摸操作
- PC键盘操作
- 声音开启 / 关闭
- 多语言界面
- 本地存档
- 关卡选择
- 多种敌人类型
- Boss战
- 武器强化
- 宝箱、钥匙、回复、金币等道具
- 攻击特效、受击表现、镜头处理、粒子效果

### 关卡说明
游戏包含大量关卡。
刚开始时只能选择第一关。
通关后会依次解锁下一关。
在关卡选择界面可以从已解锁的关卡开始游玩。

### 敌人说明
随着关卡推进，会出现能力更强、行动方式不同的敌人。
敌人类型包括高速敌人、远程攻击敌人、可以穿过墙壁的幽灵系敌人、大型耐久敌人以及Boss系敌人。

### Boss说明
部分关卡中存在Boss。
遭遇Boss后，屏幕上方会显示Boss血量条。Boss会使用环形弹幕、瞄准弹、冲锋、召唤敌人等攻击方式。
收集足够钥匙并击败Boss后，出口会解锁。

### 存档说明
本游戏会把存档数据保存到浏览器本地存储中。
保存的数据主要包括已解锁关卡、最佳记录时间、语言设置、声音开关。

清除浏览器历史或站点数据时，存档可能会消失。
不同设备或不同浏览器不会自动继承存档。

### 声音说明
可以通过上方声音按钮，或标题界面和暂停界面的声音开关来开启或关闭声音。
部分智能手机或浏览器会在用户首次操作前阻止声音播放。
此时请先点击按钮或按键一次，以启用音频。

### 推荐环境
- 最新版浏览器
- 支持竖屏布局的PC或智能手机浏览器
- 允许JavaScript运行
- 允许使用本地存储

### 故障处理
声音无法播放时：
- 请确认声音开关是否为关闭状态。
- 请检查浏览器是否允许声音播放。
- 请先点击一次界面按钮或按一次按键。

无法存档时：
- 请确认浏览器是否允许使用本地存储。
- 隐私模式或无痕模式可能不会保存数据。
- 请确认是否误按了标题界面的清除存档按钮。

界面显示异常时：
- 建议固定为竖屏显示再确认。
- 某些旧版浏览器或WebView应用可能限制Canvas绘图或音频播放。

### 再分发说明
本README用于说明同梱游戏。
只要保留 index.html，并且可以在浏览器中打开，通常就可以照常游玩。