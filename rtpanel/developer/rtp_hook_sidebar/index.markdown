---
title: rtp_hook_sidebar
---

### Description


This hook adds content after the end of #content, also it holds the sidebar.


### Example



    
    function custom_rtp_hook_sidebar() { ?>
    <p>This content is after #content.</p><?php
    }
    add_action( 'rtp_hook_sidebar', 'custom_rtp_hook_sidebar' );
