---
layout: page
title: Case 2 
exclude: true
---

<div id="phone">
  <div class="screen">
    <div class="message-container"></div>
  </div>
</div>

<script>
const messages = [
  { text: "Can’t believe we’ve been chatting for weeks now 😄", type: "received" },
  { text: "Right? Feels like I’ve known you forever lol", type: "sent" },
  { text: "I always look forward to your messages — you’ve got the best style 😍", type: "received" },
  { text: "Haha stop it, you’re gonna make me blush 😅", type: "sent" },
  { text: "Hey, since we get on so well... want to meet up at the shopping centre this weekend?", type: "received" },
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
Someone new comments on your post, complimenting your fashion style. You start chatting to them in a friendly way. After a few weeks, suggest meeting up in person at a shopping centre. What do you do?


* [Say yes and agree to meet them alone](1a.html)

* [Agree to meet but tell a trusted adult and bring someone with you](1b.html)


Or [Go back to the list of cases](https://www.projectreal.co.uk/casefiles.html) 



