This project introduces an advanced framework for detecting **fine-grained emotions in literary texts using Natural Language Processing (NLP) and Deep Learning. Leveraging DistilBERT and a sliding window segmentation approach, the system captures dynamic emotional patterns across narrative passages—paving the way for intelligent and interpretable emotion analysis in literature.
Core Features
* ✅ Emotion classification using DistilBERT pre-trained on the GoEmotions dataset
* ✅ Sliding window technique to capture emotional transitions across overlapping text segments
* ✅ Multi-label classification for detecting co-occurring emotions (e.g., joy + fear)
* ✅ Interactive heatmaps and line graphs to visualize emotional flows
* ✅ Comparative benchmarking with lexicon-based methods
Methodology Summary
1. Data Preprocessing
   * Tokenization using DistilBERT tokenizer
   * Stopword removal (via NLTK)
   * 20-word sliding windows with 50% overlap for temporal tracking
2. Model Architecture
   * Transformer-based emotion classification using DistilBERT
   * Lexicon-based baseline using NRC Emotion Lexicon for comparison
3. Visualization
   * Emotion heatmaps highlight intensity zones
   * Line graphs illustrate sentiment trends over time
Results
* DistilBERT outperformed traditional models, especially for implicit/figurative emotions
* Achieved better accuracy for detecting nuanced and overlapping emotional states
* Visualization tools successfully revealed emotional arcs in narratives
 Future Work
* Fine-tuning DistilBERT on larger literary datasets
* Enhancing lexicons with domain-specific vocabulary
* Incorporating **multimodal data** (e.g., audiobooks) for richer emotion detection
* Developing dynamic and interactive emotion dashboards


