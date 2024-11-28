Technical Overview
==================

**Architecture**:
- **Frontend**:
  - Built using HTML, CSS, and JavaScript.
  - Supports voice recording and text input.
- **Backend**:
  - Flask server providing REST APIs.
  - Processes voice data and analyzes text.
- **Machine & Deep Learning**:
  - Converts voice data into text using Google Speech-to-Text API.
  - Analyzes text and understands context using the OpenAI GPT model.

**Process Flow**:
1. Users input voice or text data.
2. The Flask server processes the input.
3. Analysis results are returned to the user.
4. Warning audio is played if necessary.