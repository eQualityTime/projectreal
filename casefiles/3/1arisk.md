---
layout: page
title: Case 3 
exclude: true
---


*   They message you on WhatsApp.
*   At first, they just  chat about the game.
*   But soon, they start asking more personal questions – where you live, what school you go to.

Next step: what do you do now?

* [Keep chatting and answer their questions](1ariska.html)

* <a href="#" id="random-link">Keep chatting but avoid answering personal questions</a>

<script>
  document.getElementById('random-link').addEventListener('click', function(event) {
    event.preventDefault(); // Prevent the default link behaviour

    // List of possible destinations
    const pages = [
      '1ariskbrisk',
      '1ariskbsafe'
    ];

    // Pick one at random
    const destination = pages[Math.floor(Math.random() * pages.length)];

    // Redirect
    window.location.href = destination;
  });
</script>

* [Tell a trusted adult and block the person](1ariskc.html) 


Or [go back to the start](index.html) 
