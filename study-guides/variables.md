# Variables
- Since there are no attributes attached to this element, no `id` or `class` name, this eliminates the use of the `getElementById` method.
- We can only use the `querySelector` or `querySelectorAll` method. However, since there is only a single instance of a `p` element, we will elect to use the `querySelector` method with the **element selector** associated with its tag name `p`.

```javascript
const pElem = document.querySelector('p');
```

Notice that we use either **single or double quotation marks** as a parameter to the `querySelector` method.