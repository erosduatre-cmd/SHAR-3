# SHAR-3
She/her any pronouns honestly i loveee games and reading
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cool Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="profile-card">
        <div class="image-container">
          <img src="https://placeholder.com" alt="Profile Picture" class="profile-pic">
        </div>
        <h2>Alex Morgan</h2>
        <p class="role">Full-Stack Developer</p>
        <p class="bio">I build cool websites and love writing clean code.</p>
        <div class="buttons">
            <a href="#contact" class="btn">Contact Me</a>
            <a href="#follow" class="btn outline">Follow</a>
        </div>
    </div>
</body>
</html>
body {
    background-color: #0f172a;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.profile-card {
    background-color: #1e293b;
    padding: 30px;
    border-radius: 16px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
    text-align: center;
    width: 300px;
    color: #f8fafc;
    .profile-pic {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    border: 3px solid #38bdf8;
    object-fit: cover;
    margin-bottom: 15px;
}

h2 {
    margin: 10px 0 5px;
    font-size: 1.4rem;
}
.role {
    color: #38bdf8;
    font-size: 0.9rem;
    margin-bottom: 15px;
    font-weight: 600;
}

.bio {
    color: #94a3b8;
    font-size: 0.85rem;
    line-height: 1.4;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 10px;
    justify-content: center;
}
.btn {
    background-color: #38bdf8;
    color: #0f172a;
    padding: 8px 16px;
    border-radius: 8px;
    text-decoration: none;
    font-size: 0.85rem;
    font-weight: bold;
    transition: background 0.2s;
}

.btn:hover {
    background-color: #0ea5e9;
}

.btn.outline {
    background-color: transparent;
    border: 1px solid #38bdf8;
    color: #38bdf8;
}
.btn.outline:hover {
    background-color: rgba(56, 189, 248, 0.1);
}
