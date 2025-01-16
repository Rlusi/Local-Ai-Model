# Local-AI-Model

A local AI model that runs on your GPU using Ollama's "Command-R" with a 128k context size.

---

## Requirements
A relatively powerful GPU is recommended, especially one with a lot of VRAM.  
- **VRAM Recommendations**:  
  - 12GB VRAM generally works but is not enough to utilize the model's full context size.  
  - More VRAM allows better performance and full context utilization.  

## Features
### Current Features
- **Command Interface**:  
  Use **F10** to open the help menu.  
- **Long-term Memory**:  
  Retains information from past conversations up to the context limit (varies with hardware).  
- **Basic Input-Output System**:  
  Handles basic tasks with a few extra functionalities.  

### Planned Features
1. **Desktop Integration**:  
   A text box directly on your desktop for ease of use.  
2. **Client-Server Usability**:  
   - Enables a less powerful device (e.g., laptop) to connect to a more powerful server (your PC).  
   - Could work with devices like Raspberry Pi for broader accessibility.  

---

## Current Limitations
The current implementation is basic due to:
- A mid-project restart caused by technical difficulties in the codebase.  
- The need for proper documentation and a GitHub repository.  

---

## Installation Notes
- The model supports a wide range of questions and instructions.  
- You may need to install some libraries to get it working properly.  

---

### Additional Notes
This model is intended to be used as an assistant, leveraging your documents to make reminders and perform other tasks. While limited at the moment, future updates aim to enhance its utility and ease of use.

