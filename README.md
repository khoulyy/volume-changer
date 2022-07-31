# volume-slider
A program that changes volume level by changing the value inside files' bytes in memory.

Note: This program works only with WAV format.

## How to use:
 1. Download source code
 2. Compile the program
   ```
   cc volume.c -o volume
   ```
 3. run the program
   ```
   ./volume <input_file_name> <output_file_name> <factor>
   ```
 in which factor (2.0) doubles the volume & 0.5 cuts the volume in half.
