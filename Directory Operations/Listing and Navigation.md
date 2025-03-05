# Linux Commands Notes

## ls (List)

**Usage:**  
`ls [options] [directory]`

**Basic Usage:**  
`ls` lists contents of the current directory.

### Common Options:
- `ls -a` - Shows all files, including hidden ones (those starting with `.`).
- `ls -l` - Uses long format with detailed information.
- `ls -h` - Shows file sizes in human-readable format.
- `ls -R` - Lists subdirectories recursively.

**Importance:**  
Most frequently used command to view directory contents, essential for navigating the filesystem and verifying file existence.

---

## ls -l (Long Listing)

**Usage:**  
`ls -l [directory]`

**Shows Detailed Information Including:**
- File permissions
- Number of links
- Owner name
- Group name
- File size (in bytes)
- Last modification time
- Filename


**Importance:**  
Critical for understanding file attributes, permissions, and metadata. Helps in troubleshooting permission issues and understanding file ownership.

---

## pwd (Print Working Directory)

**Usage:**  
`pwd`

**Description:**  
Displays the absolute path of the current working directory.

**Importance:**  
Essential for orientation in the filesystem, confirming your location, and constructing paths for scripts and commands.

---

## cd (Change Directory)

**Usage:**  
`cd [directory]`

**Common Patterns:**
- `cd /path/to/directory` - Absolute path.
- `cd directory` - Relative to current location.
- `cd ..` - Move up one directory.
- `cd ~` or just `cd` - Go to home directory.
- `cd -` - Return to previous directory.

**Importance:**  
Fundamental for filesystem navigation. Together with `ls` and `pwd`, forms the core of directory traversal in Linux.

---

## clear

**Usage:**  
`clear`

**Description:**  
Clears the terminal screen, giving you a clean workspace.

**Importance:**  
Helps maintain a tidy working environment, especially during long terminal sessions.
