# happy-birthday-sufi
Birthday webpage for Sufi
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Sufi ❤</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html, body {
      height: 100%;
      width: 100%;
      font-family: 'Segoe UI', sans-serif;
      overflow: hidden;
    }

    .page {
      position: absolute;
      width: 100%;
      height: 100%;
      transition: opacity 1s ease;
    }

    .page1 {
      background: url('data:image/jpeg;base64,') no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      backdrop-filter: brightness(0.7);
    }

    .page1 h1 {
      font-size: 48px;
      color: white;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.6);
      margin-bottom: 20px;
      animation: fadeInDown 2s ease;
    }

    .open-btn {
      padding: 14px 28px;
      background-color: #ff4d6d;
      border: none;
      border-radius: 8px;
      color: white;
      font-size: 18px;
      cursor: pointer;
      box-shadow: 0 4px 20px rgba(0,0,0,0.3);
      transition: background 0.3s;
    }

    .open-btn:hover {
      background-color: #e63950;
    }

    .page2 {
      background: linear-gradient(to bottom, #fff0f5, #ffe4e1);
      padding: 40px;
      overflow-y: auto;
      display: none;
      flex-direction: column;
      align-items: center;
    }

    .decor {
      font-size: 50px;
      margin: 10px;
    }

    .message-box {
      max-width: 700px;
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.1);
      font-size: 18px;
      color: #333;
      line-height: 1.6;
      white-space: pre-wrap;
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

<div class="page page1" id="page1">
  <h1>Happy Birthday to You, Sufi ❤</h1>
  <button class="open-btn" onclick="openMessage()">Open Your Surprise</button>
</div>

<div class="page page2" id="page2">
  <div class="decor">🌹🍫❤️</div>
  <div class="message-box">
    🎉 Happy Birthday to you Sufi ❤🫶🏻

    Hi, today is your birthday and I just wanted to wish you a happy birthday and I hope this year treats you well.

    I just want to say thank you for the part you played in my life. You were my first one I could call my best close and close friend (best girlfriend). You’re the longest one jo sanga maile aafno relation Tikaya.

    Soch ta thiya k tmy lai ni girlfriend banam vanera. You were the first one — the one I could SMS/call at any point and you’d always answer.

    The first one I laughed the hardest with. Remember those nights on the phone for hours?

    It’s been a little over 5 months since we stopped talking properly — just because of me. That doesn’t mean I’ve forgotten about you or that I no longer care.

    Truth is, I still do. I stalk your account every day and every night to see if you’re okay.

    But even though everything’s changed, I just want you to know:
    I’m still here.
    I just miss your presence.
    I miss you so much.

    I know you don’t want me, but your face tells me there’s something you can’t say.

    I don’t want to hurt you on your birthday — maybe this will be my last message for you. I don’t know if you’ll remember this or not…

    *The moon is beautiful, isn’t it?*

    And I don’t want any other girl except you because you were my last, last and only life partner I ever wanted.

    You were my happiness, my caring partner, my everything.

    If in this world it will be possible to come back — I will always be waiting for you… ❤

    Maybe you won’t believe I wrote this, but yes… I did.

    I could send it or not — I don’t know. But here it is 🫶🏻

    Once again, Happy Birthday to You, Sufi ❤
  </div>
  <div class="decor">💖🌹🍫</div>
</div>

<script>
  function openMessage() {
    document.getElementById('page1').style.display = 'none';
    document.getElementById('page2').style.display = 'flex';
  }
</script>

</body>
</html>
.page1 {
  background: url('data:image/jpeg;base64,') no-repeat center center;
  background-size: cover;
  height: 100vh;
  /* other styles */
}
<style>
.page1 {
  background: url('your-image-url.jpg') no-repeat center center;
  background-size: cover;
  height: 100vh;
  /* other styles */
}
</style>
