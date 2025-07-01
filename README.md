# Hirst-Style Dot Painting Generator

A Python turtle graphics program that creates digital art inspired by Damien Hirst’s famous spot paintings. Uses extracted image colors to generate a systematic grid of colorful dots, mimicking the iconic contemporary art style.

## Features

- **Hirst-Inspired Design:** Recreates the famous spot painting aesthetic digitally.
- **Color Palette from Real Image:** Uses 27 colors extracted from an actual image using colorgram.
- **Systematic Grid Layout:** Creates a perfect 10x10 grid of dots (100 total).
- **Random Color Selection:** Each dot gets a randomly chosen color from the extracted palette.
- **Professional Spacing:** 50-pixel spacing between dots for balanced composition.
- **Clean Presentation:** Hidden turtle cursor for gallery-ready appearance.

## Technical Implementation

- **Grid System:** 10 dots per row, 10 rows total.
- **Positioning Algorithm:** Starts from bottom-left, moves systematically.
- **Row Management:** Automatic line breaks every 10 dots.
- **Color Randomization:** `random.choice()` ensures unpredictable color distribution.
- **Dot Size:** 20-pixel diameter dots for optimal visual impact.

### Example Grid Positioning Logic

```python
for dot_count in range(1, 101):
    tim.dot(20, random.choice(color_list))  # Create colored dot
    tim.forward(50)                         # Move to next position

    if dot_count % 10 == 0:                 # End of row
        # Move to start of next row
        tim.setheading(90)    # Face up
        tim.forward(50)       # Move up one row
        tim.setheading(180)   # Face left
        tim.forward(500)      # Return to left edge
        tim.setheading(0)     # Face right for next row

## Color Palette

Features 27 carefully extracted colors, including:
- **Warm earth tones:** (202, 164, 109), (150, 75, 49)
- **Cool blues:** (52, 93, 124), (133, 163, 185)
- **Vibrant accents:** (140, 30, 19), (148, 17, 20)
- **Natural greens:** (46, 122, 86), (13, 99, 71)
- **Soft pastels:** (238, 240, 245), (233, 175, 164)

## Artistic Style

- **Contemporary Digital Art:** Modern interpretation of a famous art movement.
- **Systematic Composition:** Mathematical precision meets random color.
- **Minimalist Aesthetic:** Clean, gallery-worthy presentation.
- **Color Theory Application:** Balanced palette with varied hues and saturation.

## Usage

```bash
python hirst_dots.py
