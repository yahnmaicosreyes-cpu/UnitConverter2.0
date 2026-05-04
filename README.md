# UnitConverter2.0
Grandad proof unit converter tool
## Accessible Unit Converter (km ↔ mi)

A no-nonsense, high-visibility unit converter specifically designed for users with visual impairments or mobility challenges (e.g., seniors). Built with a "logic-first" approach to ensure mathematical precision for tracking running and walking statistics.

## 🎯 Purpose
Created for an elderly user to quickly and accurately convert distances (Kilometers ↔ Miles) shared by family members. The interface is optimized for tablets and mobile devices with a focus on "fat-finger" prevention and high readability.

## ✨ Key Features
- **High Contrast UI:** Navy blue and white text on a light gray background for maximum visibility.
- **Large Typography:** Minimum 18-20px Arial font used throughout.
- **Touch-Friendly Design:** Oversized (70px height) buttons with significant vertical spacing to prevent accidental clicks.
- **Mathematical Precision:** Uses high-precision constants:
  - `1 km = 0.621371 mi`
  - `1 mi = 1.60934 km`
- **Mobile Optimized:** Includes `inputmode="decimal"` to automatically trigger the numeric keypad on mobile devices.
- **Quick Reference Table:** A built-in table for common race distances (5K, 10K, Marathon).

## 🛠️ Technical Stack
- **HTML5:** Semantic structure.
- **CSS3:** Responsive Flexbox layout and high-contrast styling.
- **JavaScript (Vanilla):** Precise floating-point arithmetic and DOM manipulation.

## 🚀 How to Use
1. **Clone or Download:** Save the `index.html` file to your device.
2. **Open:** Simply double-click the file to open it in any modern web browser (no server required).
3. **Convert:** Enter a value, select the conversion direction, and tap the large **CONVERT** button.

## 🧑‍💻 Developer Notes
The code is contained within a single file for easy portability. Logic is decoupled from styling via CSS variables and clearly commented JavaScript functions, making it simple to extend for other units (e.g., pace or weight) in the future.

---
*Built with a focus on accessibility and physical ergonomics.*
