# ez-toast
Toast notifications, without all the bagel.

```javascript
// Can be called with or without new operator
Toast(message: string, className: string, time: integer);
```

## Basic Usage
```javascript
import { Toast } from `Path to Toast.js`;

yourButtonElement.addEventListener('click', () => {
  Toast('You Clicked My Button!');
});
```
