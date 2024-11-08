# GGRM_MD_PATCH
A patch file for the Gargoyles Genesis ROM dumped from memory from the 2023 rerelease Gargoyles Remastered

This patch makes the ROM playable in third party emulators and potentially flashcarts and adds back the button letters to the options screen.

In order to obtain the ROM that this patch works with, you need to first run Gargoyles Remastered.
Then, you need to open a hex editor that supports searching through memory.
Search for the 2nd instance of the string "(C)T-2391995.SEP". Move your cursor to 17 lines above just before "FF FF F4 D4".
Select the block starting here and is 3145728 (decimal) bytes in length. It should end in a bunch of hexadecimal 20's.
Copy and paste this data in a new file in your hex editor and save it.
Apply the patch with a BPS patcher of your choice.

Information on creating a working ROM came from: https://github.com/farmerbb/RED-Project/issues/132
