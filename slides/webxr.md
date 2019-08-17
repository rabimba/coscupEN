

<!-- .slide: data-background="resources/textures/background-radial.jpeg" -->

<h2>WebXR: Expanding WebVR to Support MR</h2>
<p>Web Platform: WebVR, <span class="blue">Browsers (Custom, Servo, FF, ...)</span>, WebAssembly</p>
<p>Native AR Platforms: ARKit, ARCore, Vision SDKs, ...</p>
<p>MR Requirements: Augmented and Virtual Realities, Anchors, <span class="blue"><br>Geospatial References, Custom Computer Vision</span>.</p>
<p><span class="green">Services for Persistence, Search, Social Sharing, Cloud CV/ML,... </span></p>
<br>
<p>https://github.com/immersive-web/webxr<br>https://github.com/immersive-web/webxr-polyfill <br>(_and more soon_)</p>

------

<!-- .slide: data-background="resources/textures/home-HoloLens-crop.jpg" -->

<div style="background: rgba(32, 32, 32, 0.5);">

<h1>"Webby" Approach to AR/VR/MR</h1>

<p>Enables some essential capabilities for pervasive social experiences</p>

<ul>
<li> Platform independence: you use the device of your choice,<br>taking advantage of platform capabilities</li>
<li> New approaches to privacy</li>
<li> Ad-hoc social experiences</li>
</ul>
</div>
------
<!-- .slide: data-background-video="media/video/videoplayback.mp4" -->
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<blockquote style="background: rgba(32, 32, 32, 0.5);">
<h3>"Webby" Approach?</h3>
<p>How about creating VR objects using Neural Net?</p>
<!-- <p>@Samuel Snider-Held</p> -->
</blockquote>

------
<!-- .slide: data-background="resources/textures/background-radial.jpeg" -->

<h2>Hubs @ COSCUP?</h2>
<p>Join</p>

<p>https://on.tchspk.rs/coscup</p>
<div class="captioned-image-row">
  <div>
    <img class="plain" data-src="resources/textures/frame.png">

  </div>
</div>

---
<!-- .slide: data-background-video="resources/videos/castle-world-social-groupchat-720p.mp4" -->
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<blockquote style="background: rgba(32, 32, 32, 0.5);">
<h3>Mozilla Social Hubs</h3>
<em>Web-based services for multi-user social experiences<br>with voice, avatars, shared-screens, etc.</em>
<p><em>Secure support for telepresense and mixed AR/VR systems</em></p>
</blockquote>

<!-- NOTES -->

i think the best we are able to say is we intend to try to abstract out large chunks of the hubs experience into reusable libraries. we've already done this on the game networking side, so you can just pull in some libraries from NPM and use the centralized Janus SFU with networked aframe. more stuff we'll be pulling out that seems likely are our interactables, avatars, and overall immersive UX with a cursor + HUD. but too early to say for sure

---
<!-- .slide: data-background-color="#000000" data-background-size="contain" data-background-position="center" data-background-video="resources/videos/ducks-and-physics.mp4" -->
---
<!-- .slide: data-background-color="#000000" data-background-size="contain" data-background-position="center" data-background-video="resources/videos/ar-vr-social-gods-eye.mp4" -->

------
<!-- .slide: data-background-color="#ffffff" data-background="resources/textures/firefox-reality-blog.png" data-background-size="contain" data-background-repeat="no-repeat" -->
---
<!-- .slide: data-background-video="resources/videos/servo-page-3d.mp4" -->
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<blockquote style="background: rgba(32, 32, 32, 0.5);">
<h3>Experiment with XR capabilities in Servo and Gecko</h3>
<em>2D DOM content in 3D, mixed 2D/3D apps</em>
<p><em>XR extensions for CV, new DOM elements, ...</em></p>
</blockquote>
---
<!-- .slide: data-background-video="media/video/xrpaint.mp4" -->
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<blockquote style="background: rgba(32, 32, 32, 0.5);">
<h3>Paint in Real World</h3>
<em>XR Painter</em>
</blockquote>
---
<!-- .slide: data-background-video="resources/videos/playcanvas-scene-720p.mp4" -->
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<blockquote style="background: rgba(32, 32, 32, 0.5);">
<h3>High Performance Graphics with WebGL2</h3>
<em>(here: Playcanvas demo, iMac, Firefox)</em>
<p><em>Experimenting with Vulcan, WebGL extensions, next-gen Web GPU</em></p> 
</blockquote>
