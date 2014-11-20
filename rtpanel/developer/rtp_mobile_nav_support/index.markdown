---
author: manish.songirkar
comments: false
date: 2014-02-07 11:12:54+00:00
layout: page
slug: rtp_mobile_nav_support
title: rtp_mobile_nav_support
wordpress_id: 57108
---

Support for mobile navigation style. default is `return " rtp-mobile-nav";`. If don't want to show mobile navigation style then use `return "";` in following code.

    
    function custom_rtp_mobile_nav_support() {
        return " rtp-mobile-nav";
    }
    add_filter( 'rtp_mobile_nav_support', 'custom_rtp_mobile_nav_support' );
