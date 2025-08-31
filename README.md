<div align="center">
    <h2>
        <strong>Vim Write-Up+</strong>
    </h2>
    <br>
    <p>
        Welcome to my THM write-up for Vim, on this README you will find links to multiple documents to help you learn Vim. Alternatively you can run the <strong>vimtutor</strong> command within your terminal and learn by doing.
    </p>
</div>

### Table of Contents

<ul>
    <li>
        <a href="#THM-Toolbox-Vim">THM Toolbox: Vim</a>
        <ul>
            <li>
                <a href="#task-1--getting-started">Task 1 &mdash; Getting Started</a></li>
            <li><a href="#task-2--">Task 2 &mdash;</a></li>
            <li><a href="#task-3--">Task 3 &mdash;</a></li>
            <li><a href="#task-4--">Task 4 &mdash;</a></li>
            <li><a href="#task-5--">Task 5 &mdash;</a></li>
        </ul>
    </li>
    <br>
    <li>
        <a href="#vimtutor-summaries">Vimtutor Summaries</a>
        <ul>
            <li><a href="#"></a></li>
        </ul>
    </li>
</ul>


### THM Toolbox: Vim

#### **Task 1** &mdash; Getting Started
#### Checking if Vim is installed within **Linux**
To see whether Vim is installed on your Linux Env, you can type `which vim` in your terminal and if its installed it will show you the directory of where its located on your system. 

> 💡**NOTE**: _Using `which vim` within your terminal, should present you with a pathway such as this, `usr/bin/vim`, this is a good indication its installed_ 

Alternatively, you could also just type `vim FILENAME` or `vim`, and if its installed it will open.

#### Installing Vim on **Linux**

- **Debian-Based Distributions**:
    - `sudo apt install vim`
- **Arch-Based Distributions**:
    - `sudo pacman -S vim`
- **Fedora-Based Distributions**:
    - `sudo dnf install vim-enhanced`

#### Installing Vim on **Windows**

You can install Vim by either downloading it [here](https://www.vim.org/download.php#pc "Link to download the Vim installer for Windows") or you can use Winget within your terminal or powershell. _winget is a windows packet manager_

- **Search for vim using `winget`**
    - `winget search vim`

> 💡**NOTE**: _After search for Vim, you should see a table like this with multiple entries unlike mine which is just a single entry for this example. Dont worry about the version number as that can change over time, the key take away is finding the Id of the package you looking for._
>
> |Name|Id|Version|Match|Source|
> |:---|:---|:---|:---|:---|
> |Vim|vim.vim|9.1.1696||winget|


- **Installing vim using `winget` _using the package Id_**
    - `winget install --id vim.vim` 

<br>

#### **Task 2 &mdash; Basic Text Editing**

**How do we enter "INSERT" mode?**
>> i

**How do we start entering text into our new Vim document?**
- [x] typing

**How do we return to command mode?**
 ESC

**How do we move the cursor left?**
 h

**How do we move the cursor right?**
 l

**How do we move the cursor up?**
 k

**How do we move the cursor down?**
 j

**How do we jump to the start of a word?**
 w

**How do we jump to the end of a word?**
 e

**How do we insert (before the cursor)**
 i

**How do we insert (at the beginning of the line?)**
 I

**How do we append (after the cursor)**
 a

 **How do we append (at the end of the line)**
 - `A`
 **How do we make a new line under the current line?**
 - `o`

<br>

#### **Task 3**

<br>

#### **Task 4**

<br>

#### **Task 5**

<hr>
