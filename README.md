<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yashh</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Inter,sans-serif;
}

body{
    min-height:100vh;
    background:#0d1117;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
}

.container{
    text-align:center;
}

h1{
    font-size:3rem;
    margin-bottom:10px;
}

.subtitle{
    color:#9ca3af;
    margin-bottom:30px;
}

.links{
    display:flex;
    justify-content:center;
    gap:15px;
    flex-wrap:wrap;
}

.btn{
    text-decoration:none;
    color:white;
    padding:14px 24px;
    border-radius:14px;
    font-weight:600;
    transition:.3s;
    display:flex;
    align-items:center;
    gap:8px;
}

.portfolio{
    background:linear-gradient(135deg,#9333ea,#7c3aed);
}

.linkedin{
    background:linear-gradient(135deg,#0A66C2,#0077b5);
}

.contact{
    background:linear-gradient(135deg,#ff6b35,#ff8a00);
}

.btn:hover{
    transform:translateY(-4px);
    box-shadow:0 10px 30px rgba(255,255,255,.15);
}
</style>
</head>

<body>

<div class="container">

    <h1>Hi, I'm Yashh 👋</h1>

    <p class="subtitle">
        Frontend & Full-Stack Developer from India <br>
        Building modern web applications with React & JavaScript.
    </p>

    <div class="links">

        <a href="https://yashh-links.vercel.app" class="btn portfolio">
            🌐 Portfolio
        </a>

        <a href="https://www.linkedin.com/in/yashh-penchi" class="btn linkedin">
            💼 LinkedIn
        </a>

        <a href="mailto:iyash321@gmail.com" class="btn contact">
            📧 Contact
        </a>

    </div>

</div>

</body>
</html>
