# Callgrind File Viewer and Syntax Highlighter

## Project Overview

This project is a specialized text editor developed in Qt that provides syntax highlighting and visualization for Callgrind output files. It aims to make profiling data more readable and easier to analyze for developers working with performance optimization.

## Features

- **Syntax Highlighting**: Custom highlighting for Callgrind file elements including:
  - Comments
  - Header keywords
  - File and function specifications
  - Cost lines and numbers
- **Large File Support**: Efficient processing of large Callgrind files using chunked highlighting is still in developement
- **Rich Text Formatting**: Preserves original file structure while applying highlighting
- **User-Friendly Interface**: Simple and intuitive Qt-based GUI
- **Basic and Advanced Highlighting Modes**: Toggle between different levels of syntax highlighting

## Usage

1. Launch the application
2. Use File > Open to load a Callgrind file (.callgrind)
3. The file will be displayed with syntax highlighting applied
4. To switch between basic and advanced highlighting, use the View menu or toolbar options

## Configuration

- Font settings can be adjusted in the application preferences
- Highlighting colors can be customized by modifying the `applyHighlighting` function in the source code

## Technical Details

### Key Functions

- `applyHighlighting()`: Applies syntax highlighting to the loaded text

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## Acknowledgments

- Qt framework for providing the foundation for the GUI
- Valgrind team for the Callgrind tool and file format specification

## Contact

Anchal Gera - [anchalgupta.chp@gmail.com](mailto:anchalgupta.chp@gmail.com)

Project Link: [https://github.com/your-username/callgrind-viewer](https://github.com/anchalgera/Callgrind-text-editor)

