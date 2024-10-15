# Movie-Recommender-System

## Overview

This Movie Recommender System is a web application built using Streamlit, designed to help users discover new movies based on their preferences. The app utilizes collaborative filtering techniques to provide personalized movie recommendations.

## Features

- **User-Friendly Interface**: An intuitive dropdown menu for selecting movies.
- **Movie Recommendations**: Get a list of recommended movies similar to the selected one.
- **Movie Posters**: Displays posters of recommended movies fetched from The Movie Database (TMDb) API.
- **Dynamic Columns**: Recommendations are displayed in a grid format for a clean and organized look.

## Technologies Used

- **Python**: The programming language used for backend logic.
- **Streamlit**: A framework for creating web applications in Python.
- **Pandas**: Used for data manipulation and analysis.
- **Requests**: For making API calls to fetch movie data and posters.
- **Pickle**: For loading pre-processed movie data and similarity matrices.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. Install the required packages:

   ```bash
   pip install streamlit pandas requests
   ```

3. Download the required data files (`movie_dict.pkl` and `similarity.pkl`) and place them in the project directory.

## Usage

1. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

2. Open the provided URL in your browser (usually `http://localhost:8501`).

3. Select a movie from the dropdown menu and click "Show Recommendation" to see the recommended movies along with their posters.

## API Key

To fetch movie posters, an API key from [The Movie Database (TMDb)](https://www.themoviedb.org/) is required. Replace the API key in the code with your own:

```python
API_KEY = 'YOUR_API_KEY_HERE'
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Streamlit](https://streamlit.io/) for providing an easy-to-use framework for building web applications.
- [The Movie Database (TMDb)](https://www.themoviedb.org/) for their extensive movie database and API.

```

### Notes:
- Replace `yourusername` in the clone URL with your actual GitHub username.
- You can add more sections or details as necessary, such as examples, screenshots, or a list of future enhancements.
- Make sure to include a LICENSE file if you decide to open-source the project.
