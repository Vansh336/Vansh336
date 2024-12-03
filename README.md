
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  text-align: center;
  width: 90%;
  max-width: 1200px;
}

header h1 {
  font-size: 3em;
  color: #333;
  animation: fadeIn 2s ease-out;
}

header p {
  font-size: 1.2em;
  color: #666;
  animation: fadeIn 2s ease-out 1s;
}

.content {
  display: flex;
  justify-content: space-around;
  margin-top: 50px;
}

.product {
  background-color: white;
  padding: 20px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  transition: transform 0.3s ease-in-out;
}

.product:hover {
  transform: scale(1.05);
}

.product-image {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

.buy-button {
  background-color: #ff6f61;
  border: none;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  margin-top: 15px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.buy-button:hover {
  background-color: #ff4a38;
}

footer {
  margin-top: 50px;
  font-size: 0.9em;
  color: #555;
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
