<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Mr. Abhishek Pav - Portfolio</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #74ebd5, #acb6e5);
}

/* HEADER */
.header {
    text-align: center;
    padding: 50px 20px;
    background: linear-gradient(90deg, #ff512f, #dd2476);
    color: white;
}

.profile-pic {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    border: 5px solid #fff;
    object-fit: cover;
    background: white;
}

/* SECTIONS */
.section {
    background: white;
    margin: 25px;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
}

.section h2 {
    color: #ff512f;
    border-left: 6px solid #dd2476;
    padding-left: 10px;
}

ul li {
    font-size: 16px;
    margin: 8px 0;
}

/* BUTTONS */
.buttons {
    text-align: center;
}

.btn {
    display: inline-block;
    margin: 12px;
    padding: 14px 25px;
    border-radius: 30px;
    font-size: 16px;
    color: white;
    text-decoration: none;
    background: linear-gradient(90deg, #36d1dc, #5b86e5);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.btn:hover {
    transform: scale(1.05);
}

.btn.whatsapp {
    background: linear-gradient(90deg, #25D366, #128C7E);
}

/* FOOTER */
.footer {
    text-align: center;
    padding: 12px;
    background: #222;
    color: #ccc;
}
</style>
</head>

<body>

<div class="header">
    <img src="photo.jpg" class="profile-pic">
    <h1>Mr. Abhishek Pav</h1>
    <p>Education & Computer Skills Trainer</p>
</div>

<div class="section">
    <h2>📘 Courses</h2>
    <ul>
        <li>10th Pass (Arts)</li>
        <li>12th Pass (Arts)</li>
        <li>DCA (Diploma in Computer Application)</li>
        <li>Graduation</li>
    </ul>
</div>

<div class="section">
    <h2>💻 Computer Skills</h2>
    <ul>
        <li>MS Word</li>
        <li>MS Excel</li>
        <li>MS PowerPoint</li>
        <li>Basic Programming</li>
    </ul>
</div>

<div class="section">
    <h2>🗣 Languages</h2>
    <ul>
        <li>Hindi</li>
        <li>English</li>
        <li>Bhojpuri</li>
    </ul>
</div>

<div class="section">
    <h2>📞 Contact</h2>
    <p><strong>Phone:</strong> 9302249762</p>
    <p><strong>Email:</strong> abhishek.pawar.9762@gmail.com</p>
</div>

<div class="buttons">
    <a href="resume.pdf" download class="btn">⬇ Download Resume</a>
    <a href="https://wa.me/919302249762?text=Hello%20Abhishek%20Sir" 
       target="_blank" class="btn whatsapp">
       💬 WhatsApp Message
    </a>
</div>

<div class="footer">
    © 2026 Mr. Abhishek Pav | All Rights Reserved
</div>

</body>
</html>
