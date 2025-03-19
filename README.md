# Movie Recommendation System

## Overview

The Movie Recommendation System is a content-based filtering application that suggests movies to users based on their preferences. Utilizing the TMDB dataset, the system uses content-based filtering which recommends movies by comparing their attributes such as genres, overviews, and keywords. It calculates similarity scores between movies to identify those with similar content.Simply enter a movie title and the system will provide a list of related movies helping you find new titles that match your interests.

## Features
- **Content-Based Filtering**: Recommends movies similar to user-selected titles by analyzing attributes like genre, overview, and keywords.
- **Interactive Interface**: Users can input their favorite movies and receive tailored suggestions instantly.

## Screenshots
![Img1](https://github.com/user-attachments/assets/1aaa2df5-6d8a-479e-893b-ca0d699435b8)


### 🔍 Movie Search
![Img2](https://github.com/user-attachments/assets/6386fed2-5c3c-470b-8a30-b4d99c76bae2) ![Img3](https://github.com/user-attachments/assets/31db08f9-b60b-4e26-85f0-27cb54d74ede)

## Installation
To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/s0wjanyaa/MovieRecSys.git
   cd MovieRecSys
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   Launch the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Launch the Application**: Follow the installation steps to start the Streamlit app.
2. **Input a Movie Title**: Enter the name of a movie you like in the search bar.
3. **Receive Recommendations**: The system will display a list of movies similar to your input, helping you discover new titles that match your interests.

## Dataset

The application leverages the TMDB dataset, which includes comprehensive information on movies such as titles, genres, overviews, and keywords. This rich dataset enables the system to perform effective content-based filtering.
 
