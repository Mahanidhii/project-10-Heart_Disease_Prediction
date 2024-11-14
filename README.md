# Heart Disease Prediction

### Description
A Regression type prediction model using Random Forest Regression algorithm. It uses accuracy score and classification report as the metric for prediction.

### Git and other commands used in the command prompt:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.
   
Docker Commands:
1. `docker build -t ,folder_name> .`
2. `docker run <folder_name>`

### Steps:
1. Create the required files such as the dataset csv file(heart.csv), training model python file, requirements txt file, Dockerfile.
2. Create a new item under Freestyle Project item type
3. Select Git in Source Code Management and paste your github repository url
4. Add Execute Windows Batch Command step in Build Steps
5. Save configurations
6. Build now and visualize console output
7. Now open command prompt with the path of the folder containing the required files
8. Execute the Docker commands mentioned above
9. Visualize the output in the command prompt and in the Docker Desktop app

### Output:
![Screenshot 2024-10-27 193431](https://github.com/user-attachments/assets/90b68158-f2c7-49ef-b520-827ace204070)

![Screenshot 2024-10-27 193359](https://github.com/user-attachments/assets/54a2b570-8a14-4bc7-97e3-96ca04dd1d6d)


