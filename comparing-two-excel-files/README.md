###### There are many ways to combine data from different excel files while using microsoft excel. You could use vlookup, index match, etc. The only issue with this method is that it is not quickly repeatable and uses human time to repeat.
###### You could also use microsoft SQL to do the similar action, but it would involve a few steps to set up and involve creating a temporary table in the database.
###### What I like about Python Panda's is that it combines the functionality of the previous two, but with more benefits. 
- You import the data files into a python IDE and the original file will not be affected by the data processed in python.
- You can quickly make multiple versions by using 'variables'
- It will also create a process that is repeatable by simply updating the variables, for example, a file name.
- Plus more

###### In the following example, I combine two files and mimic the "NOT EXIST" function from microsoft SQL.
