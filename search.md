---
layout: page
title: Search
permalink: /search/
sitemap: false
---
<div id="home-search" class="gcse-search" style="border-radius:10">
    <script>
        (function() {
            var cx = '012955325730725765879:ypx3plxhog2';
            var gcse = document.createElement('script');
            gcse.type = 'text/javascript';
            gcse.async = true;
            gcse.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') +
            '//www.google.com/cse/cse.js?cx=' + cx;
            var s = document.getElementsByTagName('script')[0];
            s.parentNode.insertBefore(gcse, s);
        })();
    </script>
    <gcse:search queryParameterName="searchString"></gcse:search>
</div>
