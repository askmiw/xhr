# xhr
监控xhr状态变化

### 应用
```js
<script src="xhr.event.js"></script>
<script>
  window.addEventListener('ajaxReadyStateChange', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxAbort', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxError', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxLoad', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxLoadStart', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxProgress', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxTimeout', function(e) {console.log(e.detail)}
  window.addEventListener('ajaxLoadEnd', function(e) {console.log(e.detail)}
</script>
```
