# Fontster

Fontster is a web application designed to help designers find the right sizes and styles for their text. With Fontster, users can configure and preview different font settings to achieve the best readability and aesthetic appeal.

## Features

- **Base Font Size**: Set the base font size for your text.
- **Text Scale**: Choose from a variety of text size scales to see how different scales affect your typography.
- **Font Family**: Select from a list of Google Fonts to see how different fonts look in your design.
- **Font Weight**: Adjust the weight of the font to see how different thicknesses affect readability and style.
- **Line Height**: Set the line height to control the spacing between lines of text.
- **Letter Spacing**: Adjust the letter spacing to see how different spacings affect text appearance.
- **Text Color**: Choose a color for your text.
- **Background Color**: Set a background color to see how text looks against different backgrounds.
- **Preview Text**: Enter custom text to see how your settings affect your actual content.
- **Unit Switcher**: Switch between px, rem, and pt units to see how font sizes translate between different measurement units.
- **Contrast Rating**: Get a contrast rating (AAA, AA, A, FAIL) based on the text and background color combinations, ensuring accessibility compliance.
- **Save Google Fonts API Key**: Save your Google Fonts API key locally for persistent access to Google Fonts.

## How to Use

1. **Enter Google Fonts API Key**: 
   - Input your Google Fonts API key in the provided field and click "Save". This will store the API key locally and fetch the list of Google Fonts.

2. **Configure Font Settings**:
   - **Base Font Size**: Set the desired base font size in pixels.
   - **Text Scale**: Select a text size scale from the dropdown.
   - **Font Family**: Choose a font from the Google Fonts dropdown. The available fonts are fetched using your API key.
   - **Font Weight**: Select the desired font weight from the options based on the chosen font.
   - **Line Height**: Adjust the line height value.
   - **Letter Spacing**: Set the letter spacing in em units.
   - **Text Color**: Choose a text color using the color picker.
   - **Background Color**: Choose a background color using the color picker.
   - **Preview Text**: Enter the text you want to preview.

3. **Switch Measurement Units**:
   - Use the unit switcher to toggle between px, rem, and pt units for font sizes.

4. **Preview and Adjust**:
   - The preview section will update in real-time as you adjust the settings. The contrast rating will indicate the accessibility compliance of your chosen text and background color combination.

## Technical Details

Fontster is built using HTML, CSS (TailwindCSS), and JavaScript. It utilizes the Google Fonts API to fetch and display a list of fonts, and allows for real-time preview and configuration of text settings.

## Setup

To use Fontster locally, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/kamephis/fontster.git
