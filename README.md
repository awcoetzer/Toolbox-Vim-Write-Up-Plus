<div align="center">
    <h2>
        <strong>Vim Write-Up+</strong>
    </h2>
    <br>
    <p>
        Welcome to my THM write-up for Vim, on this README you will find page links to each task and its questions. Alternatively you can run the <strong>vimtutor</strong> command within your terminal to learn vim interactively.
    </p>
</div>

<br>
<br>

### Table of Contents

<ul>
    <li>
        <a href="#THM-Toolbox-Vim">THM Toolbox: Vim</a>
        <ul>
            <li>
                <a href="#task-1--getting-started">Task 1 &mdash; Getting Started</a></li>
            <li><a href="#task-2--basic-text-editing">Task 2 &mdash; Basic Text Editing</a></li>
            <li><a href="#task-3--exiting-vim">Task 3 &mdash; Exiting Vim</a></li>
            <li><a href="#task-4--copy-and-paste">Task 4 &mdash; Copy and Paste</a></li>
            <li><a href="#task-5--search-and-replace">Task 5 &mdash; Search and Replace</a></li>
        </ul>
    </li>
</ul>

<br>
<br>

### THM Toolbox: Vim

#### **Task 1** &mdash; _Getting Started_
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

> 💡**NOTE**: _After searching for Vim using winget, you should see a table like this with multiple entries, unlike my example below. 
> Dont worry about the version number as that can change over time, the key take away is finding the Id of the package you looking for._
>
> |Name|Id|Version|Match|Source|
> |:---|:---|:---|:---|:---|
> |Vim|vim.vim|9.1.1696||winget|


- **Installing vim using `winget` _with the use of the package Id_**
    - `winget install --id vim.vim` 

<br>

#### **Task 2** &mdash; _Basic Text Editing_

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we enter "INSERT" mode?**|_i_|
|2.|**How do we start entering text into our new Vim document?**|_Typing_|
|3.|**How do we return to command mode?**|_ESC_|
|4.|**How do we move the cursor left?**|_h_|
|5.|**How do we move the cursor right?**|_l_|
|6.|**How do we move the cursor up?**|_k_|
|7.|**How do we move the cursor down?**|_j_|
|8.|**How do we jump to the start of a word?**|_w_|
|9.|**How do we jump to the end of a word?**|_e_|
|10.|**How do we insert (before the cursor)**|_i_|
|11.|**How do we insert (at the beginning of the line?)**|_I_|
|12.|**How do we append (after the cursor)**|_a_|
|13.|**How do we append (at the end of the line)**|_A_|
|14.|**How do we make a new line under the current line?**|_o_|

<br>

#### **Task 3** &mdash; _Exiting Vim_

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we write the file, but don't exit?**|_:w_|
|2.|**How do we write the file, but don't exit- as root?**|_:w !sudo tee %_|
|3.|**How do we write and quit?**|_:wq_|
|4.|**How do we quit?**|_:q_|
|5.|**How do we force quit?**|_:q!_|
|6.|**How do we save and quit, for all active tabs?**|_:wqa_|

<br>

#### **Task 4** &mdash; _Copy and Paste_

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we copy a line?**|_yy_|
|2.|**how do we copy 2 lines?**|_2yy_|
|3.|**How do we copy to the end of the line?**|_y$_|
|4.|**How do we paste the clipboard contents after the cursor?**|_p_|
|5.|**How do we paste the clipboard contents before the cursor?**|_P_|
|6.|**How do we cut a line?**|_dd_|
|7.|**How do we cut two lines?**|_2dd_|
|8.|**How do we cut to the end of the line?**|_D_|
|9.|**How do we cut a character?**|_x_|

<br>

#### **Task 5** &mdash; _Search and Replace_

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we search forwards for a pattern (use "pattern" for your answer)**|_/pattern_|
|2.|**How do we search backwards for a pattern (use "pattern" for your answer)**|_?pattern_|
|3.|**How do we repeat this search in the same direction?**|_n_|
|4.|**How do we repeat this search in the opposite direction?**|_N_|
|5.|**How do we search for "old" and replace it with "new"**|_%s/old/new/g_|
|6.|**How do we use "grep" to search for a pattern in multiple files?**|_:vimgrep_|

<hr>

> 💡 **NOTE**: _If you wish to learn Vim interactively, run `vimtutor` in your terminal and it will open up an interactive document within Vim._
