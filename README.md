## Project Structure

project/
│
├── main.py                    # Main game and training logic
├── visualize.py               # NEAT visualization utilities
├── config-feedforward.txt     # NEAT configuration file
├── requirements.txt           # Python dependencies
│
├── imgs/
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.png
│   ├── base.png
│   └── bg.png

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd <project-directory>


python -m venv venv
source venv/bin/activate    # Linux / Mac
venv\Scripts\activate       # Windows

pip install -r requirements.txt

python main.py
```
