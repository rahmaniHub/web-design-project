font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #111;
  color: #fff;
  text-align: center;
}

header {
  background: url('https://example.com/ford.jpg') no-repeat center center/cover;
  padding: 100px 20px;
}

header h1 {
  font-size: 3em;
  margin-bottom: 10px;
}

.btn {
  background: #ff5500;
  color: white;
  padding: 12px 25px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
}

section {
  padding: 60px 20px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  font-size: 1.2em;
  margin: 10px 0;
}

form input, form button {
  padding: 10px;
  margin: 10px;
  width: 80%;
  max-width: 300px;
}

form button {
  background: #28a745;
  color: white;
  border: none;
  border-radius: 5px;
}

footer {
  background: #000;
  padding: 20px;
}
```
✅ *JavaScript (script.js):*
```javascript
document.getElementById('orderForm').addEventListener('submit', function(e) {
  e.preventDefault();
  document.getElementById('response').textContent = "Thank you! We'll contact you soon.";
});
```
