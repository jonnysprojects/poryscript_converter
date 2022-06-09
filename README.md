# .inc to .pory Converter

This is a simple bash shell script that when ran in the main pokeemerald folder, will convert all scripts.inc files in every map in data/maps/, into the appropriate scripts.pory file by copying the contents of the scripts.inc file into raw \`\` tags. It will skip any directory that already has a scripts.pory file as to not overwrite any scripts that you already converted to the .pory extension. 

Once the bash file is in your pokeemerald directory, simply navigate to your folder in WSL and type:
`./inc_to_pory`
And it will run the shell script and convert all your files. You may need to give it permissions with chmod 777 inc_to_pory if it doesn't work at first and make sure its in the right directory. 
