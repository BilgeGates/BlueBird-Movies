<h1 align="center">BlueBird Movies</h1>
BlueBird Movies is a React-based movie website that allows users to search for movies by title, sort them by genre, view trending and upcoming movies, and bookmark their favorite movies. The website is designed to be user-friendly and visually appealing.
<hr/>
<img src="/src/assets/project__image/Home.jpg" />
<hr/>
<h2> 🍿 Features </h2>
<ul>
<li>Search and watch movies: users can search for movies by title and can watch them easily</li>
<li>Genre-wise display: movies can be sorted by genre</li>
<li>Trending Movies: displays a section for trending movies</li>
<li>Upcoming movies: displays a section for upcoming movies</li>
<li>Movie Details: users can view detailed information about each movie</li>
<li>Bookmark Movies: users can bookmark their favorite movies for later viewing</li>
<li>Google Authentication: users can sign in using their Google account</li>
</ul>
<hr/>
<h2> 🍿 Technology </h2>
<p>BlueBird Movies is built using the following technologies:
</p>
<ul>
<li>ReactJS</li>
<li>TMDB API</li>
<li>Firebase Google Authentication</li>
<li>Framer Motion</li>
</ul>
<hr/>
<h1> 🍿 How to Run the Website on Your System</h1>
<h2>Step 1: Download and Extract the Code</h2>
<p>Firstly, download the entire website code and extract the ZIP file to a folder on your local system.</p>
<h2>Step 2: Obtain the TMDB Movies API Key and Firebase Configuration</h2>
<p>Before starting the website, you will need to obtain the TMDB Movies API key and Firebase configuration. Follow these steps to obtain them and add them to your <code>.env</code> file.</p>
<h3> ▶️ Get TMDB API Key</h3>
<p> Go to <a href="https://www.themoviedb.org/" target="_blank">https://www.themoviedb.org/</a> and log in.</p><br>
<p> - Click on your user profile picture in the navigation bar, and select "Settings".</p><br>
<p> - In the settings, select "API" and generate an API key.</p>
<h3> ▶️ Firebase Setup</h3>
<p>Note that Firebase is only required for Google authentication. If you are not using Google authentication in your application, you can skip this step. </p>
<p> - Go to the Firebase Console and create a new app. </p>
<p> - After creating the app, build a web app by clicking "Add App" and following the instructions. </p>
<img src="./src/assets/project__images" />

![Firebase Build App Screenshot](https://user-images.githubusercontent.com/87109400/231568774-1ea09ada-34b8-4035-80d4-90ac79c1c8ed.png)

- Copy the configuration information provided in the green line, and paste it into the `.env` file:

![image](https://user-images.githubusercontent.com/87109400/231570250-9256c1bc-6669-423a-8b95-06d9577485a0.png)

- Next, to activate Google authentication in Firebase, go to **Build > Authentication** and enable Google authentication.
- To use Google authentication in localhost, add your localhost/127.0.0.1 as an Authorized Domain at **Build > Authentication > Settings > Authorized Domains** and add localhost or 127.0.0.1 to this section.

![image](https://user-images.githubusercontent.com/87109400/231575419-ca703ebd-5380-45b6-8afe-33b9c1af778e.png)

<h2>Step 3: Run the Website</h2>
<p>Open your code editor (such as VS Code) and navigate to the project directory. Then, open a terminal and run the following command:</p>
<pre><code>npm run dev</code></pre>
<p>This will start the application. Open a web browser and navigate to <a href="http://localhost:5173" target="_blank">http://localhost:5173</a> to access the website.</p>
<p>Note: Ensure that you have carefully added the TMDB API key and Firebase authentication configuration to your <code>.env</code> file. If the <code>.env</code> file is not working, add all the API keys and configuration manually.</p>
<hr>
<h1>🍿 Demo</h1>
<p>Check out our live demo at https://bluebird-movies.netlify.app </p>

# 🍿 How to Run the Website on Your System

## Step 1: Download and Extract the Code

Firstly, download the entire website code and extract the ZIP file to a folder on your local system.

## Step 2: Obtain the TMDB Movies API Key and Firebase Configuration

Before starting the website, you will need to obtain the TMDB Movies API key and Firebase configuration. Follow these steps to obtain them and add them to your `.env` file.

### ▶️ Get TMDB API Key

- Go to https://www.themoviedb.org/ and log in.
- Click on your user profile picture in the navigation bar, and select "Settings".
- In the settings, select "API" and generate an API key.

### ▶️ Firebase Setup

Note that Firebase is only required for Google authentication. If you are not using Google authentication in your application, you can skip this step.

- Go to the Firebase Console and create a new app.
- After creating the app, build a web app by clicking "Add App" and following the instructions.

![Firebase Add App Screenshot](https://user-images.githubusercontent.com/87109400/231569204-445d8007-fe75-4012-a21b-a71f4f4bc697.png)

![Firebase Build App Screenshot](https://user-images.githubusercontent.com/87109400/231568774-1ea09ada-34b8-4035-80d4-90ac79c1c8ed.png)

- Copy the configuration information provided in the green line, and paste it into the `.env` file:

![image](https://user-images.githubusercontent.com/87109400/231570250-9256c1bc-6669-423a-8b95-06d9577485a0.png)

- Next, to activate Google authentication in Firebase, go to **Build > Authentication** and enable Google authentication.
- To use Google authentication in localhost, add your localhost/127.0.0.1 as an Authorized Domain at **Build > Authentication > Settings > Authorized Domains** and add localhost or 127.0.0.1 to this section.

![image](https://user-images.githubusercontent.com/87109400/231575419-ca703ebd-5380-45b6-8afe-33b9c1af778e.png)

## Step 3: Run the Website

Open your code editor (such as VS Code) and navigate to the project directory. Then, open a terminal and run the following command:

```bash
npm run dev
```

This will start the application. Open a web browser and navigate to http://localhost:3000 to access the website.

Note: Ensure that you have carefully added the TMDB API key and Firebase authentication configuration to your .env file. If the .env file is not working, add all the API keys and configuration manually.

<hr/>

# 🍿 Demo

- Check out our live demo at https://moviesbluebird.netlify.app/
