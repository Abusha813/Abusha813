<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Abusha813's Profile</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="profile-card">
    <h1>👋 Hi, I’m <span class="username">@Abusha813</span></h1>
    <ul class="profile-info">
      <li>👀 I’m interested in <span class="placeholder">...</span></li>
      <li>🌱 I’m currently learning <span class="placeholder">...</span></li>
      <li>💞️ I’m looking to collaborate on <span class="placeholder">...</span></li>
      <li>📫 How to reach me: <span class="placeholder">...</span></li>
      <li>😄 Pronouns: <span class="placeholder">...</span></li>
      <li>⚡ Fun fact: <span class="placeholder">...</span></li>
    </ul>
    <footer>
      <p>✨ This is a special repository because its <code>README.md</code> appears on your GitHub profile!</p>
    </footer>
  </div>
</body>
</html>

body {
  background-color: #f4f4f9;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  display: flex;
  justify-content: center;
  padding: 40px;
  color: #333;
}

.profile-card {
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  padding: 30px;
  max-width: 600px;
  width: 100%;
}

h1 {
  font-size: 1.8rem;
  margin-bottom: 20px;
}

.username {
  color: #007acc;
  font-weight: bold;
}

.profile-info {
  list-style: none;
  padding: 0;
  margin: 0 0 20px 0;
}

.profile-info li {
  margin-bottom: 10px;
  font-size: 1.1rem;
}

.placeholder {
  font-style: italic;
  color: #555;
}

footer {
  font-size: 0.9rem;
  color: #777;
  border-top: 1px solid #eee;
  padding-top: 15px;
}
