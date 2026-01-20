# RTTC - Real-Time Translation & Chat

**RTTC** is a mobile application developed with React Native (Expo) designed to bridge communication gaps between different languages. Featuring advanced voice, text, and image (OCR) translation capabilities, the app provides a seamless tool for overcoming language barriers.

## 🚀 Features

The application is organized into key modules:

* **🗣️ Voice & Text Translation:** Instant translation with speech recognition support (`expo-speech-recognition`) and text-to-speech synthesis (`expo-speech`).
* **👥 Bilingual Mode:** An optimized interface for face-to-face conversations between two people speaking different languages.
* **📷 OCR (Image Translation):** Use the camera to extract and translate text from images, documents, or signs.
* **💬 Quick Phrases:** Fast access to common phrases for travel or emergency situations.
* **📜 Smart History:** All translation and OCR history is saved locally or in the cloud (Supabase) for future reference.
* **👤 Account Management:** User authentication and profile management system.

## 🛠️ Tech Stack

* **Framework:** [React Native](https://reactnative.dev/) with [Expo](https://expo.dev/) (SDK 54)
* **Navigation:** Expo Router
* **Backend / Database:** [Supabase](https://supabase.com/)
* **Local Storage:** AsyncStorage
* **UI Components:** React Native Paper, React Native Vector Icons
* **Testing:** Jest & React Native Testing Library

## 📱 Installation & Setup

### Prerequisites
* Node.js installed.
* A physical device (Android/iOS) with the **Expo Go** app or a configured emulator.

### Steps

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/VascoMaoglo/rttc.git](https://github.com/your-username/rttc.git)
    cd rttc
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Configure Environment Variables**
    Create a `.env` file in the root directory with your Supabase keys (example):
    ```env
    EXPO_PUBLIC_SUPABASE_URL=your_supabase_url
    EXPO_PUBLIC_SUPABASE_ANON_KEY=your_anon_key
    EXPO_PUBLIC_RAPIDAPI_KEY
    ```

4.  **Run the application**
    ```bash
    npm start
    ```
    * Press `a` to open on Android.
    * Press `i` to open on iOS.
    * Press `w` to open on Web.

## 🧪 Testing

The project uses **Jest** for unit and integration testing.

```bash
# Run all tests
npm test

# Run tests with coverage report
npm test -- --coverage
