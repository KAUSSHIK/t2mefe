# t2mefe

# Kausshik's Assistant Frontend

This is the frontend component of Kausshik's Assistant, a Streamlit-based web application that allows recruiters to interact with an AI chatbot to learn about Kausshik Manojkumar.

## Technology Stack

- Python 3.10
- Streamlit
- HTTPX for asynchronous HTTP requests

## Setup

1. Clone the repository:
   ```
   git clone <your-repo-url>
   cd <your-repo-name>
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Update the backend URL:
   In `app.py`, update the `url` variable in the `send_message` function to point to your deployed backend URL.

## Running the Frontend Locally

To run the Streamlit app locally:

```
streamlit run app.py
```

The app will open in your default web browser.

## Deploying to Streamlit Sharing

1. Push your code to a GitHub repository.
2. Go to [Streamlit Sharing](https://share.streamlit.io/) and sign in with your GitHub account.
3. Click on "New app" and select your repository, branch, and main file path (app.py).
4. Click "Deploy".

For more detailed instructions, refer to the [Streamlit Sharing documentation](https://docs.streamlit.io/streamlit-cloud/get-started/deploy-an-app).

## Usage

Once the app is running:

1. Type your question about Kausshik in the text input field.
2. Click "Send" or press Enter.
3. The AI-generated response will appear in the chat interface.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Specify your license here]
