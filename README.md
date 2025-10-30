# 💬 Intelligent Customer Feedback Chatbot

This project is a **Streamlit-based chatbot** that analyzes customer
feedback and answers questions about product reviews, sentiment trends,
and overall satisfaction.

## 🚀 Features

-   Upload a **CSV file** containing customer feedback.
-   Ask questions like:
    -   "Which product got the best rating?"
    -   "What's the average feedback?"
    -   "How many positive reviews are there?"
-   Uses a **rule-based NLP logic** for now (expandable with
    Transformers).
-   Simple **interactive UI** built with Streamlit.

## 🧠 Technologies Used

-   **Python**
-   **Streamlit**
-   **Pandas**
-   **Transformers (Hugging Face pipeline)**

## ⚙️ How to Run

1.  Clone the repository:

    ``` bash
    git clone https://github.com/Anjali-Chebathina/Intelligent-Customer-Feedback-Analysis-System-using-AI.git
  
    ```

2.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

3.  Run the Streamlit app:

    ``` bash
    streamlit run app.py
    ```

4.  (Optional) Expose the app publicly using ngrok:

    ``` bash
    from pyngrok import ngrok
    public_url = ngrok.connect(8501)
    print(public_url)
    ```

## 🗂️ Example Dataset Format

  Product Name   Review                   Rating
  -------------- ------------------------ --------
  Speaker        Amazing sound quality!   5
  Light          Poor build quality       2

## 💡 Future Improvements

-   Integrate real **sentiment analysis** using Hugging Face models.
-   Add **conversation memory** for a more natural chat experience.
-   Visualize feedback insights with **charts**.

## 🤝 Contributing

Feel free to fork this repo, improve the chatbot logic, and create a
pull request!



------------------------------------------------------------------------

### 🧑‍💻 Author

**Anjali Chebathina**
