# 💬 Intelligent Customer Feedback Chatbot
## 🏢 Company
**Flikt Technology Web Solution Pvt. Ltd.**

This project was developed and submitted as part of an internship under **Flikt Technology Web Solution**.  
It demonstrates real-world application of **AI, NLP, and Streamlit** in analyzing and interacting with customer feedback data.

---

## 🧾 Project Description
The **Intelligent Customer Feedback Chatbot** is an interactive AI-based system built using **Streamlit** and **Hugging Face Transformers**.  
It helps users upload customer feedback datasets (CSV files) and interactively query insights such as:

- Positive or negative feedback trends  
- Product comparisons  
- Rating summaries  
- Customer satisfaction levels  
- Review-based analysis  

## 🖼️ Screenshots

### 🏠 Home Page
<img width="1919" height="969" alt="Screenshot 2025-10-30 201531" src="https://github.com/user-attachments/assets/2eefaf5e-0835-4368-9f6b-d42d3b680404" />


### 📂 Upload Feedback Section
<img width="1323" height="715" alt="Screenshot 2025-10-30 202104" src="https://github.com/user-attachments/assets/ea668190-60b8-47a8-9c37-8633eb4013ab" />


### 💬 Chatbot Interaction
<img width="1909" height="960" alt="Screenshot 2025-10-30 203217" src="https://github.com/user-attachments/assets/3b114e0e-55ec-4155-8f29-30e11a631570" />


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

##  📊 Example Questions for Chatbot
-----------------------------------------------

You can ask the chatbot:

“Which product got the best rating?”

“Show me negative reviews.”

“What is the average rating?”

“Compare the speakers and chandeliers.”

“Are most customers satisfied?”

##  🙌 Acknowledgements
--------------------------------------------

- Flikt Technology Web Solution Pvt. Ltd. for providing guidance and support.

- Hugging Face for their pre-trained NLP models.

- Streamlit for the rapid web app framework.

------------------------------------------------------------------------

### 🧑‍💻 Author

**Anjali Chebathina**

📧 Email: anjalichebathina.com


