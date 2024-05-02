---
layout: default
title: Thank You
permalink: forplex/success/
---

<script>
    const urlParams = new URLSearchParams(window.location.search);
    const checkout_session_id = urlParams.get('session_id');
    if (checkout_session_id) posthog.alias(checkout_session_id);
</script>

# Thank you for subscribing!
Your subscription has now been successfully confirmed. Enjoy your music anywhere you go.

<img width="300" src="/assets/images/check_animated.gif" />
