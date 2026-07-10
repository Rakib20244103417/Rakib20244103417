<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>University Repositories</title>

<style>
body{
    font-family:Arial,sans-serif;
    background:#f5f5f5;
    margin:40px;
}
h2{
    margin-bottom:5px;
}
p{
    color:#666;
}
.container{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:20px;
}
.card{
    background:#fff;
    border:1px solid #d0d7de;
    border-radius:8px;
    padding:18px;
    transition:.2s;
}
.card:hover{
    box-shadow:0 3px 12px rgba(0,0,0,.12);
}
.card h3{
    margin:0;
    color:#0969da;
}
.card p{
    font-size:14px;
    line-height:1.5;
}
.lang{
    margin-top:15px;
    font-size:14px;
}
.dot{
    height:12px;
    width:12px;
    background:#f34b7d;
    border-radius:50%;
    display:inline-block;
    margin-right:6px;
}
</style>

</head>
<body>

<h2>University Repositories</h2>

<p>My university coursework archive of course materials, assignments and practice.</p>

<div class="container">

<div class="card">
<h3>cse324</h3>
<p>Compiler Design from my 6th semester. Instructor: Md. Nahid Hossian</p>
<div class="lang">
<span class="dot"></span>C++
</div>
</div>

<div class="card">
<h3>cse326</h3>
<p>Microprocessor and Microcontroller Lab from my 6th semester. Instructor: Nourin Khandaker</p>
<div class="lang">
<span class="dot" style="background:#b07219;"></span>Assembly
</div>
</div>

<div class="card">
<h3>cse322</h3>
<p>Artificial Intelligence and Expert System Lab from my 6th semester.</p>
<div class="lang">
<span class="dot" style="background:#3572A5;"></span>Python
</div>
</div>

<div class="card">
<h3>cse342</h3>
<p>Java Advanced Programming from my 5th semester.</p>
<div class="lang">
<span class="dot" style="background:#b07219;"></span>Java
</div>
</div>

<div class="card">
<h3>cse320</h3>
<p>Computer Networks from my 5th semester.</p>
<div class="lang">
<span class="dot" style="background:#b07219;"></span>Java
</div>
</div>

<div class="card">
<h3>cse318</h3>
<p>System Analysis and Design from my 5th semester.</p>
</div>

<div class="card">
<h3>cse302</h3>
<p>Technical Writing and Presentation from my 5th semester.</p>
</div>

<div class="card">
<h3>cse210</h3>
<p>Operating System Lab assignments and projects completed during my 4th semester.</p>
<div class="lang">
<span class="dot"></span>C++
</div>
</div>

</div>

</body>
</html>
