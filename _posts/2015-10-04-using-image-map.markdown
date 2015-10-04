---
layout: post
title:  "Using Image Map"
date:   2015-10-04
---

<p class="intro"><span class="dropcap">H</span>ey There! Today I am going to discuss about image maps. We all know how to make an image clickable and redirect it to a link. But, have you ever thought if we want only a part of an image clickable or many different parts of an image clickable and redirect them to different links. This can be acheived with the help of image map.</p>

<p>Suppose we have the following Batman VS Superman image and we want that any one who clicks on the batman section should be redirected to batman and the superman section should redirect to superman.</p>

<img src="http://extrasline.com/wp-content/uploads/2014/08/Batman-V-Superman-2016-640x346.jpg" usemap="#metroid">

<p>This can be acheived through the following code:</p>

<map name="metroid" id="metroid">
        <area shape="rect" coords="0,0,320,345" href="https://en.wikipedia.org/wiki/Batman" alt="batman" title="I AM BATMAN!!">
        <area shape="rect" coords="320,0,640,346" href="https://en.wikipedia.org/wiki/Superman" alt="superman" title="SUPERMAN!!!">
</map>

<script src="https://gist.github.com/kspmayank/1b484b1ed261a423378e.js"></script>
