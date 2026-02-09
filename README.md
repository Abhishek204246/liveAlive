* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background:#4190CC;
}

.container {
  width: 100%;
  max-width: 400px;
  padding: 20px;
}

.card {
  background: white;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0px 10px 25px rgba(0, 0, 0, 0.2);
}

.card h2 {
  text-align: center;
  margin-bottom: 8px;
  font-size: 24px;
}

.card p {
  text-align: center;
  color: gray;
  margin-bottom: 20px;
}

.input-group {
  margin-bottom: 15px;
}

.input-group label {
  display: block;
  margin-bottom: 6px;
  font-weight: bold;
}

.input-group input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 8px;
  outline: none;
  font-size: 15px;
}

.input-group input:focus {
  border-color: #2575fc;
}

.row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
  font-size: 14px;
}

.remember {
  display: flex;
  gap: 6px;
  align-items: center;
}

.link {
  text-decoration: none;
  color: #2575fc;
  font-weight: bold;
}

.link:hover {
  text-decoration: underline;
}

.btn {
  width: 100%;
  padding: 12px;
  border: none;
  background: #2575fc;
  color: white;
  font-size: 16px;
  border-radius: 10px;
  cursor: pointer;
  transition: 0.3s;
}

.btn:hover {
  background: #1e5ed8;
}

.signup {
  margin-top: 18px;
  text-align: center;
  font-size: 14px;
}
