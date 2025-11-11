To run this program, you must put a "seed.txt" file in the root folder, which is your structure seed file. The program will check all seeds and their sister seeds in the file,
so if you put 1 seed in the file, it will search 65536 seeds for you.
When you finish the checking, a result.txt will generate. If result.txt already exist, the program won't work. So you have to copy the result to somewhere else then delete the result.txt 
for checking again.
The "Cavefinder.java" file is a bit faster but don't check the exact height for seeds, the "CavefinderWithHeight.java" checks the height at (0,0) by seed-checker to make sure it's below Y=-50.
