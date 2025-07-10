
# Pelican Bicycle SVG Generator

## Introduction
This project uses the `svgwrite` library to generate an SVG image of a bicycle and a pelican. The bicycle consists of two wheels and a frame, while the pelican is drawn with basic shapes and animated using the `animateTransform` method. The resulting SVG file can be opened in any browser or vector graphics software.

## Installation Instructions
To run the code, you will need Python installed on your system. The project requires the following Python library:

- **svgwrite**

You can install the required library using pip:

```bash
pip install svgwrite
```

## Usage Instructions
1. Clone or download this repository.
2. Ensure that Python 3.x is installed along with the required libraries.
3. Run the Jupyter notebook (`Main.ipynb`) in a Jupyter notebook environment or a Python IDE.

```bash
jupyter notebook Main.ipynb
```

This will generate an SVG file with a bicycle and an animated pelican.

## Code Explanation

### Key Components:
- **SVG Drawing**: The code uses the `svgwrite` library to create an SVG canvas and draw the bicycle and pelican.
- **Bicycle Drawing**: It draws two circles for the wheels and lines for the frame, creating a simple bicycle shape.
- **Pelican Drawing**: The pelican is drawn using ellipses and polygons for the body, head, and beak.
- **Animation**: The pelican's animation is created using the `animateTransform` method, making it move up and down continuously.

### Functions:
- **create_pelican_bicycle_svg()**: This function draws the bicycle and pelican, applies the animation to the pelican, and saves the SVG to a file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
