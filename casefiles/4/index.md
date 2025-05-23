---
layout: page
title: Case 4 
exclude: true
---



<div id="phone">
  <div class="screen">
    <div class="message-container"></div>
  </div>
</div>

<script>
const messages = [
  { text: "hey it's becky don't geek out", type: "received" },
  { text: "im at a friends house out of town and can't get home", type: "received" },
  { text: "can you snd cash or come n get me or smth without telling my parents", type: "received" },
  { text: "???", type: "sent" },
  { text: "yh its me I borrowed his phone lol", type: "received" },
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

You get an urgent voice message from a friend on a new number. They say they’re stuck in another city and don’t have money to get home, but they don’t want to tell their parents. What do you do?



* [Send them money immediately to help](1a.html)
* [Don’t send the money – check a few things first](1b.html)


Or [Go back to the list of cases](https://www.projectreal.co.uk/casefiles.html) 



