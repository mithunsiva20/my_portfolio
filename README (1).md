# Mithun S | Portfolio Website

A personal portfolio website for **Mithun S**, an aspiring software developer. It is a single, self-contained HTML page with no frameworks, build steps, or external dependencies.

## Features

- Single-page layout with smooth scrolling and sticky navigation
- Sections for Home, About, Education, Skills, Projects, Certifications, and Contact
- Responsive design for desktop and mobile
- Automatic light and dark mode based on the visitor's system settings
- Safe-area padding for phones with notches

## Sections

| Section        | Content                                                              |
|----------------|----------------------------------------------------------------------|
| Home           | Name and title: Mithun S, Aspiring Software Developer                |
| About          | Short introduction                                                   |
| Education      | B.Sc. Computer Technology, KPR College of Arts, Science and Research (CGPA 7.5) |
| Skills         | Java, C, Problem Solving, Teamwork, AI Tools                         |
| Projects       | IronLog (Fast Lift), LeetCode Tracker                                |
| Certifications | AI Workshop, Digital Marketing, Technical Certifications             |
| Contact        | Email, phone, GitHub, LinkedIn                                       |

## Project Structure

```
portfolio/
├── portfolio.html   # The entire website (HTML, CSS, and minimal markup)
└── README.md        # This file
```

## Getting Started

No installation is required.

1. Download or clone the project folder.
2. Open `portfolio.html` in any modern web browser.

To run it with a local server (optional):

```bash
# Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000/portfolio.html`.

## Customization

Open `portfolio.html` in a text editor and update the following:

1. **Contact details:** Replace the placeholder values in the Contact section:
   - `your.email@example.com`
   - `+91 00000 00000`
   - `github.com/yourusername`
   - `linkedin.com/in/yourprofile`
2. **Project links:** Replace the `href="#"` values in the Projects section with your GitHub repository or live demo URLs.
3. **Project descriptions:** Update the text for IronLog and LeetCode Tracker to reflect what they actually do.
4. **Certification details:** Add issuing organizations, dates, or certificate links as needed.
5. **About section:** Personalize the introduction with your own goals and interests.
6. **Colors:** Change the `--accent` variable in the `:root` block to use a different theme color.

## Deployment

Because the site is a single static file, it can be hosted for free on any of these services:

- **GitHub Pages:** Push the file to a repository, rename it to `index.html`, and enable Pages in the repository settings.
- **Netlify:** Drag and drop the project folder onto the Netlify dashboard.
- **Vercel:** Import the project folder or repository.

## Browser Support

Works in all modern browsers, including Chrome, Firefox, Safari, and Edge.

## License

This project is for personal use. All content, including names, project descriptions, and certifications, belongs to Mithun S.

## Contact

- Email: your.email@example.com
- GitHub: github.com/yourusername
- LinkedIn: linkedin.com/in/yourprofile
