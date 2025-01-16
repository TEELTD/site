<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trust Energy And Engineering Limited</title>
    <link rel="icon" type="image/jpeg" href="/mnt/data/favicon.jpg">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #141414;
            background-image: url('https://images.unsplash.com/photo-1616014980403-78eff61bca4f?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            color: white;
        }
        header {
            background-color: #e50914;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 1.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #141414;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 1rem;
        }
        nav a:hover {
            color: #e50914;
        }
        .container {
            padding: 50px 20px;
            text-align: center;
        }
        .container h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .container p {
            font-size: 1.2rem;
            line-height: 1.6;
        }
        footer {
            background-color: #141414;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: #222;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
        }
        .contact-form button {
            background-color: #e50914;
            color: white;
            border: none;
            padding: 15px 20px;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #b20710;
        }
        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
            margin-top: 20px;
        }
        .photo-gallery img {
            width: 200px;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
            cursor: pointer;
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            justify-content: center;
            align-items: center;
        }
        .modal img {
            max-width: 90%;
            max-height: 90%;
            border-radius: 5px;
        }
        .modal:target {
            display: flex;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Trust Energy BD</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#photos">Photos</a>
        <a href="#contact">Contact</a>
    </nav>

    <div id="home" class="container">
        <h2>Home</h2>
        <p>Your trusted partner for energy solutions in Bangladesh.</p>
    </div>

    <div id="about" class="container">
        <h2>About Us</h2>
        <p>Trust Energy BD is dedicated to providing sustainable and innovative energy solutions to meet your needs.</p>
    </div>

    <div id="services" class="container">
        <h2>Our Services</h2>
        <ul style="list-style: none; padding: 0;">
            <li style="margin: 10px 0;">✔ Renewable Energy Consulting</li>
            <li style="margin: 10px 0;">✔ Solar Panel Installation</li>
            <li style="margin: 10px 0;">✔ Energy Efficiency Audits</li>
        </ul>
    </div>

    <div id="photos" class="container">
        <h2>Photos</h2>
        <div class="photo-gallery">
            <a href="#modal1"><img src="https://via.placeholder.com/200" alt="Photo 1"></a>
            <a href="#modal2"><img src="https://via.placeholder.com/200" alt="Photo 2"></a>
            <a href="#modal3"><img src="https://via.placeholder.com/200" alt="Photo 3"></a>
            <a href="#modal4"><img src="https://via.placeholder.com/200" alt="Photo 4"></a>
            <a href="#modal5"><img src="https://via.placeholder.com/200" alt="Photo 5"></a>
            <a href="#modal6"><img src="https://scontent.fdac142-1.fna.fbcdn.net/v/t39.30808-6/447977846_919698833290193_5163737312525366358_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=cc71e4&_nc_eui2=AeGZ6Icsv0aoYdOKBsT4uNJgRZYsjWWSsgtFliyNZZKyC-i3-rstnP9wog6tStOC_A08k5NUcQDY6eyLolPbAZ4G&_nc_ohc=LiOlkHrp7mAQ7kNvgGR-9ui&_nc_oc=Adj68vtdCB_imX3oDI7pk-aQI1dk5FxmfrZyuR1c_E6l3pcpS3s3Ky8Tk1kA2Tav5Xc&_nc_zt=23&_nc_ht=scontent.fdac142-1.fna&_nc_gid=AW7lFDzhRrElrOJnAWCV32B&oh=00_AYAiuYR8RIKrMfYV03Ta1OYE97sTpIrErIL5f7E-XrQiFA&oe=678EC659" alt="Photo 6"></a>
        </div>
        <div id="modal1" class="modal">
            <img src="https://via.placeholder.com/200" alt="Photo 1">
        </div>
        <div id="modal2" class="modal">
            <img src="https://via.placeholder.com/200" alt="Photo 2">
        </div>
        <div id="modal3" class="modal">
            <img src="https://via.placeholder.com/200" alt="Photo 3">
        </div>
        <div id="modal4" class="modal">
            <img src="https://via.placeholder.com/200" alt="Photo 4">
        </div>
        <div id="modal5" class="modal">
            <img src="https://via.placeholder.com/200" alt="Photo 5">
        </div>
        <div id="modal6" class="modal">
            <img src="https://scontent.fdac142-
