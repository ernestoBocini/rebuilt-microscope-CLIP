# 🔬 CLIP Microscope

An interactive web application for exploring what individual neurons in OpenAI's CLIP model learn from ImageNet. This tool provides deep insights into neural network interpretability through beautiful visualizations and comprehensive analysis.

## 🚀 Live Demo

**[🔗 Try it live on Streamlit Cloud](https://your-app-url-here.streamlit.app)**

## ✨ Features

- 🎨 **Feature Visualizations**: Lucid-generated images showing what each neuron detects
- 🖼️ **Top Activating Images**: View the ImageNet images that most strongly activate each neuron
- 📊 **Analysis Dashboard**: Statistical analysis including activation distributions and concept discovery
- 🕸️ **Neuron Networks**: Explore relationships between similar neurons
- 📈 **Global Statistics**: Dataset-wide insights and neuron comparison tools
- 🎯 **Smart Navigation**: Categorized neuron suggestions and random exploration
- 📱 **Responsive Design**: Works beautifully on desktop and mobile

## 🧠 What You Can Discover

Explore fascinating insights like:
- **Neuron 89**: Responds strongly to Donald Trump images
- **Neuron 244**: Detects Spider-Man and superhero imagery  
- **Neuron 355**: Activates on puppies and cute animals
- **Neuron 432**: Recognizes smiles and happy expressions
- **Neuron 1095**: Specializes in sunglasses detection
- And 2,555+ more neurons with unique specializations!

## 🔬 Technical Details

- **Model**: OpenAI CLIP RN50x4
- **Layer**: Image Encoder Blocks
- **Dataset**: ImageNet (training split)
- **Neurons Analyzed**: 2,560 total
- **Images per Neuron**: Top 100 activating examples
- **Data Hosting**: Hugging Face Datasets (free & fast)

## 📊 Dataset

The underlying data is hosted on Hugging Face:
**[📁 ernestoBocini/clip-microscope-imagenet](https://huggingface.co/datasets/ernestoBocini/clip-microscope-imagenet)**

Contains:
- 256,000+ top activating ImageNet images
- 2,560 Lucid-generated feature visualizations
- Comprehensive metadata with activation statistics
- All data organized for fast web access

## 🛠️ Local Development

### Prerequisites
- Python 3.8+
- pip

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/clip-microscope.git
   cd clip-microscope
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run app.py
   ```

4. **Open your browser**
   Navigate to `http://localhost:8501`

## 🚀 Deployment

This app is designed to deploy seamlessly on Streamlit Cloud:

1. Fork this repository
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub account
4. Select this repository
5. Set main file: `app.py`
6. Deploy!

## 📈 Performance

- **Fast Loading**: Metadata cached for 1 hour
- **Efficient Images**: Direct loading from Hugging Face CDN
- **Responsive UI**: Optimized for both desktop and mobile
- **Global Access**: No geographic restrictions

## 🎯 Use Cases

Perfect for:
- **AI Researchers**: Understanding what vision models learn
- **Students**: Learning about neural network interpretability
- **Educators**: Teaching computer vision concepts
- **Curious Minds**: Exploring the inner workings of AI

## 🏗️ Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  Streamlit App  │───▶│ Hugging Face    │───▶│    ImageNet     │
│   (Frontend)    │    │   (Metadata)    │    │    (Images)     │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

- **Streamlit**: Interactive web interface
- **Hugging Face**: Hosts all data (free tier)
- **ImageNet**: Source of training images

## 🤝 Contributing

Contributions welcome! Areas for improvement:
- Additional analysis visualizations
- More neuron similarity metrics
- Enhanced UI/UX features
- Performance optimizations

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- **OpenAI**: For the original [Microscope](https://microscope.openai.com) tool and CLIP model
- **ImageNet**: For the dataset used in training
- **Hugging Face**: For free dataset hosting
- **Streamlit**: For the amazing web app framework

## 📞 Contact

- **GitHub**: [@your-username](https://github.com/your-username)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/ernestoBocini/clip-microscope-imagenet)

---

*Explore the hidden patterns in AI vision models! 🔍*