public
======

public libraries

---
### Commands to use-

1. Clone the repository:
   git clone https://github.com/bhanupe/public
2. Navigate to the repository:
   cd public
3. Create and switch to a new branch:
   git checkout -b yt-upw-1
4. Create a folder named utilities:
   mkdir utilities
5. Create a sub-folder named word_processors under utilities:
   mkdir utilities/word_processors
6. Move the find_anagrams.py file to the word_processors folder:
   mv <path_to_find_anagrams.py> utilities/word_processors/
7. Stage the file for commit:
   git add utilities/word_processors/find_anagrams.py
8. Commit the file with a meaningful message:
   git commit -m "[UPW-1] [Deliver findanagrams.py 01-04-2025]"


### Usage Instructions for `find_anagrams.py`

### How to Use `find_anagrams.py`

1. Input File Organization:
   - Place input word files (e.g.,`.txt` files) in a specificfolder for processing with recursively spread in sub folders 
   - Each file should contain a list of words, one word per line.

2. Running the Script:
   - Navigate to the directory containing the script:
     cd utilities/word_processors
   - Run the script with the input file as an argument:
     python3 find_anagrams.py Words.txt
     
3. Examples of Input Files:
   - Download word lists from websites like:
     - https://www.levidromelist.com/levidrome-list/dictionary
     - https://www.keithv.com/software/wlist/
   - Ensure the files are plain text (`.txt`) and formatted as one word per line.

4. Limitations:
   - Supported: `.txt` files with UTF-8 encoding.
   - Not Supported: Binary files, PDFs, or other non-text formats. Avoid using files with unsupported characters or formats.
