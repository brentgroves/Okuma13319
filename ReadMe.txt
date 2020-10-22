Remember to :set ff=dos in NVIM and use Gnome Hex editor to add a 0x1A, EOF, 
to the end of all code before uploading to a CNC.
Also examine file to ensure 0xD and 0xA is at the end of every line
and that 0x1A is the last character in the file.

Follow steps 1 to 5 for OTLM.SSB first and then
the main_program.min

Replace existing program filename.(ssb|min) with plex updated program.
1. upload filename0.(ssb|min), copy file to cnc md0.
2. list filename0.(ssb|min) to verify it looks ok.
3. load ocom0.min into CNC so you will be able to rename the original filename.(ssb|min)
4. rename original filename.(ssb|min) to filenamex.(ssb|min)
5. rename filename0.min to filename.min.

Do this after all new files have been uploaded and renamed.
6. load filename.min
7. run program


