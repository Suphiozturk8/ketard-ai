# Ketard-AI

## Installation

### Requirements
* Python3
* GNU+Linux
* [Ollama](https://ollama.com/download/linux)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ket0x4/ketard-ai.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd ketard-ai
   ```
3. **Create a virtual environment:**
   ```bash
   python3 -m venv .venv
   ```
4. **Activate the virtual environment:**
     ```bash
     source .venv/bin/activate
     ```
5. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```
6. **Configure the settings:**
   - Rename `settings.json.example` to `settings.json`:
     ```bash
     mv settings.json.example settings.json
     ```
   - Edit `settings.json` with your preferred settings.

7. **Run the bot:**
   ```bash
   python3 ketard.py
   ```

## License

This project is licensed under the MIT License.
