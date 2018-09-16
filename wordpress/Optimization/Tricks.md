- get all handles for scripts and styles loaded
    - then deque those not needed on a page in functions.php
- get handles for all plugins loaded
    - unset plugins not needed on a page in a php file in the mu_plugins folder
- autoptimize plugin
- image analysis on webpage_speed
    - it gives webp options
- defer all js files
- use Query Monitor to analyse all queries and Page Generation time

Some site specific
- woocomerce paypal extension loads paypal script which is very heavy
- mailchimp plugin also fetches a sizeable script