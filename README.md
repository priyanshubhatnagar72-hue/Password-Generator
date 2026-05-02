# Define the content for the README.md file
readme_content = """# 🔐 Password Generator

A simple and effective Python-based tool to generate secure, randomized passwords based on user-defined criteria.

## 🚀 Features
- **Customizable Length:** Choose exactly how many letters, numbers, and symbols you want.
- **Randomized Security:** Utilizes Python's `random` module to ensure characters are picked and shuffled unpredictably.
- **Easy to Use:** Interactive command-line interface.

## 🛠️ How It Works
1. **Input:** The user specifies the quantity of letters, numbers, and symbols.
2. **Collection:** The script selects random characters from pre-defined lists.
3. **Shuffling:** The script uses `random.shuffle()` to ensure the password doesn't follow a predictable pattern (e.g., all letters first, then numbers).
4. **Output:** A secure string is printed to the console.
