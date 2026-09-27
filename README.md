/Users/harshsingh/Documents/Portfolio/
├── index.html                    # Entry HTML & SEO meta tags
├── package.json                  # Dependencies & scripts
├── tailwind.config.js            # Custom color palette, dark mode & glow effects
├── vite.config.ts                # Vite build configuration
├── src/
│   ├── main.tsx                  # React entry point
│   ├── App.tsx                   # Main layout assembling all sections
│   ├── index.css                 # Global CSS, scrollbars & glassmorphism
│   ├── context/
│   │   └── ThemeContext.tsx      # Dark / light theme provider
│   ├── data/
│   │   └── portfolioData.ts      # 👈 Edit this to update your bio, skills, projects & links!
│   └── components/
│       ├── Navbar.tsx            # Sticky navigation with theme toggle & mobile drawer
│       ├── Hero.tsx              # Hero banner with code preview card & CTAs
│       ├── About.tsx             # Bio, stats cards, and personal hobbies
│       ├── Skills.tsx            # Grouped tech stack with interactive filter
│       ├── Projects.tsx          # 6 project cards with demo and code links
│       ├── Experience.tsx        # Career timeline with quantifiable achievements
│       ├── Education.tsx         # Degree, coursework & certifications
│       ├── Contact.tsx           # Contact form and direct links
│       ├── Footer.tsx            # Copyright & scroll-to-top button
│       └── ScrollProgress.tsx    # Reading progress bar
