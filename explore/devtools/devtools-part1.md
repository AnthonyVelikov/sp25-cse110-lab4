1. citylots.json
2. expose.js
3. 239 B
4. 69 ms
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36
6. GitHub.com
7. Thu, 15 Sep 2022 22:44:30 GMT
8. application/json; charset=utf-8
9. function fetchData() {
  fetch('./citylots.json')
}

function init() {
  document.getElementById('fetchData').addEventListener('click', fetchData);
}