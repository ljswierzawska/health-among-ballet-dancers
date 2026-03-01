# Health Among Ballet Dancers

A scrollytelling data journalism piece investigating the health challenges — physical, mental, and hormonal — facing elite and collegiate ballet dancers.

**Live site:** https://ljswierzawska.github.io/health-among-ballet-dancers/

## Structure

- `index.html` — the full scrollytelling story (add your text and charts here)

## How to customize

### Add your own background photos
Each `.chapter` section has a `background-image` URL. Replace the Unsplash URLs with your own ballet photos:
```html
<section class="chapter" style="background-image: url('your-photo.jpg'); ...">
```

### Embed your ggplot2 charts
Export your R charts as PNG and replace the `<div class="chart-box">` placeholders:
```html
<div class="chart-box">
  <img src="charts/your-chart.png" alt="Chart description" style="width:100%; border-radius:6px;">
</div>
```
Or embed a DataWrapper iframe directly inside `.chart-box`.

### Fill in your text
Search for `[` in the file — every bracketed placeholder is text you need to write.

## Data sources

- Arcelus et al. (2021). *Eating Disorders in Classic Ballet.* Frontiers in Nutrition. https://doi.org/10.3389/fnut.2021.665654
- Collegiate Dancer Wellness Survey. https://pmc.ncbi.nlm.nih.gov/articles/PMC10456971/
- Lehbil et al. (2025). *Menstrual cycle disorders among elite ballet dancers.* Science & Sports. https://doi.org/10.1016/j.scispo.2024.10.006
