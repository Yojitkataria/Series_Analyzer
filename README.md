---
title: Naruto TVanalyser
emoji: 🍥
colorFrom: orange
colorTo: red
sdk: gradio
sdk_version: 4.0.0
app_file: app.py
pinned: false
---

# TVanalyser - Naruto Character Analysis & Chatbot Platform

A comprehensive AI-powered platform for analyzing Naruto anime content, featuring theme classification, character network analysis, jutsu classification, and interactive character chatbots.

<img width="1918" height="927" alt="Screenshot 2025-09-02 102344" src="https://github.com/user-attachments/assets/af489f4f-e16d-45a7-bab7-0dcff15060a9" />

## 🎯 Project Overview

TVanalyser is a multi-phase machine learning project that leverages various NLP techniques to analyze and interact with Naruto anime content. The platform combines theme classification, character relationship mapping, jutsu categorization, and conversational AI to create an immersive fan experience.

## 🛠️ Tech Stack & Architecture

### Core Technologies
- **Python 3.12+**
- **Gradio** - Interactive UI framework
- **Hugging Face Transformers** - Pre-trained models and fine-tuning
- **spaCy** - Advanced NLP processing
- **NetworkX** - Graph analysis and visualization
- **PyVis** - Interactive network visualization

### Data Processing
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **nltk** - Natural language processing
- **pathlib** - File system operations

## 📊 Project Phases

### Phase 1 – Theme Classifier
**Objective**: Classify themes and their importance across 300+ Naruto episodes

**Technologies**:
- `transformers` - Hugging Face model integration
- `nltk` - Text preprocessing and analysis
- `pandas` - Data handling
- `numpy` - Numerical operations
- `pathlib` - File management

**Model**: `facebook/bart-large-mnli`
- Zero-shot classification for theme detection
- Importance scoring for narrative elements
- Episode-level theme analysis

<img width="1919" height="537" alt="Screenshot 2025-09-02 102415" src="https://github.com/user-attachments/assets/1f336963-7489-48fd-be10-ac45dccff751" />
  
### Phase 2 – Character Neural Network
**Objective**: Build an interactive web of character connections and relationships

**Technologies**:
- `nltk` - Text processing
- `pandas` - Data manipulation
- `networkx` - Graph theory and network analysis
- `pyvis` - Interactive network visualization
- `pathlib` - File operations

**Model**: `spacy en_core_web_trf`
- Named Entity Recognition (NER) for character identification
- Relationship extraction from dialogue and narrative
- Dynamic network visualization with character interactions

<img width="1864" height="828" alt="Screenshot 2025-09-02 102505" src="https://github.com/user-attachments/assets/8877ce96-88b6-425b-8e64-1407f254e9c5" />

### Phase 3 – Text Classification (Jutsu Classification)
**Objective**: Classify queries into ninja techniques (Ninjutsu, Genjutsu, Taijutsu)

**Technologies**:
- `numpy` - Numerical computing
- `pandas` - Data analysis
- `evaluate` - Model evaluation metrics
- `huggingface_hub` - Model management
- `sklearn` - Machine learning utilities
- `datasets` - Data handling

**Model**: Fine-tuned `distilbert/distilbert-base-uncased`
- Custom training on Naruto-specific terminology
- Multi-class classification for jutsu types
- High accuracy classification system

🔗 **Hugging Face Model**: https://lnkd.in/gCN-atFY

<img width="1798" height="607" alt="Screenshot 2025-09-02 103109" src="https://github.com/user-attachments/assets/f7d70269-3874-4f1e-8668-a62aec44f89d" />

### Phase 4 – Character Chatbot
**Objective**: Enable conversations with favorite characters (Naruto, Sasuke, Sakura)

**Evolution & Learning**:
- **Initial Approach**: `meta-llama/Meta-Llama-3-8B`
  - Experienced challenges with Colab Pro GPU requirements
  - Gained hands-on experience with model deployment trade-offs
  - Learned about scaling challenges and inference pipeline optimization
  - **Experiment Link**: https://lnkd.in/gpBD445n

- **Current Solution**: Gemini API with fine-tuning
  - Focused on conversation design and retrieval augmentation
  - Implemented multi-agent conversation flows
  - Optimized for resource efficiency and deployment scalability

<img width="1839" height="670" alt="Screenshot 2025-09-02 105824" src="https://github.com/user-attachments/assets/e25c7f27-1dee-4e59-8c3c-d68566f3f4d2" />

## 🎨 User Interface

**Gradio Integration**
- Seamless integration with Hugging Face ecosystem
- Interactive and responsive web interface
- Real-time model inference and visualization
- User-friendly design for complex AI operations

## 📁 Project Structure

