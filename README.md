Me doing an awk tutorial here http://sparky.rice.edu/~hartigan/awk.html 

'''bash
List commands run in /Users/peterconerly/code/awktutorial
vim file1
clear
cat file1
cat file1 | awk '$1 < $2 {print $0, $1/$2}'
cat file1 | awk '$1 < $2 {print $0, $1/$2}'> file2
cat file
cat file2
vim file2
vim file
rm file
ls
cat file1 | awk '$1 {print $0, $1/$2}'
cat file1 | awk '$1 {print $0, $1/$2}' > file2
touch junk1
touch junk2
touch junkWut
ls junk1 junk2 junkWut
ls junk1 junk2 junkWut | awk '{print "cp "$0" ./iraf/"$0".dat"}' | csh
mkdir irah
mkdir iraf
rm -rf irah
ls iraf/
ls -al | awk 'NF'
ls -al
ls -al | awk '{print NF}'
ls -al | awk '{print NF, NR}'
ls -al | awk '{print NF, NR, BEGIN, END}'
ls -al | awk '{print NF, NR, END}'
ls -al | awk '{print NF, END}'
touch dupes
vim dupes
cat dupes | awk ' !x[$0]++'
cat dupes | awk ' x[$0]++'
cat dupes | awk ' !x[$0]'
cat dupes
cat dupes | awk ' ![$0]'
cat dupes | awk ' x[$0]'
cat dupes | awk ' !y[$0]++'
cat dupes | awk '{ y[$0]++} print y[$0]'
cat dupes | awk '{ y[$0]++ print y[$0]'
cat dupes | awk '{ y[$0]++} {print y[$0]'
cat dupes | awk '{ y[$0]++} {print y[$0]}'
cat dupes | awk 'y[$0]++ {print y[$0]}'
cat dupes | awk 'y[$0]++ {print y[$0]; print "nope"}'
cat dupes | awk 'y[$0]++ {print y[$0]; print $0}'
cat dupes | awk 'y[$0]++ ? {print y[$0]} : {print $0};'
cat dupes | awk 'y[$0]++ ? print y[$0] : print $0;'
cat dupes | awk '{print i; i++}'
cat dupes | awk 'i++ {print i; i++}'
cat dupes | awk 'i {print i; i++}'
python
cd iraf/
lc
'''
