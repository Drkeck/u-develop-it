# CHAPTER 12
SQL

## chapter 1

### 1.6

#### Gripe [1]
the begining of this chapter is not very clear on what needs to be done, i had to re-read this part 2-3 times to make sure i understood it.

what does `verify` tell me? nothing. this is our first time using SQL and you're telling me that i need to verify that something works, but you don't tell me what i should expect from `verifying` so i can make a safe assumption that it worked.

Will it send an error if it fails?

will it do nothing if it fails? 

its not clear and its not clear if i should move on from this point and continue or double back and check if my work is correct, or that i didn't miss something WHICH IS THE ENTIRE POINT OF VERIFYING. 

#### Answer
the verification is that it doesn't throw an error..?

### Gripe [2]

you have us link our files to the database while not being entirely clear on the instructions to create the files with `$ touch` and fill the files in with VS Code. 

also there's a section where you have us make `schema.sql` and `seeds.sql` and link it to `election.db` and you ask us to `verify` that this is working by using `SELECT * FROM candidates` without telling us that we need to have `elections.db` to be opened in the SQLite CLI using `.open <filename>`, i had to legit guess this was the issue cause it wasn't clear about it in the lesson. 