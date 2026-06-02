# 📱 **Playcatch - Musik-Empfehlungssystem mit KI**

## **Beschreibung**
Playcatch ist eine Anwendung zur Musikempfehlung basierend auf Sentimentanalyse. Das System analysiert die Emotionen des Benutzers durch Text und schlägt Musik vor, die zu seiner aktuellen Stimmung passt.

## **Funktionen**
- ✨ **Sentimentanalyse**: Verwendet mehrsprachiges BERT-Modell zur Emotionserkennung
- 🎵 **Intelligente Empfehlung**: Schlägt Musik basierend auf dem emotionalen Zustand des Benutzers vor
- 💬 **Konversationsschnittstelle**: Interaktiver Chatbot in der Befehlszeile
- 🌍 **Mehrsprachig**: Unterstützt Sentimentanalyse in mehreren Sprachen

## **So funktioniert es**
1. Der Benutzer beschreibt, wie er sich fühlt
2. Das System analysiert die Stimmung der Nachricht (traurig, neutral oder glücklich)
3. Die Anwendung gibt das am besten geeignete Lied für diese Stimmung zurück

## **Verwendete Technologien**
- **PyTorch**: Machine-Learning-Framework
- **Transformers**: Vortrainierte KI-Modelle (BERT)
- **Gradio**: Benutzeroberfläche (optional)
- **Hugging Face**: Modelle und Datensätze

## **Anforderungen**
```
torch
transformers
gradio
datasets
huggingface_hub
```

## **Installation**
```bash
pip install -r requirements.txt
```

## **Anleitung zum Verwenden**
```bash
python playcatch.py
```
Geben Sie Ihre Emotionen ein und erhalten Sie Musikempfehlungen. Geben Sie "exit" ein, um zu beenden.

## **Musikkatalog**
- Ivete Sangalo
- Adele
- Linkin Park
- Pharrell Williams

## **Autor**
Ruana Ramos

## **Lizenz**
MIT
