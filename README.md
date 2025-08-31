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

#### **Task 3** &mdash; Exiting Vim

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we write the file, but don't exit?**|_:w_|
|2.|**How do we write the file, but don't exit- as root?**|_:w !sudo tee %_|
|3.|**How do we write and quit?**|_:wq_|
|4.|**How do we quit?**|_:q_|
|5.|**How do we force quit?**|_:q!_|
|6.|**How do we save and quit, for all active tabs?**|_:wqa_|

<br>

#### **Task 4** &mdash; Copy and Paste

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we copy a line?**|__|
|2.|**how do we copy 2 lines?**|__|
|3.|**How do we copy to the end of the line?**|__|
|4.|**How do we paste the clipboard contents after the cursor?**|__|
|5.|**How do we paste the clipboard contents before the cursor?**|__|
|6.|**How do we cut a line?**|__|
|7.|**How do we cut two lines?**|__|
|8.|**How do we cut to the end of the line?**|__|
|9.|**How do we cut a character?**|__|

<br>

#### **Task 5** &mdash; Search and Replace

|#|Question|Answer|
|:---|:---|:---|
|1.|**How do we search forwards for a pattern (use "pattern" for your answer)**|__|
|2.|**How do we search backwards for a pattern (use "pattern" for your answer)**|__|
|3.|**How do we repeat this search in the same direction?**|__|
|4.|**How do we repeat this search in the opposite direction?**|__|
|5.|**How do we search for "old" and replace it with "new"**|__|
|6.|**How do we use "grep" to search for a pattern in multiple files?**|__|

<hr>
