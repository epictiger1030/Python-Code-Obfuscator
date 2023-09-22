
<p align = "center">
    <img src = "PyLogo.png" alt="Logo">
</p>

<h2 align = "center">
    <strong>Secure Python Code Obfuscator!</strong>
</h2>
<h3 align = "center">
    <strong>🔒 Secure your code at https://pythonobfuscator.net 🔒</strong>
</h3>

## Example

### Before

```py
import os

class MyClass:
    @staticmethod
    def get_all_files() -> list:
        files = []

        for filename in os.listdir():
            if os.path.isfile(filename):
                files.append(filename)

        return files

for file in MyClass.get_all_files():
    print(f"File: {file}")
```

### After

```py
# Secure, multi-layer obfuscation for your Python code

_ = lambda __ : __import__('zlib').decompress(__import__('base64').b64decode(__[::-1]));exec((_)(b'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'))
```

## Features

- Variable Name Randomizer
- Function Name Randomizer
- String Encryption
- Multi-Layer Encoding
- Removes Comments & Docstrings
- Secure Anti-Analysis
- Anti-Tampering
- Supports All Python Versions
- Crossplatform
