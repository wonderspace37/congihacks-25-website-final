# CogniHacks 2025 Website

## Overview
This is the official website for CogniHacks 2025, featuring a main landing page and a dedicated "Go Live" hub for the hackathon event.

## File Structure

```
cognihacks-web-Aman/
├── index.html              # Main landing page
├── live.html               # Go Live hub page (new)
├── resources/              # Resource documentation directory
│   ├── bci-setup.html     # BCI Setup Guide
│   └── openai-api.html    # OpenAI API Guide
├── assets/                 # Images and sponsor logos
├── styles.css              # Main stylesheet
└── script.js               # Main JavaScript functionality
```

## New Features

### Go Live Page (`live.html`)
- **Live Hub**: Centralized information hub for the hackathon event
- **Track Details**: Expandable accordion sections for each track (BCI, GenAI)
- **Resources**: Links to detailed documentation and guides
- **Quick Access**: Flip card design similar to "When, Where, Who, Why" cards - click to flip and see detailed information
- **Help Section**: Information about getting assistance from organizers wearing blue lanyards

### Resource Pages (`resources/`)
- **Blog-style Format**: Long-form articles with comprehensive information
- **Interactive Elements**: Code examples, step-by-step guides, best practices
- **Responsive Design**: Mobile-friendly layout with proper navigation
- **Back Navigation**: Easy return to the live hub

## Navigation Updates

### Main Navigation
- "Register" link replaced with "Go Live" link
- "Go Live" navigates to `/live.html`
- All other navigation items remain unchanged

### Live Hub Navigation
- Consistent navigation bar across all pages
- Proper relative linking between pages
- Mobile-responsive navigation menu

## Track Information

### BCI & Human Enhancement Track
- Hardware: Emotiv Insights, Mn8 headphones, Pro licenses
- Team size: Minimum 5 members
- Training: 9:45 AM session
- Hacking starts: 10:15 AM

### GenAI for Humans Track
- APIs: OpenAI API keys provided
- Team size: 2-6 members
- Demo: 9:45 AM showcase
- Hacking starts: 10:00 AM

## Resource Pages

### BCI Setup Guide (`resources/bci-setup.html`)
- Complete hardware setup instructions
- Software installation and configuration
- Calibration and training procedures
- Development integration examples
- Troubleshooting guide

### OpenAI API Guide (`resources/openai-api.html`)
- API setup and authentication
- Code examples in Python and JavaScript
- Best practices and optimization
- Project ideas and use cases
- Rate limiting and cost management

### Judging Criteria (`resources/judging-criteria.html`)
- Complete judging criteria breakdown
- Scoring system and evaluation guidelines
- Track-specific evaluation criteria
- Presentation tips and best practices
- Common pitfalls to avoid

## Usage

### For Participants
1. **Main Page**: Learn about CogniHacks 2025 and event details
2. **Go Live**: Access the live hub during the hackathon
3. **Resources**: Read detailed guides for your chosen track
4. **Quick Links**: Access essential event resources

### For Organizers
1. **Content Updates**: Modify HTML files to update information
2. **Resource Addition**: Create new HTML files in the `resources/` directory
3. **Navigation**: Update navigation links as needed
4. **Styling**: Modify `styles.css` for design changes

## Technical Details

### Responsive Design
- Mobile-first approach
- CSS Grid and Flexbox layouts
- Breakpoints at 768px for mobile devices

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- JavaScript ES6+ features

### File Dependencies
- Font Awesome 6.0.0 for icons
- Google Fonts (Inter) for typography
- External CDN resources for performance

## Development

### Adding New Resource Pages
1. Create new HTML file in `resources/` directory
2. Use the existing resource page template structure
3. Update navigation links in `live.html`
4. Test navigation and responsive design

### Updating Content
- All content is in HTML format for easy editing
- No build process required
- Direct file editing supported
- Version control recommended for content management

## Support

For technical issues or content updates:
- Check file paths and relative links
- Verify CSS class names and structure
- Test navigation on mobile devices
- Ensure all assets are properly linked

---

**CogniHacks 2025** - Building the future of brain-computer interfaces through innovation, collaboration, and cutting-edge technology.
