---
layout: page
title: Case 3 
exclude: true
---


## What are you going to do? 
You’ve been playing games online with someone for a few months. They say they are your age and now they want to chat outside of the game on WhatsApp. They ask for your number. What do you do?

Next step: what do you do now?

* <a href="#" id="random-link">Give them your number - that seems harmless</a>

<script>
  document.getElementById('random-link').addEventListener('click', function(event) {
    event.preventDefault(); // Prevent the default link behaviour

    // List of possible destinations
    const pages = [
      '1asafe',
      '1arisk'
    ];

    // Pick one at random
    const destination = pages[Math.floor(Math.random() * pages.length)];

    // Redirect
    window.location.href = destination;
  });
</script>

* [Ask them to stay on the game chat instead](1b.html)


Or [Go back to the list of cases](https://www.projectreal.co.uk/casefiles.html) 



