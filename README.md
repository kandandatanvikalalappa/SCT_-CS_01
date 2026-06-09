# Caesar Cipher Tool (Task 01)

An enterprise-grade Python command-line utility implementing the classic Caesar Cipher algorithm. This tool supports both encryption and decryption operations with dynamic shifting while preserving character casing and special formatting.

-> Features
- **Bi-directional Processing**: Switch between encryption and decryption modes seamlessly.
- **Case Preservation**: Uppercase and lowercase boundaries are strictly respected.
- **Symbol Protection**: Punctuation, spaces, and numeric values remain completely unaltered.
- **Mathematical Safety**: Built-in modulo wrapping handling prevents index boundary overflow errors.

-> How to Run
Ensure you have Python 3 installed. Execute the script from your terminal:
```bash
python Task01
```

->  Parameters
- **Operation Mode**: Select either `encrypt` or `decrypt`.
- **Message**: The string text input you wish to convert.
- **Shift Key**: An integer value indicating the substitution offset character distance.
