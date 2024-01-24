# basics-commands
| Command | Description | Example |
| --- | --- | --- |
| cd /path/to/directory | Change the current directory | cd /path/to/directory - Navigate to a specific folder |
| pwd | Print the current working directory | pwd - Display the current directory path |
| ls -l | List files with details. | ls -l - List files with details. |
| ls -a | List all files, including hidden ones. | ls -a - List all files, including hidden ones. |
| ls -t | Sort files by modification time. | ls -t - Sort files by modification time. |
| ls -h | List sizes in human-readable format. | ls -h - List sizes in human-readable format. |
| ls -R | Recursively list subdirectories. | ls -R - Recursively list subdirectories. |
| cp -r | Copy directories and their contents recursively. | cp -r source_directory/ destination_directory/ - Copy a directory recursively. |
| cp -i | Prompt before overwriting existing files. | cp -i file.txt new_folder/ - Prompt before overwriting. |
| cp -u | Copy only when the source file is newer. | cp -u source.txt destination.txt - Copy if newer. |
| cp -v | Enable verbose mode to display what's being copied. | cp -v file.txt new_folder/ - Enable verbose mode. |
| mv -u | Move only when the source file is newer. | mv -u source.txt destination.txt - Move if newer. |
| mv -i | Prompt before overwriting existing files. | mv -i old.txt new.txt - Prompt before overwriting. |
| mv -v | Enable verbose mode to display the move operation. | mv -v old.txt new.txt - Enable verbose mode. |
| rm -r | Remove directories and their contents recursively. | rm -r directory_to_remove/ - Remove a directory recursively. |
| rm -i | Prompt before each removal. | rm -i file.txt - Prompt before removing. |
| rm -f | Forcefully remove without prompting. | rm -f file.txt - Forcefully remove. |
| find -name | Search for files with a specific name. | find /path/to/search -name "*.txt" - Find .txt files by name. |
| find -type | Search for specific types (e.g., f for files). | find /path/to/search -type d - Find directories. |
| find -exec | Execute a command on each found item. | find /path/to/search -exec grep "pattern" {} \; - Execute grep on found files. |
| grep | Search for a pattern in files. | grep "search_text" file.txt - Search for text in a file |
| grep -i | Ignore case distinctions in the search pattern. | grep -i "search_text" file.txt - Case-insensitive search. |
| grep -r | Recursively search directories. | grep -r "pattern" /path/to/search - Recursive search. |
| grep -n | Show line numbers for matched lines. | grep -n "pattern" file.txt - Show line numbers. |
| cat | Display the content of a file | cat file.txt - Display the content of "file.txt" |
| nano | Create or edit a file with Nano | nano new_file.txt - Create or edit a file with Nano |
| less | View file content with paging | less file.txt - View "file.txt" page by page |
| head | Display the beginning of a file | head -n 10 file.txt - Display the first 10 lines of "file.txt" |
| tail | Display the end of a file | tail -n 5 file.txt - Display the last 5 lines of "file.txt" |
| touch | Create an empty file | touch new_file.txt - Create an empty file |
| mkdir | Create a new directory | mkdir new_directory - Create a directory named "new_directory" |
| xdg-open | Open a file or URL using the default application. | xdg-open file.txt - Open "file.txt" with the default app |
| nautilus | Open the file manager. | nautilus - Open the file manager. |
| open | Open a file or folder using the default application | open file.txt - Open "file.txt" with the default app |