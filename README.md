# Computational Linguistics Teaching Assistant 🎓

A chatbot that serves as a teaching assistant for Computational Linguistics, leveraging content from Stanford's CS224N course. The bot uses advanced NLP techniques to provide accurate, source-backed answers about word vectors, neural networks, and NLP concepts.

## Features ✨

- **Strict Knowledge Base**: Answers only from verified course materials
- **Source Attribution**: Cites specific lectures for each response
- **Key Concepts**: Highlights relevant technical concepts
- **User-Friendly Interface**: Clean, intuitive Gradio web interface
- **Smart Context**: Maintains conversation history for better responses

## Technology Stack 🛠️

- **Framework**: LangChain
- **Language Model**: OpenAI GPT-4
- **Vector Store**: Pinecone
- **Embeddings**: OpenAI Ada-002
- **Interface**: Gradio
- **Content Processing**: Whisper (for lecture transcription)

## Setup and Installation 🚀

1. Clone the repository
2. Install requirements:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
OPENAI_API_KEY=your_key_here
PINECONE_API_KEY=your_key_here
PINECONE_INDEX_NAME=your_index_name
```

4. Run the application:
```bash
python chatbot_interface.py
```

## Usage 💡

1. Launch the application
2. Type your question in the input box
3. Get responses with:
   - Direct answers from course content
   - Source lecture references
   - Related key concepts
   - Follow-up suggestions

## Project Structure 📁

```
.
├── chatbot_interface.py    # Main Gradio interface and chat logic
├── pinecone_utils.py       # Pinecone connection utilities
├── requirements.txt        # Project dependencies
└── README.md              # This file
```

## Example Questions 🤔

- "What are word vectors?"
- "How do neural networks work in NLP?"
- "What is GloVe and what problem does it solve?"

## Limitations ⚠️

- Only answers questions based on available course content
- Currently covers specific lectures from CS224N
- Requires API keys for OpenAI and Pinecone

## Future Improvements 🔮

- Add more course content
- Implement speech input/output
- Add interactive visualizations
- Expand to more NLP topics

## Credits 👏

- Based on Stanford's CS224N course materials
- Built with LangChain and Gradio frameworks
- Utilizing OpenAI's GPT-4 and Whisper models

## License 📝

[Your chosen license]
