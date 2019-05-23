---
title: Building a React Based Portfolio Index Site
date:
description:
---

*After playing around with Gatsby.js to rebuild my web presence, I started looking more into the JAMstack idea/community and I realized I needed to brush up and practice on my React/JavaScript site generation knowledge. With that I mind, I am setting out to convert a basic html generated portfolio site to one built with react components. Follow along with this series. This site will be styled using Materialize.css*

You can view what the final product we are building towards looks like [here](https://00e9e64bac211982abf0c9efd8643ec6ececfb7661f4f639e8-apidata.googleusercontent.com/download/storage/v1/b/simple-html/o/index.html?qk=AD5uMEvkAYOsuF-qksWnmI-eEvvhDen-XjBG5cDQZKxMn8FXdT9ZM8IXIceOJe9IwRtSyokU0QABxJeoOeqKOHtv7oHni4RMejJOoAOzflPpE2YDFyrcs4I4ydg7Tnh2-CVFDHScBZT0zB5HyRiKF-03crsyf2VCroipaLiCwrDwOLHhV3hBO87egaKQueeMoQgDANvG3sFu-MzLNxL06a2adpDxpUGUog3BxA0djpHgmX2Pz81i9bGBq6r_Uv0lFHdMAFag3EHc7mpbmKMLIybW3WQLfBgfyw6GxNnj2kAVU-_TL23iY3D-VDQ74j4kXj4OUq-9svQnQdnh9PtjwpqjTaHAUIcNR_W6DIJQqf3_t0Sotf2oqiVgc8L8K3JsmljsQh8DKKvlANv_nl18pEUfKXzcuSeqxukW-lZS_Tl4HPq61avr_QsPb-yl_QoFO0tpohCaeGV-CnDA1TvBN8XmydPP8HJGjqga3z7om7tdf1RK0Ti-2Zrr1OXXInV2kFsBgFYpygb39yJXIpSZMAtf_xiczv2CO7xmuU_yk4VeQeQNQVfDOMwLgjXaCq7v8HX3YtCMIo54Os3L3Nkj3j1FaDXbS65SAtGIJNCVAx2gs2to79p4riO4yvZY43BgGqqm9eoHC_4Ou6QxvX78HCyllSATORc5NQZOBz8och_OQPEbSCTCbo88BMriVkMdE6mxqGSUQVZYq4_6GSEfPQltN8GgAeYA6HLBYR9zkxcFhL32ouZn0h4NtWG5c-y6g5_iUkJzI-N4). The code repo can be found on GitHub [here](https://github.com/jristow/react-conversion-tutorial). Head on over to the repo and open up the index.html file in your favorite code editor to begin.

# Part One: Setting up a common header
When we look at the overall layout of the page, we can see where certain parts of the page would be repeated across any other pages of this site. The easiest one is the header part. Instead of repeating ourselves by putting the raw header code in every page of this website, why don't we build out a header component that can be imported into any other page we build?

## Converting from HTML to JavaScript

