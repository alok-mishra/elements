# Element & Ion Flashcards

A responsive, interactive flashcard application for learning chemical elements and polyatomic ions. Built with vanilla HTML, CSS, and JavaScript - no dependencies required.

## Features

- **Dual Deck System**: Switch between Elements (symbol → name) and Polyatomic Ions (formula → name)
- **Interactive Cards**: Tap or click to flip cards and reveal answers
- **Navigation**: Multiple ways to navigate through cards
  - Arrow buttons on both sides of the card
  - Control buttons below the card
  - Keyboard shortcuts (Space to flip, Arrow keys to navigate)
  - Touch gestures (swipe left/right, tap to flip)
- **Shuffle Mode**: Randomize the deck order for varied practice
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Proper Chemical Notation**: Subscripts and superscripts render correctly for ion formulas

## Getting Started

Simply open `elements-flash-cards.html` in any modern web browser. No build process or installation required.

```bash
# Clone the repository
git clone <repository-url>

# Open the file
open elements-flash-cards.html
```

Or double-click the HTML file to open it in your default browser.

## Usage

### Controls

**Desktop:**
- Click on the card to flip it
- Use arrow buttons (← →) to navigate
- Press `Space` to flip the card
- Press `→` or `←` arrow keys to navigate
- Click "Shuffle" to randomize the deck

**Mobile:**
- Tap the card to flip it
- Swipe left/right to navigate between cards
- Use the side arrow buttons for navigation
- Tap "Shuffle" to randomize the deck

### Decks

**Elements Deck**: 50 common chemical elements
- Front: Element symbol (e.g., "H", "Au", "Fe")
- Back: Element name (e.g., "Hydrogen", "Gold", "Iron")

**Polyatomic Ions Deck**: 21 common polyatomic ions
- Front: Chemical formula with proper subscripts/superscripts (e.g., NH₄⁺, CO₃²⁻)
- Back: Ion name (e.g., "Ammonium", "Carbonate")

## Content

### Elements Included
Covers the most commonly used elements in chemistry, including:
- Main group elements (H, C, N, O, etc.)
- Transition metals (Fe, Cu, Au, etc.)
- Noble gases (He, Ne, Ar, etc.)
- Heavy elements (U, Pu, Ra, etc.)

### Polyatomic Ions Included
- Common cations: Ammonium (NH₄⁺)
- Oxyanions: Nitrate, Sulfate, Phosphate series
- Halogen oxyanions: Chlorate series
- Other important ions: Hydroxide, Cyanide, Acetate, Peroxide

## Technical Details

- **Framework**: Vanilla JavaScript (no dependencies)
- **Styling**: Custom CSS with CSS variables for theming
- **Compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile Support**: Touch gestures, safe area insets for notched devices
- **Accessibility**: ARIA labels, keyboard navigation

## Customization

To add more elements or ions, edit the `elements` or `ions` arrays in the JavaScript section:

```javascript
const elements = [
    { sym: "H", name: "Hydrogen" },
    // Add more elements here
];

const ions = [
    { sym: "NH<sub>4</sub><sup>+</sup>", name: "Ammonium" },
    // Add more ions here (use HTML tags for sub/superscripts)
];
```

## License

Feel free to use and modify for educational purposes.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests for:
- Additional elements or ions
- UI improvements
- Bug fixes
- New features
