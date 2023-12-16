  <style>
    
    body {
      font-family: Arial, sans-serif;
      background-color: #0080ff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      flex-direction: column;
    }
    * {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      line-height: 1.5;
      box-sizing: border-box;
    }

    body {
      height: 100vh;
      background-color: #0080ff;
      padding: 1.5rem;
      margin: 0;
    }

    .container {
      background-color: #0080ff;
      height: 100%;
      width: 100%;
      border-radius: 6px;
      box-shadow: 0 4px 28px rgba(0, 0, 0, 0.25);
      border: 1px solid #1f1f53;
      padding: 1rem;
      overflow: scroll;
    }

    /* Scrollbar Styles */
    ::-webkit-scrollbar {
      width: 10px;
    }

    ::-webkit-scrollbar-track {
      background-color: #0080ff;
    }

    ::-webkit-scrollbar-thumb {
      background-color: #0080ff;
      border-radius: 20px;
    }

    ::-webkit-scrollbar-thumb:hover {
      background-color: #0080ff;
    }

    .snowflake {
      position: fixed;
      width: 10px;
      height: 10px;
      background-color: white;
      border-radius: 50%;
      animation: snowfall 7s linear infinite;
      z-index: 9999; /* Ensures snowflakes appear above content */
      opacity: 1;
    }

    @keyframes snowfall {
      0% {
        transform: translateY(-50vh) rotate(0deg);
        opacity: 0;
      }
      100% {
        transform: translateY(120vh) rotate(360deg);
        opacity: 1;
      }
    }

    h1 {
      animation: colorChange 5s infinite;
    }

    @keyframes colorChange {
      0% {
        color: orange;
      }
      25% {
        color: white;
      }
      50% {
        color: red;
      }
      75% {
        color: white;
      }
      100% {
        color: orange;
      }
    }

    a {
      animation: colorChange 7s infinite;
      text-decoration: wavy;
      color: black;
      font-size: 20px;
      margin-top: 20px;
    }

    c {
      animation: colorChange 12s infinite;
      text-decoration: bold;
      color: whitesmoke;
      font-size: 20px;
      margin-top: 20px;
    }

    b {
      animation: colorChange 5s infinite;
      text-decoration: underline;
      color: whitesmoke;
      font-size: 20px;
      margin-top: 20px;
    }

    body {
      background-size: 100%;
      background-repeat: repeat;
      background-attachment: fixed;
      background-position: center;
      filter: brightness(100%);
    }
  </style>

