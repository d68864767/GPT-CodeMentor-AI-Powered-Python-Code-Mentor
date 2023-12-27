# GPT-CodeMentor: AI-Powered Python Code Mentor

## Project Introduction and Purpose

GPT-CodeMentor is a Python script that leverages GPT (Generative Pre-trained Transformer) technology to provide mentorship and code reviews for Python developers. The script analyzes Python code and offers suggestions, explanations, and improvements. It aims to assist Python developers in improving their coding skills and producing higher-quality code by providing AI-driven mentorship and code reviews. It offers valuable guidance for developers at various skill levels.

## Installation Instructions

1. Clone the repository to your local machine.
2. Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

## Usage Guide with Examples

To use GPT-CodeMentor, run the script from the command line with the Python file you want to analyze as an argument:

```bash
python GPT-CodeMentor.py your_file.py
```

You can also specify the depth of code review you desire (1-3) using the `-l` or `--level` option:

```bash
python GPT-CodeMentor.py your_file.py -l 2
```

## Supported Code Review Categories

GPT-CodeMentor supports the following code review categories:

1. Code Structure Analysis
2. Code Quality Analysis
3. Adherence to Best Practices
4. AI-Powered Code Review Suggestions
5. Explanations for Code Review Suggestions

## Customization Options

You can customize the depth of code review by specifying a level (1-3) when running the script. Level 1 includes basic style checks, while level 3 includes in-depth optimization suggestions.

## How GPT-CodeMentor Works

GPT-CodeMentor uses OpenAI's GPT API for natural language processing and code analysis. It first ensures the code file is safe to analyze, then analyzes the code structure and quality, and finally reviews the code and provides suggestions for improvement.

## Acknowledgments and Credits

This project uses the following open-source packages:

- OpenAI's GPT API
- pylint
- ast
- astor

## Contribution Guidelines

If you want to contribute to this project, please submit a pull request.

## License Information

This project is licensed under the MIT License.

## Testing and Validation

The script includes a test suite that ensures the code reviews and suggestions provided are accurate, helpful, and well-structured. To run the tests, use the following command:

```bash
python -m unittest test.py
```

## Security Measures

GPT-CodeMentor includes security measures to protect user data and ensure the safe handling of code files. It checks if the file exists, if it's a Python file, if it's too large, and if it's known to be malicious.

## Error Handling

The script includes error-handling mechanisms to gracefully handle unexpected issues during code analysis and review.

## Documentation and Comments

The code is well-structured and well-documented, with comments explaining the purpose and functionality of each section.

## Continuous Improvement

We plan for ongoing improvements and updates to enhance the script's code analysis capabilities and review suggestions. User feedback is encouraged to help guide these improvements.

## User Feedback

We encourage users to provide feedback on the quality and usefulness of the AI-powered code reviews and mentorship. Please submit your feedback as an issue on the project's GitHub page.
