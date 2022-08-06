# Function
| Group | Function | Note |
| ---- | ---- | ---- |
| show | showHotkeys() | Show Hotkeys |
| | showVersion() | Show Version |
| hotGUI | hot_gui("hotstr") | Hotstring GUI |
| | hot_gui("hotkey") | Hotkey GUI |
| Recorder | toRecordScreen() | Record Screen |
| | toRecordWindow() | Record Window |
| | Pause() | Pause Record |
| | Stop() | Stop Record |
| | Play() | Play Record |
| | Edit() | Edit Record |
| OCR | OCR() | OCR & save to clipboard |
| TTS | ttsSpeech() | TTS Speech selection |
| | ttsPause() | TTS Play/Pause |
| | ttsStop() | TTS Stop |
| web | googleSearch() | Google Search selection |
| | google_translate() | Google translate selection |
| Date | sendDate() | Send Date (yyyy-MM-dd) |
| Text | reInput() | reInput selection (after changing input mode youself) |
| | toUpper() | Uppercase selection |
| | toLower() | Lowercase selection |
| | trimStr() | Trim selection |
| Shutdown | cmdShut() | Schedule Shutdown |
| | cancelShut() | Cancel Scheduled Shutdown |
| window | sendAltTab() | Switch window |
| | showDesktop() | Show Desktop |
| File | toggleHiddenFilesDisplay() | Toggle Hidden Files Display |
| | RUN ::{645FF040-5081-101B-9F08-00AA002F954E} | Open Recycle Bin |

# Add your script
1. new directory named "lib"
2. add your script in directory lib
3. add function in your script with Hotkey GUI

# Version
major. minor(. build)\
主版號：當你做了不相容的 API 修改\
次版號：當你做了向下相容的功能性新增\
修訂號：當你做了向下相容的問題修正\

| Date | Version | Type | Note |
| ---- | ---- | ---- | ---- |
| 2021-03-11 | 0.1.0 | Feature | | |
| 2022-03-11 | 1.0.0 | Feature | mouse over tray icon show GUI |
| 2022-03-14 | 1.1.0 | Refactor | split Recorder.ahk from tool.ahk and include it |
| 2022-03-28 | 1.2.0 | Feature | add GUI_Hotstr.ahk |
| 2022-05-29 | 1.3.0 | Feature | add TTS.ahk |
| 2022-05-31 | 1.4.0 | Refactor | add gui of hotkey/hotstring to edit Tool.ahk & include lib dir with Includes.ahk(but cannot use in exe) |
|2022-06-12 | 1.4.1 | Refactor | change gui of hotkey/hotstring to edit Hot_def.ahk & change [label] to [function] in Recorder.ahk |
| 2022-06-16 | 1.5.0 | Feature|check new version online |
| 2022-07-06 | 1.5.1 | Fix | autorun Hot_def.ahk & change TTS rate & change url of Tool.zip |
| 2022-08-05 | 1.5.2 | Fix | add google_translate() & repair bug (reInput()、googleSearch()) |

