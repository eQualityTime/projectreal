---
layout: page
title: Case 1 
exclude: true
---

<div id="phone">
  <div class="screen">
    <div class="message-container"></div>
  </div>
</div>

<script>
const messages = [
  { text: "Hey, I'm the mod for riverstyles.com's forum - how are you doing?", type: "received" },
  { text: "👍", type: "sent" },
  { text: "Just a heads-up — your account might be in trouble!", type: "received" },
  { text: "wdym", type: "sent" },
  { text: "It's no big deal, you just have to re-athenticate here: https://bit.ly/4dvohrZ", type: "received" },
];

const container = document.querySelector('.message-container');

messages.forEach((msg, index) => {
  setTimeout(() => {
    const div = document.createElement('div');
    div.className = `message ${msg.type}`;
    div.textContent = msg.text;
    container.appendChild(div);
    container.scrollTop = container.scrollHeight;
  }, 1000 * index);
});
</script>


## What are you going to do? 




You receive a message from someone claiming to be a site moderator. They tell you your account is about to be banned and urge you to click a link immediately to fix it. What do you do? 

* [Click The link right away - this sounds serious!](1a.html)

* [Don't click the link and instead check the site's offical help page](1b.html)


Or [Go back to the list of cases](https://www.projectreal.co.uk/casefiles.html) 



