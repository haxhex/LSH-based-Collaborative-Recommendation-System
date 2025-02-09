# LSH-based Collaborative Recommendation System with Privacy-Preservation

## Overview
This project explores the integration of Locality Sensitive Hashing (LSH) with collaborative filtering recommendation systems while ensuring privacy preservation. Built on the MovieLens 20M dataset and custom-scraped Instagram data, it focuses on scalable data handling, privacy-preserving methods, and personalized recommendations. The main objectives include efficient recommendation generation using LSH, maintaining user privacy, and applying the system to real-world datasets.

## Project Structure
- **Dataset Exploration:** Analyzing and understanding MovieLens and Instagram datasets.  
- **Preprocessing:** Data cleaning, transformation, and sparse representation for scalable computations.  
- **Train-Test Splitting:** Partitioning the dataset to ensure robust model evaluation.  
- **LSH-based Collaborative Filtering:** Implementing the method based on LSH for efficient similarity search.  
- **Hyperparameter Optimization:** Fine-tuning LSH parameters to enhance recommendation accuracy.  
- **Evaluation:** Measuring performance using precision, recall, and NDCG metrics.

## Key Features
- Privacy-preserving recommendations leveraging LSH  
- Big data handling with sparse representations  
- Custom Instagram engagement-based recommendations  
- LSH hyperparameter tuning and evaluation  

## Technologies Used
- **Python:** Data processing and model implementation  
- **Pandas & NumPy:** Data manipulation and matrix computations  
- **Scikit-learn:** Nearest neighbor search using LSH  
- **Matplotlib & Seaborn:** Data visualization  
- **Jupyter Notebooks:** Code documentation and analysis  

## Installation
1. Clone the repository:  
   `git clone https://github.com/your-username/lsh-privacy-recommendation.git`  
   `cd lsh-privacy-recommendation`  
2. Create and activate a virtual environment:  
   `python3 -m venv venv`  
   `source venv/bin/activate` (Windows: `.\\venv\\Scripts\\activate`)  
3. Install dependencies:  
   `pip install -r requirements.txt`

## Datasets
- **MovieLens 20M Dataset:** [Available here](https://grouplens.org/datasets/movielens/20m/)  
- **Instagram Interaction Data:** Includes:  
  - `InstaDataset.info`: Metadata of Instagram pages (followers, engagement)  
  - `InstaUserDataset.info`: User interactions with pages  

## Recommendation Algorithm
- **LSH-based Similarity Search:** Finds similar users based on hashed representations of their interactions.  
- **Rating Rules (Instagram Dataset):**  
  - Follows a page: 0.3 points  
  - Likes a post: 0.1 points  
  - Comments on a post: 0.2 points  

## Results
- Precision and recall curves to evaluate recommendation performance  
- Comparison of LSH configurations for optimal results  
- Sample analysis of recommendations on custom Instagram data  

## Future Improvements
- Integrating advanced engagement metrics  
- Exploring alternative hashing methods  
- Strengthening privacy with cryptographic solutions  

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## References
- MovieLens Dataset: [grouplens.org](https://grouplens.org/datasets/movielens/20m/)  
- IEEE Paper: LSH-based Collaborative Recommendation Method with Privacy-Preservation (2020)  
- Python Libraries: BeautifulSoup, Selenium for data scraping  
