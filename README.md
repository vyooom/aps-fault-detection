# neurolab-mongo-python

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 2 - Run main.py file

```bash
python main.py
```

### Step 3: Git version

```
git --version
```

### Step 4: Connect to mongo db 
 by clicking on th Mongodb 

 ### Step 5: Download the data set  
 
 ```
wget https://raw.githubusercontent.com/avnyadav/sensor-fault-detection/main/aps_failure_training_set1.csv
```

### Step 6: Insert this record into Mongodb by using python:
create data_dump.py file in the vscode   
write codes to initialise the 

### Step 7: Make a github repository:
Add git ignore file in pyhton
Copy the git repository address

### Step 8: Connect the VS CODE to the github repo
Remove the already connected repo
1. current repo
```
git remote -v
```
2. remove origin
```
git remote remove origin
```
3. check the pointer
```
git log
```
4. connect to the git; origin is a conventional name
```
git remote add origin https://github.com/vyooom/aps-fault-detection.git
```

5. to save your changes but their is problem
```
git push origin main
```
6. First we have to change the VSCODE as per the github
```
git pull origin main
```
will show error '''fatal error: refusing to merge unrelated histories'''

#### upto 02:10:53 done on 27/11/2022

7. Using git reset command
```
git reset --soft 6afd
# git reset --soft <last comit id inital 5 letters>
```
8. adding the git file to staging area
```
git add .
git status
```

9. commit the staged files:
```
git commit -m "This is my first version"
```
this will show errors

10. have to add email and user name
```
git config --global user.email abhishek894@gmail.com
git config --global user.name vyooom
```
11. again commit
```
git commit -m "This is my first version"
```
12. pushing the changes forcefully to git/ not recommended normally
```
git push origin main -f
```
13. Creating conflict: This line is added in Github by Abhishek.


