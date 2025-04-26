# 🎤 Voice and Text to QR Code Generator 📱

This web-based tool allows users to generate QR codes from either voice input 🎙️ or manual text entry ✍️. It provides an interactive and intuitive interface, allowing users to create QR codes in real-time with their voice or by typing in text. The generated QR codes can then be displayed on the page, and a history of generated QR codes is stored for easy access 🗂️.

## 🌟 Features:

1. **Voice Input 🗣️:**  
   Users can click the "Start Recording" button 🎤 to record their voice, and the tool will convert their spoken words into text. The spoken text is dynamically shown in the preview area, and a corresponding QR code is generated in real-time.

2. **Text Input 📜:**  
   Users can also manually type text into a provided input field 📝. Upon clicking the "Generate QR from Text" button, the tool generates a QR code based on the input text.

3. **QR Code Display 🏷️:**  
   The generated QR code is displayed below the text preview in a well-sized canvas element, which can be scanned using any QR code reader 📲.

4. **QR Code History 🕒:**  
   Every generated QR code is saved in the browser's local storage, allowing users to view a history of all previously created QR codes 🔄. This history is displayed in a scrollable list 📃, showing the text input used to generate each QR code.

5. **Error Handling ⚠️:**  
   If the user attempts to generate a QR code without entering any text (either via voice or manually), an error message 🚨 is shown, prompting them to enter some text.

## 🎨 UI Design:

- The UI has been designed to be minimalistic and user-friendly with a dark theme 🌑 to ensure good visibility in low-light environments 💡.
- The page layout is split into two main sections: one for displaying the main image (which is an illustrative background related to QR codes) 🖼️ and the other for the interactive controls 🎮.
- The buttons are styled to be easy to click ⬇️, and input fields are responsive and clear to use 💬.
- Mobile-friendly design ensures that the tool works well across devices 📱, including smartphones and tablets.

## 🛠️ Technologies Used:

- **HTML & CSS:** For structuring and styling the page 🌐.
- **JavaScript:** For handling user input, generating QR codes, and storing the history using the browser’s local storage 💾.
- **QRCode.js Library:** A popular JavaScript library 📚 for generating QR codes from text input.
