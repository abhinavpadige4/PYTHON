### Project Name: **MadLib Story Generator**

---

### Description:

This project is a simple **MadLib Story Generator** that reads a text file containing a story template, identifies placeholders for words (enclosed in `<` and `>`), prompts the user to provide replacements for those placeholders, and then outputs the complete story with the provided words.

---

### Files:

1. **`story.txt`**: This is the text file containing the story template. It includes placeholders enclosed in `<` and `>` which will be replaced by user input.
2. **`madlib_story_generator.py`**: The Python script that runs the MadLib generator.

---

### Code Overview:

- The program opens the `story.txt` file and reads its content.
- It scans the story to find words enclosed within `<` and `>`, identifying them as placeholders.
- The program prompts the user to provide words to replace each placeholder.
- Finally, the script replaces the placeholders with the user-provided words and prints the completed story.

---

### How to Run:

1. **Prepare the Story Template**: Create a `story.txt` file with your story, using placeholders wrapped in `<` and `>`. For example:
   ```
   Once upon a time, there was a <noun> who lived in a <place>. Every day, the <noun> would <verb> with <adjective> joy.
   ```
2. **Run the Script**: Execute the Python script:
   ```bash
   python madlib_story_generator.py
   ```
   The script will prompt you to enter words for the placeholders like `<noun>`, `<place>`, etc.
   
3. **View the Completed Story**: Once all the placeholders are filled in, the completed story will be printed on the console.

---

### Example:

If your `story.txt` contains:
```
A <adjective> day in <place>. The <noun> loves to <verb>.
```
When you run the program, it will prompt:
```
Enter a word for <adjective>: sunny
Enter a word for <place>: park
Enter a word for <noun>: dog
Enter a word for <verb>: play
```
The final output will be:
```
A sunny day in the park. The dog loves to play.
```

---

### Requirements:

- Python 3.x
- `story.txt` file with placeholders

---

### Future Enhancements:

- Allow users to save the completed story to a new file.
- Enable input validation to ensure proper word types (e.g., noun, verb) are entered.
