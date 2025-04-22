# **AI Bug Fixer - VS Code Extension**

## **📌 Overview**
**AI Bug Fixer** is a powerful **VS Code extension** that helps developers analyze and fix error messages using **OpenAI's API** and **Stack Overflow data**. It can process **syntax errors from the editor** and **runtime errors from the terminal**, offering **real-time debugging assistance** and an **interactive AI chat window**.

## **🚀 Features**
✅ **AI-Powered Error Analysis** - Detects and explains errors in code.
✅ **Works for Syntax & Runtime Errors** - Supports both editor errors and terminal logs.
✅ **Stack Overflow Integration** - Fetches relevant solutions from Stack Overflow.
✅ **Interactive AI Chat** - Users can ask follow-up debugging questions.
✅ **Clipboard Support** - Copies terminal errors for analysis.
✅ **VS Code Integration** - Works seamlessly within VS Code’s Command Palette.

---

## **🛠 Installation**
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/ai-bug-fixer-vscode.git
   cd ai-bug-fixer-vscode
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Open the project in VS Code:**
   ```sh
   code .
   ```
4. **Run the extension in Debug Mode:**
   - Press `F5` to launch the Extension Development Host.
   - Open a file with errors and highlight an error message.
   - Open the Command Palette (`Cmd + Shift + P` or `Ctrl + Shift + P`).
   - Select **"Analyze Error with AI"**.

---

## **⚙️ Usage**
### **🔍 Analyzing Errors from the Editor**
1. Open a file with an error (e.g., `test.js`).
2. Highlight the error message.
3. Press `Cmd + Shift + P` (Mac) or `Ctrl + Shift + P` (Windows/Linux).
4. Select **"Analyze Error with AI"**.
5. AI will suggest fixes and explanations.
6. An **interactive AI chat** window will open for further debugging.

### **📌 Analyzing Runtime Errors from the Terminal**
1. Run a command that produces an error in the terminal.
2. **Manually copy** the error log (`Cmd + C` or `Ctrl + C`).
3. Press `Cmd + Shift + P` (Mac) or `Ctrl + Shift + P` (Windows/Linux).
4. Select **"Analyze Error with AI"**.
5. The extension will analyze the **clipboard content**.
6. AI-generated solutions and Stack Overflow links will be displayed.

---

## **🔗 API Integration**
### **1️⃣ OpenAI API (ChatGPT)**
- Used for **analyzing errors** and **providing AI-driven solutions**.
- Requires an **OpenAI API key** (set in VS Code settings).

### **2️⃣ Stack Overflow API**
- Fetches **relevant questions & answers** related to the error.

---

## **⚠️ OpenAI API Setup**
### **🔑 Adding Your API Key**
1. **Get your API key** from [OpenAI API](https://platform.openai.com/account/api-keys).
2. Open **VS Code settings (JSON Mode)** (`Cmd + Shift + P` → "Preferences: Open Settings (JSON)").
3. Add this entry:
   ```json
   "aiBugFixer.openaiApiKey": "sk-YOUR-API-KEY"
   ```
4. **Restart VS Code**.

### **💰 Managing API Limits**
- If you receive a **429 Rate Limit error**, you may need to upgrade your OpenAI API plan.
- Purchase API credits from [OpenAI Billing](https://platform.openai.com/account/billing).

---

## **🔧 Troubleshooting**
| Issue | Solution |
|--------|----------|
| "Analyze Error with AI" not appearing | Restart VS Code & ensure the extension is activated. |
| "No error log selected" | Copy the error log manually before running the command. |
| OpenAI API error (429) | Check API limits and upgrade if necessary. |
| Extension not activating | Ensure you have **VS Code 1.97.0 or later**. |

---

## **📜 License**
This project is licensed under the **MIT License**.

---

## **📌 Future Improvements**
🚀 **Enhance AI chat capabilities** - Enable real-time conversations.
🚀 **Improve error detection** - Automatically differentiate syntax vs. runtime errors.
🚀 **One-click "Apply Fix"** - AI will modify the code inside VS Code.
🚀 **Better terminal integration** - Allow direct selection of terminal logs (if VS Code API supports it in the future).

---

## **👨‍💻 Contributing**
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

We welcome all contributions to improve **AI Bug Fixer**!

---

## **🤝 Acknowledgments**
Special thanks to:
- **OpenAI** for providing powerful AI models.
- **Stack Overflow** for its wealth of developer knowledge.
- **VS Code API** for making extensions seamless.

🚀 **Happy Coding!**

