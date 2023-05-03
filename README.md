# Patterns for .gitignore files
| Pattern | Explanation/Matches | Examples |
| -------- | -------- | -------- |
| file.txt | All files with file.txt will be ignored | file.txt |
| Lines starting with a # symbol | These lines are comments and will be ignored by git | # this is a gitignore file|
| Blank lines | Blank lines are ignored by  git |  |
| *.txt | ignores all files that end with .txt extension or the specified extension | samp.txt, file1.txt, file2.txt, example.txt will all be ignored |
| logs/ | ignores the logs directory and all of its contents (or the specified directory) | logs/, node_modules/, pycache/ |
| ** | Matches directories and their sub-directories | to ignore files with '.tmp' extension in any directory, we will use `**/*.tmp` |
| ! | includes a file or a directory that would otherwise be ignored | Row 3, Column 3 |
| Row 3, Column 1 | Row 3, Column 2 | Row 3, Column 3 |
| Row 3, Column 1 | Row 3, Column 2 | Row 3, Column 3 |
