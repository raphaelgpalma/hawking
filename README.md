## Hawking - A Voice Assistant powered with Wikipedia Search

This is a simple voice assistant that utilizes the Wikipedia library to search for information based on user speech. The assistant is capable of conducting searches for word or concept definitions, providing a Wikipedia summary for the queried subject.
Operation

The voice assistant Hawking interacts with the user to understand their queries and perform searches on Wikipedia. Users can ask questions or request definitions for specific words or terms.

The assistant can understand commands such as:

    "what is [term or word]?"
    "what was [term or word]"
    "who is [person]?"
    "define [term or concept]"

The code is written in Python and uses the following libraries:

    wikipedia: To search for information on Wikipedia.
    speech_recognition: To capture user's voice input.
    pyttsx3: To synthesize voice responses from the assistant.

## Installation

To run the code, you need to have Python installed on your computer. Additionally, you need to install the libraries used in the code. Use pip, the Python package manager, to install them:

```bash
pip install wikipedia-api
pip install SpeechRecognition
pip install pyttsx3
```

## How to Use

    Run the script assistant.py in the terminal or your preferred Python IDE.
    The assistant will greet you and ask how it can help.
    Speak your query or question when the assistant indicates that it is listening.
    The assistant will search for the answer on Wikipedia and read the summary aloud.
    After reading, the assistant will ask if it can help with anything else.
    To end the assistant, simply say "Now."

## Notes

    The assistant uses the Wikipedia library to search for information on Wikipedia. Therefore, the availability and accuracy of information depend on the quality of the data available on Wikipedia.
    In case of errors in the search or understanding of the user's speech, the assistant will inform about the issue and ask for the query to be repeated.

I hope this README helps present the voice assistant code using the Wikipedia library clearly and concisely. If there's any other specific detail you would like to include in the README, feel free to modify it according to your project's needs.

## Usage

1.Create a virtual environment:

```bash
python -m venv venv
```

2. Install the dependencies:

 ```bash
pip install -r requirements.txt
 ```

3. Run

```bash
python main.py
```
