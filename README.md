## Project

Realtime screen sharing system

## Roles

- User
- Agent

## As a User

- I can initiate a screen sharing session with the agent
- I can stop the screen sharing session with the agent


## As an Agent

- I can request the user to share his/her screen
- I can see everything that the user is doing inside the app.


<body>
  <img src="/static/img/shared.png" class="sharedScreen">
</body>

Script:

$(document).ready(function() {
  setInterval(function() {
    $(".sharedScreen").attr("src", "/static/img/shared.png?v=" + someRandomNumber);
  }, 100);
});

