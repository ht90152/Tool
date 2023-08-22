# OS
Windows

# AutoHotkey v1.1
https://www.autohotkey.com/

# Function
| Group | Function | Note | Hotkey |
| ---- | ---- | ---- | ---- |
| Show | showHotkeys() | Show Hotkeys | [Ctrl+Alt+K] |
| | showVersion() | Show Version | [Ctrl+Alt+B] |
| HotGUI | hot_gui("hotstr") | Hotstring GUI | [Ctrl+Alt+H] |
| | hot_gui("hotkey") | Hotkey GUI | [Ctrl+Alt+E] |
| Recorder | toRecordScreen() | Record Screen | [F1] |
| | toRecordWindow() | Record Window | [F2] |
| | Pause() | Pause Record | [F3] |
| | Stop() | Stop Record | [F4] |
| | Play() | Play Record | [F5] |
| | Edit() | Edit Record | [F6] |
| OCR | OCR() | OCR & save to clipboard | [Ctrl+Alt+C] |
| TTS | ttsSpeech() | TTS Speech selection | [Ctrl+Alt+1] |
| | ttsPause() | TTS Play/Pause | [Ctrl+Alt+2] |
| | ttsStop() | TTS Stop | [Ctrl+Alt+3] |
| Web | googleSearch() | Google Search selection | [Ctrl+Alt+G] |
| | google_translate() | Google translate selection | [Ctrl+Alt+J] |
| Date | sendDate() | Send Date (yyyy-MM-dd) | [Ctrl+Alt+D] |
| Text | reInput() | reInput selection (after changing input mode from english to 注音 youself) | [Ctrl+Alt+R] |
| | toUpper() | Uppercase selection | [Ctrl+Alt+U] |
| | toLower() | Lowercase selection | [Ctrl+Alt+L] |
| | trimStr() | Trim selection | [Ctrl+Alt+T] |
| Shutdown | cmdShut() | Schedule Shutdown | [Ctrl+Alt+S] |
| | cancelShut() | Cancel Scheduled Shutdown | [Ctrl+Alt+A] |
| Window | sendAltTab() | Switch window | [LButton+RButton] |
| | showDesktop() | Show Desktop | [RButton+LButton] |
| File | toggleHiddenFilesDisplay() | Toggle Hidden Files Display | [Ctrl+Alt+F] |
| | RUN ::{645FF040-5081-101B-9F08-00AA002F954E} | Open Recycle Bin | [Ctrl+Alt+X] |
| APP | Winset, Alwaysontop, , A | Selected Window Always on top | [Ctrl+F1] |
| | Pause | Pause APP | [Ctrl+F2] |
| | Suspend | Suspend Hotkey |  [Ctrl+F3] |
| | ExitApp | Exit APP |  [Ctrl+F4] |
| | Reload | Reload APP | [Ctrl+F5] |

# Add your script
1. new directory named "lib"
2. add your script in directory "lib"
3. include your script in Includes.ahk
4. add function in your script with Hotkey GUI

# Version
major. minor(. build)\
主版號：當你做了不相容的 API 修改\
次版號：當你做了向下相容的功能性新增\
修訂號：當你做了向下相容的問題修正

| Date | Version | Type | Note | Reference |
| ---- | ---- | ---- | ---- | ---- |
| 2021-03-11 | 0.1.0 | Feature |  |  |
| 2022-03-11 | 1.0.0 | Feature | mouse over tray icon show GUI |  |
| 2022-03-14 | 1.1.0 | Refactor | split Recorder.ahk from tool.ahk and include it | https://www.autohotkey.com/boards/viewtopic.php?t=34184 |
| 2022-03-28 | 1.2.0 | Feature | add GUI_Hotstr.ahk |  |
| 2022-05-29 | 1.3.0 | Feature | add TTS.ahk |  |
| 2022-05-31 | 1.4.0 | Refactor | add gui of hotkey/hotstring to edit Tool.ahk & include lib dir with Includes.ahk(but cannot use in exe) | |
| 2022-06-12 | 1.4.1 | Refactor | change gui of hotkey/hotstring to edit Hot_def.ahk & change [label] to [function] in Recorder.ahk | |
| 2022-06-16 | 1.5.0 | Feature | check new version online |  |
| 2022-07-06 | 1.5.1 | Fix | autorun Hot_def.ahk & change TTS rate & change url of Tool.zip |  |
| 2022-08-05 | 1.5.2 | Fix | add google_translate() & repair bug (reInput()、googleSearch()) |  |
| 2022-08-08 | 1.5.3 | Fix | fix text of Hotkey GUI |  |
| 2023-08-22 | 1.5.4 | Fix | fix update function(check network) & rename exe with version |  |
