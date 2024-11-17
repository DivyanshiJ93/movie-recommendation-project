# 🎥 **Movie Recommendation System**  

This project implements a **content-based filtering** approach to build a movie recommendation system. By leveraging movie metadata such as genres, cast, crew, and keywords, the system provides personalized recommendations based on the content similarity between movies.  

---

## 📌 **Key Features**  
- **Content-Based Filtering**: Uses metadata to generate similarity scores between movies.  
- **Cosine Similarity**: Computes the similarity matrix for precise recommendations.  
- **Interactive Streamlit App**: Provides a seamless user interface to interact with the recommender system.  
- **Data-Driven Approach**: Powered by a real-world dataset of 5000+ movies from TMDB.  

---

## 🛠️ **Technical Workflow**  
### **1. Data Preprocessing**  
- **Cleaning and Filtering**: Handles missing or irrelevant data.  
- **Metadata Engineering**: Combines features such as genres, keywords, and cast into a unified textual format.  
- **TF-IDF Vectorization**: Converts textual metadata into numerical vectors to calculate similarity.  

### **2. Similarity Computation**  
- **Cosine Similarity**: Measures the angle between vectors to determine the degree of similarity between movies.  
- **Top-5 Recommendations**: Retrieves the most similar movies based on the computed similarity scores wrt different parameters.  

### **3. User Interaction**  
- The application is hosted on **Streamlit and Render**, providing an intuitive and interactive interface for users to:  
  - Input a movie name.  
  - View the top recommended movies based on similarity.  
  - Explore details like genres, cast, and crew of the recommendations.  

---

## 📂 **Project Structure**  
- **`main.py`**: Orchestrates the recommendation flow and integrates the Streamlit app.  
- **`preprocess.py`**: Handles all preprocessing and metadata engineering.  
- **`display.py`**: Facilitates the output interface.  
- **Datasets**:  
  - `tmdb_5000_movies.csv`: Contains metadata for 5000+ movies.  
  - `tmdb_5000_credits.csv`: Includes cast and crew details.  

---

## 💻 **Installation and Usage**  
### **1. Clone the Repository**  
```bash
git clone https://github.com/DivyanshiJ93/movie-recommendation-project.git
cd movie-recommendation-project
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Application**  
```bash
streamlit run main.py
```

---

## 🌟 **Project Snippets**  

### **Home Page**  
Welcome screen where users can input a movie name and explore recommendations.  

![Home Page](https://drive.google.com/file/d/1GG7SbbDF5grFS9T8vAWxLRhhy25RI5eA/view?usp=sharing)  

---

### **Recommendations Display**  
The output page displaying the recommended movies along with their metadata.  

![Recommendations Page](https://drive.google.com/file/d/1GjYxwc7NgrL1cLq4TKWaVWBxCFWuw339/view?usp=sharing)  

---

### **Detailed View**  
Users can view detailed metadata for a selected movie, including genres, cast, and crew.  

![Detailed View](https://drive.google.com/file/d/11zs6tD2Y-CJdjXvq1kkJsv7eJ_i8RdaH/view?usp=sharing)  

---

## 📊 **Dataset Overview**  
This project utilizes the **TMDB 5000 Movies Dataset**, containing:  
- **Movies Metadata**: Genres, release dates, popularity, runtime, etc.  
- **Cast and Crew Details**: Key contributors for each movie.  
- **Keywords**: Descriptive tags for movies.  

---

## 🚀 **Future Enhancements**  
- **Hybrid Filtering**: Combine content-based filtering with collaborative filtering for improved accuracy.  
- **Deployment**: Optimize the hosted Streamlit app for faster performance on platforms like Render or Heroku.  
- **Dynamic Data Integration**: Integrate live metadata from TMDB APIs to keep recommendations up to date.  

---

## 🛠️ **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - `Streamlit`: For building the web interface.  
  - `Pandas`: For data preprocessing.  
  - `Scikit-learn`: For TF-IDF vectorization and similarity computation.  
  - `NumPy`: For numerical operations.  

---

📑 Project Resources
1. Project Report
The detailed project report includes:

Overview of the recommendation system.
Methodology, including preprocessing, similarity computation, and deployment.
Results and future improvements.
📄 ![Download the Project Report](https://docs.google.com/document/d/1f7a-zZTlRzRV67ldzoPl-9nldwOSOIr1/edit?usp=sharing&ouid=106286490124518764986&rtpof=true&sd=true)

2. Presentation
The accompanying presentation covers:

Summary of the project’s goals and achievements.
Key technical and analytical insights.
Visuals for easy understanding of the workflow and results.
📽️ ![Download the Presentation](https://docs.google.com/presentation/d/1FCDgmcJTQnXNH7PhOE6IOEzaaxsNKgMC/edit?usp=sharing&ouid=106286490124518764986&rtpof=true&sd=true)



## 👩‍💻 **Author**  
**Divyanshi Jain**  
- Second year student currently passionate about Machine Learning.  
   

Feel free to contribute or suggest improvements by opening issues or pull requests in the repository.  

---

