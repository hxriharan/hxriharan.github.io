# Visit Counter for Jekyll Website

This repository includes multiple visit counter components for your Jekyll website. The counters track page visits using localStorage and provide various display options.

## Features

- **Simple Visit Counter**: Basic floating counter with visit count
- **Footer Visit Counter**: Counter embedded in the footer
- **Advanced Visit Counter**: Detailed analytics with unique visitors and daily tracking
- **Configurable**: Easy to enable/disable and customize
- **Responsive**: Works on desktop and mobile devices
- **Privacy-friendly**: Uses localStorage (client-side storage)

## Installation

The visit counter is already integrated into your Jekyll site. Here's what was added:

### Files Created:
- `_includes/visit-counter.html` - Simple floating counter
- `_includes/visit-counter-footer.html` - Footer counter
- `_includes/advanced-visit-counter.html` - Advanced analytics counter

### Configuration Added:
The following settings were added to your `_config.yml`:

```yaml
# Visit Counter Settings
visit_counter:
  enabled: true
  position: "floating" # "floating" or "footer"
  show_icon: true
  animation: true
```

## Usage

### Basic Floating Counter (Default)
The basic visit counter is automatically included on all pages. It appears as a floating element in the bottom-right corner.

### Footer Counter
To use the footer counter instead, replace the include in `_layouts/default.html`:

```html
<!-- Replace this line: -->
{% include visit-counter.html %}

<!-- With this: -->
{% include visit-counter-footer.html %}
```

### Advanced Counter
To use the advanced counter with detailed analytics:

```html
<!-- Replace this line: -->
{% include visit-counter.html %}

<!-- With this: -->
{% include advanced-visit-counter.html %}
```

## Configuration Options

### Enable/Disable
```yaml
visit_counter:
  enabled: true  # Set to false to disable
```

### Position
```yaml
visit_counter:
  position: "floating"  # "floating" or "footer"
```

### Customization
You can customize the appearance by modifying the CSS in each include file:

- Colors and styling
- Position and size
- Animation effects
- Mobile responsiveness

## How It Works

### Data Storage
- Uses `localStorage` to store visit data
- Data persists across browser sessions
- No server-side storage required

### Tracking Features
- **Simple Counter**: Tracks total page visits
- **Advanced Counter**: Tracks:
  - Total visits
  - Unique visitors
  - Daily visit counts
  - Session data

### Privacy
- All data is stored locally in the user's browser
- No external tracking services required
- GDPR and privacy-friendly

## Customization Examples

### Change Counter Position
Edit the CSS in the include files:

```css
.visit-counter {
  position: fixed;
  bottom: 20px;  /* Change vertical position */
  right: 20px;   /* Change horizontal position */
}
```

### Change Colors
```css
.visit-counter {
  background: rgba(0, 0, 0, 0.8);  /* Background color */
  color: white;                     /* Text color */
}

.counter-number {
  color: #4CAF50;  /* Number color */
}
```

### Disable Animation
Set `animation: false` in `_config.yml` or remove animation code from the JavaScript.

## Integration with Analytics Services

The counters can be integrated with external analytics services:

### Google Analytics
```javascript
// Already included in the code
if (typeof gtag !== 'undefined') {
  gtag('event', 'page_visit', {
    event_category: 'engagement',
    event_label: data.page,
    value: data.count
  });
}
```

### Custom Analytics Endpoint
```javascript
// Uncomment and modify in the include files
fetch('/api/analytics', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify(data)
}).catch(console.error);
```

## Troubleshooting

### Counter Not Appearing
1. Check if `visit_counter.enabled` is set to `true` in `_config.yml`
2. Verify the include is present in `_layouts/default.html`
3. Check browser console for JavaScript errors

### Counter Not Updating
1. Clear browser localStorage: `localStorage.clear()`
2. Check if JavaScript is enabled
3. Verify no ad blockers are interfering

### Mobile Issues
1. The counters are responsive by default
2. Advanced counter starts collapsed on mobile
3. Check CSS media queries for mobile-specific styling

## Browser Support

- Chrome/Chromium: Full support
- Firefox: Full support
- Safari: Full support
- Edge: Full support
- Internet Explorer: Limited support (localStorage available in IE8+)

## License

This visit counter is part of your Jekyll site and follows the same license as your site.

## Contributing

Feel free to modify the counter components to better suit your needs. The code is well-commented and modular for easy customization. 