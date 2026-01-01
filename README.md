# XDG App Menu with Python
A simple XDG desktop file launcher written in Python.

## Features
- Categorized menu display
- Vi-like key binds
- Regex search

## Requirements
- Python3
- GTK3
- Python bindings for GTK3
- xdg-open

If you are using a typical desktop environment on a stable version of the distribution,
these are likely already installed.

I have confirmed that it works with the version
that can be installed via apt in Debian 13.

## Usage
Run the following command:
```shell
./applauncher
```

You can use the following key operations:
| key          | description                                         |
| :----------: | :----------                                         |
| k            | Move cursor up                                      |
| j            | Move cursor down                                    |
| l            | Move cursor right / Go to the application selection |
| h            | Move cursor left / Quit the application selection   |
| /            | Focus search box                                    |
| Esc          | Exit program / Quit the application selection       |

## License
This project is licensed under the MIT License.
Please read the [LICENSE](LICENSE) file for details.
