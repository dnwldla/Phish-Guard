API Reference
=============

**Endpoints**:
- **/process_text**: Analyzes text data.
  - **Request Format**:
    ```json
    { "user_message": "text" }
    ```
  - **Response Format**:
    ```json
    { "modelOutput": "analysis result", "audioBlob": "warning message audio data" }
    ```

- **/process_voice**: Analyzes voice data.
  - **Request Format**:
    Audio file (FormData).
  - **Response Format**:
    ```json
    { "convertedText": "converted text", "modelOutput": "analysis result", "audioBlob": "audio data" }
    ```