```
TVanalyser/
├── character_chatbot/          # Phase 4 - Character chatbot implementation
├── character_network/          # Phase 2 - Character relationship analysis
├── components/                 # UI components and assets
├── crawler/                   # Data collection utilities
├── data/                      # Datasets and processed data
├── text_classification/       # Phase 3 - Jutsu classification
├── theme_classifier/          # Phase 1 - Theme analysis
├── utils/                     # Shared utilities and data loaders
├── vaishnaviiii34/           # Model checkpoints and training artifacts
└── gradio_app.py             # Main application entry point
```

## 🚀 Getting Started

### Prerequisites
- Python 3.12+
- Virtual environment (recommended)

### Installation
1. Clone the repository
2. Create and activate virtual environment
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
```bash
python gradio_app.py
```

## 📈 Key Features

- **Multi-Modal Analysis**: Combines text classification, NER, and conversational AI
- **Interactive Visualizations**: Dynamic character networks and theme analysis
- **Scalable Architecture**: Modular design supporting multiple ML models
- **Real-time Inference**: Fast model predictions through optimized pipelines
- **User-Friendly Interface**: Intuitive Gradio-based web application

## 🎓 Learning Outcomes

This project demonstrates expertise in:
- **Model Fine-tuning**: Custom training on domain-specific data
- **Deployment Trade-offs**: Understanding resource constraints vs. model performance
- **Multi-Agent Systems**: Complex conversation flows and retrieval augmentation
- **End-to-End ML Pipelines**: From data collection to user interface
- **Production Considerations**: Scaling, optimization, and maintenance

## 📊 Data Sources

- **300+ Naruto Episodes**: Comprehensive anime content analysis
- **Subtitles**: Multi-language subtitle processing
- **Character Data**: Extensive character relationship mapping
- **Jutsu Database**: Curated ninja technique classifications

## 🤝 Contributing

This project showcases advanced NLP techniques and ML deployment strategies. Feel free to explore the codebase and adapt the methodologies for your own projects.

## 📄 License

This project is for educational and demonstration purposes.
---
🔗 **LinkedIn Post**: https://www.linkedin.com/posts/vaishnavi-mishra-b17ba6256_adding-another-skill-that-nowadays-is-a-must-activity-7368537981785153538-WKyB?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD8uPMMBqRpwGF1E1y23LaGw3BRKzCllt0Q 
---

*Built with ❤️ using Python, Hugging Face, and Gradio*


' Form1.vb
Imports System.Drawing
Imports System.Windows.Forms

