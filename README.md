# **Deepgram Transcription App**

This is a React-based web application that allows users to record audio, transcribe it using the Deepgram API, and view past transcriptions. The app is responsive and styled using Tailwind CSs

## **Features**

- 🎙️ **Audio Recording:** Start and stop audio recording using the microphone.  
- 📝 **Audio Transcription:** Transcribe recorded audio in real-time using the Deepgram API.  
- 💾 **Save Transcriptions:** Save and display past transcriptions for reference.  
- 📱 **Responsive Design:** Works seamlessly on mobile, tablet, and desktop.  
- 🎨 **Styling:** Clean and modern design implemented with Tailwind CSS.  

---

## **Technologies Used**

- **Frontend Framework:** React.js  
- **Styling:** Tailwind CSS  
- **Audio Recording:** MediaRecorder API  
- **Transcription Service:** Deepgram API  
- **State Management:** React Hooks  

---

## **Setup Instructions**

Follow the steps below to run the application locally:

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/deepgram-transcription-app.git
cd deepgram-transcription-app
```

### **2. Install Dependencies**
```bash
npm install
```

### **3. Set Up Tailwind CSS**
Tailwind CSS is already configured. You can find the configuration file in `tailwind.config.js`. Ensure the directives in `src/index.css` are:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### **4. Add Deepgram API Key**
- Sign up for a free account on [Deepgram](https://www.deepgram.com).
- Get your API key.
- Replace `YOUR_DEEPGRAM_API_KEY` in the file `src/components/Transcription.js` with your API key.

```javascript
Authorization: `Token YOUR_DEEPGRAM_API_KEY`,
```

### **5. Start the Development Server**
Run the following command to start the app:
```bash
npm start
```
The app will be available at `http://localhost:3000`.

---

## **Usage**

1. Click **"Start Recording"** to record audio.  
2. Click **"Stop Recording"** when done.  
3. Click **"Transcribe Audio"** to transcribe the audio.  
4. View the transcription in the **"Transcribed Text"** section.  
5. All transcriptions are saved under **"Past Transcriptions"**.

---

## **File Structure**

```
deepgram-transcription-app/
├── src/
│   ├── components/
│   │   ├── Microphone.js   # Handles audio recording
│   │   ├── Transcription.js # Handles transcription and past transcription display
│   ├── index.css          # Tailwind CSS styles
│   ├── App.js             # Main application logic
│   ├── index.js           # React entry point
├── tailwind.config.js      # Tailwind configuration
├── package.json            # Project dependencies and scripts
└── README.md               # Project documentation
```

---

## **Screenshots**

### **1. Audio Recording**
| ![Recording Screenshot](https://via.placeholder.com/400x200) |
|:----------------------------------------------------------:|
| Recording in progress |

### **2. Transcription**
| ![Transcription Screenshot](https://via.placeholder.com/400x200) |
|:----------------------------------------------------------------:|
| Transcribed text displayed |

---

## **Future Improvements**

- 🌟 Real-time transcription display during recording.  
- 🌟 Support for multiple languages.  
- 🌟 Export transcriptions as text files or PDFs.  

---

