# KeyLogger
Simple Java keylogger using [JNativehook](https://github.com/kwhat/jnativehook).


## Features
- Writes all keypress/release/typed events to a log file in the format: `ARROW` `KEY`, where `KEY` is the textual representation of the key pressed/released/typed and `ARROW` in the format of:

| Arrow | Event     |
|:-----:|-----------|
| ↓     | Pressed   |
| ↑     | Releassed |
| ↨     | Typed     |

- System tray icon with items for showing the log file, error log and exiting the program.
- Error message on error instead of silently failing (not that it should fail).


## Usage
`java -jar KeyLogger.jar <log directory>`
