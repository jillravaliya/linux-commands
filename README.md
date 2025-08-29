# Linux Commands


### 1. pwd (Print Working Directory)
- `pwd` → shows current directory (absolute path)
- `pwd -P` → physical path (resolves symlinks)
- `pwd -L` → logical path (keeps symlinks as is)

---

### 2. ls (List files)
- `ls` → list files
- `ls -l` → long format (permissions, owner, size, date)
- `ls -a` → include hidden files
- `ls -lh` → human readable sizes
- `ls -R` → recursive listing
- `ls -t` → sort by time
- `ls -S` → sort by size
- `ls -d */` → show only directories

---

### 3. cat (Concatenate and display files)
- `cat file.txt` → show content
- `cat -n file.txt` → show with line numbers
- `cat file1 file2 > combined.txt` → merge files
- `cat > file.txt` → create file (CTRL+D to stop)
- `tac file.txt` → reverse cat (from bottom to top)

---

### 4. less (View file with navigation)
- `less file.txt` → open file with navigation
- `/word` → search forward
- `?word` → search backward
- `n` / `N` → next/previous match
- `q` → quit

---

## 5. head (Show beginning of file)
- `head file.txt` → first 10 lines
- `head -n 20 file.txt` → first 20 lines
- `head -c 50 file.txt` → first 50 characters

---

### 6. tail (Show end of file)
- `tail file.txt` → last 10 lines
- `tail -n 20 file.txt` → last 20 lines
- `tail -f logfile.log` → live monitoring of logs

---

### 7. echo (Print text / variables)
- `echo "Hello"` → prints Hello
- `echo $USER` → prints current user
- `echo $HOME` → prints home directory
- `echo -e "Hi\nBye"` → enable escapes (\n, \t etc.)
- `echo *` → wildcard expansion (lists files in dir)

---

### 8. touch (Create empty file / update time)
- `touch file.txt` → creates empty file
- `touch -c file.txt` → update timestamp only if file exists
- `touch file{1..3}.txt` → creates file1, file2, file3

---

### 9. mkdir (Make directory)
- `mkdir newdir` → create directory
- `mkdir -p a/b/c` → create nested directories
- `mkdir dir{1..5}` → create multiple dirs

---

### 10. rmdir (Remove directory)
- `rmdir emptydir` → removes empty dir
- `rmdir -p a/b/c` → removes nested empty dirs
- `rm -r nonemptydir` → removes non-empty dirs (using rm)

---

### 11. rm (Remove files/directories)
- `rm file.txt` → delete file
- `rm -i file.txt` → ask before deleting
- `rm -r dir/` → remove directory and contents
- `rm -rf dir/` → force delete without prompt

---

### 12. cp (Copy files/directories)
- `cp file1 file2` → copy file
- `cp file.txt dir/` → copy file into dir
- `cp -r dir1 dir2` → copy directory recursively
- `cp -i file1 file2` → confirm before overwrite

---

### 13. mv (Move/Rename files)
- `mv file.txt newdir/` → move file
- `mv old.txt new.txt` → rename file
- `mv -i file1 file2` → confirm before overwrite

---

### 14. nano (Text Editor)
- `nano file.txt` → open file in nano editor
- `CTRL+O` → save changes
- `CTRL+X` → exit nano
- `CTRL+K` → cut line
- `CTRL+U` → paste line
- `CTRL+W` → search within file
- `CTRL+G` → help menu

