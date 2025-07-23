---
permalink: /about/
title: "Coin Example"
---

<h1>Quantum Coin Flipping in Voting Systems</h1>

<p>This project explores how quantum coin flipping protocols can bring fairness and security to modern digital voting systems.</p>

<h2>🧠 The Idea</h2>
<p>Quantum coin flipping allows two parties to generate a random outcome (heads/tails) without either being able to cheat. This can help:</p>
<ul>
  <li>Secure random choices in online elections</li>
  <li>Prevent vote manipulation</li>
  <li>Guarantee fairness in consensus</li>
</ul>

<h2>🎮 Simulate the Flip</h2>
<button onclick="flipCoin()">Flip the Coin</button>
<p id="result" style="font-size: 24px;"></p>

<script>
  function flipCoin() {
    const result = Math.random() < 0.5 ? "🪙 Heads (|0⟩)" : "🪙 Tails (|1⟩)";
    document.getElementById("result").innerText = result;
  }
</script>

<h2>📚 Learn More</h2>
<ul>
  <li><a href="https://quantum.country/qcvc">Quantum Coin Flipping Explained</a></li>
  <li><a href="https://arxiv.org/abs/quant-ph/9906108">Blum's Coin Flipping Protocol</a></li>
</ul>
