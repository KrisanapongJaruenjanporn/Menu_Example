```js
// Array of menu items
let menuItems = [
  { text: "Home", url: "/" },
  { text: "About", url: "/about" },
  { text: "Contact", url: "/contact" },
  { text: "Profile", url: "/contact" },
];

// Get the menu element
let menu = document.getElementById("menu");

// Loop through the menu items and create list items
for (let i = 0; i < menuItems.length; i++) {
  let menuItem = menuItems[i];
  let li = document.createElement("li");
  let a = document.createElement("a");
  a.href = menuItem.url;
  a.textContent = menuItem.text;
  li.appendChild(a);
  menu.appendChild(li);
}
```
<img width="389" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Menu_Example/assets/121858059/2f0718af-b5ff-4df6-b863-99a21a570b01">
