intersection(other)<img width="1599" height="1196" alt="974" src="https://github.com/user-attachments/assets/78f443b0-af57-454e-b754-08616451e40a" />
<img width="512" height="512" alt="2297" src="https://github.com/user-attachments/assets/4d54a85d-7794-495a-bad2-fbb8e72bde1e" />
---
title: "Document: all property"
short-title: all
slug: Web/API/Document/all
page-type: web-api-instance-property
status:
  - deprecated
browser-compat: api.Document.all
---

{{APIRef("DOM")}}{{Deprecated_Header}}

The {{DOMxRef("Document")}} interface's read-only **`all`** property returns an {{DOMxRef("HTMLAllCollection")}} rooted at the document node.

Rather than using `document.all` to return an {{DOMxRef("HTMLAllCollection")}} of all the document's elements in document order, you can use {{DOMxRef("Document.querySelectorAll")}} to return a {{DOMxRef("NodeList")}} of all the document's elements in document order:

```js
const allElements = document.querySelectorAll("*");
```

## Value

An {{DOMxRef("HTMLAllCollection")}} which contains every element in the document.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
