---
# the default layout is 'page'
icon: fas fa-info-circle
order: 1
---

<html>
<head>
<style>
  /* The container for the entire timeline */
  .timeline {
    position: relative;
    max-width: 600px;
    margin: 20px auto;
    font-family: sans-serif;
  }

  /* The vertical line */
  .timeline::after {
    content: '';
    position: absolute;
    width: 2px;
    background-color: #ddd;
    top: 0;
    bottom: 0;
    left: 80px; /* Aligns the line next to the dates */
  }

  /* Container for each individual entry */
  .container {
    padding: 10px 40px;
    position: relative;
    background-color: inherit;
    margin-left: 80px; /* Pushes text to the right of the line */
  }

  /* The dots on the timeline */
  .container::after {
    content: '';
    position: absolute;
    width: 12px;
    height: 12px;
    left: -7px; /* Centers the dot on the line */
    background-color: #fff;
    border: 2px solid #007bff;
    top: 15px;
    border-radius: 50%;
    z-index: 1;
  }

  /* The Date labels */
  .date {
    position: absolute;
    left: -90px;
    top: 13px;
    width: 70px;
    text-align: right;
    font-weight: bold;
    color: #555;
    font-size: 0.9em;
  }

  /* The text content */
  .content {
    font-size: 14px;
    line-height: 1.4;
    color: #333;
  }
</style>
</head>
<body>

<div class="timeline">  
  <div class="container">
    <div class="date">2026</div>
    <div class="content">First prototype completed and sent for user testing.</div>
  </div>

  <div class="container">
    <div class="date">2024</div>
    <div class="content"><a href="https://arxiv.org/abs/2505.01370">Engineering CSS surgery: compiling any CNOT in any code</a>, Clément Poirson, Joschka Roffe, Robert I. Booth</div>
  </div>
</div>

</body>
</html>