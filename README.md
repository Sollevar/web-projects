# ***Web-верстка***
## Информация о библиотеках используемых в работах
---
### **Для реализации слайдера https://swiperjs.com/**
```javascript
 const swiper = new Swiper('.swiper', {
  slidesPerView: 1,
  slidesPerGroup: 1,
  loop:true,
  pagination: {
    el: '.swiper-pagination',
    type: 'bullets',
    clickable:true,
  },
})
```
---
### **Для реализации аккордеон https://github.com/michu2k/Accordion**
```javascript
new Accordion('.accordion-list', {
	elementClass: 'accordion',
	triggerClass: 'accordion__control',
	panelClass: 'accordion__content',
	activeClass: 'accordion--active'
});
```
---
## Оба сайта адаптивны и прекрасно функционируют на любых устройствах