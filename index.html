<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Should I Buy Today?</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .transition-all {
      transition: background-color 0.5s, color 0.5s;
    }
  </style>
</head>
<body id="body" class="min-h-screen flex items-center justify-center transition-all">

  <div class="text-center space-y-6">
    <h1 id="title" class="text-4xl font-bold drop-shadow-lg">
      Should I Buy <span id="ticker" class="underline">NVDA</span> Today?
    </h1>

    <button 
      id="fetchBtn"
      class="px-6 py-3 bg-white hover:bg-gray-100 text-black font-semibold rounded-lg shadow-md transition"
    >
      Get Recommendation
    </button>

    <p id="result" class="text-2xl font-medium mt-4"></p>
  </div>

  <script>
    const tickers = [
      { symbol: "NVDA", color: "#76B900" },  // Nvidia green
      { symbol: "MSFT", color: "#0078D4" },  // Microsoft blue
      { symbol: "TSLA", color: "#E31937" },  // Tesla red
      { symbol: "AAPL", color: "#A2AAAD" }   // Apple silver/gray
    ];

    let index = 0;
    const tickerEl = document.getElementById("ticker");
    const titleEl = document.getElementById("title");
    const bodyEl = document.getElementById("body");

    function updateTicker() {
      const { symbol, color } = tickers[index];
      tickerEl.textContent = symbol;
      bodyEl.style.backgroundColor = color + "22";  // soft background
      titleEl.style.color = color;
      index = (index + 1) % tickers.length;
    }

    setInterval(updateTicker, 2000);  // update every 2 seconds
    updateTicker(); // initial call

    // API 통신 로직
    document.getElementById("fetchBtn").addEventListener("click", async () => {
      const resultEl = document.getElementById("result");
      const currentSymbol = tickerEl.textContent;
      resultEl.textContent = "Loading...";

      try {
        const response = await fetch(`https://your-gcp-api.com/${currentSymbol.toLowerCase()}`);
        const data = await response.json();
        resultEl.textContent = data.recommendation || "No recommendation received.";
      } catch (e) {
        resultEl.textContent = "Error fetching data.";
        console.error(e);
      }
    });
  </script>

</body>
</html>
