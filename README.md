# Bold Words in Text Function

This Python function allows you to bold specific words or phrases in a `.docx` document. It is designed to work with the `python-docx` library and supports flexible, case-insensitive matching to bold target phrases while respecting word boundaries.

## Features
- **Case-insensitive matching**: The function matches words regardless of case.
- **Word boundaries**: Ensures only full words are matched, avoiding partial matches inside larger words.
- **Support for multiple phrases**: You can pass a list of phrases to be bolded in the document.
