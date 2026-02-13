# For-my-Valentine-
A little surprise for my love 😍!!
<!DOCTYPE html>
<html>
<head>
    <title>For My Fizza ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            font-family: 'Georgia', serif;
            text-align: center;
            color: white;
            overflow: hidden;
        }

        .container {
            margin-top: 100px;
            padding: 20px;
        }

        h1 {
            font-size: 48px;
            animation: fadeIn 3s ease-in-out;
        }

        p {
            font-size: 22px;
            width: 70%;
            margin: 20px auto;
            line-height: 1.6;
            animation: fadeIn 5s ease-in-out;
        }

        button {
            margin-top: 30px;
            padding: 15px 30px;
            font-size: 20px;
            border: none;
            border-radius: 30px;
            background: white;
            color: #ff4d6d;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #ffe6eb;
        }

        .heart {
            position: absolute;
            color: red;
            font-size: 20px;
            animation: float 5s linear infinite;
        }

        @keyframes float {
            from { transform: translateY(100vh); }
            to { transform: translateY(-10vh); }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>

<body>

<div class="container">
    <h1>For My Dearest Fizza ❤️</h1>

    <p>
        Fizza,  
        Before you, life was just days passing by.  
        But after you, every moment became a memory worth keeping.  
        Your smile feels like peace to my restless heart.  
        Your voice feels like home to my wandering soul.
    </p>

    <p>
        I don’t know what I did to deserve someone as pure,  
        as kind, and as beautiful as you.  
        But I promise this —  
        I will always respect you, protect you,  
        and love you with honesty and loyalty.
    </p>

    <p>
        You are not just my Valentine…  
        You are my today, my tomorrow,  
        and every dream I pray for. ❤️
    </p>

    <button onclick="showMessage()">Click Here ❤️</button>
</div>

<script>
    function showMessage() {
        alert("Fizza ❤️ I Love You More Than Words Can Ever Explain. Forever Yours.");
    }

    function createHeart() {
        const heart = document.createElement("div");
        heart.classList.add("heart");
        heart.innerHTML = "❤️";
        heart.style.left = Math.random() * 100 + "vw";
        heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
        document.body.appendChild(heart);

        setTimeout(() => {
            heart.remove();
        }, 5000);
        }

    setInterval(createHeart, 300);
</script>

</body>
</html>
