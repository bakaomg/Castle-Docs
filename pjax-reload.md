## PJAX
- 重载刷新后失效的JS

## 部分示例
### APlyaer
```javascript
loadMeting();
```

### 百度统计
```javascript
if (typeof _hmt !== 'undefined'){
 _hmt.push(['_trackPageview', location.pathname + location.search]);
}  
```

### 谷歌统计
```javascript
if (typeof ga !== 'undefined'){
 ga('send', 'pageview', location.pathname + location.search);
}
```

### Prism.js
```javascript
if (typeof Prism !== 'undefined') {
 Prism.highlightAll(true,null);
}
```

### MathJax
```javascript
if (typeof MathJax !== 'undefined'){
 MathJax.Hub.Queue(["Typeset",MathJax.Hub]);
}
```