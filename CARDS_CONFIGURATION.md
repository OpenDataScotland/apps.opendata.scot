# Example: How to add a new card to the Open Data Scotland Apps

To add a new card to the apps directory, simply edit the `_data/apps.yml` file and add a new entry with the following structure:

```yaml
- title: "Your App Name"
  description: "A brief description of what your app does and its purpose."
  url: "https://yourapp.opendata.scot"
  icon: "bi-icon-name"           # Bootstrap Icons class name
  color: "primary"               # Bootstrap color: primary, secondary, success, danger, warning, info, light, dark
  button_text: "Custom Button"   # Text to display on the button
  column_width: "col-md-6"       # Bootstrap column width: col-md-6 (half width) or col-md-12 (full width)
```

## Available Bootstrap Colors:
- `primary` (blue)
- `secondary` (gray)
- `success` (green)
- `danger` (red)
- `warning` (yellow)
- `info` (cyan)
- `light` (light gray)
- `dark` (dark gray)

## Available Bootstrap Icons:
Visit https://icons.getbootstrap.com/ for a full list of available icons. Use the class name without the `bi-` prefix (it's added automatically).

## Column Width Options:
- `col-md-6`: Half width card (2 cards per row on medium+ screens)
- `col-md-12`: Full width card (1 card per row)
- `col-md-4`: Third width card (3 cards per row on medium+ screens)

The full-width cards (`col-md-12`) automatically get centered text alignment.

## Example of a new card:

```yaml
- title: "Data Analytics Dashboard"
  description: "Interactive dashboard for analyzing Scottish demographic and economic data with visualizations and reports."
  url: "https://analytics.opendata.scot"
  icon: "bi-bar-chart"
  color: "secondary"
  button_text: "View Analytics"
  column_width: "col-md-6"
```

After adding a new entry, run `bundle exec jekyll build` or `bundle exec jekyll serve` to see the changes.
