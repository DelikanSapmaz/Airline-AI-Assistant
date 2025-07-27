


<img width="1839" height="943" alt="projejpeg" src="https://github.com/user-attachments/assets/0f00fc3c-809b-462d-962d-8cca6eedc4c1" />








🔧 Environment Setup
To run this project, you need to set up a Python environment and provide your OpenAI API key in a .env file.

1. Create and activate a virtual environment (optional but recommended):
bash
Kopyala
Düzenle
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
2. Install the required packages:
bash
Kopyala
Düzenle
pip install -r requirements.txt
3. Create a .env file in the root directory of the project:
This file will store your OpenAI API key securely.

Example .env file:

ini
Kopyala
Düzenle
OPENAI_API_KEY=your_openai_api_key_here
⚠️ Make sure not to share your .env file or commit it to version control. You can add .env to your .gitignore.
