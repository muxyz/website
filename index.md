---
layout: default
title: "Community"
description: "Building blocks for life"
---
<center>
  <div class="apps">
  <a href="https://chat.mu.xyz">
    <button style="height: 60px; width: 100px; cursor: pointer;">
      <img class="img" src="/images/icons/chat.png">
      <br>Chat
    </button>
  </a>
  <a href="https://news.mu.xyz">
    <button style="height: 60px; width: 100px; cursor: pointer;">
      <img class="img" src="/images/icons/news.png">
      <br>News
    </button>
  </a>
  <a href="https://pray.mu.xyz">
    <button style="height: 60px; width: 100px; cursor: pointer;">
      <img class="img" src="/images/icons/pray.png">
      <br>Pray
    </button>
  </a>
  </div>
  <br><br>
  <h3>Donate</h3>
  <p>ETH</p>
  <img src="images/Screenshot_20240222-185412.png" style="width: 100px; height: auto;" >
  <p id="address" style="display: none;">0x36C34859bcf9DCC706f1fE2D5789f21f51495499</p>
  <br>
  <a href="#address" onclick="cp()">Copy Address</a>
</center>
<script>
  function cp() {
    var copyText = document.getElementById("address");

     // Copy the text inside the text field
    navigator.clipboard.writeText(copyText.innerTexta);
    return false;
  }
</script>
