# Linux Command Line

## Commands:

**apt update** - checks for updates on Debian based systems.

**Syntax:**

`$ sudo apt update`

**apt upgrade** - Applies updates on Debian based systems.

**Syntax:**

`$ sudo apt upgrade`

**date** - Displays current time & date.

**Syntax:**

`$ date`

**df** - Reports file systems disk space usage.

**Syntax:**

`$ df`

**Options:**

* **-a, --all:** Include pseudo, duplicate, inaccessible files.
* **-h:** Prints sizes in powers of 1024 \(e.g. 1023M\).
* **-H:** Prints sizes in powers of 1000 \(e.g. 1.1G\).
* **-l:** Limit listing to local file systems.
* **--total:** Elide all entries insignificant to available space, and produce a grand total.
* **-T:** Prints file system type.
* **--help:** Displays help menu.
* **--version:** Outputs version info.

**mv** - move \(rename\) files.

**Syntax:**

`$ mv <source> <destination>`

**free** - Displays amount of free and use memory in the system:

**Syntax:**

`$ free`

**Options:**

* **-h:** Shows output into human readable units.
* **-c \#:** Displays the result **\#**'s times.
* **-s \#:** Continuously display result **\#**'s seconds apart.
* **-t:** Displays a line showing the column totals.
  * **Note:** Run this command with the **option: -th**  

**pwd** - Prints name of current/working directory.

**Syntax:**

`$ pwd`

**Options:**

* **-L:** Use **pwd** from environment, even if it contains symlinks.
* **-P:** Avoid all symlinks.
  * **Note:** If no option is specified, **-P** is assumed.

**cd -** Changes current/working directory.

**Syntax:**

`$ cd`

**ls** - List directory contents.

**Syntax:**

`$ ls`

**Options:**

* **-a:** Shows hidden files/contents.
* **-C:** Lists entries by columns.
* **--format=word**
 * **word:**
    * across, **-X**
    * commas, **-m**
    * horizontal, **-x**
    * long, **-l**
    * single-column, **-1**
    * verbose, **-l**
    * vertical, **-C**
* **-h:** Human readable output.
* **-l:** Long listing format.
* **-r:** Reverse order while sorting.
* **-R:** Lists subdirectories recursively.
* **-s:** Prints the allocated size of each file.
* **-S:** Sorts by file size, largest first.
* **Add the following options to sort:**
  * size, **-S**
  * time, **-t**
  * version, **-v**
  * extension, **-X**

**cat** - Concatenates files and prints on the standard-output.

`$ cat`

**Options:**

* **-n:** Number all output lines.

**file** - Determines file type.

`$ file`

**Options:**

* **-b:** Does not prepend filenames to output.

**less** - Opposite of **more** command (reads from file).

`$ less`

* **Note:** Once executed, type "**/**" to search for keywords.  

**mkdir** - Makes directories.

`$ mkdir`

**Options:**

* **-m:** Sets file mode (as in **chmod**)
  * **E.g.** `$ mkdir -m=700 <filename>`
