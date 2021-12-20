## Merge PS4 pkg files in Linux

1.You can merge the pkg files by copying the merge.sh and pkg-merge-x64.exe to the folder containing the pkg files.

2.Then open the terminal then type this command to give permission to the script:

```
chmod +x merge.sh
```

3.After that open the terminal in the folder containing the pkg files and the merge.sh and pkg-merge-x64.exe and type the following command:

```
./merge.sh
```

4.When the merging will be complete, the terminal will say the following:

```
Package Merger has completed the task. You can now close the terminal.
```

5.You will see a file named "merged.pkg". This is your final merged file.
