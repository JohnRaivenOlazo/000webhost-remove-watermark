# 000webhost Watermark Remover

A JavaScript code for removing watermark from 000webhost.

## Usage

### Quick Removal
```javascript
document.addEventListener('DOMContentLoaded', () => document.querySelector("img[alt='www.000webhost.com']").remove());
```
### Full Code
```
document.addEventListener('DOMContentLoaded', () => {
  const watermark = document.querySelector("img[alt='www.000webhost.com']");
  // Check if the image is present before removing
  if (watermark) {
    watermark.remove();
  }
});
```

