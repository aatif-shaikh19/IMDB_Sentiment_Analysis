 **IMDB Movie Review Sentiment Analysis**
 This project performs sentiment analysis on IMDB movie reviews using Natural Language Processing and machine learning techniques. The final model is deployed in a simple web application built with Streamlit.
 ## 
 Project Structure
 1. **IMDB_Movie_Sentiment_Analysis.ipynb**
   - Data preprocessing
   - Text cleaning and tokenization
   - Vectorization using `TfidfVectorizer`
   - Model training (Logistic Regression)
   - Evaluation using accuracy, classification report, and confusion matrix
 2. **Model_Testing&Web_Application.ipynb**
   - Model testing
   - Streamlit-based web app for real-time sentiment prediction
 ## 
 Features- Binary sentiment classification (Positive / Negative)- Uses TF-IDF for feature extraction- Logistic Regression classifier- Interactive web app using Streamlit
 ## 
 Installation & Setup
 1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/imdb-sentiment-analysis.git
   cd imdb-sentiment-analysis
   ```
 2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
 3. Run the Streamlit app:
   ```bash
   streamlit run Model_Testing&Web_Application.ipynb
   ```
 > Make sure to convert the model notebook to a `.py` script using:
 ```bash
 jupyter nbconvert --to script Model_Testing&Web_Application.ipynb
 ```
 ## 
 Dependencies- pandas- numpy
- scikit-learn- matplotlib- seaborn- nltk- streamlit
 
 ## 
 Example Output
 Input: _"This movie was fantastic! The storyline was gripping."_
 Output: **Positive**
