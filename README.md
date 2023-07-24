# copyAndSort
This is a simple powershell script that will copy files from one folder to another and sort them by date.

I used it to organize a folder with more than a million files.
It copies from A to B and in B it orders the file in Year/Month/day folders.
After it copies the file it then moves the original to a subdirectory called "History".

The script runs for 10 minutes each time, in my experience (in Azure shares) it processes about 100 files per minute.
