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
  { text: "Hey, it’s Becky. Don’t freak out.", type: "received" },
  { text: "I’m at some guy’s house in another city. I don’t have any money to get home 😞", type: "received" },
  { text: "Please don’t tell my parents. Can you send me something?", type: "received" },
  { text: "Wait… is this really you? This isn’t your number.", type: "sent" },
  { text: "Yeah it’s me, I JUST  borrowed a phone. Please, I’m really stuck.", type: "received" },
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



