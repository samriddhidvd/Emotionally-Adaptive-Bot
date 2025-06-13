# Emotionally Adaptive Bot 

A personalized AI chatbot that adapts its responses to your emotional state.  
Fine-tuned on real interview data across six universal emotions (Sadness, Happiness, Fear, Anger, Surprise, Disgust) using LoRA for efficient adaptation.  

**Key Features**  
- Emotion recognition and tone-matched responses  
- Lightweight 4-bit quantized LLaMA-3 8B model  
- Simple CLI/web interface (`app.py`)  

**Quick Start**  
```bash
git clone https://github.com/samriddhidvd/Emotionally-Adaptive-Bot.git
cd Emotionally-Adaptive-Bot
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
python app.py --model-path ./models/finetuned

