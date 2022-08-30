PMD https://github.com/pmd/pmd

environment: 

	openjdk version "11.0.16" 
  
	Ubuntu 20.04
We hava selected our ruleset.

usage:

	$ ./pmd-bin-6.47.0/bin/run.sh pmd -d ${dir} -f csv -R rulesets/java/all.xml > $dir.csv

{dir} is your dictionary to detect.
