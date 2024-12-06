# Code Combine

## Overview
Code Combine is a Python application that merges multiple code files from a selected directory into a single markdown file. This is particularly useful for preparing code snippets for Large Language Models (LLMs), as they process code more efficiently when provided with full context rather than individual file uploads.

## Features
- Select a directory containing code files.
- Combines all code files into a single markdown file.
- Handles encoding issues gracefully.
- Outputs the markdown file with a naming convention based on the directory and date.

## Requirements
- Python 3.x
- PyQt5

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/code-combine.git
   cd code-combine
   ```

2. Install the required packages:
   ```bash
   pip install PyQt5
   ```

## Usage
1. Run the application:
   ```bash
   python code-combine.py
   ```

2. Click on "Select Directory" to choose the folder containing your code files.

3. The application will create a markdown file named `directoryName_YYYY-MM-DD_output.md` in the current working directory.

## Motivation
I created this tool because I've noticed that LLMs process code more efficiently when you paste in the full context rather than uploading individual files. This application helps streamline that process.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact
For questions or feedback, please reach out to [your-email@example.com].
