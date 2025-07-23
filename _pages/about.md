---
permalink: /about/
title: "About"
---

Tempor velit sint sunt ipsum tempor enim ad qui ullamco. Est dolore anim ad velit duis dolore minim sunt aliquip amet commodo labore. Ut eu pariatur aute ea aute excepteur laborum. Esse ea esse excepteur minim mollit qui cillum excepteur ex dolore magna. Labore deserunt fugiat incididunt incididunt sint ea. Consequat dolore aute laboris quis proident quis non et est consectetur ex eiusmod sit culpa.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

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
