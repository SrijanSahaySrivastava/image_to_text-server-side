# Gemini Image Description Generator

This is a FastAPI application that generates descriptions for images. It uses the `gemini_image` model to generate the descriptions.

## Installation

1. Clone this repository.
2. Make an environment with `python -m venv env`.
3. Activate the environment with `source env/bin/activate` on Linux or `env\Scripts\activate` on Windows.
4. Install the requirements with `pip install -r requirements.txt`.

## Usage

1. Run the server with `uvicorn main:app --reload`.
2. Send a POST request to `http://localhost:8000/upload/` with a `url` query parameter containing the URL of the image you want to process.

## Testing with Postman

1. Open Postman.
2. Create a new request.
3. Set the request method to `POST`.
4. Enter `http://localhost:8000/upload/` in the request URL field.
5. Go to the `Params` tab.
6. In the `Key` field, type `url`. In the `Value` field, enter the URL of the image you want to process.
7. Click `Send` to make the request.
