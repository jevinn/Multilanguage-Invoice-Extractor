# Multilanguage Invoice Extractor

This is a Streamlit web application that utilizes Google's Generative AI model to extract information from invoices uploaded as images. It allows users to input a prompt and upload an invoice image, and then generates a response based on the uploaded image and the input prompt.

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Create a `.env` file in the root directory of the project and add your Google API key. You can obtain an API key from the Google Cloud Console.
4. Run the Streamlit app using `streamlit run app.py`.
5. Access the application in your web browser at `http://localhost:8501`.

## Usage

1. Upon accessing the application, you'll see a text input field where you can provide a prompt.
2. Upload an image of an invoice using the provided file uploader.
3. Click on the "Talk to me" button to generate a response based on the uploaded image and input prompt.
4. The generated response will be displayed below the button.

## Dependencies

- Streamlit: 0.89.0
- Pillow: 9.0.0
- google-generativeai: (version compatible with your Google API key)
- dotenv: 0.19.5

## File Structure

- `app.py`: Main Streamlit application file.
- `requirements.txt`: List of Python dependencies.
- `.env`: Environment file for storing sensitive information (e.g., API keys).

## Contributing

Contributions are welcome! If you have any suggestions, feature requests, or found a bug, please open an issue or submit a pull request.

