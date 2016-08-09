# CHANGES

## Version 1.1.3
- gamepad_set_callback の第1引数(ctx) に NULL を指定できるようにする

## Version 1.1.2
- README.md の改定のみ

## Version 1.1.1
- XCode でビルドした時に警告が出ないようにする

## Version 1.1.0
- キーボード と マウス の入力にも対応
- gamepad_init の仕様を変更 (破壊的変更)
  - before: `void* gamepad_init();`
  - after: `void* gamepad_init(int useGamePad, int useKeybord, int useMouse);`

## Version 1.0.0
- first version
- 以降, 更新は Pull Request でおこないます

