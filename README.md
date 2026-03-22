# Tatva-Cafe
HTML and CSS cafe wesbite

-> Download raw file 
-> Open in Visual Studio Code

Go to:
Cmd + F: menuData 

Should look like: 

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
      { title: 'Poori', items: [
        { name: 'Poori', price: '$7.77' },
        { name: 'Dal', price: '$7.77' },
        { name: 'Kurma', price: '$7.77' },
        { name: 'Chole', price: '$8.00' },
        { name: 'Aam Ras', price: '$8.77' },
        { name: 'Paneer', price: '$8.77' },
      ]},

    .........etc...
/// then the user can change the prices manually 
    
