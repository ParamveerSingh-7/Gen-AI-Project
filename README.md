# **AI Negotiation Assistant**

## **Overview**

The **AI Negotiation Assistant** is an interactive AI-powered chatbot that simulates real-world negotiation scenarios. Users can negotiate the price of a product with an AI salesperson, who responds with realistic counter-offers and justifications based on product features, competitor prices, and customer loyalty.

This assistant leverages Google's Gemini Generative AI for dynamic, context-aware negotiation, making it ideal for practicing negotiation skills or simulating business sales interactions.

---

## **Interface**

Frontend UI:

![AI Negotiation Assistant Frontend](../Screenshot%202025-05-10%20at%2011.59.31%E2%80%AFAM.png)

---

## **Key Features**

- **Product Negotiation**: Negotiate the price of a high-end product with the AI.
- **Real-Time AI Responses**: The AI justifies prices and counters offers based on negotiation context.
- **Dynamic Pricing**: Offers adjust based on product features, competitor prices, and customer loyalty.
- **Multiple Rounds**: Up to 7 negotiation rounds before a final offer is made.
- **Competitor Awareness**: The AI references competitor prices in its negotiation strategy.
- **Customer Loyalty Factor**: Discounts and offers are influenced by a simulated loyalty score.

---

## **Installation**

### **Prerequisites**

- Python 3.7+
- Streamlit
- Google Generative AI SDK
- Google Cloud account with Gemini API access

### **Steps to Install**

1. **Clone the Repository**:

   ```bash
   git clone <your-repo-url>
   cd <your-project-folder>
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r req.txt
   ```

3. **Set Up Google Gemini API**:

   - Sign up for Google Cloud and enable the Generative AI API (Gemini).
   - Create an API key and replace the placeholder in `neg.py` with your key.

4. **Run the Application**:
   ```bash
   streamlit run neg.py
   ```

---

## **Usage**

- **Start a Negotiation**: The chatbot introduces the product and its price.
- **Make Offers**: Enter your price offers or negotiation messages.
- **AI Counter-Offers**: The AI responds, justifying its price and referencing competitors.
- **Negotiate Up to 7 Rounds**: The process continues until a deal is reached or the maximum rounds are completed.

---

## **Project Structure**

- **neg.py**: Main Streamlit app and negotiation logic.
- **req.txt**: Project dependencies.

---

## **Configuration**

- **Product Details**: Change the product name, price, and features in the `Product` class in `neg.py`.
- **API Key**: Insert your Gemini API key in `neg.py`.
- **Negotiation Settings**: Adjust max rounds, discount limits, and other parameters in the `NegotiationChatbot` class.

---

## **Technologies Used**

- **Python**
- **Streamlit**
- **Google Generative AI (Gemini)**
- **Random Module** (for dynamic competitor prices and loyalty)

---

## **Contributing**

Contributions are welcome! Please submit a pull request with your improvements or bug fixes.

---
