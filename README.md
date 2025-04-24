📚 Book Recommendation System (Hybrid)
This is a hybrid book recommendation system that suggests books based on either:

👤 User ID: Recommends books personalized to a specific user.

📘 Book Title: Recommends books similar to a given book.

It combines User-Based and Item-Based Collaborative Filtering using KNN models built from scratch with fallback logic for cold-start problems.

💡 Features
🔍 Hybrid Input: Accepts either User ID or Book Title

🧠 Collaborative Filtering: Implements item-based and user-based KNN approaches

📊 Predicted Ratings: Displays personalized predicted scores

⭐ Average Ratings: Shows global average ratings per book

🖼️ Book Covers: Displays book cover image, title, and author

🚨 Fallback Suggestions: Recommends top-rated books for unknown inputs

🧰 Technologies Used
Python

Streamlit

Pandas

Scikit-learn

Jupyter Notebook

🗂️ Project Structure
📁 Book_Recommendation_System/
├── app.py – Main Streamlit app
├── Books_df.pkl – Book metadata
├── filtered_df.pkl – Cleaned rating data
├── user_model.pkl – User-based KNN model
├── item_model.pkl – Item-based KNN model
├── trainset.pkl – User interaction matrix
├── trainset_item.pkl – Item similarity matrix
├── title_to_isbn.pkl – Title-to-ISBN mapping
└── README.md

🚀 How to Run Locally
Make sure Python and Streamlit are installed.

bash
Copy
Edit
git clone https://github.com/yourusername/Book_Recomm_Sys.git
cd Book_Recomm_Sys
streamlit run app.py


🙌 Acknowledgments
Book-Crossing Dataset

Streamlit Team

Community sources for KNN recommender system logic