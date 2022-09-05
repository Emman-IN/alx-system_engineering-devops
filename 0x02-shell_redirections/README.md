
Learning Shell, I/O Redirections and filters
0. Write a script that prints “Hello, World”, followed by a new line to the standard output.

1. Write a script that displays a confused smiley "(Ôo)'.

2. Display the content of the /etc/passwd file.

3. Display the content of /etc/passwd and /etc/hosts
4. Display the last 10 lines of /etc/passwd

6. rite a script that displays the third line of the file iacta.

The file iacta will be in the working directory

You’re not allowed to use sed7. Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.


8. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.


9. rite a script that duplicates the last line of the file iacta

The file iacta will be in the working directory  
10. Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. Write a script that counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted

[?1049h[22;0;0t[>4;2m[?1h=[?2004h[1;36r[?12h[?12l[22;2t[22;1t[27m[23m[29m[m[H[2J[?25l[2;1H[1m[34m~                                                                    [3;1H~                                                                    [4;1H~                                                                    [5;1H~                                                                    [6;1H~                                                                    [7;1H~                                                                    [8;1H~                                                                    [9;1H~                                                                    [10;1H~                                                                    [11;1H~                                                                    [12;1H~                                                                    [13;1H~                                                                    [14;1H~                                                                    [15;1H~                                                                    [16;1H~                                                                    [17;1H~                                                                    [18;1H~                                                                    [19;1H~                                                                    [20;1H~                                                                    [21;1H~                                                                    [22;1H~                                                                    [23;1H~                                                                    [24;1H~                                                                    [25;1H~                                                                    [26;1H~                                                                    [27;1H~                                                                    [28;1H~                                                                    [29;1H~                                                                    [30;1H~                                                                    [31;1H~                                                                    [32;1H~                                                                    [33;1H~                                                                    [34;1H~                                                                    [35;1H~                                                                    [m[36;52H0,0-1[9CAll[12;27HVIM - Vi IMproved[14;27Hversion 8.1.3741[15;23Hby Bram Moolenaar et al.[16;16HModified by team+vim@tracker.debian.org[17;14HVim is open source and freely distributable[19;21HHelp poor children in Uganda![20;12Htype  :help iccf[34m<Enter>[m       for information [22;12Htype  :q[34m<Enter>[m               to exit         [23;12Htype  :help[34m<Enter>[m  or  [34m<F1>[m  for on-line help[24;12Htype  :help version8[34m<Enter>[m   for version info[1;1H[?25h[?25l[36;42HC[1;1H[36;42H [1;1H[36;42Hc$[1;1H[36;42H  [1;1H[36;1H[1m-- INSERT --[m[36;52H[K[36;52H0,1[11CAll[1;1H[?25h[?25lA[12;27H[1m[34m                 [14;27H                [15;23H                        [16;16H                                       [17;14H                                           [19;21H                             [20;12H                                              [22;12H                                              [23;12H                                              [24;12H                                              [m[36;52H1,2[1;2H[?25h[?25lT[36;54H3[1;3H[?25h[?25l[36;54H4[1;4H[?25h[36;1H[K[1;3H[?25l[36;42H^[[1;3H[36;42H  [1;4H[36;52H1,3[11CAll[1;3H[?25h[?25l[36;1HType  :qa!  and pr...hanges and exit Vim[36;52H[K[36;52H1,3[11CAll[1;3H[?25h[?25l[36;42H^X[1;3H[36;42H  [1;3H[?25h[?25l[36;52H[K[36;52H1,3[11CAll[1;3H[?25h[?25l[36;52H[K[36;52H1,3[11CAll[1;3H[?25h[?25l[36;52H[K[36;52H1,3[11CAll[1;3H[?25h[?25l[36;52H[K[36;52H1,3[11CAll[1;3H[?25h[?25l[36;52H[K[36;52H1,3[11CAll[1;3H[?25h[?25l[36;42H^D[1;3H[36;42H  [1;3H[?25h[?25l[36;42Hgq[1;3H[?25h[?25l[36;44Hgq[1;3H[36;42H    [1;1H[36;54H1[1;1H[?25h[?25l[36;42Hgq[1;1H[?25h[?25l[36;44Hgq[1;1H[36;42H    [1;1H[?25h[?25l[36;42HN[1;1H[36;1H?\.\/\~ [36;9H[K[36;1H[31msearch hit TOP, continuing at BOTTOM[m[1m[37m[41mE486: Pattern not found: \.\/\~[m[36;32H[K[1;1H[36;52H1,1[11CAll[1;1H[?25h[?25l[36;42HB[1;1H[36;42H [1;1H[?25h[?25l[36;42HS[1;1H[36;42H [1;1H[36;42Hcc[1;1H[36;42H  [1;1H[36;1H[1m--[m[1m[37m[41m8[m[1m INSERT[m[1m[37m[41mt[m[1m --[m[1m[37m[41mn[m[36;13H[K[36;52H1,1[11CAll[1;1H[K[1;1H[?25h[?25lF[36;54H2[1;2H[?25h[?25lD[36;54H3[1;3H[?25h[?25lF[36;54H4[1;4H[?25h[?25lS[36;54H5[1;5H[?25h[?25lD[36;54H6[1;6H[?25h[?25l[1;5H[K[36;54H5[1;5H[?25h[?25l[1;4H[K[36;54H4[1;4H[?25h[?25l[1;3H[K[36;54H3[1;3H[?25h[?25lG[36;54H4[1;4H[?25h[?25lH[36;54H5[1;5H[?25h[?25lG[36;54H6[1;6H[?25h[?25lJ[36;54H7[1;7H[?25h[?25lH[36;54H8[1;8H[?25h[?25lF[36;54H9[1;9H[?25h[?25lH[36;54H10[1;10H[?25h[?25lH[36;55H1[1;11H[?25h[?25lH[36;55H2[1;12H[?25h[?25lH[36;55H3[1;13H[?25h[?25lH[36;55H4[1;14H[?25h[?25lH[36;55H5[1;15H[?25h[?25lH[36;55H6[1;16H[?25h[?25lH[36;55H7[1;17H[?25h[?25lH[36;55H8[1;18H[?25h[?25lH[36;55H9[1;19H[?25h[?25lH[36;54H20[1;20H[?25h[?25lH[36;55H1[1;21H[?25h[?25lH[36;55H2[1;22H[?25h[?25lH[36;55H3[1;23H[?25h[?25lH[36;55H4[1;24H[?25h[?25lH[36;55H5[1;25H[?25h[?25lH[36;55H6[1;26H[?25h[?25lH[36;55H7[1;27H[?25h[?25lH[36;55H8[1;28H[?25h[?25lH[36;55H9[1;29H[?25h[?25lH[36;54H30[1;30H[?25h[?25lH[36;55H1[1;31H[?25h[?25lH[36;55H2[1;32H[?25h[?25lH[36;55H3[1;33H[?25h[?25lH[36;55H4[1;34H[?25h[?25lH[36;55H5[1;35H[?25h[?25lH[36;55H6[1;36H[?25h[?25lH[36;55H7[1;37H[?25h[?25lH[36;55H8[1;38H[?25h[36;1H[K[1;37H[?25l[36;42H^[[1;37H[36;42H  [1;38H[36;52H1,37[10CAll[1;37H[?25hCreate a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest
13 .Create a script that takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted

14. Display lines containing the pattern “root” from the file /etc/passwd

Display the number of lines that contain the pattern “bin” in the file /etc/passwd


