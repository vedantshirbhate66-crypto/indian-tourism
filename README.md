# 🇮🇳 Tourism in India — Website Project

A multi-page, static HTML website showcasing tourism in India. Built as an informational and application portal for travelers interested in exploring India's destinations, activities, and culture.

---

## 📁 Project Structure

```
tourism-india/
│
├── index.html          # Home page — welcome & overview
├── about.html          # About page — why visit India, types of tourism
├── destinations.html   # Popular destinations with images
├── activities.html     # Activities & experiences available
├── apply.html          # Application/registration form for tours
├── gallery.html        # Photo gallery of Indian landmarks
├── map.html            # Map of India
└── Map_of_India.png    # India map image asset
```

---

## 🌐 Pages Overview

| Page | Description |
|------|-------------|
| **Home** (`index.html`) | Welcome page with a brief introduction to India's highlights |
| **About** (`about.html`) | Background on Indian tourism, UNESCO sites, types of tourism |
| **Destinations** (`destinations.html`) | Cards for Taj Mahal, Goa, Kerala, Himalayas, Rajasthan, Varanasi |
| **Activities** (`activities.html`) | Trekking, cultural immersion, safaris, water sports, culinary tours |
| **Apply** (`apply.html`) | Form to register for exclusive tour programs |
| **Gallery** (`gallery.html`) | Grid-based photo gallery of major Indian attractions |
| **Map** (`map.html`) | Visual map of India |

---

## ✨ Features

- **Responsive Navigation** — consistent navbar across all pages linking every section
- **Indian Flag-themed Styling** — saffron (`#FF9933`), white, and green (`#128807`) color palette inspired by the Indian tricolour
- **Multi-page Architecture** — each topic has a dedicated page for clarity and easy navigation
- **Tourist Application Form** — collects name, email, phone, destination preference, interests, and experience level
- **Destination Cards** — visual cards for 6 major Indian tourism spots
- **Activity Listings** — categorised experiences for all traveller types
- **Photo Gallery** — CSS Grid-based layout for an attractive gallery view

---

## 🚀 Getting Started

### Prerequisites
No frameworks or build tools required. This is a pure HTML/CSS static site.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/tourism-india.git
   cd tourism-india
   ```

2. **Open in browser:**
   Simply open `index.html` in any modern web browser:
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```

   Or use a local development server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js (npx)
   npx serve .
   ```

3. **Visit:** `http://localhost:8000`

---

## 🎨 Design Highlights

- **Color Palette:** Indian flag-inspired saffron, white, and green tones
- **Background Gradients:** Each page has a unique gradient reflecting its theme
- **Typography:** Clean Arial/sans-serif for readability
- **Card Layouts:** Flexbox-based destination cards
- **Gallery Grid:** CSS Grid with `auto-fit` for responsive image layout
- **Form UX:** Clean, accessible form with dropdowns and textarea fields

---

## 🗺️ Key Destinations Covered

- 🕌 **Taj Mahal, Agra** — Symbol of eternal love
- 🏖️ **Goa Beaches** — Vibrant nightlife and Portuguese heritage
- 🛶 **Kerala Backwaters** — Serene houseboat cruises
- 🏔️ **Himalayas** — Trekking and adventure hub (Leh, Shimla)
- 🐪 **Rajasthan Desert** — Camel safaris and royal palaces
- 🕯️ **Varanasi** — Spiritual heart of India on the Ganges

---

## 🧗 Activities Offered

- Trekking & Adventure (Himalayas, Rishikesh, Himachal)
- Cultural Immersion (Diwali, Yoga, Tribal villages)
- Wildlife & Safaris (Ranthambore, Kerala, Bharatpur)
- Beach & Water Sports (Andaman, Goa, Kashmir)
- Culinary Tours (Delhi street food, Kerala spices, Rajasthani royal cuisine)

---

## 📋 Application Form Fields

The `apply.html` page includes a registration form with:
- Full Name
- Email Address
- Phone Number
- Preferred Destination (dropdown)
- Interests (free text)
- Travel Experience Level (Beginner / Intermediate / Expert)

---

## 🛠️ Technologies Used

- **HTML5** — Semantic page structure
- **CSS3** — Inline styling with gradients, flexbox, and grid
- **No JavaScript frameworks** — Lightweight and dependency-free

---

## 📌 Future Improvements

- [ ] Add real destination images (replace placeholder images)
- [ ] Connect the Apply form to a backend or form service (e.g., Formspree)
- [ ] Add JavaScript for interactive map markers
- [ ] Make the gallery filterable by region
- [ ] Integrate Google Maps API on the Map page
- [ ] Add a `contact.html` page with social links
- [ ] Improve mobile responsiveness with media queries

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

> *"Incredible India — A land of diversity, culture, and timeless beauty."*
