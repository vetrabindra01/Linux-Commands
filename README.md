# Linux-Commands


1) Count no of line in .gz file on mac
   
for i in *.gz; do echo ${i}; zcat < ${i} | wc -l ; done

3) move files using list of files
mv `cat list.txt` ../

4) grep from two files
https://stackoverflow.com/questions/45625032/grep-lines-that-appear-partly-in-one-file-to-another
grep -iFf id.txt file.txt

