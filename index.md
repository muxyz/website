---
layout: default
title: "Home"
description: "Building blocks for life"
---
<center>
  <a href="https://chat.mu.xyz"><button style="height: 50px; width: 100px; cursor: pointer;">Chat</button></a>
  <a href="https://news.mu.xyz"><button style="height: 50px; width: 100px; cursor: pointer;">News</button></a>
  <a href="https://pray.mu.xyz"><button style="height: 50px; width: 100px; cursor: pointer;">Pray</button></a>
  <br><br>
  <h3>Donate</h3>
  <p>ETH</p>
  <img src="images/Screenshot_20240222-185412.png" style="width: 200px; height: auto;" >
  <p id="address" style="word-wrap: break-word; max-width: 300px;">0x36C34859bcf9DCC706f1fE2D5789f21f51495499</p>
  <a href="#address" onclick="cp()">Copy</a>
</center>
<script>
  function cp() {
    var copyText = document.getElementById("address");

    // Select the text field
    copyText.select();
    copyText.setSelectionRange(0, 99999); // For mobile devices

     // Copy the text inside the text field
    navigator.clipboard.writeText(copyText.value);
    return false;
  }
</script>
