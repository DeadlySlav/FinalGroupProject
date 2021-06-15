# FinalGroupProject
#### This project will use music from different genres and be able to play them using an Amazon service (EC2) Completion of this project will be based on if these requirements are met: 
#### 1) Music plays
#### 2) Able to skip/Change song/s 
#### 3) [Optional  - additional goal] Able to view different Music + genres 

## EC2/WordPress installation:
#### 1. Log into/Create uyour aws account and log into the console

#### 2. Search for EC2 or select it from Compute services

#### 3. Select launch instance from EC2 dashboard or go to isntaces tab on left hand side and select instances, from there click on Launch Instance

#### 4. In step 1 select AWS marketplace and search for bitnami for quick results or search down list until you find WordPress Certified by Bitnami and select it

#### 5. Select t2 micro (free tier) then select Configure Instance Details at bottom of page

#### 6. On step 3 leave everything as default

#### 7. For step 4 use the maximum amount of storage, which for this tier is 30 GB

#### 8. For step 5 Add tag with Key as Name and Value as the name you wish the EC2 to be. For example ours has our names and what project it is.

#### 9. For step 6 create a new security group and don't change the ports. Only add new ones if you plan on using different ports to access the site

#### 10. Select launch and a menu will appear mentioning a key pair. Select a previously made key pair or create a new one and save the key pair. You will need it to log into the instance via putty later.

#### 11. Wait for your EC2 to finish and itializing then process to developing your site.

## Plugin’s installation:

#### Step 1) Go to your site and click on the URL and enter /admin at the very end of your site’s URL and enter “user” for the  username and enter the password.
#### Step 2) To get the password head over to the AWS instances site and select your instance then head over to “Actions” then click the drop down and go to “Monitor and troubleshoot” then click “Get system log” then look for a box that will be made of the text “ # “ and inside it will say “Setting Bitnami application password to ‘************’ There you go you now have the admin login to your site.
#### Step 3) Now on the left side go to plugins and select “Add new” and in the Search bar enter “MP3 Music Player by Sonaar” then click “Install now” then “Activate” 
Step 4) Congrats now you have the Music player and to create a playlist click on the tab that says “MP3 Player” on the left. Then click “Add new Playlist”


## Adding music and creating a Playlist
#### Step 1: To add music after installing “MP3 Music Player by Sonaar” and going to your admin client side click on the MP3 Player on the left side then click “Add New Playlist” 
#### Step 2: Enter a playlist name and scroll down to “Track 1”
#### Step 3: Under source file select Local MP3 then click “Add or Upload File” and select your desired MP3
#### Step 4: Add an optional track image by clicking “Add image”
#### Step 5: to Add another track scroll down until you see “Add Another Track” and repeat steps 3-4 and you are done! 


## Making a new page and adding your playlist 
#### Step 1: select the “Pages” tab 
#### Step 2: click “Add New”
#### Step 3: Name the page at the top 
#### Step 4: Click the plus sign in the middle below the header and type “Classic” into the search bar and select it.
#### Step 5: Once The classic block is added click inside the block and click on the MP3 logo on the right side of the block
#### Step 6: Select the existing playlist you made earlier and then click “Insert Shortcode” and done!
#### Step 7: Click the big blue button that says “Publish”
