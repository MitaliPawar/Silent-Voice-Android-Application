# Silent-Voice-Android-Application
Silent Voice is an Android application that converts hand gestures into text and voice using a TensorFlow Lite model. The app is designed to support communication for individuals with speech or hearing impairments by recognizing real-time gestures through the mobile camera and converting them into meaningful output.
## 🎯 How It Works

### **1️⃣ Capture Input**
The camera captures a live frame of your hand gesture.

### **2️⃣ Preprocessing**
The image is resized & normalized before being passed to the TFLite model.

### **3️⃣ Prediction**
The TensorFlow Lite interpreter outputs the predicted label from `labels.txt`.

### **4️⃣ Text Display**
The predicted letter/word appears on the screen.

### **5️⃣ Voice Output**
Android Text-to-Speech converts text into speech.
