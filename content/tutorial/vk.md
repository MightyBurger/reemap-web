+++
title = "Appendix: Virtual Key Codes"
weight = 800
+++

# Appendix: Virtual Key Codes

This page of the manual reveals some technical detail behind Reemap for reference.

Reemap handles both mouse and keyboard inputs. For keyboard inputs, Reemap uses Windows
[virtual key codes](https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes).

Reemap classifies each virtual key code in one of three categories:

|Category|Explanation|
|:--:|:--|
|Common|This key is present in most modern hardware and can be remapped.|
|Rare|This key is uncommon in present hardware or is otherwise a key you might not want to remap, and is hidden by default. These keys can be shown in the settings.|
|Unmappable|Reemap will not let you remap this key.|

Below is a comprehensive list of virtual key codes Reemap handles.

|Code     | Symbolic Name            | Category   | Reemap Name|
|:--:     |:--:                      |:--:        |:--|
| 0x01    | LBUTTON                  | Rare       | Left Click as key
| 0x02    | RBUTTON                  | Rare       | Right Click as key
| 0x03    | CANCEL                   | Rare       | Control break processing
| 0x04    | MBUTTON                  | Rare       | Middle Click as key
| 0x05    | XBUTTON1                 | Rare       | Mouse X1 as key
| 0x06    | XBUTTON2                 | Rare       | Mouse X2 as key
| 0x08    | BACK                     | Common     | Backspace
| 0x09    | TAB                      | Common     | Tab
| 0x0C    | CLEAR                    | Common     | Clear
| 0x0D    | RETURN                   | Common     | Enter
| 0x10    | SHIFT                    | Rare       | Shift (ambidextrous)
| 0x11    | CONTROL                  | Rare       | Ctrl (ambidextrous)
| 0x12    | MENU                     | Rare       | Alt (ambidextrous)
| 0x13    | PAUSE                    | Common     | Pause
| 0x14    | CAPITAL                  | Common     | Caps Lock
| 0x15    | KANA_HANGUL              | Rare       | IME Kana/Hangul
| 0x16    | IME_ON                   | Rare       | IME On
| 0x17    | JUNJA                    | Rare       | IME Junja
| 0x18    | FINAL                    | Rare       | IME Final
| 0x19    | HANJA_KANJI              | Rare       | IME Hanja/Kanji
| 0x1A    | IME_OFF                  | Rare       | IME Off
| 0x1B    | ESCAPE                   | Common     | Escape
| 0x1C    | CONVERT                  | Rare       | IME Convert
| 0x1D    | NONCONVERT               | Rare       | IME Nonconvert
| 0x1E    | ACCEPT                   | Rare       | IME Accept
| 0x1F    | MODECHANGE               | Rare       | IME Mode Change
| 0x20    | SPACE                    | Common     | Space
| 0x21    | PRIOR                    | Common     | Page Up
| 0x22    | NEXT                     | Common     | Page Down
| 0x23    | END                      | Common     | End
| 0x24    | HOME                     | Common     | Home
| 0x25    | LEFT                     | Common     | Left Arrow
| 0x26    | UP                       | Common     | Up Arrow
| 0x27    | RIGHT                    | Common     | Right Arrow
| 0x28    | DOWN                     | Common     | Down Arrow
| 0x29    | SELECT                   | Rare       | Select
| 0x2A    | PRINT                    | Rare       | Print
| 0x2B    | EXECUTE                  | Rare       | Execute
| 0x2C    | SNAPSHOT                 | Common     | Print Screen
| 0x2D    | INSERT                   | Common     | Insert
| 0x2E    | DELETE                   | Common     | Delete
| 0x2F    | HELP                     | Rare       | Help
| 0x30    | KEY0                     | Common     | 0
| 0x31    | KEY1                     | Common     | 1
| 0x32    | KEY2                     | Common     | 2
| 0x33    | KEY3                     | Common     | 3
| 0x34    | KEY4                     | Common     | 4
| 0x35    | KEY5                     | Common     | 5
| 0x36    | KEY6                     | Common     | 6
| 0x37    | KEY7                     | Common     | 7
| 0x38    | KEY8                     | Common     | 8
| 0x39    | KEY9                     | Common     | 9
| 0x41    | A                        | Common     | A
| 0x42    | B                        | Common     | B
| 0x43    | C                        | Common     | C
| 0x44    | D                        | Common     | D
| 0x45    | E                        | Common     | E
| 0x46    | F                        | Common     | F
| 0x47    | G                        | Common     | G
| 0x48    | H                        | Common     | H
| 0x49    | I                        | Common     | I
| 0x4A    | J                        | Common     | J
| 0x4B    | K                        | Common     | K
| 0x4C    | L                        | Common     | L
| 0x4D    | M                        | Common     | M
| 0x4E    | N                        | Common     | N
| 0x4F    | O                        | Common     | O
| 0x50    | P                        | Common     | P
| 0x51    | Q                        | Common     | Q
| 0x52    | R                        | Common     | R
| 0x53    | S                        | Common     | S
| 0x54    | T                        | Common     | T
| 0x55    | U                        | Common     | U
| 0x56    | V                        | Common     | V
| 0x57    | W                        | Common     | W
| 0x58    | X                        | Common     | X
| 0x59    | Y                        | Common     | Y
| 0x5A    | Z                        | Common     | Z
| 0x5B    | LWIN                     | Common     | Left Windows
| 0x5C    | RWIN                     | Common     | Right Windows
| 0x5D    | APPS                     | Common     | Menu
| 0x5F    | SLEEP                    | Common     | Sleep
| 0x60    | NUMPAD0                  | Common     | Numpad 0
| 0x61    | NUMPAD1                  | Common     | Numpad 1
| 0x62    | NUMPAD2                  | Common     | Numpad 2
| 0x63    | NUMPAD3                  | Common     | Numpad 3
| 0x64    | NUMPAD4                  | Common     | Numpad 4
| 0x65    | NUMPAD5                  | Common     | Numpad 5
| 0x66    | NUMPAD6                  | Common     | Numpad 6
| 0x67    | NUMPAD7                  | Common     | Numpad 7
| 0x68    | NUMPAD8                  | Common     | Numpad 8
| 0x69    | NUMPAD9                  | Common     | Numpad 9
| 0x6A    | MULTIPLY                 | Common     | Multiply
| 0x6B    | ADD                      | Common     | Add
| 0x6C    | SEPARATOR                | Rare       | Separator
| 0x6D    | SUBTRACT                 | Common     | Subtract
| 0x6E    | DECIMAL                  | Common     | Decimal
| 0x6F    | DIVIDE                   | Common     | Divide
| 0x70    | F1                       | Common     | F1
| 0x71    | F2                       | Common     | F2
| 0x72    | F3                       | Common     | F3
| 0x73    | F4                       | Common     | F4
| 0x74    | F5                       | Common     | F5
| 0x75    | F6                       | Common     | F6
| 0x76    | F7                       | Common     | F7
| 0x77    | F8                       | Common     | F8
| 0x78    | F9                       | Common     | F9
| 0x79    | F10                      | Common     | F10
| 0x7A    | F11                      | Common     | F11
| 0x7B    | F12                      | Common     | F12
| 0x7C    | F13                      | Common     | F13
| 0x7D    | F14                      | Common     | F14
| 0x7E    | F15                      | Common     | F15
| 0x7F    | F16                      | Common     | F16
| 0x80    | F17                      | Common     | F17
| 0x81    | F18                      | Common     | F18
| 0x82    | F19                      | Common     | F19
| 0x83    | F20                      | Common     | F20
| 0x84    | F21                      | Common     | F21
| 0x85    | F22                      | Common     | F22
| 0x86    | F23                      | Common     | F23
| 0x87    | F24                      | Common     | F24
| 0x90    | NUMLOCK                  | Common     | Num Lock
| 0x91    | SCROLL                   | Unmappable | Scroll Lock
| 0xA0    | LSHIFT                   | Common     | Left Shift
| 0xA1    | RSHIFT                   | Common     | Right Shift
| 0xA2    | LCONTROL                 | Common     | Left Ctrl
| 0xA3    | RCONTROL                 | Common     | Right Ctrl
| 0xA4    | LMENU                    | Common     | Left Alt
| 0xA5    | RMENU                    | Common     | Right Alt
| 0xA6    | BROWSER_BACK             | Rare       | Browser Back
| 0xA7    | BROWSER_FORWARD          | Rare       | Browser Forward
| 0xA8    | BROWSER_REFRESH          | Rare       | Browser Refresh
| 0xA9    | BROWSER_STOP             | Rare       | Browser Stop
| 0xAA    | BROWSER_SEARCH           | Rare       | Browser Search
| 0xAB    | BROWSER_FAVORITES        | Rare       | Browser Favorites
| 0xAC    | BROWSER_HOME             | Rare       | Browser Home
| 0xAD    | VOLUME_MUTE              | Common     | Volume Mute
| 0xAE    | VOLUME_DOWN              | Common     | Volume Down
| 0xAF    | VOLUME_UP                | Common     | Volume Up
| 0xB0    | MEDIA_NEXT_TRACK         | Common     | Media Next Track
| 0xB1    | MEDIA_PREV_TRACK         | Common     | Media Previous Track
| 0xB2    | MEDIA_STOP               | Common     | Media Stop
| 0xB3    | MEDIA_PLAY_PAUSE         | Common     | Media Play/Pause
| 0xB4    | LAUNCH_MAIL              | Common     | Start Mail
| 0xB5    | LAUNCH_MEDIA_SELECT      | Common     | Select Media
| 0xB6    | LAUNCH_APP1              | Common     | Start Application 1
| 0xB7    | LAUNCH_APP2              | Common     | Start Application 2
| 0xBA    | OEM_1                    | Common     | OEM 1
| 0xBB    | OEM_PLUS                 | Common     | Plus
| 0xBC    | OEM_COMMA                | Common     | Comma
| 0xBD    | OEM_MINUS                | Common     | Minus
| 0xBE    | OEM_PERIOD               | Common     | Period
| 0xBF    | OEM_2                    | Common     | OEM 2
| 0xC0    | OEM_3                    | Common     | OEM 3
| 0xDB    | OEM_4                    | Common     | OEM 4
| 0xDC    | OEM_5                    | Common     | OEM 5
| 0xDD    | OEM_6                    | Common     | OEM 6
| 0xDE    | OEM_7                    | Common     | OEM 7
| 0xDF    | OEM_8                    | Rare       | OEM 8
| 0xE2    | OEM_102                  | Common     | OEM 102
| 0xE5    | PROCESSKEY               | Rare       | IME Process
| 0xE7    | PACKET                   | Rare       | Unicode Packet
| 0xF6    | ATTN                     | Rare       | Attn
| 0xF7    | CRSEL                    | Rare       | CrSel
| 0xF8    | EXSEL                    | Rare       | ExSel
| 0xF9    | EREOF                    | Rare       | Erase EOF
| 0xFA    | PLAY                     | Rare       | Play
| 0xFB    | ZOOM                     | Rare       | Zoom
| 0xFC    | NONAME                   | Unmappable | Reserved
| 0xFD    | PA1                      | Rare       | PA1
| 0xFE    | OEM_CLEAR                | Rare       | OEM Clear












































































































































































