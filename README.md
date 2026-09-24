# NGO Website Template

A reusable, HTML and CSS-first NGO website template.

## Files

```text
NGO-New-Age-Website-Template/
├── index.html
├── style.css
└── README.md
```

The visual boxes use gradients/placeholders until an NGO adds its own media.

## Sections

1. Hero
2. About
3. Impact
4. Causes / Initiatives
5. Real Stories
6. Events
7. Get Involved
8. Spread the Word panel
9. Footer

## How to use

1. Open `index.html` and replace `YOUR NGO`, `YOUR NGO NAME`, placeholder descriptions, dates, impact figures, causes, stories, and events with the NGO's verified information.
2. Open `style.css` if you want to change the color system, spacing, typography, or responsive behavior.
3. Open `index.html` directly in a browser, or use VS Code Live Server.

## Adding your NGO logo/name

The template intentionally uses text branding:

```html
<a href="#top" class="brand">
  <span>YOUR</span> NGO
  <small>FOUNDATION</small>
</a>
```

Replace the text with the organization's preferred name. A logo image can be added later if required.

## Adding images later

The template has image-ready containers but does not ship with any organization-specific images. To add a real image, place it inside the appropriate container. For example:

```html
<div class="story-photo story-photo-one">
  <img src="images/your-story.jpg" alt="Short description">
  <span>STORY TITLE</span>
</div>
```

The existing CSS already supports full-bleed images with `object-fit: cover`.

## Buttons and links

The template does not contain an NGO's real donation, volunteer, or social URLs. Replace the `href="#"` placeholders with the organization's actual URLs.

Examples:

```html
<a href="https://your-ngo.example/donate">Donate</a>
<a href="https://your-ngo.example/volunteer">Volunteer</a>
```

Use the organization's verified URLs before publishing.

## CSS-only features

- Sticky header
- CSS-only mobile navigation
- Smooth scrolling
- Responsive layout
- CSS-only story lightboxes using `:target`
- CSS-only spread panel using `:target`
- View Timeline cinematic cause animation where supported by the browser
- `prefers-reduced-motion` support
- No JavaScript required

## Cause animation

Browsers without View Timeline support will still display the cause content normally.

## Important customization checklist

Before publishing, replace:

- `YOUR NGO` / `YOUR NGO NAME`
- Mission and About text
- Founded year and reach
- Impact figures
- Six cause names, descriptions and metrics
- Four story titles, dates, descriptions and photos
- Event dates and descriptions
- Donate URL
- Volunteer URL
- Official website URL
- Social sharing URLs
- Footer copyright text
- Hero and story media

Keep claims, statistics, event details, and impact figures based on information the NGO has verified.

## License / reuse

This template is provided as a reusable starting point. Replace all placeholder content and links with the organization's own material before deployment.
