# Spell_Grammar_Checker![Screenshot (93)](https://github.com/user-attachments/assets/a7909713-a139-47b9-b5f8-9eeedadb6a38)
 Description:
This version of the app expands functionality beyond basic text input by adding file upload support. The interface consists of:

Textarea Input: For direct typing or pasting of text.

Correct Button (for text input): Triggers grammar and spell check for typed content.

Corrected Word Display: Shows suggested corrections (e.g., Corrected Word: body).

Grammar Mistakes Output: Displays details like (['typographical'], 1) indicating types and number of errors found.

File Upload Feature:

Input to choose a file (likely .txt, .docx, or similar).

Another Correct button to process the uploaded file.

💻 Languages and Technologies Used:
🔹 Frontend:
HTML: Basic structure for form fields, labels, buttons, etc.

CSS/Bootstrap: For styling.

Black background

White text

Blue Correct buttons with Bootstrap styling hints.

JavaScript (possibly): Optional enhancements (like form validation or dynamic display updates).

🔸 Backend:
Python with Flask: Based on the URL http://127.0.0.1:5000/spell.

Flask handles both form submissions and file uploads.

Likely structured to accept POST requests with either:

Form text (request.form)

Uploaded file (request.files)

🧠 Spell & Grammar Correction Engine:
Possible libraries used:

TextBlob or GingerIt – For basic grammar/spelling fixes.

LanguageTool (via language_tool_python) – For detailed grammar checks (like typographical errors).

Custom model/NLP logic – If you’re parsing errors like (['typographical'], 1).
