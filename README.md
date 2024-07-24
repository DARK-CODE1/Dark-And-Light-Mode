``` JavaScript
window.onload = function () {
  localStorageTheme=localStorage.getItem('theme')

  if (localStorageTheme ==='dark') {
    document.body.classList.add('dark')
  }
};
```