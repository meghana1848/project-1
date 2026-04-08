# Johnson Tiles - Premium Flooring Studio 🏛️

## 📌 Project Overview
**Johnson Tiles** is a high-end, luxury front-end web application designed for a premium tile retail experience. The project serves as a digital showroom, showcasing an extensive collection of luxury tiles and marbles, and provides a precision tool for customers to calculate material requirements based on room measurements.

**Tagline:** *"Excellence in Every Square Foot"*

## ✨ Key Features
- **Luxury User Experience:** A sophisticated "Deep Black & Gold" theme designed to evoke a sense of prestige and elegance.
- **Interactive Welcome Gateway:** A custom entry screen that allows users to filter their experience by space (Flooring, Walls, Bathroom, or Bedroom).
- **Dynamic Large-Scale Catalogue:** 
    - Implements a data-driven generator producing 100+ unique tile models.
    - Category-based filtering for a seamless browsing experience.
    - Detail modals providing deep descriptions and luxury specifications for each product.
- **Precision Tile Calculator:** 
    - Calculates total square footage based on room dimensions.
    - Converts tile dimensions (inches) to square feet.
    - Automatically adds a **10% industry-standard wastage buffer** for cutting and breakage.
    - Outputs the exact number of boxes required for order.
- **Business Integration:** Fully integrated with business contact details for **Sri Balaji Tiles Bazar**.

## 🛠️ Tech Stack
- **HTML5:** Semantic structure for a professional web layout.
- **Tailwind CSS:** Modern utility-first framework for responsive, high-end styling.
- **JavaScript (ES6):** Dynamic rendering, category filtering, and mathematical logic.
- **FontAwesome:** Professional iconography for a polished UI.
- **Google Fonts:** Using *Playfair Display* (Serif) for luxury headings and *Poppins* for clean readability.

## 🏢 Business Information
- **Store Name:** Johnson Tiles (Sri Balaji Tiles Bazar)
- **Location:** Rajam, Vizianagaram District, Andhra Pradesh - 532127
- **Contact:** +91 9494969489
- **Email:** meghanavangapandu18@gmail.com

## 🚀 How to Run
1. Clone the repository or download the project folder.
2. Open `index.html` in any modern web browser (Chrome, Edge, or Firefox).
3. No installation or server setup is required as all styles are handled via CDN.

## 📐 Calculation Formula
The calculator uses the following professional logic:
$\text{Total Area} = \text{Length} \times \text{Width}$
$\text{Tile Area (sq ft)} = \frac{\text{Tile Size (inches)}^2}{144}$
$\text{Total Boxes} = \lceil \frac{(\text{Total Area} / \text{Tile Area}) \times 1.10}{\text{Tiles Per Box}} \rceil$
