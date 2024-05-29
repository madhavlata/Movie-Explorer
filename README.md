# Movie Explorer
Movie Explorer is a web application that allows users to search for movies by title and get details.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **API**: OMDb API
- **Deployment**: Render (frontend), Render (backend)

## Features
- Search movies by title
- View movie details including title, release year, synopsis, and poster image

## Development Process
- Firstly, I developed its backend using OMDb API which provides 1000 free request per day.
- Then I developed its frontend UI and connected it with backend making API calls functional and visible.
- So finally this way Movie Explorer web app is ready to use.

## How to setup this locally
1. Clone the repository.
2. Install dependencies:
    - Backend: `npm install`
    - Frontend: `npm install`
3. Create a `.env` file in the backend directory with your OMDb API key:
    OMDB_API_KEY= your_key
4. Run the backend server:
    ```bash
    npm start
    ```
5. Run the frontend application:
    ```bash
    npm run start
    ```


## Deployment
- Backend: Deployed on Render
- Frontend: Deployed on Render

## Assumptions
- OMDb API doesn't provide facility to search by genre.
- OMDb API providing 1000 requests per day is sufficient.
