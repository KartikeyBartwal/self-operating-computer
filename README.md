# Iron Sensei AI Framework

<h1 align="center">Iron Sensei AI Framework</h1>

<p align="center">
  <strong>An advanced AI-driven framework for autonomous computer operation.</strong>
</p>
<p align="center">
  Utilizing cutting-edge multimodal AI, Iron Sensei AI views the screen and executes a series of mouse and keyboard actions to accomplish complex objectives.
</p>

<div align="center">
  <img src="readme/iron-sensei-ai.png" width="750" style="margin: 10px;"/>
</div>

## Key Features
- **Multimodal AI Compatibility**: Seamlessly integrates with advanced AI models.
- **Autonomous Decision-Making**: AI determines optimal mouse and keyboard actions.
- **Flexible & Scalable**: Can be extended to support additional AI models and use cases.

## Installation

1. **Install Iron Sensei AI**
```bash
pip install iron-sensei-ai
```

2. **Run Iron Sensei AI**
```bash
operate
```

3. **Enter API Key**
   - Obtain an API key from your preferred AI provider.
   - To update the key later, modify the `.env` file.

4. **Grant System Permissions** (Mac users)
   - Allow "Screen Recording" and "Accessibility" in "System Preferences".

## Supported AI Models

Iron Sensei AI integrates with multiple advanced AI models, enabling seamless operation:

- **GPT-based AI Models**: High-accuracy screen analysis and control.
- **Vision-based AI Models**: Enhanced recognition for visual tasks.
- **Custom Models**: Easily integrate your own AI models.

## Usage & Commands

To run Iron Sensei AI with different AI models, use the following commands:

### Default Mode
```bash
operate
```

### Running with Specific AI Models
```bash
operate -m model_name
```
Replace `model_name` with one of the supported AI models.

### Enabling Voice Mode
```bash
operate --voice
```
Allows voice input for controlling operations.

### Enabling OCR Mode
```bash
operate -m model_with_ocr
```
Utilizes Optical Character Recognition for enhanced text-based interactions.

## Local Deployment

To run Iron Sensei AI on your local machine:

1. Clone the repository:
```bash
git clone https://github.com/your-repo/iron-sensei-ai.git
```
2. Navigate to the project directory:
```bash
cd iron-sensei-ai
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Run the framework:
```bash
operate
```

## Contributing

We welcome contributions! Please check the `CONTRIBUTING.md` file for guidelines.

## Feedback & Support

For any feedback or support, feel free to reach out through our official communication channels.

## Compatibility
- **Operating Systems**: Windows, Mac OS, Linux
- **Dependencies**: Python 3.8+

## Stay Updated
Follow our latest updates and improvements by staying connected with our official channels.

---
Iron Sensei AI is designed for efficiency, precision, and seamless AI-powered automation. 🚀
