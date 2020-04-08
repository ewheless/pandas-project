# COVID-19 Google Search Trends

This project will explore Google trends search results in response to changes in coronavirus news. I compared search data using the Google API with Johns Hopkins COVID tacking map data to compare searches to the rate of confirmed cases and deaths.

## How to publish and submit your project

1. Make sure you have navigated to your `data-journalism` folder with your terminal first. Clone a fresh copy of this template and navigate to the folder.

   ```
   git clone git@github.com:JOUR73351/pandas-project.git NAME-OF-YOUR-PROJECT-HERE
   cd NAME-OF-YOUR-PROJECT-HERE
   ```

2) Remove my git tracking from the project

   ```
   rm -rf .git
   ```

3) Create a new repository on GitHub called `NAME-OF-YOUR-PROJECT-HERE` with the following settings.
   <br>
   <img src="assets/newrepo.png" width="500">

4) Run these git commands to initialize the repo. Make sure you've checked `ssh`.

   ```
   git init
   git add -A
   git commit -m "first commit"
   git remote add origin git@github.com:YOUR-USERNAME-HERE/YOUR-REPO-HERE.git
   git push -u origin master
   ```

5) Write your pitch in `README.md`.

6) Write your story in and add your assets and charts to `index.html`. Feel free to play around with and change the styles in `style.css`, but you are not required to. Delete the code that you don't need for your story. The story itself should be no less than 150 words and include at least one chart from Datawrapper. You can embed a Datawrapper chart in your story by copying the embed code into your html as I have done in `index.html.`
   <br>
   <img src="assets/datawrapper.png" width="500">

7) You can preview a local version of your story by running a python server.

   ```
   python -m SimpleHTTPServer 8000
   ```

   Then, navigate to `http://localhost:8000` in your browser. Before step 8, you must quit the python server by pressing `ctrl+c`.

8) To save a version of your story on GitHub, run the following git commands.

   ```
   git add -A
   git commit -m "YOUR-COMMIT-MESSAGE-HERE"
   git push
   ```

9) To publish, go to the settings of your GitHub repo, scroll down to GitHub Pages, and configure the source to the master branch.
   ![GitHub Pages](assets/ghpages.png)
