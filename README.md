# DynamicColorContainer Widget Documentation

## Description

The **DynamicColorContainer** widget allows developers to dynamically set background and text colors using Mendix expressions. This eliminates the need for manually writing CSS classes or using the Dynamic Class section. The widget accepts color values as strings, including those generated through expressions or from string attributes.

## Typical Usage Scenarios

- Provide a flexible styling solution where UI design requires color variations based on expressions or user input.
- Apply dynamic background colors to containers without creating custom CSS classes.
- Change text colors dynamically within the container while preserving the original widget structure.

## Supported Color Values

### 1. `#284ce4`:
- **Name**: Hex Code
- **Description**: This hex code represents a color in the RGB color model:
  - Red = 40 (Hex: 28)
  - Green = 76 (Hex: 4c)
  - Blue = 228 (Hex: e4)

### 2. `rgb(40 76 228)`:
- **Name**: RGB (Red, Green, Blue)
- **Description**: A color model representing colors by specifying the intensity of red, green, and blue light (40, 76, and 228 respectively).

### 3. `hsl(228.51deg 77.69% 52.55%)`:
- **Name**: HSL (Hue, Saturation, Lightness)
- **Description**: Describes colors using three components:
  - Hue: Angle on the color wheel (0–360 degrees)
  - Saturation: Percentage of color intensity
  - Lightness: Percentage of brightness

### 4. `oklch(0.5 0.23 266.57)`:
- **Name**: OKLCH (a perceptually uniform color model)
- **Description**: A perceptually uniform color model using three components:
  - Lightness (L)
  - Chroma (C)
  - Hue (H)
  It is designed to be more perceptually uniform than traditional color spaces like RGB or HSL.

### 5. `lab(38 32.97 -81.98)`:
- **Name**: CIELAB (International Commission on Illumination, Lab* model)
- **Description**: A color model that represents color using three components:
  - L (lightness)
  - a (green to red)
  - b (blue to yellow)
  This model is based on human vision and is widely used in color science.

### 6. `oklab(0.5 -0.01 -0.23)`:
- **Name**: OKLAB (a perceptually uniform color model)
- **Description**: Another perceptually uniform color model similar to OKLCH, with components:
  - L (lightness)
  - a (green to red)
  - b (blue to yellow)
  It is designed to align better with human perception of color differences.

## Dependencies

- No Dependencies

## Installation

### Steps:

1. **Import the widget** into your Mendix project.
2. **Place the widget** inside a data widget, such as a List View, DataGrid2, or DataView.
3. **Configure the properties** to set:
   - **Background color** (via expression, StringAttribute, or static value)
   - **Text color** (optional, defaulting to black if not provided)
   - **Default color** (optional)
4. **Add child widgets** inside the container as needed.
5. **Test the styling changes** dynamically in both Studio Pro and runtime environments.

## Bugs
- **No bugs have been reported so far.**
- If any bugs are found, please add them in the reviews section.




