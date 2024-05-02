---
layout: default
title: Thank You
permalink: forplex/success/
---

<script>
    const urlParams = new URLSearchParams(window.location.search);
    const checkout_session_id = urlParams.get('session_id');
    if (checkout_session_id) posthog.alias({alias: checkout_session_id});
</script>

# Thank you for subscribing!
Your subscription has now been successfully confirmed. Enjoy your music anywhere you go.

<img width="300" src="/assets/images/check_animated.gif" />

## Update your watch
Retrieve the subscription status on your watch. Make sure your phone is connected or you have wifi setup on your watch.
![Update Watch Subscription](/assets/images/watch.update.subscription.jpg)