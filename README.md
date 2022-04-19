# FIM
File Integrity Monitor (FIM)

Start 

Collect new Baseline, or
Begin monitoring files with saved Baseline

Collect new Baseline
Calculate HASH value from target files
Store the file|hash pairs in baseline.txt 

Begin monitoring files with saved Baseline
Load file:hash pairs from baseline.txt

Continuously monitor file integrity
Loop through each file target file, calculate the hash, and compare the file|hash to what is baseline.txt

Notify user if a file is changed or deleted
If a file's actual hash is different than what is recorded in the baseline, print to the screen (color), if a file has been changed or deleted. (integrity compromise)