Public Class Form1
    Inherits Form

    Public Sub New()
        Me.Text = "Series_Analyzer - Architecture Diagram"
        Me.ClientSize = New Size(1000, 700)
        Me.DoubleBuffered = True
        Me.BackColor = Color.White
    End Sub

    Protected Overrides Sub OnPaint(e As PaintEventArgs)
        MyBase.OnPaint(e)
        Dim g As Graphics = e.Graphics
        g.SmoothingMode = Drawing2D.SmoothingMode.AntiAlias

        Dim titleFont As New Font("Segoe UI", 14, FontStyle.Bold)
        Dim boxFont As New Font("Segoe UI", 9)
        Dim smallFont As New Font("Segoe UI", 8)
        Dim boldFont As New Font("Segoe UI", 9, FontStyle.Bold)

        ' Helper to draw a rounded rectangle-ish box with text
        Dim drawBox = Sub(x As Integer, y As Integer, w As Integer, h As Integer, header As String, lines As String())
                          Dim rect As New Rectangle(x, y, w, h)
                          Using brush = New SolidBrush(Color.FromArgb(230, 245, 255))
                              g.FillRectangle(brush, rect)
                          End Using
                          g.DrawRectangle(Pens.Black, rect)
                          g.DrawString(header, boldFont, Brushes.Black, New PointF(x + 8, y + 6))
                          Dim ty As Integer = y + 28
                          For Each ln In lines
                              g.DrawString(ln, boxFont, Brushes.Black, New PointF(x + 8, ty))
                              ty += 16
                          Next
                      End Sub

        ' Draw title
        g.DrawString("Series_Analyzer — High level architecture", titleFont, Brushes.Black, New PointF(12, 8))

        ' Positions for boxes
        Dim leftX As Integer = 30
        Dim midX As Integer = 370
        Dim rightX As Integer = 690
        Dim topY As Integer = 70
        Dim rowGap As Integer = 140

        ' Crawler box
        drawBox(leftX, topY, 260, 80, "Crawler", New String() {"Scrape transcripts", "Extract raw text"})

        ' Data / Preprocessing box
        drawBox(leftX, topY + rowGap, 260, 100, "Data / Preprocessing", New String() {"Cleaning, tokenization", "Save CSV/JSON for models"})

        ' Theme classifier
        drawBox(midX, topY, 260, 100, "Theme Classifier", New String() {"Transformers (zero-shot)", "Episode-theme scores"})

        ' Character Network
        drawBox(midX, topY + rowGap, 260, 100, "Character Network", New String() {"spaCy NER", "NetworkX / PyVis", "Graph visualizations"})

        ' Jutsu classifier
        drawBox(rightX, topY, 260, 80, "Jutsu Classifier", New String() {"DistilBERT fine-tuned", "Ninja-technique labels"})

        ' Chatbot
        drawBox(rightX, topY + rowGap, 260, 100, "Character Chatbot", New String() {"LLM (Gemini/Llama)", "Retrieval-augmented dialog"})

        ' Gradio / UI at bottom center
        Dim uiX As Integer = 240
        Dim uiY As Integer = topY + rowGap * 2 + 20
        drawBox(uiX, uiY, 520, 110, "Gradio UI / Serving (app.py, gradio_app.py)", New String() {"Interactive UI", "Trigger model endpoints", "Visualize networks & chat"})

        ' Draw arrows / flows (simple lines + arrows)
        Dim drawArrow = Sub(x1 As Integer, y1 As Integer, x2 As Integer, y2 As Integer)
                            g.DrawLine(New Pen(Color.Black, 2), x1, y1, x2, y2)
                            ' draw simple arrow head
                            Dim ang As Double = Math.Atan2(y2 - y1, x2 - x1)
                            Dim len As Integer = 12
                            Dim arrow1X As Integer = x2 - CInt(len * Math.Cos(ang - Math.PI / 6))
                            Dim arrow1Y As Integer = y2 - CInt(len * Math.Sin(ang - Math.PI / 6))
                            Dim arrow2X As Integer = x2 - CInt(len * Math.Cos(ang + Math.PI / 6))
                            Dim arrow2Y As Integer = y2 - CInt(len * Math.Sin(ang + Math.PI / 6))
                            g.DrawLine(Pens.Black, x2, y2, arrow1X, arrow1Y)
                            g.DrawLine(Pens.Black, x2, y2, arrow2X, arrow2Y)
                        End Sub

        ' arrows from crawler -> data
        drawArrow(leftX + 200, topY + 40, leftX + 50, topY + rowGap + 10)

        ' arrows from data -> Theme classifier & Character network & Jutsu classifier
        drawArrow(leftX + 200, topY + rowGap + 50, midX + 30, topY + 30) ' to Theme
        drawArrow(leftX + 200, topY + rowGap + 50, midX + 30, topY + rowGap + 50) ' to Character network
        drawArrow(leftX + 200, topY + rowGap + 50, rightX + 30, topY + 30) ' to jutsu

        ' arrows from Theme, Network, Jutsu -> UI
        drawArrow(midX + 260, topY + 40, uiX + 30, uiY + 15)
        drawArrow(midX + 260, topY + rowGap + 40, uiX + 160, uiY + 15)
        drawArrow(rightX + 260, topY + 40, uiX + 450, uiY + 15)

        ' arrow from UI -> Chatbot and Chatbot outputs to UI
        drawArrow(uiX + 480, uiY + 50, rightX + 100, topY + rowGap + 40)
        drawArrow(rightX + 80, topY + rowGap + 70, uiX + 480, uiY + 80)

        ' Small labels for flows
        g.DrawString("raw transcripts", smallFont, Brushes.DarkBlue, New PointF(leftX + 120, topY + 32))
        g.DrawString("cleaned data", smallFont, Brushes.DarkBlue, New PointF(leftX + 140, topY + rowGap + 60))
        g.DrawString("themes", smallFont, Brushes.DarkGreen, New PointF(midX + 60, topY + 10))
        g.DrawString("NER -> Graph", smallFont, Brushes.DarkGreen, New PointF(midX + 60, topY + rowGap + 10))
        g.DrawString("jutsu labels", smallFont, Brushes.DarkGreen, New PointF(rightX + 60, topY + 10))
        g.DrawString("user interactions (classify / view / chat)", smallFont, Brushes.Black, New PointF(uiX + 10, uiY + 95))

        ' Legend box
        Dim legendX As Integer = 760
        Dim legendY As Integer = 20
        g.DrawRectangle(Pens.Black, legendX, legendY, 210, 90)
        g.DrawString("Legend", boldFont, Brushes.Black, New PointF(legendX + 8, legendY + 6))
        g.DrawString("- Crawler -> Data -> Models -> UI", smallFont, Brushes.Black, New PointF(legendX + 8, legendY + 34))
        g.DrawString("- Models: Theme / Network / Jutsu", smallFont, Brushes.Black, New PointF(legendX + 8, legendY + 52))
        g.DrawString("- Chatbot uses retrieval + LLM", smallFont, Brushes.Black, New PointF(legendX + 8, legendY + 70))

    End Sub

    <STAThread()>
    Public Shared Sub Main()
        Application.EnableVisualStyles()
        Application.SetCompatibleTextRenderingDefault(False)
        Application.Run(New Form1())
    End Sub

End Class
