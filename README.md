<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <style>
        /* Adding some animation effects */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1 {
            animation: fadeIn 2s ease-in-out;
        }

        h3 {
            animation: slideIn 2s ease-in-out;
        }

        /* Keyframes for the animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin: 10px 0;
            font-size: 18px;
            animation: fadeIn 2s ease-in-out;
        }

        p img {
            transition: transform 0.3s ease;
        }

        p img:hover {
            transform: scale(1.1);
        }

        /* Animating the icons */
        .icon-container a {
            margin: 0 15px;
            display: inline-block;
            animation: fadeIn 2s ease-in-out;
        }

        .icon-container img {
            width: 40px;
            height: 40px;
            transition: transform 0.3s ease;
        }

        .icon-container img:hover {
            transform: scale(1.2);
        }

        /* Stats animation */
        .stats-container {
            animation: fadeIn 2s ease-in-out;
        }

        .github-stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <h1>Hi, This is Amit</h1>
    <h3>Passionate about learning technologies, interested in electronics, Arduino, Raspberry Pi, microcontrollers, and embedded systems.</h3>
    
    <p align="left">
        <img src="https://komarev.com/ghpvc/?username=asraghuvanshi52&label=Profile%20views&color=0e75b6&style=flat" alt="asraghuvanshi52" />
    </p>
    
    <p align="left">
        <a href="https://github.com/ryo-ma/github-profile-trophy">
            <img src="https://github-profile-trophy.vercel.app/?username=asraghuvanshi52" alt="asraghuvanshi52" />
        </a>
    </p>

    <ul>
        <li>🌱 I’m currently exploring more about <strong>Swift</strong></li>
        <li>💬 Ask me about <strong>Java, Swift, Android</strong></li>
        <li>✉️ You can reach me at <strong>asraghuvanshi52@gmail.com</strong></li>
    </ul>

    <h3>Connect with me:</h3>

    <h3>Languages and Tools:</h3>
    <div class="icon-container">
        <a href="https://firebase.google.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" />
        </a>
        <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" />
        </a>
        <a href="https://www.linux.org/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" />
        </a>
        <a href="https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/apple_objectivec/apple_objectivec-icon.svg" alt="objectivec" />
        </a>
        <a href="https://postman.com" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" />
        </a>
        <a href="https://redux.js.org" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" />
        </a>
        <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" />
        </a>
        <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" />
        </a>
        <a href="https://webpack.js.org" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/d00d0969292a6569d45b06d3f350f463a0107b0d/icons/webpack/webpack-original-wordmark.svg" alt="webpack" />
        </a>
    </div>

    <div class="github-stats">
        <div class="stats-container">
            <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=asraghuvanshi&show_icons=true&locale=en&layout=compact" alt="asraghuvanshi" />
        </div>

        <div class="stats-container">
            <img align="center" src="https://github-readme-stats.vercel.app/api?username=asraghuvanshi&show_icons=true&locale=en" alt="asraghuvanshi" />
        </div>

        <div class="stats-container">
            <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=asraghuvanshi&" alt="asraghuvanshi" />
        </div>
    </div>

</body>

</html>
