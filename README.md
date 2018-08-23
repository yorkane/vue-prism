# vue-prism
Vue component for Prism

# Installation:
1. save prism.vue into your project
2. npm install prismjs (or yarn add prismjs)

# Usage
### Only [javascript, markup, css, clike] supported in current version. Default with javascript
code as below
## 1 Slot inject
```xml
<prism>{{code}}</prism>
```
## 2 Variable inject
```xml
<prism :code="yourCodeVar"></prism>
```

## 3 Predefine language
```css
<prism language="css">
.class1 {
color: #000;
}
</prism>
```

## 4 Auto language detection
```c
<prism>
for(i = 1, i< 10 , i++) {
  print(i)
}
</prism>
```
