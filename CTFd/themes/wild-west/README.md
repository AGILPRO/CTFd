# Wild West Theme for CTFd

🤠 **Yeehaw!** Welcome to the Wild West CTFd Theme!

## Description

The Wild West theme brings the rugged, adventurous spirit of the American frontier to your CTFd platform. With its Western-inspired color palette, wooden textures, and saloon-style aesthetics, this theme transforms your CTF challenges into an exciting Wild West adventure.

## Features

- **Western Color Palette**: Earthy browns, tans, creams, and gold accents
- **Wooden Textures**: Buttons and cards styled with wooden panel effects
- **Saloon Style**: Navigation bars and headers with classic Wild West saloon styling
- **Wanted Poster Challenges**: Challenge buttons styled like old Western wanted posters
- **Desert Sky Background**: Gradient background simulating prairie and desert skies
- **Decorative Elements**: Cowboy hat emoji and other Western touches

## Installation

1. Copy the `wild-west` directory to your CTFd installation's `CTFd/themes/` directory
2. Restart your CTFd instance
3. Go to Admin Panel → Config → Appearance
4. Select "Wild West" as your theme
5. Save changes

## Theme Structure

```
wild-west/
├── config.json          # Theme configuration
├── templates/
│   └── base.html       # Base template extending core theme
├── static/
│   └── css/
│       └── wild-west.css  # Wild West custom styles
└── README.md           # This file
```

## Customization

The Wild West theme extends CTFd's core theme, so it inherits all core functionality while adding Western flair. You can customize the theme by:

- Modifying color variables in `wild-west.css`
- Adding custom Western-themed images
- Extending templates in the `templates/` directory
- Adding custom fonts (consider Western-style fonts like "Rye" or "Smokum")

## CSS Variables

The theme uses these CSS custom properties:

```css
--wild-west-brown: #8B4513
--wild-west-tan: #D2B48C
--wild-west-cream: #F5DEB3
--wild-west-dark: #3E2723
--wild-west-red: #B22222
--wild-west-gold: #FFD700
```

## Credits

- **Author**: AGILPRO
- **Version**: 1.0.0
- **Based on**: CTFd Core Theme
- **License**: Same as CTFd (Apache License 2.0)

## Screenshots

*(Add screenshots here when the theme is deployed)*

## Support

For issues or suggestions related to this theme, please open an issue in this repository.

## Compatibility

- CTFd Version: 3.0+
- Browser Support: Modern browsers (Chrome, Firefox, Safari, Edge)

---

**Happy Hacking, Partner! 🤠**
