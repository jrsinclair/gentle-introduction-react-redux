---

# A Gentle Introduction to React and Redux

---

## Brace yourselves

---

![ ](https://dl.dropboxusercontent.com/s/ghfbp0gyanso6fv/2017-06-28%20at%2017.09.png)

---

```html
<button class="SlideBtn is-active js-SlideBtn">
    <span class="SlideBtn-knob"></span>
</button>
```

```javascript
$('.js-SlideBtn').on('click', (evt) => {
    $(evt.currentTarget).toggleClass('is-active');
});
```
