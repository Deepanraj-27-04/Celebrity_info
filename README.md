

`# OpenAI API Integration for Celebrity Search

## Overview
This project integrates the OpenAI API to search for information about celebrities. It utilizes Streamlit for the user interface and leverages OpenAI's language models for generating responses.

## Setup
1. Clone the repository:
    bashCopy code
   
   git clone <repository_url> `

1.  Install dependencies:

    bashCopy code

    `pip install -r requirements.txt`

Configuration
-------------

1.  Obtain an API key from OpenAI and store it in `constants.py` file as `openai_key`.

Usage
-----

1.  Run the Streamlit application:

    bashCopy code

    `streamlit run example1.py`

2.  Input the name of the celebrity you want to search for.
3.  The application will display information about the celebrity, including their date of birth and major life events.

Components
----------

-   `example1.py`: Main Python script containing the Streamlit application code.
-   `constants.py`: Constants file containing the OpenAI API key.
-   `langchain/`: Package containing modules for interacting with OpenAI API and managing language models.
-   `streamlit/`: Streamlit-specific configuration and UI components.

Details
-------

-   The application prompts the user to input the name of a celebrity.
-   It uses the input to generate a prompt for OpenAI API to inquire about the celebrity.
-   The application retrieves the date of birth of the celebrity using the generated prompt.
-   It then uses the date of birth to generate a prompt for OpenAI API to inquire about major events happening around that time.
-   Finally, the application displays the retrieved information about the celebrity and major events.

Contributing
------------

Contributions are welcome! Please submit pull requests or open issues for any improvements or bug fixes.

License
-------

This project is licensed under the MIT License - see the LICENSE file for details.
