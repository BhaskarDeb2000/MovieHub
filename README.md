# MovieHub

MovieHub is a movie discovery platform where users can explore movies, search for their favorites, sign in, and create a personalized watchlist. Whether you're a movie enthusiast or just looking for something new to watch, MovieHub has you covered with an easy-to-use interface and powerful features.

## Features

1. **Browse All Movies**  
   - Display all available movies with details like title, poster, and description.
  
2. **Search for Movies**  
   - Users can search for movies by title to find exactly what they're looking for.

3. **User Authentication**  
   - Users can sign up and sign in to their accounts to personalize their movie experience.

4. **Watchlist**  
   - After signing in, users can add movies to their personalized watchlist for future viewing.

### Tech Stack

- **React** - Frontend framework for building interactive user interfaces.
- **Vite** - Fast build tool and development environment for React apps.
- **Redux** - State management for handling global state.
- **React Hooks** - For managing state and side effects in functional components.
- **Vercel** - Platform for deploying the app seamlessly.
- **OMDb API** - Movie database API for fetching movie information.

### Setup Instructions

To run MovieHub locally, you'll need an API key from the OMDb API.

1. **Get Your API Key**  
   - Visit [OMDb API](https://www.omdbapi.com/apikey.aspx) and sign up to get your personal API key.

2. **Create a `.env` File**  
   - In the root directory of the project, create a `.env` file.
   - Add the following lines to the `.env` file, replacing `<your-api-key>` with the API key you received from OMDb:

     ```env
     VITE_SUPABASE_URL=<url>
     VITE_SUPABASE_ANON_KEY=<your-api-key>
     ```

3. **Install Dependencies**  
   After you've added the API key, install the dependencies by running:

   ```bash
   npm install
   ```

4. **Start the Development Server**  
   Run the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and go to `http://localhost:3000` to see the app in action.

### Deployment

MovieHub is deployed on **Vercel**. You can access the live version here:

[MovieHub Live](https://moviehub.vercel.app)
