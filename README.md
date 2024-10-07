# 💳 Payment Icons Selector

## 🌟 Overview
Payment Icons Selector is a simple web tool that allows users to dynamically select payment icons from a list, and generate HTML code for the selected icons. It helps developers easily integrate payment icons into their websites by selecting only the icons they need.

This project is built using **HTML**, **Tailwind CSS**, and **JavaScript** and fetches icon data from a `JSON` file to dynamically generate icon buttons. Each selected icon is displayed with a ✅, and you can easily clear the selection and start again.

## ✨ Features
- 🖼 **Dynamic Icon Loading**: Icons are loaded dynamically from a JSON file.
- ✅ **Select Payment Icons**: Users can toggle the selection of various payment icons.
- 📝 **Generate HTML Code**: Upon selecting the desired icons, the HTML code is generated and displayed in a textarea.
- 🔄 **Clear Selection**: A "Clear" button allows users to deselect all icons and reset the code.
- 🎨 **User-Friendly UI**: The application uses Tailwind CSS for a clean and responsive UI.

## 🏦 Icons Included
Currently, the following icons are included in the project:
- 💳 Visa
- 💳 Mastercard
- 💳 AMEX
- 💳 OMNet
- 💳 Meza
- 💳 Mada
- 💳 Valu
- 💳 Sympl
- 💳 Tabby
- 💳 PostPay
- 💳 Tamara

You are welcome to contribute by adding more icons to the project! 🙌 See below for details.

## 🛠️ How It Works
1. The application loads a list of payment icons from the `icons.json` file.
2. Users can toggle the selection of icons. A checkmark (✅) appears on selected icons.
3. The generated HTML code for the selected icons is displayed in a textarea, which can be copied and used in your project.
4. Users can also clear all selections and reset the generated code.

## ➕ Adding More Icons
To add more icons:
1. Edit the `icons.json` file in the root directory.
2. Add a new icon object with the following structure:
   ```json
   {
      "name": "NewIconName",
      "src": "https://link-to-icon.com/icon.svg"
   }```
3. Ensure the icon link points to a valid image, preferably an SVG format.

## 🚀 Setup and Usage
1. Clone the repository:
```git clone https://github.com/yourusername/payment-icons-selector.git```
2. Navigate to the project folder:
```cd payment-icons-selector```
3. Open the index.html file in a browser to use the tool.

## 🤝 Contribution
Contributions are welcome! Feel free to add new payment icons or improve the UI/UX. You can open an issue or submit a pull request with your improvements. Let’s make this project even better together! 💡

# To Contribute:
1. Fork the repository.
2. Create a new branch:
``` git checkout -b feature-new-icon ```
3. Commit your changes and push the branch:
```git push origin feature-new-icon```
4. Open a pull request.

### 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

### Key Features of the README:
- **Emojis**: Added to make the text more fun and engaging.
- **Markdown Formatting**: Clear headings and sections for easy navigation.
- **Contribution Instructions**: Detailed steps on how to contribute to the project.

This format is designed to be user-friendly and visually appealing, making it