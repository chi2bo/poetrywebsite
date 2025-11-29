# Poetry Portfolio Website

A beautiful, interactive poetry portfolio website featuring Chinese and English poems organized by themes.

## Project Structure

```
poetrywebsite/
├── index.html              # Main landing page with poem category grid
├── poems/                  # Individual poem pages organized by theme
│   ├── poem-love.html
│   ├── poem-you.html
│   ├── poem-me.html
│   ├── poem-people.html
│   ├── poem-walking.html
│   ├── poem-water.html
│   ├── poem-sunshine.html
│   ├── poem-random.html
│   ├── poem-night.html
│   ├── poem-life.html
│   ├── poem-nothing.html
│   └── poem-complain.html
├── css/                    # Stylesheets
│   ├── main.css           # Main styles (desktop) with modal enhancements
│   ├── mobile.css         # Mobile-responsive styles
│   └── [theme].css        # Individual theme-specific styles
├── js/
│   └── index.js           # JavaScript for modal interactions and page transitions
├── package.json           # Node.js dependencies (Barba.js for page transitions)
├── Gemfile               # Jekyll configuration (if using Jekyll)
└── .gitignore            # Git ignore rules

```

## Features

- **Interactive Modal System**: Click on poem categories to see available poems in beautiful modal popups
- **Smooth Animations**: Frosted glass effects with backdrop blur and slide-down animations
- **Responsive Design**: Mobile-friendly layout with separate CSS for different screen sizes
- **Organized by Themes**: Poems are grouped into 12 categories (Love, You, Me, People, Walking, Water, Sunshine, Random, Night, Life, Nothing, Complain)
- **Page Transitions**: Barba.js integration for smooth navigation between pages

## Technologies Used

- HTML5
- CSS3 (with backdrop-filter for frosted glass effects)
- JavaScript (with Barba.js for page transitions)
- Jekyll (optional, for static site generation)

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. For Jekyll (optional):
   ```bash
   bundle install
   bundle exec jekyll serve
   ```

3. Open `index.html` in a browser or use a local server

## Poem Categories

The portfolio features 12 thematic categories, each with multiple poems:
- 爱 (Love)
- 你 (You)
- 我 (Me)
- 人们 (People)
- 行走 (Walking)
- 水 (Water/H2O)
- 阳光 (Sunshine)
- 胡思乱想 (Random Thoughts)
- 夜空 (Night Sky)
- 生命 (Life)
- 什么都没有 (Nothing)
- 抱怨 (Complain)

## Customization

- Edit `css/main.css` to modify modal styles and overall appearance
- Edit `css/mobile.css` for mobile-specific adjustments
- Individual poem styles can be customized in their respective CSS files
- Add new poems by creating HTML files in the `poems/` directory and updating `index.html`


