Found clues with grep "CLUE" in the crimescene file

With said clue found 3 witness's and their address with the "grep "Annabel""

Going through the 'streets' file using 'head', I found the the corresponding interviews to the address and found the next clue with a witness describing a blue honda with the a L337 tag

Using 'grep -A 5' to find all the owners of blue honda by filtering the "L337" portion of they license plate. With grep and cat we were able to wind down the suspects with memberships with Delta, AAA, the library, and the Museum of Bash, which the suspect was found to have memberships to.


Musas-MacBook-Air:memberships msillah$ cat Delta_Skymiles AAA Terminal_City_Library Museum_of_Bash_History | grep -c "Jeremy Bower"
4

Thus Jeremy Bower was the suspect