<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aleesha Nadeem | Kaggle Grandmaster</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', sans-serif;
}

body{
    height:100vh;
    background: linear-gradient(-45deg, #0f2027, #203a43, #2c5364, #1c1c1c);
    background-size: 400% 400%;
    animation: gradientMove 10s ease infinite;
    color:white;
    overflow-x:hidden;
}

@keyframes gradientMove{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

.container{
    text-align:center;
    padding-top:80px;
    animation: fadeIn 2s ease-in-out;
}

@keyframes fadeIn{
    from{opacity:0; transform:translateY(40px);}
    to{opacity:1; transform:translateY(0);}
}

h1{
    font-size:50px;
    letter-spacing:2px;
}

.typing{
    font-size:22px;
    margin-top:15px;
    border-right:3px solid white;
    width:0;
    overflow:hidden;
    white-space:nowrap;
    animation: typing 4s steps(40, end) forwards, blink 0.8s infinite;
}

@keyframes typing{
    from{width:0}
    to{width:420px}
}

@keyframes blink{
    50%{border-color:transparent;}
}

.section{
    margin-top:60px;
    animation: fadeUp 2s ease forwards;
}

@keyframes fadeUp{
    from{opacity:0; transform:translateY(30px);}
    to{opacity:1; transform:translateY(0);}
}

.card{
    background: rgba(255,255,255,0.05);
    margin:20px auto;
    padding:25px;
    width:60%;
    border-radius:15px;
    backdrop-filter: blur(10px);
    transition:0.4s;
}

.card:hover{
    transform:scale(1.05);
    box-shadow:0 0 25px rgba(0,255,255,0.6);
}

.highlight{
    color:#00f7ff;
    font-weight:bold;
}

.footer{
    margin-top:50px;
    font-size:14px;
    opacity:0.7;
}
</style>

</head>
<body>

<div class="container">

<h1>Aleesha Nadeem</h1>

<div class="typing">
Kaggle Datasets Grandmaster | Rank #10 Worldwide
</div>

<div class="section">

<div class="card">
<h2>🚀 About Me</h2>
<p>
BSCS Student passionate about 
<span class="highlight">Data Science</span>, 
<span class="highlight">Machine Learning</span>, and 
<span class="highlight">AI Product Building</span>.
</p>
</div>

<div class="card">
<h2>🏆 Achievements</h2>
<p>
Kaggle Datasets Grandmaster <br>
Ranked #10 Worldwide <br>
Multiple Trending Datasets
</p>
</div>

<div class="card">
<h2>🛠 Tech Stack</h2>
<p>
Python | SQL | C++ <br>
Pandas | NumPy | Scikit-learn <br>
Git | GitHub | MySQL
</p>
</div>

<div class="card">
<h2>🎯 Vision</h2>
<p>
Building scalable AI systems with global impact.
</p>
</div>

</div>

<div class="footer">
© 2026 Aleesha Nadeem | Future AI Founder
</div>

</div>

</body>
</html>
