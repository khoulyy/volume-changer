# volume-slider
A program that changes volume level by changing the value inside files' bytes in memory.

Note: This program works only with WAV format.

## How to use:
 1. Download source code
 2. Compile the program by
   ```
   cc volume.c -o volume
   ```
 3. run the program by 
   ```
   ./volume <input_file_name> <output_file_name> <factor>
   ```
 <p>Example: </p> `./volume song1.wav song2.wav 2.0`
  
