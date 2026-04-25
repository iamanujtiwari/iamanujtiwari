<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Step by Step Typewriter</title>

  <style>
    body {
      background: white;
      color: black;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .container {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .typewriter {
      font-size: 22px;
      font-weight: bold;
      white-space: nowrap;
      overflow: hidden;
      width: 0;
      border-right: 2px solid black;
      animation: typing 2s steps(30, end) forwards;
    }

    .line1 {
      animation-delay: 0s;
    }

    .line2 {
      animation-delay: 2.2s;
    }

    .line3 {
      animation-delay: 4.4s;
    }

    .line4 {
      animation-delay: 6.6s;
    }

    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
        border-right: none;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="typewriter line1">Hi, I'm Anuj Tiwari</div>
    <div class="typewriter line2">Building projects</div>
    <div class="typewriter line3">Learning daily</div>
    <div class="typewriter line4">Growing as a developer 🚀</div>
  </div>

</body>
</html>
