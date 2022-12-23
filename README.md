# The Wish Card

## Prerequisites

- Have python and pip installed on your system


## Note
* Make sure your make an PR before put your card into story. Any story without PR will not be accepted (How to make PR is mentioned below)
* The dimensions of the card must remain the same.
* Copying another participants code is strictly prohibited.

## Setup

### Step 1 - Fork
As the first step, you have to `fork` this repository to your own github account. 
For that please click on the fork button on the top right corner of your window.  
You will now have the forked repository among your own repositories.    
![Fork](https://github.com/dkowsikpai/card/blob/main/Screenshots/fork.png)
<br>

### Step 2 - Clone 
Clone the repository to your local machine using the git command.
```
git clone <url_to_forked_repository>
```

<br>

### Step 3 - Changing working directory
This will change the working directory to the newly cloned repository. 
```
  cd wish-card/
```

<br>

### Step 4 - Install Flask
Use pip to install flask. 
```
  pip install flask
```

<br>

### Step 5 - Run the application
The application can be run using the command. The application will be running at `localhost:5000` by default.
```
python app.py
```

<br>


## Make Your Card

* Open the file &namelist.html within templates folder, where the names of all the participants seen on the homepage of the website is given. Copy the relevant section of code as shown below and insert another record with your own details.

```
<a class="participant" href="/<github-username>">
  <div>
    <div class="name"> <your name> </div>
    <div class="college"> <your college> </div>
  </div>
</a>

```

* Within templates folder create a copy of sample.html and change the name to ```<your_github_username>.html``` If your username is ```abc``` then change the new file's name to ```abc.html```.
* Going to the url ```localhost:5000/<github-username>``` will now give you the sample card.
* Within static folder, create a copy of "sample" folder and modify its name to your "github-username"
* Open the earlier created html file in a text editor of your choice. Change the name inside ```<title>``` tag.
* Now, replace the path to the css file with the path to the css file in your newly created folder in static.

### Put Your Creative Hat
* You can change the css file within the your newly created folder in static. New CSS styles or even animations can be included.


### Get Your Card

* Click on ```Download Card``` button to download your card







## How to Commit 
You can check your change using the following command

```
 git status
```
this command will show you the changes that you have made and left untracked, you have to add these changes to the staging area.

<br> 
Now, you should add it to the staging area using the following command.

```
  git add .
```
`.` specifies to add all the chnges to the staging area.
<br>
Now that the changes are tracked or added to the staging area you should make a commit regarding that particular change using the following command in the terminal. 

```
  git commit -m "<commit message>" 
```
The `commit message` message should specify what is the change made for, it will result in well documentation of the project

<br><br>

## Pushing the commit

Now that you have commited your changes you should push the changes to the remote git repository for that you can use the following command, given below

```
  git push -u origin main
```
This will automatically push your commit to the remote repository, it may ask your password / passphrase for authentication.


<br><br>

## Create A Pull Request(PR)
- Push your changes to the github repository.
- Go To Pull requests tab on github
- Click on `New Pull Request` button. 
- Make sure that head repository is your repository
![Pull Request Head](https://github.com/dkowsikpai/card/blob/main/Screenshots/PR%20Head.png)
- Make sure it is showing green tick mark
- Press on `Create Pull Request` Button
![Create PR](https://github.com/dkowsikpai/card/blob/main/Screenshots/Create%20PR.png)
- Add necessary title and description
- Hit `Create Pull Request` Button

<br>

