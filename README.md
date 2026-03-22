# Tatva Cafe
A fully self-contained website for Tatva Cafe, a 100% pure vegetarian Indian cafe in Ellisville, MO. Built entirely in HTML and CSS with no frameworks, no backend, and no third-party dependencies.

---

## Features
- Interactive menu with four categories: Breakfast, Chaat, Sweets, and Beverages
- Photo gallery
- Location and contact information
- Catering inquiry flow
- All images embedded via base64 encoding — no external hosting required

---

## How to Use

### View the Site
1. Download the raw HTML file
2. Open it in any browser — it works offline with no setup

### Edit the Menu / Prices
1. Download the raw file
2. Open it in Visual Studio Code
3. Press `Cmd + F` (Mac) or `Ctrl + F` (Windows) and search for `menuData`
4. You will find a section that looks like this:

```html
<script>
const menuData = {
  breakfast: {
    type: 'categories',
    note: 'Available from open to close',
    categories: [
      { title: 'Idli', items: [
        { name: 'Plain Idli (4 pieces)', price: '$7.77' },
        { name: 'Podi Idli (3 pieces)', price: '$8.00' },
        { name: 'Ghee Podi Idli (3 pieces)', price: '$8.77', best: true },
        { name: 'Sambar Dip', price: '$7.77' },
        { name: 'Tawa Fry', price: '$8.77' },
      ]},
      { title: 'Vada', items: [
        { name: 'Plain Vada (4 pieces)', price: '$7.77' },
        { name: 'Sambar Vada Dip', price: '$7.77' },
        { name: 'Tawa Fry', price: '$8.77' },
      ]},
      { title: 'Dosa', items: [
        { name: 'Plain Dosa', price: '$7.77' },
        { name: 'Onion Dosa', price: '$8.00' },
        { name: 'Paneer Dosa', price: '$8.77' },
        { name: 'Masala', price: '$8.77', best: true },
        { name: 'Mysore Masala', price: '$10.77', best: true },
      ]},
      // ... and so on for each category
    ]
  }
}
</script>
```

5. Find the item you want to update and change the `price` field
6. Save the file and open it in your browser to confirm the change

### Adding a "Best Seller" Star
Add `best: true` to any item to show a star next to it on the menu:
```js
{ name: 'Mysore Masala', price: '$10.77', best: true }
```

---

## Built With
- HTML
- CSS

---

## License
Copyright (c) 2026 Tatva. All Rights Reserved. See [LICENSE](LICENSE) for details.
