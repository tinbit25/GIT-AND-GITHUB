
### **Basic VS Code Extensions for MERN Stack Beginners**

Here’s a streamlined list of essential extensions to get started with the MERN stack:

---

### **General Development**
1. **Prettier - Code Formatter** (by Prettier)  
   - Automatically formats your code to keep it clean and readable.

2. **ESLint** (by Microsoft)  
   - Helps identify and fix common JavaScript and React code errors.

3. **Material Icon Theme** (by Philipp Kief)  
   - Adds icons for files and folders for better navigation.

---

### **Front-End Development**
4. **Live Server** (by Ritwick Dey)  
   - Launch a local server to preview HTML/CSS changes with live reload.

5. **Auto Rename Tag** (by Jun Han)  
   - Automatically renames paired HTML tags when editing.

6. **CSS Peek** (by Pranay Prakash)  
   - Quickly see CSS styles applied to HTML elements.

---

### **React Development**
7. **React Developer Tools** (by burkeholland)  
   - Provides basic React snippets and syntax highlighting.

8. **JavaScript (ES6) Code Snippets** (by charalampos karypidis)  
   - Quick access to JavaScript and React snippets.

---

### **Back-End Development**
9. **REST Client** (by Huachao Mao)  
   - Test APIs directly within VS Code.

10. **MongoDB for VS Code** (by MongoDB, Inc.)  
    - Interact with your MongoDB database seamlessly.

---

### **Optional for Better Navigation**
11. **Path Intellisense** (by Christian Kohler)  
    - Autocompletes file paths for imports in JavaScript files.

---

# Introduction to Terminals and Bash Commands

### **What is a Terminal?**
A **terminal** is a tool used to directly communicate with your computer through text commands.
 It is often referred to as the **command line** or **console**. Unlike graphical user interfaces (GUIs), 
 where you use windows and icons to interact, the terminal allows you to perform tasks like navigating folders,
  copying files, or executing programs by typing specific commands.

---

## **1.3 Essential Bash Commands**
When working in the terminal, you will encounter the term **directory** frequently.  
A **directory** is simply another name for a **folder**. Below are key Bash commands that you will use often.

---

### **Basic Commands**
These commands help you navigate and manage files and directories.

| **Command** | **Description** | **Example** |
|-------------|-----------------|-------------|
| **`pwd`**   | Prints the full path of the current working directory (shows where you are in the system). | 
Typing `pwd` might return `/home/user/Documents`. |
| **`cd`**    | Changes the current directory to a new one (like opening a folder). | `cd Desktop` moves you to 
the Desktop folder. |
| **`ls`**    | Lists the files and directories in the current directory. | Typing `ls` 
might return: `file1.txt folder1 folder2`. |
| **`mkdir`** | Creates a new directory (folder). | `mkdir Projects` creates a folder named `Projects`. |
| **`touch`** | Creates a new file in the current directory. | `touch file.txt` creates an empty file named `file.txt`. |

---

### **Working with `echo`**
The `echo` command is versatile and allows you to display text, create files, or write to files.

| **Command**                          | **Description** | **Example** |
|--------------------------------------|-----------------|-------------|
| `echo "text"`                        | Prints text to the terminal. | `echo "Hello World"` displays `Hello World`. |
| `echo > filename`                    | Creates an empty file. | `echo > style.css` creates an empty file named `style.css`. |
| `echo "text" > filename`             | Creates a file and writes the specified text into it. | `echo "Hello" > index.html` creates a file `index.html` with the text `Hello`. |

---

### **Managing Files and Directories**
Use these commands to move, rename, or delete files and folders.

| **Command**                       | **Description** | **Example** |
|-----------------------------------|-----------------|-------------|
| **`mv source destination`**       | Moves or renames a file or directory. | `mv file.txt folder/`
 moves `file.txt` to `folder`. |
|                                   |                 | `mv oldname.txt newname.txt` renames 
`oldname.txt` to `newname.txt`. |
| **`rm`**                          | Deletes files. | `rm file.txt` removes `file.txt`. |
| **`rmdir`**                       | Deletes empty directories. | `rmdir EmptyFolder` removes
 `EmptyFolder` (if it has no files). |
| **`rm -r`**                       | Deletes a directory and its contents (files and subdirectories). 
| `rm -r FolderWithFiles` removes `FolderWithFiles` and all its contents. |
| **`rm -rf`**                      | Forcefully deletes a directory and all its contents without confirmation. 
| `rm -rf ImportantFolder` deletes `ImportantFolder` and everything inside. |

---

### **Step-by-Step Practice Exercise**

Follow these steps to practice the commands:

1. Open the terminal and navigate to your desktop:
   ```bash
   cd Desktop
   ```
2. Create a new directory called `Practice`:
   ```bash
   mkdir Practice
   ```
3. Move into the `Practice` directory:
   ```bash
   cd Practice
   ```
4. Create an empty file named `example.txt`:
   ```bash
   touch example.txt
   ```
5. Write "Hello World" into `example.txt`:
   ```bash
   echo "Hello World" > example.txt
   ```
6. Rename the file `example.txt` to `renamed_example.txt`:
   ```bash
   mv example.txt renamed_example.txt
   ```
7. Create a new subdirectory named `SubFolder`:
   ```bash
   mkdir SubFolder
   ```
8. Move the file `renamed_example.txt` into `SubFolder`:
   ```bash
   mv renamed_example.txt SubFolder/
   ```
9. Delete the `SubFolder` and its contents:
   ```bash
   rm -r SubFolder
   ```

---

### **Question for Students**
---

1. Navigate to your **Desktop** to start the project:
2. Create a new project directory called `MyProject`:
3. Inside `MyProject`, create two directories: `src` and `assets`:
4. Create an empty file named `index.html` inside the `src` directory:
5. Write the text `<h1>Welcome to My Project</h1>` into the `index.html` file:
6. Rename the file `index.html` to `home.html`:
7. Move the file `home.html` from the `src` directory to the `assets` directory:
8. Delete the `src` directory since it is now empty:
9. Create a backup file called `project-backup.txt` directly in the `MyProject` folder:
10. Write the text `Backup created successfully.` into the `project-backup.txt` file:
11. Remove the `assets` directory and all its contents:
12. Finally, delete the entire `MyProject` directory and all its files:
---

