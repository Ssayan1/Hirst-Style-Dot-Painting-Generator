# Hirst-Style Dot Painting Generator

A Python turtle graphics program that creates digital art inspired by Damien Hirst's famous spot paintings using extracted image colors.

## 🚀 Features

- **Grid-Based Art**: Creates systematic 10x10 dot patterns
- **Color Extraction**: Uses real image colors for authentic palettes
- **Random Placement**: Each dot gets a randomly selected color
- **Gallery-Ready**: Clean, professional presentation
- **Customizable**: Easy to modify grid size and colors

## 🛠️ Technologies Used

- Python 3.x
- Turtle Graphics Module
- Random Module
- Colorgram.py (for color extraction)

## 📋 Prerequisites

```bash
Python 3.6 or higher
```

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/hirst-dot-painting.git
   ```

2. **Navigate to project directory**
   ```bash
   cd hirst-dot-painting
   ```

3. **Install dependencies**
   ```bash
   pip install colorgram.py
   ```

## 🎮 Usage

**Run the program:**
```bash
python main.py
```

**Customize colors:**
```python
# Extract colors from your own image
import colorgram
colors = colorgram.extract("your_image.jpg", 30)
```

## 📸 Example Output

The program creates a 10x10 grid of colorful dots like this:
```
● ● ● ● ● ● ● ● ● ●
● ● ● ● ● ● ● ● ● ●
● ● ● ● ● ● ● ● ● ●
● ● ● ● ● ● ● ● ● ●
```
*(Each dot is a different random color)*

## 🎨 Customization Options

```python
# Change grid size
number_of_dots = 64   # Creates 8x8 grid
number_of_dots = 144  # Creates 12x12 grid

# Adjust dot size
tim.dot(15, color)    # Smaller dots
tim.dot(25, color)    # Larger dots

# Modify spacing
tim.forward(40)       # Closer together
tim.forward(60)       # Further apart
```

## 🤝 Contributing

Feel free to fork this project and submit pull requests!

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)

---
⭐ Star this repo if you found it helpful!
