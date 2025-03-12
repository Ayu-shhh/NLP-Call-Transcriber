# NLP-Call-Transcriber
An automated Transcriber and translater for audio calls to CSV file for better analysis.
**Project: Automated Audio Transcription, Translation, and Role Identification System**

**Objective:**
Developed a Python-based pipeline to **transcribe, translate, and analyze** Spanish-language call recordings, converting them into structured conversations for further analysis.

---

### **Technologies Used:**
- **Python** (Data processing & automation)
- **OpenAI Whisper API** (Speech-to-text transcription)
- **OpenAI GPT-3.5 Turbo** (Text translation & NLP tasks)
- **Pandas** (Data structuring & CSV generation)
- **OS Module** (File handling & automation)

---

### **Project Overview:**
1. **Audio File Processing:**
   - Iterated through **MP3 call recordings** in a specified directory.
   - Used OpenAI **Whisper API** to generate **Spanish transcriptions**.

2. **Translation:**
   - Sent the transcribed text to **GPT-3.5 Turbo** for **English translation**.

3. **Role Identification:**
   - Identified speakers as **"Agent"** or **"Client"** based on text analysis.
   - Extracted **structured dialogues** from conversations.

4. **Data Structuring & Export:**
   - Stored **conversation details** (File Name, Speaker Role, Dialogue) in a Pandas **DataFrame**.
   - Exported the structured data to **CSV** for reporting & further analysis.

---

### **Key Contributions:**
✅ Built an **end-to-end automated pipeline** for processing call recordings.
✅ Integrated **AI-powered transcription & translation** to convert raw audio into **structured text**.
✅ Developed a **role identification mechanism** for speaker differentiation.
✅ Automated **data extraction & storage** into CSV format for business insights.
✅ Implemented **error handling & logging** to manage failures in API calls & file processing.

---

### **Impact:**
- Reduced **manual effort** in transcribing and analyzing customer-agent interactions.
- Enabled **quick insights** from call center conversations for **customer service optimization**.
- Scaled efficiently to process **large volumes** of audio data.

---

### **Future Enhancements:**
- Improve **role identification** using **NLP models** for sentiment & intent analysis.
- Implement **multi-threading** for faster processing of bulk audio files.
- Develop a **web interface** for non-technical users to upload and process recordings easily.

