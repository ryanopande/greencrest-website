# Greencrest Advent School Website

A calm, traditional, faith-based website for Greencrest Advent School - a Kenyan primary school offering education from ECD to Grade 9.

## Tech Stack

- **Astro**: Modern static site generator
- **Tailwind CSS**: Utility-first CSS framework
- **Decap CMS**: Headless CMS for content management
- **TypeScript**: Type-safe development

## Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open [http://localhost:4321](http://localhost:4321) in your browser

### Building for Production

```bash
npm run build
```

The built site will be in the `dist/` directory.

## Project Structure

```
greencrest-advent-school/
├── public/
│   ├── admin/          # CMS configuration
│   └── images/         # Image assets (placeholders included)
├── src/
│   ├── components/     # Reusable components (Navigation, Footer)
│   ├── layouts/        # Page layouts
│   ├── pages/          # All website pages
│   ├── styles/         # Global styles and Tailwind config
│   └── data/           # CMS-managed content (news, calendar, staff, gallery)
└── astro.config.mjs    # Astro configuration
```

## Content Management

### Setting Up Decap CMS

1. **For Netlify Deployment**
   - Deploy to Netlify
   - Enable Git Gateway in Netlify settings
   - Access CMS at `/admin`

### Managing Content

- **News Posts**: Add/edit news articles via CMS
- **Calendar Events**: Manage school calendar events
- **Staff Profiles**: Update staff information and photos
- **Gallery Albums**: Create and manage photo albums

## Customization

### Colors

```css
@theme {
  --color-green-light: #a8d5a3;
  --color-green-medium: #6b9f5f;
  --color-green-dark: #3d6b2f;
  --color-green-darker: #2d4f22;
  --color-cream: #f5f3f0;
  --color-beige: #e8e4dd;
}
```

## Pages

- **Home**: Hero section, mission, key pillars, student life preview
- **About**: School history, values, Adventist foundation, headteacher's message
- **Academics**: ECD, Lower Primary, Upper Primary, Junior School programs
- **Admissions**: Application process, requirements, fees, visit booking form
- **Student Life**: Boarding life, clubs & sports, meals & welfare
- **Staff**: Leadership team, teaching staff, support staff
- **Calendar**: Term dates, important events, exam periods, visiting days
- **News**: School announcements, events, achievements
- **Gallery**: Photo albums of school events and activities
- **Contact**: Contact information, visiting hours, contact form
- **Safeguarding**: Child protection policy and privacy policy

## Deployment

1. Push code to GitHub/GitLab
2. Connect repository to Netlify
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Enable Git Gateway for CMS

## Maintenance

### For Non-Technical Staff

1. **Content Updates**: Use the CMS at `/admin` to update:
   - News posts
   - Calendar events
   - Staff profiles
   - Gallery albums

2. **Image Updates**: 
   - Upload new images to `public/images/`
   - Reference them in CMS or page files

3. **Contact Information**:
   - Update in `src/components/Footer.astro`
   - Update in `src/pages/contact.astro`

## Support

For technical support or questions about the website, please contact the development team or refer to:
- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Decap CMS Documentation](https://decapcms.org/docs)

## License

This website is proprietary to Greencrest Advent School.

---

**Built with care for Greencrest Advent School**  
*A Tradition of Excellence*
# greencrest-website
