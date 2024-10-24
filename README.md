<h1 id="mushroom-cards-animations">Mushroom Cards Animations</h1>
<img src="https://community-assets.home-assistant.io/original/4X/2/4/7/247cb76d8c3fe0e33d061109ddfd7fc7337ee132.gif"
   alt="Mushroom Chip Animated Scene">
<p> All these animations were shared by <a href="https://community.home-assistant.io/u/rhysb">rhysb</a> on the home assistant community, i thought of compiling them down on a single gist to give more visibility to this.</p>
<p> I highly encourage you to look and like the original post <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily-part-1/388590/3240">click here</a></p>

<h1 id="requirements">Requirements</h1>

<p>All these CSS animations require <a href="https://github.com/thomasloven/lovelace-card-mod">Thomas Lovén’s card_mod</a>. This can be installed via HACS.</p>

<div class="cooked">
   <h2>
      <a name="built-in-mushroom-animations-1"
         class="anchor"
         href="#built-in-mushroom-animations-1"></a>Built-in Mushroom Animations
   </h2>
   <p>There are two built-in animations for Mushroom cards that can be used without specifying any <code>@keyframes</code>. These are <code>spin</code>, which is used for the rotating fan, and <code>pulse</code>, which fades in and out.</p>
   <h4>
      <a name="built-in-spin-animation-changed-2"
         class="anchor"
         href="#built-in-spin-animation-changed-2"></a>Built-in Spin Animation (changed):
   </h4>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="266"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/3/f/d3f53da8f48271dc66c0df4794aa6326d55694d3.gif"
         alt="Mushroom Built-in Spin"
         data-base62-sha1="uf4aGDAEQZ0hcVCLxsTfq8qQBhx"
         width="266"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 266 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details open="">
      <summary>
         Spin Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Spin</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:fan</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">teal</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
      animation: spin 1s linear infinite;
    }
</span></code></pre>
   </details>
   <h4>
      <a name="built-in-pulse-animation-changed-3"
         class="anchor"
         href="#built-in-pulse-animation-changed-3"></a>Built-in Pulse Animation (changed):
   </h4>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="266"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/9/8/2/982a92229da3e076896f8018e99e3b8f3e0fe1a1.gif"
         alt="Mushroom Built-in Pulse"
         data-base62-sha1="lI7MyhWDiIhvdY7UIpS7nuwXmM1"
         width="266"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 266 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Pulse Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:pulse</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Pulse</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
      animation: pulse 2s ease-in-out infinite;
    }
</span></code></pre>
   </details>
   <h2>
      <a name="animated-mushroom-cards-4"
         class="anchor"
         href="#animated-mushroom-cards-4"></a>Animated Mushroom Cards
   </h2>
   <h4>
      <a name="mushroom-media-player-card-unchanged-5"
         class="anchor"
         href="#mushroom-media-player-card-unchanged-5"></a>Mushroom Media Player Card (unchanged):
   </h4>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="131"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/c/e/f/cefb0b16145afb6b47a6a82dfd7cc6ea777fb2b5.gif"
         alt="Mushroom Media Player Card with Animated Icons"
         data-base62-sha1="tx2dr35k0uoXoUjHpd40yzcSWj3"
         width="517"
         height="131"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 131;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Media Player Animated Icons
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-bash" data-highlighted="yes"><span class="hljs-built_in">type</span>: custom:mushroom-media-player-card
entity: media_player.currently_playing
icon: mdi:play
use_media_info: <span class="hljs-literal">true</span>
use_media_artwork: <span class="hljs-literal">false</span>
show_volume_level: <span class="hljs-literal">false</span>
media_controls:
  - play_pause_stop
  - previous
  - next
volume_controls:
  - volume_buttons
  - volume_set
fill_container: <span class="hljs-literal">false</span>
card_mod:
  style: |
   mushroom-shape-icon {
      display: flex;
      {% <span class="hljs-built_in">set</span> media_type = state_attr(config.entity, <span class="hljs-string">'media_content_type'</span>) %}
      {% <span class="hljs-keyword">if</span> media_type == <span class="hljs-string">'tvshow'</span> %}
        --card-mod-icon: mdi:television-classic;
        animation: flicker 1s linear infinite alternate;
      {% <span class="hljs-keyword">elif</span> media_type == <span class="hljs-string">'movie'</span> %}
        --card-mod-icon: mdi:movie-roll;
        animation: spin 2s linear infinite reverse;
      {% <span class="hljs-keyword">elif</span> media_type == <span class="hljs-string">'music'</span> %}
        --card-mod-icon: mdi:music;
        animation: beat 1.3s ease-out infinite both;
      {% <span class="hljs-keyword">elif</span> media_type == <span class="hljs-string">'playlist'</span> %}
        --card-mod-icon: mdi:music;
        animation: beat 1.3s ease-out infinite both;
      {% <span class="hljs-keyword">else</span> %}
        --card-mod-icon: mdi:play;
      {% endif %}
    }
    @keyframes flicker {
      0%, 31.98%, 32.98%, 34.98%, 36.98%, 39.98%, 67.98%, 68.98%, 95.98%, 96.98%, 97.98%, 98.98%, 100% { --icon-color: rgba(var(--rgb-indigo), 1); }
      32%, 33%, 35%, 36%, 37%, 40%, 68%, 69%, 96%, 97%, 98%, 99% { --icon-color: rgba(var(--rgb-indigo), 0.6); }
    }
    @keyframes beat {
      0%, 60% { --icon-symbol-size: 21px; }
      5%, 17%, 57% { --icon-symbol-size: 22px; }
      10%, 20%, 51% { --icon-symbol-size: 23px; }
      25%, 45% { --icon-symbol-size: 24px; }
      30%, 39% { --icon-symbol-size: 25px; }
      33% { --icon-symbol-size: 26px; }
    }
    ha-card {
      {% <span class="hljs-keyword">if</span> not is_state(config.entity, <span class="hljs-string">'off'</span>) %}
        background: rgba(var(--rgb-card-background-color), 0.6) url( <span class="hljs-string">'{{ state_attr(config.entity, "entity_picture") }}'</span> ) center no-repeat;
        background-size: cover;
        background-blend-mode: overlay;
      {% endif %} 
    }
</code></pre>
   </details>
   <h4>
      <a name="mushroom-climate-card-unchanged-6"
         class="anchor"
         href="#mushroom-climate-card-unchanged-6"></a>Mushroom Climate Card (unchanged):
   </h4>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="139"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/7/f/47f98442436a24afa951769d19a2b0e13d920bed.gif"
         alt="Mushroom Climate Card with Animated Icons"
         data-base62-sha1="agIudicw6fba1b2pXWAWiXxlEIt"
         width="517"
         height="139"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 139;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <p>Climate Animated Icons</p>
   <details>
      <summary>
         Climate Animated Icons
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-php" data-highlighted="yes">type: custom:mushroom-climate-card
entity: climate.office_air_conditioner
hvac_modes:
  - heat_cool
  - heat
  - cool
  - fan_only
  - dry
show_temperature_control: <span class="hljs-literal">true</span>
collapsible_controls: <span class="hljs-literal">false</span>
name: Air Conditioner
card_mod:
  style: |
    mushroom-shape-icon {
      {% <span class="hljs-keyword">if</span> <span class="hljs-title function_ invoke__">is_state</span>(config.entity, <span class="hljs-string">'heat_cool'</span>) %}
        --card-mod-icon: mdi:autorenew;
        animation: spin <span class="hljs-number">3</span>s ease-in-out infinite alternate;
      {% elif <span class="hljs-title function_ invoke__">is_state</span>(config.entity, <span class="hljs-string">'heat'</span>) %}
        --card-mod-icon: mdi:fire;
        animation: heat <span class="hljs-number">2</span>s infinite;
      {% elif <span class="hljs-title function_ invoke__">is_state</span>(config.entity, <span class="hljs-string">'cool'</span>) %}
        --card-mod-icon: mdi:snowflake;
        animation: cool <span class="hljs-number">6</span>s ease-in-out infinite;
      {% elif <span class="hljs-title function_ invoke__">is_state</span>(config.entity, <span class="hljs-string">'dry'</span>) %}
        --card-mod-icon: mdi:water-percent;
        animation: dry <span class="hljs-number">1.5</span>s linear infinite;
      {% elif <span class="hljs-title function_ invoke__">is_state</span>(config.entity, <span class="hljs-string">'fan_only'</span>) %}
        --card-mod-icon: mdi:fan;
        animation: spin <span class="hljs-number">1</span>s linear infinite;
      {% <span class="hljs-keyword">else</span> %}
        --card-mod-icon: mdi:air-conditioner;
      {% <span class="hljs-keyword">endif</span> %}
      display: flex;
    }
    @keyframes cool {
      <span class="hljs-number">0</span>%, <span class="hljs-number">100</span>% { transform: <span class="hljs-title function_ invoke__">rotate</span>(<span class="hljs-number">25</span>deg); }
      <span class="hljs-number">25</span>% { transform: <span class="hljs-title function_ invoke__">rotate</span>(-<span class="hljs-number">25</span>deg); }
      <span class="hljs-number">50</span>% { transform: <span class="hljs-title function_ invoke__">rotate</span>(<span class="hljs-number">50</span>deg); }
      <span class="hljs-number">75</span>% { transform: <span class="hljs-title function_ invoke__">rotate</span>(-<span class="hljs-number">50</span>deg); }
    }
    @keyframes heat {
      <span class="hljs-number">0</span>%, <span class="hljs-number">100</span>% { --icon-color: <span class="hljs-title function_ invoke__">rgba</span>(<span class="hljs-keyword">var</span>(--rgb-red), <span class="hljs-number">1</span>); }
      <span class="hljs-number">10</span>%, <span class="hljs-number">90</span>% { --icon-color: <span class="hljs-title function_ invoke__">rgba</span>(<span class="hljs-keyword">var</span>(--rgb-red), <span class="hljs-number">0.8</span>); }
      <span class="hljs-number">20</span>%, <span class="hljs-number">80</span>% { --icon-color: <span class="hljs-title function_ invoke__">rgba</span>(<span class="hljs-keyword">var</span>(--rgb-red), <span class="hljs-number">0.6</span>); }
      <span class="hljs-number">30</span>%, <span class="hljs-number">70</span>% { --icon-color: <span class="hljs-title function_ invoke__">rgba</span>(<span class="hljs-keyword">var</span>(--rgb-red), <span class="hljs-number">0.4</span>); }
      <span class="hljs-number">40</span>%, <span class="hljs-number">60</span>% { --icon-color: <span class="hljs-title function_ invoke__">rgba</span>(<span class="hljs-keyword">var</span>(--rgb-red), <span class="hljs-number">0.2</span>); }
      <span class="hljs-number">50</span>% { --icon-color: <span class="hljs-title function_ invoke__">rgba</span>(<span class="hljs-keyword">var</span>(--rgb-red), <span class="hljs-number">0</span>); }
    }
    @keyframes dry {
      <span class="hljs-number">0</span>%, <span class="hljs-number">100</span>% { --icon-symbol-size: <span class="hljs-number">21</span>px; }
      <span class="hljs-number">10</span>%, <span class="hljs-number">90</span>% { --icon-symbol-size: <span class="hljs-number">22</span>px; }
      <span class="hljs-number">20</span>%, <span class="hljs-number">80</span>% { --icon-symbol-size: <span class="hljs-number">23</span>px; }
      <span class="hljs-number">30</span>%, <span class="hljs-number">70</span>% { --icon-symbol-size: <span class="hljs-number">24</span>px; }
      <span class="hljs-number">40</span>%, <span class="hljs-number">60</span>% { --icon-symbol-size: <span class="hljs-number">25</span>px; }
      <span class="hljs-number">50</span>% { --icon-symbol-size: <span class="hljs-number">26</span>px; }
    }
</code></pre>
   </details>
   <h2>
      <a name="mushroom-card-icon-animations-7"
         class="anchor"
         href="#mushroom-card-icon-animations-7"></a>Mushroom Card Icon Animations
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="65"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/0/9/609281341829cf92afb3d0cf3be913f95e9ccef0.gif"
         alt="Mushroom Boil"
         data-base62-sha1="dMjILvNATdrsjGH3PrhIsWQeqJi"
         width="263"
         height="65"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 65;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Boil Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-template-card
primary: Boil
icon: mdi:kettle-steam
icon_color: red
card_mod:
  style: |
    ha-state-icon {
      animation: boil 500ms infinite;
    }
    @keyframes boil {
      0%, 100% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      10% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); clip-path: polygon(0 0, 66% 10%, 67% 30%, 88% 52%, 100% 100%, 0 100%); }
      20% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      30% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      40% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      50% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      60% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      70% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      80% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      90% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/f/3/af37c70fc4773093a6b2c882a422e49875321b4c.gif"
         alt="Mushroom Fire"
         data-base62-sha1="p033JBIfLXVD3VJsfMne2u2iaZe"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Fire Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-template-card
primary: Fire
icon: mdi:fire
icon_color: red
card_mod:
  style: |
    ha-state-icon {
      animation: fire 1.5s infinite;
      transform-origin: 50% 85%;
    }
    @keyframes fire {
      0% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      5% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      10% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      15% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      20% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      25% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      30% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      35% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      40% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      45% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      50% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      55% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      60% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      65% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      70% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      75% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      80% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      85% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      90% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      95% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-red)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
      100% { transform: rotate(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">deg) scaleY(</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">9</span>, <span class="hljs-number">12</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">); color: rgb(var(--rgb-deep-orange)); opacity: </span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">7</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span>}}</span><span class="language-xml">; }
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/c/4/dc479d6793e2162f9d96335f8a680779e573ed5e.gif"
         alt="Mushroom Shower"
         data-base62-sha1="vqGtC1aLiaGuivSmOFLjStzxenc"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Shower Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:shower-head
icon_color: light-blue
primary: Shower
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: clip <span class="hljs-number">0.7s</span> ease-out infinite;
    }
    <span class="hljs-keyword">@keyframes</span> clip {
      <span class="hljs-number">0%</span> {<span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">45%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/5/d/55da54c7f686cf09d7b97f1e9938007ae6657af5.gif"
         alt="Mushroom Sprinkler"
         data-base62-sha1="cfum9KFcgOg7ntF3QiPE4ldDLtX"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Sprinkler Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:sprinkler
icon_color: cyan
primary: Sprinkler
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: sprinkle <span class="hljs-number">2s</span> linear infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">29%</span> <span class="hljs-number">88%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> sprinkle {
      <span class="hljs-number">0%</span>, <span class="hljs-number">15%</span>, <span class="hljs-number">30%</span>, <span class="hljs-number">45%</span>, <span class="hljs-number">60%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">55%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0deg</span>); }
      <span class="hljs-number">1%</span>, <span class="hljs-number">16%</span>, <span class="hljs-number">31%</span>, <span class="hljs-number">46%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">10deg</span>); }
      <span class="hljs-number">6%</span>, <span class="hljs-number">21%</span>, <span class="hljs-number">36%</span>, <span class="hljs-number">51%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">2deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/e/f/6ef9912646d6d1aa28954bc7789e398189246ebb.gif"
         alt="Mushroom Washing Machine"
         data-base62-sha1="fPJdqslpnrOzsIe5UjFEibCrADh"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Washing Machine Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:washing-machine
icon_color: amber
primary: Washing Machine
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: shake <span class="hljs-number">400ms</span> ease-in-out infinite, drum <span class="hljs-number">2s</span> ease infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">110%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> shake {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0</span>, <span class="hljs-number">0</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">20%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.4px</span>, -<span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
      <span class="hljs-number">40%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.4px</span>, <span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">4deg</span>); }
      <span class="hljs-number">60%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.4px</span>, <span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
      <span class="hljs-number">80%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.4px</span>, -<span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">4deg</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> drum {
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">68%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">41%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">65%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/f/5/7f51aaf77ba9a82347f189c719b4ad50faef7e0e.gif"
         alt="Mushroom Dishwasher"
         data-base62-sha1="iajBTMfLKmEn9GpaX3eOwL26M9g"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Dishwasher Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:dishwasher
icon_color: blue
primary: Dishwasher
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: bounce <span class="hljs-number">1.5s</span> ease-in-out infinite, wash <span class="hljs-number">1s</span> ease-in-out infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> bounce {
      <span class="hljs-number">0%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span>, <span class="hljs-number">100%</span> {<span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">1.2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">5deg</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">1.1px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> wash {
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">78%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/a/d/3adf85bdedd27c0458000c731206e5f1ec23a64d.gif"
         alt="Mushroom Dryer"
         data-base62-sha1="8oOArONNVSG3IFKni86lwMQyO7z"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Dryer Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:tumble-dryer
icon_color: teal
primary: Dryer
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: shake <span class="hljs-number">400ms</span> ease-in-out infinite, drum <span class="hljs-number">1s</span> infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">65%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> shake {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">4deg</span>); }
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> drum {
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">78%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/c/8/3/c83ffd45d459d68021647bd3221093ddd04b9bf8.gif"
         alt="Mushroom Ding"
         data-base62-sha1="szuAConcyShV4laGA0I0NviA12o"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Ding Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Ding
icon: mdi:bell-ring
icon_color: indigo
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: ring <span class="hljs-number">4s</span> linear infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">15%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> ring {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">2%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">30deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">6%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">28deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">34deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">14%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">32deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">18%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">30deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">22%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">28deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">26%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">26deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">24deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">34%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">22deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">38%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">20deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">42%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">18deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">46%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">16deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">14deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">54%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">12deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">58%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">10deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">62%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">8deg</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
      <span class="hljs-number">66%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">6deg</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
      <span class="hljs-number">74%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">2deg</span>); }
      <span class="hljs-number">78%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">1deg</span>); }
      <span class="hljs-number">82%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">1deg</span>); }
      <span class="hljs-number">86%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">5%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/6/4/564de8475f9dbfed0343f4613b64f15bd1d3aefc.gif"
         alt="Mushroom Alarm"
         data-base62-sha1="cjtYE3zQ2sxq5WRc4Q76acHWU9e"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Alarm Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:alarm
icon_color: red
primary: Alarm
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: alarm <span class="hljs-number">0.8s</span> ease infinite;
    }
    <span class="hljs-keyword">@keyframes</span> alarm {
      <span class="hljs-number">0%</span>, <span class="hljs-number">80%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">27deg</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">21deg</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">9deg</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">1.2px</span>) }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="262"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/7/2/e72d711fba3217a43e512fdd62e85c6444a937d4.gif"
         alt="Mushroom Rocket Man"
         data-base62-sha1="wZ5EzNG5bhsMkVoTQMyxqZObTV2"
         width="262"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 262 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Rocket Man Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:rocket-launch
icon_color: deep-orange
primary: Rocket Man
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: thrust <span class="hljs-number">100ms</span> infinite, motion <span class="hljs-number">3s</span> ease-in-out infinite;
    }
    <span class="hljs-keyword">@keyframes</span> thrust {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">47%</span>, <span class="hljs-number">22%</span> <span class="hljs-number">57%</span>, <span class="hljs-number">28%</span> <span class="hljs-number">63%</span>, <span class="hljs-number">0</span> <span class="hljs-number">91%</span>, <span class="hljs-number">11%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">37%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">45%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">33%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">47%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">66%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">92%</span>, <span class="hljs-number">28%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">9%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
    }
      <span class="hljs-keyword">@keyframes</span> motion {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3px</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">3px</span>) <span class="hljs-built_in">translateX</span>(<span class="hljs-number">2px</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/d/3/3d31fcbfb8df0ff02adc61584753f12a06a366a3.gif"
         alt="Mushroom Fountain"
         data-base62-sha1="8JmdPbSeAXmwfW1hcNTqV8JikQX"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Fountain Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Fountain
icon: mdi:fountain
icon_color: light-blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: fountain <span class="hljs-number">1.5s</span> ease infinite;
    }
    <span class="hljs-keyword">@keyframes</span> fountain {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">47%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">47%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">37%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">21%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">44%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">20%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">0</span> <span class="hljs-number">36%</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">22%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">1%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">0</span>, <span class="hljs-number">31%</span> <span class="hljs-number">21%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">0</span> <span class="hljs-number">36%</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">28%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">23%</span> <span class="hljs-number">28%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">0</span> <span class="hljs-number">36%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/2/7/72721407d022e7334438248a7e6d34f198884205.gif"
         alt="Mushroom Motion"
         data-base62-sha1="gkqQh2oEkKuX8pvrqhK4X015bSt"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Motion Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:motion-sensor
icon_color: blue
primary: Motion
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: motion <span class="hljs-number">2s</span> linear infinite;
      }
      <span class="hljs-keyword">@keyframes</span> motion {
        <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attr">--shape-color</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-blue), <span class="hljs-number">0.3</span>); }
        <span class="hljs-number">50%</span> { <span class="hljs-attr">--shape-color</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-blue), <span class="hljs-number">0.2</span>); }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: clip <span class="hljs-number">2s</span> linear infinite;
      }
      <span class="hljs-keyword">@keyframes</span> clip {
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">55%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/9/4/494ea70ef260da14132f4e2bd3420cd5253d3c40.gif"
         alt="Mushroom Cog"
         data-base62-sha1="asvmNrnB7tOdA8XHGJPNEa094hq"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Cog Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Cog</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:cog</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">grey</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
      animation: spin 1.5s steps(5) infinite;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/9/5/4/954a4c2549cff5fb2fd2c347298edc2c73b4c63a.gif"
         alt="Mushroom Signal"
         data-base62-sha1="liGk7TXOzKCxxLSstPoW9CPO3JE"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Signal Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:wifi
icon_color: green
primary: Signal
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: ping <span class="hljs-number">2s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> ping {
        <span class="hljs-number">60%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-green), <span class="hljs-number">0.7</span>); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">15px</span> transparent; }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: clip <span class="hljs-number">2s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite;
      }
      <span class="hljs-keyword">@keyframes</span> clip {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">0%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">85%</span>); }
        <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">30%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">85%</span>); }
        <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">55%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">85%</span>); }
        <span class="hljs-number">60%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">80%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">85%</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/c/2/7/c27716587392841cf1aa1950a6bdd4811f9ba3dc.gif"
         alt="Mushroom Alert"
         data-base62-sha1="rKjLTSXMbJWFM8i0SXwl0ZmSk8c"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Alert Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:alarm-light
icon_color: red
primary: Alert
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: alert-shape <span class="hljs-number">0.8s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> alert-shape {
        <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attr">--shape-color</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-orange), <span class="hljs-number">0.2</span>); }
        <span class="hljs-number">60%</span> { <span class="hljs-attr">--shape-color</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.2</span>); }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: alert <span class="hljs-number">0.8s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> alert {
        <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">18%</span>, <span class="hljs-number">65%</span> <span class="hljs-number">20%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/e/4/2e4e2805526f7cb0e910f74986967c79d86d4132.gif"
         alt="Mushroom Console"
         data-base62-sha1="6BDpAPHJcKSt9HeA74mNC4pSmae"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Console Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:console-line
icon_color: grey
primary: Console
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: console <span class="hljs-number">1s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> console {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">24%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/8/d/58dc5463c94e13bfa2298c7e1f0f0abb48dc1f85.gif"
         alt="Mushroom Keypad"
         data-base62-sha1="cG64qOEszJX2bwx7YqeYJ9OMdzn"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Keypad Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:dialpad
icon_color: blue
primary: Keypad
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: ping <span class="hljs-number">4s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> ping {
        <span class="hljs-number">55%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">1px</span> <span class="hljs-number">0px</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-blue), <span class="hljs-number">0.3</span>) inset; }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">15px</span> transparent inset; }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: pin <span class="hljs-number">4s</span> infinite;
        <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>;
      }
      <span class="hljs-keyword">@keyframes</span> pin {
        <span class="hljs-number">0%</span>, <span class="hljs-number">15%</span>, <span class="hljs-number">25%</span>, <span class="hljs-number">35%</span>, <span class="hljs-number">45%</span>, <span class="hljs-number">55%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">10%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">1%</span> <span class="hljs-number">23%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">23%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
        <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">62%</span> <span class="hljs-number">0</span>, <span class="hljs-number">61%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
        <span class="hljs-number">30%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">25%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">37%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">49%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">26%</span>, <span class="hljs-number">0</span> <span class="hljs-number">25%</span>); }
        <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">51%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">37%</span> <span class="hljs-number">51%</span>); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">100%</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/d/6/2d6cd1fa8c55c55393e2883fa47089a3df073678.gif"
         alt="Mushroom Eye"
         data-base62-sha1="6tQDd5gvUaUXZluO8aYMETBmwKk"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Eye Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:eye
icon_color: blue
primary: Eye
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: wink <span class="hljs-number">4s</span> ease-in-out infinite;
    }
    <span class="hljs-keyword">@keyframes</span> wink {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">19%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.05</span>, <span class="hljs-number">0.6</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">49%</span>, <span class="hljs-number">86%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">70%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">71%</span>, <span class="hljs-number">43%</span> <span class="hljs-number">71%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">21%</span> <span class="hljs-number">57%</span>, <span class="hljs-number">13%</span> <span class="hljs-number">49%</span>, <span class="hljs-number">0</span> <span class="hljs-number">49%</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">28%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">0.95</span>, <span class="hljs-number">1.05</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/9/0/49002210f9fef06f48f37e71e7f7f21ac9c99ace.gif"
         alt="Mushroom Camera 1"
         data-base62-sha1="apN8HSvF8m0ltprVMWDX8FxVgAK"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Camera #1 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:cctv
icon_color: deep-purple
primary: <span class="hljs-string">'Camera #1'</span>
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: flip <span class="hljs-number">8s</span> ease-in-out infinite alternate;
    }
    <span class="hljs-keyword">@keyframes</span> flip {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
    } 
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/9/0/790b0fa0ebcb0eb80dc77c7a2d5b9caed6304d74.gif"
         alt="Mushroom Camera 2"
         data-base62-sha1="hgNtgNJW96kfd4L550gMGXMxgl6"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Camera #2 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: <span class="hljs-string">'Camera #2'</span>
icon: mdi:cctv
icon_color: deep-purple
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: scan <span class="hljs-number">5s</span> ease-in-out infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">90%</span> <span class="hljs-number">80%</span>
    }
    <span class="hljs-keyword">@keyframes</span> <span class="hljs-attribute">scan</span> {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">20deg</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/3/0/d30cd69a0df54b0e3f5ec88eef18d128378f0fac.gif"
         alt="Mushroom Battery 1"
         data-base62-sha1="u72fDlfy73kmC0JlUygR3XwdMuM"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Battery #1 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:battery
icon_color: green
primary: <span class="hljs-string">'Battery #1'</span>
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: charge <span class="hljs-number">3s</span> linear infinite;
    }
    <span class="hljs-keyword">@keyframes</span> charge {
      <span class="hljs-number">0%</span>, <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">84%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">84%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/d/b/7db0df10bcde17b07f8798f3e213fdee6f34fd6d.gif"
         alt="Mushroom Battery 2"
         data-base62-sha1="hVUCZAcpTnlJGWT5Rhyb0vipUHH"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Battery #2 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:battery-high
icon_color: green
primary: <span class="hljs-string">'Battery #2'</span>
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: charge <span class="hljs-number">3s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite;
    }
    <span class="hljs-keyword">@keyframes</span> charge {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">84%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">84%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/8/4/a/84affb194f31b6f5b85636ddea3ead4728df5bf2.gif"
         alt="Mushroom Wrench"
         data-base62-sha1="iVO3VucfQnTVxpj5SL72E4MYys2"
         width="263"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Wrench Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Wrench
icon: mdi:wrench
icon_color: grey
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: tighten <span class="hljs-number">1.5s</span> ease-in-out infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">31%</span> <span class="hljs-number">31%</span>
    }
    <span class="hljs-keyword">@keyframes</span> tighten {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">20deg</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">15deg</span>); }
    }
</code></pre>
   </details>
   <h2>
      <a name="mushroom-title-animations-all-unchanged-1"
         class="anchor"
         href="#mushroom-title-animations-all-unchanged-1"></a>Mushroom Title Animations
   </h2>
   <p>These ones run once to transition in the Mushroom Title.</p>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="99"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/4/c/e4cab18eeed2d07ca217d2d2090dd43cdd804a4f.gif"
         alt="Mushroom Title Typewriter"
         data-base62-sha1="wDZ8crGYgLwQC9fADWg86scJ9IH"
         width="517"
         height="99"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 99;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Typewriter Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom.
  subtitle: Typewriter
card_mod:
  style:
    mushroom-title-card$: |
      h1 {
        <span class="hljs-attribute">width</span>: <span class="hljs-number">9ch</span>;
        <span class="hljs-attribute">animation</span>: typing <span class="hljs-number">5s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">9</span>), cursor <span class="hljs-number">0.25s</span> step-end <span class="hljs-number">30</span> alternate;
        <span class="hljs-attribute">overflow</span>: hidden;
        <span class="hljs-attribute">border-right</span>: <span class="hljs-number">2px</span> solid transparent;
        <span class="hljs-attribute">font-family</span>: monospace;
      }
       <span class="hljs-keyword">@keyframes</span> typing {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">width</span>: <span class="hljs-number">0</span>; }
      }
      <span class="hljs-keyword">@keyframes</span> cursor {
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">var</span>(--primary-text-color); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="99"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/5/3/d53635f722d61e341dfeca012f7a19a164ee9649.gif"
         alt="Mushroom Title Scale-In"
         data-base62-sha1="uq9Qx4BrWYZA8ZHHycfANq3WXoJ"
         width="517"
         height="99"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 99;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Scale-in Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom 🍄
  subtitle: Scale-in
card_mod:
  style:
    mushroom-title-card$: |
      * {
          <span class="hljs-attribute">animation</span>: scale-in <span class="hljs-number">1s</span>;
          <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">15%</span>;
      }
      <span class="hljs-keyword">@keyframes</span> scale-in {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="99"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/6/d/b6d7c0bea8c3973c104cfcc1c38b49df469ed99a.gif"
         alt="Mushroom Title Fade-In"
         data-base62-sha1="q5v9bhS5ErkQYzvnMxRL9wyXlKq"
         width="517"
         height="99"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 99;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Fade-in Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom 🍄
  subtitle: Fade-in
card_mod:
  style:
    mushroom-title-card$: |
      * {
        <span class="hljs-attribute">animation</span>: fade <span class="hljs-number">1s</span> ease-in;
      }
      <span class="hljs-keyword">@keyframes</span> fade {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="99"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/0/9/009cbf14337dfd517f058dd7bd6864b2566a009e.gif"
         alt="Mushroom Title Focus"
         data-base62-sha1="5pPjmpzNh7J3flXDYYOfleyOwC"
         width="517"
         height="99"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 99;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Focus Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom 🍄
  subtitle: Focus
card_mod:
  style:
    mushroom-title-card$: |
      * {
        <span class="hljs-attribute">animation</span>: focus <span class="hljs-number">1.5s</span>;
      }
      <span class="hljs-keyword">@keyframes</span> focus {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">filter</span>: <span class="hljs-built_in">blur</span>(<span class="hljs-number">10px</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="105"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/d/2/ed2cbb850b40d947605b7d6cc562f247d3f44465.gif"
         alt="Mushroom Title Drop-In"
         data-base62-sha1="xQ8ZXOUyiwL4HP0TZMNush70EPr"
         width="517"
         height="105"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 105;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Drop-in Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom 🍄
  subtitle: Drop-in
card_mod:
  style:
    mushroom-title-card$: |
      * {
        <span class="hljs-attribute">animation</span>: drop-in <span class="hljs-number">1.1s</span> both;
      }
      <span class="hljs-keyword">@keyframes</span> drop-in {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">400px</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; <span class="hljs-attribute">filter</span>: <span class="hljs-built_in">blur</span>(<span class="hljs-number">40px</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">38%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; <span class="hljs-attribute">filter</span>: <span class="hljs-built_in">blur</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
        <span class="hljs-number">55%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">16px</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; }
        <span class="hljs-number">72%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; }
        <span class="hljs-number">81%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">7px</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; }
        <span class="hljs-number">90%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; }
        <span class="hljs-number">95%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="105"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/c/5/d/c5dd82318205e747314e18496ea5881ec3572ff9.gif"
         alt="Mushroom Title Slide-In"
         data-base62-sha1="seoDMipGWRPoxmSW16lNgIJz74J"
         width="517"
         height="105"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 105;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Slide-in Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom 🍄
  subtitle: Slide-in
card_mod:
  style:
    mushroom-title-card$: |
      * {
        <span class="hljs-attribute">animation</span>: slide-in <span class="hljs-number">1.1s</span> both;
      }
      <span class="hljs-keyword">@keyframes</span> slide-in {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">600px</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">2.5</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">0.2</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; <span class="hljs-attribute">filter</span>: <span class="hljs-built_in">blur</span>(<span class="hljs-number">40px</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">38%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">0</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">1</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; <span class="hljs-attribute">filter</span>: <span class="hljs-built_in">blur</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
        <span class="hljs-number">55%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">68px</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">1.1</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.95</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; }
        <span class="hljs-number">72%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">0</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">1</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; }
        <span class="hljs-number">81%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">32px</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">1.05</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.98</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; }
        <span class="hljs-number">90%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">0</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">1</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; }
        <span class="hljs-number">95%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">8px</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-in; }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">0</span>); <span class="hljs-attribute">animation-timing-function</span>: ease-out; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="99"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/0/d/10d4a3e8787071c750a2558eeef19815a7d00113.gif"
         alt="Mushroom Title Flicker"
         data-base62-sha1="2oTdAAwpLBwuSeqVlfemjWPQvez"
         width="517"
         height="99"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 99;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Flicker Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mod-card
card:
  type: custom:mushroom-title-card
  title: Mushroom 🍄
  subtitle: Flicker
card_mod:
  style:
    mushroom-title-card$: |
      * {
        <span class="hljs-attribute">animation</span>: flicker <span class="hljs-number">1.1s</span> both;
      }
      <span class="hljs-keyword">@keyframes</span> flicker {
        <span class="hljs-number">0%</span>, <span class="hljs-number">10%</span>, <span class="hljs-number">10.2%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">20.6%</span>, <span class="hljs-number">30%</span>, <span class="hljs-number">30.6%</span>, <span class="hljs-number">45%</span>, <span class="hljs-number">55.1%</span>, <span class="hljs-number">57%</span>, <span class="hljs-number">60.1%</span>, <span class="hljs-number">65%</span>, <span class="hljs-number">75.1%</span>, <span class="hljs-number">77%</span>, <span class="hljs-number">85.1%</span>, <span class="hljs-number">86%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">10.1%</span>, <span class="hljs-number">20.1%</span>, <span class="hljs-number">30.1%</span>, <span class="hljs-number">30.5%</span>, <span class="hljs-number">45.1%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">55%</span>, <span class="hljs-number">57.1%</span>, <span class="hljs-number">60%</span>, <span class="hljs-number">65.1%</span>, <span class="hljs-number">75%</span>, <span class="hljs-number">77.1%</span>, <span class="hljs-number">85%</span>, <span class="hljs-number">86.1%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
      }
</code></pre>
   </details>
   <h2>
      <a name="mushroom-spinner-animations-2"
         class="anchor"
         href="#mushroom-spinner-animations-2"></a>Mushroom Spinner Animations
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/9/e/49e270bf6267e7dacdd90a3d768a534bd83abade.gif"
         alt="Mushroom Comet Spinner"
         data-base62-sha1="axC06yxkimsrTsWXrKVwdNmAMMu"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Comet Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Comet
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border-right</span>: <span class="hljs-number">4px</span> solid;
        <span class="hljs-attribute">border-bottom</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">1s</span> linear infinite, comet <span class="hljs-number">10s</span> infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">38px</span>;
      }
      <span class="hljs-keyword">@keyframes</span> comet {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); }
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); }
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); }
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); }
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); }
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); }
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); }
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); }
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); }
        <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); }
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); }
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/7/9/a79e9ed99fb129a7a809d9ff42fa203bce317148.gif"
         alt="Mushroom Crescent Spinner"
         data-base62-sha1="nUPzZcfyRyCXEnLaWehwbi2ngtq"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Crescent Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Crescent
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">1px</span> solid <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-disabled), <span class="hljs-number">0.8</span>);
        <span class="hljs-attribute">border-right</span>: <span class="hljs-number">3px</span> solid <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">1s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">40px</span>;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/5/6/356b66b8c4b4540679b979610bda4c64ad2eff8d.gif"
         alt="Mushroom Munch Spinner"
         data-base62-sha1="7CzpxYHZv6zHwsf0SP0nGcY6ux7"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Munch Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Munch
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));
        <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">34px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1.5s</span> linear infinite reverse;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));
        <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">34px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/2/c/72c03bc3eb89a053ab24496e32c236af88ff5615.gif"
         alt="Mushroom Double Spinner"
         data-base62-sha1="gn8hYr6EK6ohUIBJUsdPlVFrZ7n"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Double Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Double
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> double transparent;
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));
        <span class="hljs-attribute">border-bottom-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">20px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite reverse;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> double transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange));
        <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange));
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/4/b/54b0c3c96ca878fa54930386531a72b9131b8af7.gif"
         alt="Mushroom St. Nick Spinner"
         data-base62-sha1="c5cP6KWktDQe0oMgaj1ITycQ05x"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         St. Nick Spinner (changed, this one does look weird on firefox for me for some reason. works fine on mobile.)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: St. Nick
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> dashed <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">5px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">0.5s</span> linear infinite reverse;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">8px</span> dotted <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red));
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/6/0/f60ec1d10b29b13793c62a1e367c9ec70e3b06d2.gif"
         alt="Mushroom Gradient Spinner"
         data-base62-sha1="z6J4D0f9woXuZrNIFGTnc1cehIS"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Gradient Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Gradient
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
         <span class="hljs-attribute">background</span>: <span class="hljs-built_in">radial-gradient</span>(farthest-side, <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)) <span class="hljs-number">94%</span>, transparent) top/<span class="hljs-number">4px</span> <span class="hljs-number">4px</span> no-repeat, <span class="hljs-built_in">conic-gradient</span>(transparent <span class="hljs-number">30%</span>, <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)));
         -webkit-<span class="hljs-attribute">mask</span>: <span class="hljs-built_in">radial-gradient</span>(farthest-side, transparent <span class="hljs-built_in">calc</span>(<span class="hljs-number">100%</span> - <span class="hljs-number">4px</span>), <span class="hljs-number">#000</span> <span class="hljs-number">0</span>);
         <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">1s</span> infinite linear;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/0/b/50b08a1481d3fe3ef03155ec538bfd72cd86442c.gif"
         alt="Mushroom Dots Spinner"
         data-base62-sha1="bvOqKHkwVWlSshgDE4F0spITpog"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Dots Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Dots
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
          <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> dotted transparent;
          <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">800ms</span> ease-in-out infinite, color <span class="hljs-number">10s</span> infinite;
          <span class="hljs-attr">--shape-color</span>: none;
          <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
      <span class="hljs-keyword">@keyframes</span> <span class="hljs-attribute">color</span> {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); }
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); }
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); }
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); }
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); }
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); }
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); }
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); }
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); }
        <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); }
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); }
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/8/a/9/8a90dbf2968b0e2a3df7b1b0e005d5f94d24266f.gif"
         alt="Mushroom Radial Spinner"
         data-base62-sha1="jLOfw0HokW8A5vslF3q2jOPeB2v"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Radial Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Radial
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">3px</span> solid <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red));
        <span class="hljs-attribute">border-right-color</span>: transparent;
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">24px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">36px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1.5s</span> linear infinite;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">3px</span> solid <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue));
        <span class="hljs-attribute">border-right-color</span>: transparent;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/c/8/fc8db709406bae447a7bd083b88d3aa4061f0578.gif"
         alt="Mushroom Dual Spinner"
         data-base62-sha1="A2bWCx2IZ5pg2AEe6qnH2kZUmmY"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Dual Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Dual
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">1s</span> ease infinite;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange));
        <span class="hljs-attribute">border-bottom-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange));
        <span class="hljs-attr">--shape-color</span>: none <span class="hljs-meta">!important</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/a/f/daff425060276caf8d947bcd14f0788dc906153b.gif"
         alt="Mushroom Morse Spinner"
         data-base62-sha1="vfkYFshxKo2XDe3IdmIFi1Mh2EH"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Morse Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Morse
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> dashed transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple));
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">20px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite reverse;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> dashed transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink));
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink));
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/1/5/31546f9636905ab019ea44095700e1e06e2dc39d.gif"
         alt="Mushroom Fade Spinner"
         data-base62-sha1="72oixKDhUfx3mNOnqBkRZfK3JKt"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Fade Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Fade
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: fade <span class="hljs-number">25s</span> linear infinite reverse;
        <span class="hljs-attr">--shape-color</span>: none;
      }
      <span class="hljs-keyword">@keyframes</span> fade {
        <span class="hljs-number">6.24%</span>, <span class="hljs-number">12.49%</span>, <span class="hljs-number">18.74%</span>, <span class="hljs-number">24.99%</span>, <span class="hljs-number">31.24%</span>, <span class="hljs-number">37.49%</span>, <span class="hljs-number">43.74%</span>, <span class="hljs-number">49.99%</span>, <span class="hljs-number">56.24%</span>, <span class="hljs-number">62.49%</span>, <span class="hljs-number">68.74%</span>, <span class="hljs-number">74.99%</span>, <span class="hljs-number">81.24%</span>, <span class="hljs-number">87.49%</span>, <span class="hljs-number">93.74%</span>, <span class="hljs-number">100%</span>  { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">20px</span> <span class="hljs-number">20px</span> transparent inset; }
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-orange), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-amber), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-yellow), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-lime), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple), <span class="hljs-number">0.7</span>) inset; }
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink), <span class="hljs-number">0.7</span>) inset; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/b/6/0b6d4d0c93b73d7e18961f8f99ab7dc39731d473.gif"
         alt="Mushroom Dotty Spinner"
         data-base62-sha1="1D5qySQx4hvcYc5TPV8Vl3fL06D"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Dotty Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">5px</span> dotted transparent;
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite, color <span class="hljs-number">60s</span> infinite;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">30px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">32px</span>;
      }
      <span class="hljs-keyword">@keyframes</span> <span class="hljs-attribute">color</span> {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); }
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); }
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); }
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); }
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); }
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); }
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); }
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); }
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); }
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); }
        <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); }
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite reverse, color <span class="hljs-number">60s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> <span class="hljs-attribute">color</span> {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); }
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); }
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); }
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); }
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); }
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); }
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); }
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); }
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); }
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); }
        <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); }
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">border-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/c/9/1/c91c60bf7291956cf8d8111ef937e1b30b224adb.gif"
         alt="Mushroom Plain Spinner"
         data-base62-sha1="sH6LNDcDHG4uAdD0qKjMAcLDMRd"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Plain Spinner (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Plain
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">5px</span> solid <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-disabled));
        <span class="hljs-attribute">border-left-color</span>: transparent;
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">1s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">32px</span>;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/4/2/b4200accf7236a3fa3e4d5e2637d7679fdf3f7f2.gif"
         alt="Mushroom Toggle Spinner"
         data-base62-sha1="pHsASf5A0d9dHcmflI0QcGAPDkm"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Toggle Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Toggle
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-top-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan));
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">1s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">34px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite reverse;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan));
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan));
      }}
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/3/7/337e435f3fd57ac066384d43d81430f279ea3185.gif"
         alt="Mushroom Spheres Spinner"
         data-base62-sha1="7lwRQRHhVQQPAZ1zRnKkkzx5o6F"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Spheres Spinner (changed, this one looks very weird on firefox for me. but works fine on mobile.)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: none
primary: Spheres
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape  {
        <span class="hljs-attribute">border</span>: <span class="hljs-number">12px</span> dotted transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red));
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">18px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">18px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite reverse;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">12px</span> dotted transparent;
        <span class="hljs-attribute">border-right-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue));
        <span class="hljs-attribute">border-left-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue));
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/6/5/b651709838934de52191981d6998400fe6e50270.gif"
         alt="Mushroom Triple Spinner"
         data-base62-sha1="q0RnMHtHf9dfnT06AloS9kCX5cI"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Triple Spinner (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:loading
icon_color: red
primary: Triple
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-color</span>: none <span class="hljs-meta">!important</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-bottom-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green));
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
        <span class="hljs-attr">--icon-symbol-size</span>: <span class="hljs-number">42px</span>;
        <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">34px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">4s</span> linear infinite;
        <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
        <span class="hljs-attribute">border</span>: <span class="hljs-number">4px</span> solid transparent;
        <span class="hljs-attribute">border-bottom-color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue));
      }
</code></pre>
   </details>
   <h2>
      <a name="mushroom-card-active-animations-all-unchanged-3"
         class="anchor"
         href="#mushroom-card-active-animations-all-unchanged-3"></a>Mushroom Card Active Animations (all unchanged)
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/0/0/e00a3d804ec42926a5ad28313834c34f286ca1b9.gif"
         alt="Mushroom Activate Background"
         data-base62-sha1="vXWTmEU58oKbuAWlUghwudag22R"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Background (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Background</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active {
      background: rgba(var(--rgb-disabled), 0.1);
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/e/9/5e9be9640ae2125a88c2892342c346166ef1fe59.gif"
         alt="Mushroom Activate Box-shadow"
         data-base62-sha1="duWV86bY21z5s9UkF0oIQOWth2x"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Box-Shadow (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Box-Shadow</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active {
      box-shadow: 0 0 20px rgba(var(--rgb-disabled), 0.8);
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/3/1/e313e0eac0bcae6f9a021ecf6d04473cf3031005.gif"
         alt="Mushroom Activate Scale-Out"
         data-base62-sha1="woOYtEQqwb6AdPUN6fK7MX9ksHr"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Scale-Out (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Scale-Out</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active {
      transform: scale(1.02);
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/a/0/3a040597fce00c5c3d8a0bd1d549e22ef53da42e.gif"
         alt="Mushroom Activate Scale-In"
         data-base62-sha1="8hejdSamcoR8Y16XpcTzzkljpKK"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Scale-In (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Scale-In</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active {
      transform: scale(0.975);
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/e/b/7eb8b057df6586083a1b6eb753256a423bf63545.gif"
         alt="Mushroom Activate Push Down"
         data-base62-sha1="i51R1KiMGtxJYat946kK2mKbf7f"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Push Down (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Push</span> <span class="hljs-string">Down</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active {
      transform: translateY(1.5px);
      transition: 0s;
      box-shadow: 0 0.5px 2px 0 rgba(0, 0, 0, 0.16);
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/b/d/abd279d1cf8d4fc22a393d7091f5cc1ce40533be.gif"
         alt="Mushroom Activate Push In"
         data-base62-sha1="ow0AzxPoDzQYZ1T05VPqsp4F9bo"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Push In (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Push</span> <span class="hljs-string">In</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active {
      transform: translateY(-1.5px);
      transition: 0s;
      box-shadow: 0 0.5px 2px 0 rgba(0, 0, 0, 0.16);
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/c/d/0cd0b4748e716ad02cbc75de5b28d7572d1507bc.gif"
         alt="Mushroom Activate Ripple"
         data-base62-sha1="1PmSqpB1LpFXxvCwtidpUTPZFOk"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Ripple (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Activate Mushroom
icon: mdi:mushroom
icon_color: red
secondary: Ripple
tap_action:
  action: none
hold_action:
  action: none
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">overflow</span>: hidden;
    }  
    ha-card<span class="hljs-selector-pseudo">:after</span> {
      <span class="hljs-attribute">display</span>: none;
      <span class="hljs-attribute">content</span>: <span class="hljs-string">""</span>;
      <span class="hljs-attribute">position</span>: absolute;
      <span class="hljs-attribute">border-radius</span>: <span class="hljs-number">50%</span>;
      <span class="hljs-attribute">background-color</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-disabled), <span class="hljs-number">0.1</span>);
      <span class="hljs-attribute">width</span>: <span class="hljs-number">100px</span>;
      <span class="hljs-attribute">height</span>: <span class="hljs-number">100px</span>;
      <span class="hljs-attribute">margin-top</span>: -<span class="hljs-number">50px</span>;
      <span class="hljs-attribute">margin-left</span>: -<span class="hljs-number">50px</span>;
      <span class="hljs-attribute">top</span>: <span class="hljs-number">50%</span>;
      <span class="hljs-attribute">left</span>: <span class="hljs-number">50%</span>;
      <span class="hljs-attribute">animation</span>: ripple <span class="hljs-number">750ms</span>;
      <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>;
    }
    ha-card<span class="hljs-selector-pseudo">:active</span><span class="hljs-selector-pseudo">:after</span> {
      <span class="hljs-attribute">display</span>: block;
    }
    <span class="hljs-keyword">@keyframes</span> ripple {
      <span class="hljs-selector-tag">from</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-selector-tag">to</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">10</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/5/e/25ed9038bb1c9073d1420f4d3d6cc572cc8c10e9.gif"
         alt="Mushroom Activate 3D Perspective"
         data-base62-sha1="5pwDTSMvklXpzRcpsPmD00LnwQp"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate 3D Perspective (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">3D</span> <span class="hljs-string">Perspective</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    :host {
      perspective: 900px;
    }
    ha-card:active {
      transform: rotateY(20deg);
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/2/1/621d904e1fb0a9284c9a863776487eb6eedc2eb0.gif"
         alt="Mushroom Activate 3D Tilt"
         data-base62-sha1="dZY8buzJIJrVFSAvkF3pBNwFcK4"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate 3D Tilt (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">3D</span> <span class="hljs-string">Tilt</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    :host {
      perspective: 1000px;
    }
    ha-card:active {
      transform: rotate3d(0.5, -0.9, 0, 10deg) rotate(1deg);
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="267"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/b/4/7b43b0b32d75bec51024a658460187dfac43ea38.gif"
         alt="Mushroom Activate 3D Flap"
         data-base62-sha1="hArKMnUnwopDuOP2XPRN8J7WPkk"
         width="267"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 267 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate 3D Flap (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">3D</span> <span class="hljs-string">Flap</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    :host {
      perspective: 900px;
    }
    ha-card:active {
      transform: rotateX(25deg);
      transform-origin: center bottom;
      transition: 0s;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/c/9/bc99d523341f5fc2a7b9ec28a5a5975171d54816.gif"
         alt="Mushroom Activate Trash"
         data-base62-sha1="qUrlEkFlM8SMex597SznOoXJbzE"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Activate Icon Spin (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Activate</span> <span class="hljs-string">Mushroom</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">secondary:</span> <span class="hljs-string">Icon</span> <span class="hljs-string">Spin</span>
<span class="hljs-attr">tap_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">hold_action:</span>
  <span class="hljs-attr">action:</span> <span class="hljs-string">none</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-card:active mushroom-shape-icon { 
        display: flex;
        #--icon-animation: spin 1s;
        transform: rotate(360deg);
        transition: 500ms;
    }
</span></code></pre>
   </details>
   <h2>
      <a name="applying-active-animations-to-your-theme-unchanged-4"
         class="anchor"
         href="#applying-active-animations-to-your-theme-unchanged-4"></a>Applying Active Animations to your Theme (unchanged)
   </h2>
   <p>Rather than applying the active animations to each card, you can apply the to all cards by adding the <code>card_mod</code> to your theme.</p>
   <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">Mushroom Custom:
  card-mod-theme: <span class="hljs-string">"Mushroom Custom"</span>

  card-mod-card: |
    ha-card:active {
      <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.02</span>);
      <span class="hljs-attribute">transition</span>: <span class="hljs-number">0s</span>;
    }
</code></pre>
   <p>Reference documentation</p>
   <p><a href="https://github.com/thomasloven/lovelace-card-mod/wiki/Card-mod-Themes"
         rel="noopener nofollow ugc">Card mod Themes · thomasloven/lovelace-card-mod Wiki · GitHub <span class="badge badge-notification clicks"
            title="24 clicks">24</span></a><br>
      <a href="https://github.com/thomasloven/lovelace-card-mod/blob/b8c48b925643389fea5b1c0185ad7e0cbbd2bb76/README-themes.md"
         rel="noopener nofollow ugc">lovelace-card-mod/README-themes.md at master · thomasloven/lovelace-card-mod · GitHub <span class="badge badge-notification clicks"
            title="6 clicks">6</span></a>
   </p>
   <p>Updated Posts <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"><br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7717">Part 1</a>, Part 2, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7723">Part 3</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7725">Part 4</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7726">Part 5</a><br>
      Original Posts by <a class="mention"
         href="/u/rhysb">@rhysb</a> <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"> please only like his posts.<br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3240">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3256">Part 2</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3272">Part 3</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3348">Part 4</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/4043">Part 5</a>
   </p>
   <h2>
      <a name="more-mushroom-card-icon-animations-1"
         class="anchor"
         href="#more-mushroom-card-icon-animations-1"></a>More Mushroom Card Icon Animations
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/d/1/6d11a5cbe3a42ecbeb37bfa40fe8259a179f7e66.gif"
         alt="Mushroom Flash Animation"
         data-base62-sha1="fyRQXsBI84VXYXW9jjiWHf1pTGS"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Flash Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: flash <span class="hljs-number">4s</span> linear infinite;
    }
    <span class="hljs-keyword">@keyframes</span> flash {
      <span class="hljs-number">0%</span>, <span class="hljs-number">4%</span>, <span class="hljs-number">8%</span>, <span class="hljs-number">12%</span>, <span class="hljs-number">16%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">24%</span>, <span class="hljs-number">28%</span>, <span class="hljs-number">32%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0px</span>,<span class="hljs-number">0px</span>); }
      <span class="hljs-number">2%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.3px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">6%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.3px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.2px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">14%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.2px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">18%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.2px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">22%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.5px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">26%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.5px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">34%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">1px</span>, <span class="hljs-number">5px</span>); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
      <span class="hljs-number">38%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0px</span>, <span class="hljs-number">0px</span>); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-white)); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/7/b/f7bf1106d098a2209d87fb2a8e026e0a9e7ab629.gif"
         alt="Mushroom Charge Animation"
         data-base62-sha1="zlFibugdj8UgHsRLTkts83bX2vD"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Charge Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-template-card
icon: mdi:lightning-bolt
icon_color: amber
primary: Charge
card_mod:
  style: |
    ha-state-icon {
      animation: charge 1s linear infinite;
    }
    @keyframes charge {
      0%, 10%, 20%, 30%, 40%, 50%, 60%, 70%, 80%, 90%, 100% { transform: translate(0, 0); }
      5% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      15% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      25% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      35% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      45% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      55% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      65% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      75% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      85% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
      95% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-10</span>, <span class="hljs-number">10</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px); }
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/c/2/7c223e70f708aae6a68bce582ea9f90c5c1f7356.gif"
         alt="Mushroom Double Rainbow Animation"
         data-base62-sha1="hI8zyPtFLrCHjs04B9ewODFwLie"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Double Rainbow Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:looks
primary: Double Rainbow
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: rainbow <span class="hljs-number">40s</span> linear infinite;
      }
      <span class="hljs-keyword">@keyframes</span> rainbow {
        <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> {<span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow), <span class="hljs-number">0.2</span>); }
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue), <span class="hljs-number">0.2</span>); }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">81.25%</span> { -<span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple), <span class="hljs-number">0.2</span>);}
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink), <span class="hljs-number">0.2</span>);}
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: double <span class="hljs-number">3s</span> linear infinite alternate, rainbow <span class="hljs-number">40s</span> linear infinite
      }
      <span class="hljs-keyword">@keyframes</span> double {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">98%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">0deg</span>); }
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">22%</span>, <span class="hljs-number">0</span> <span class="hljs-number">75%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>); }
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">75%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">0deg</span>); }
        <span class="hljs-number">50.1%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">75%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">50%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">22%</span>, <span class="hljs-number">0</span> <span class="hljs-number">75%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">98%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
      }
      <span class="hljs-keyword">@keyframes</span> rainbow {
        <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> {<span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red));}
        <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange));}
        <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange));}
        <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber));}
        <span class="hljs-number">25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow));}
        <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime));}
        <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green));}
        <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green));}
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal));}
        <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan));}
        <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue));}
        <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue));}
        <span class="hljs-number">75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo));}
        <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple));}
        <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple));}
        <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink));}
      }
</code></pre>
   </details>
   <p><img src="https://community-assets.home-assistant.io/original/4X/5/3/1/53195e5a4fe8fb859af4be3642a999a852c5cdd0.png"
         alt="Mushroom Random Animation"
         data-base62-sha1="bR7YSBM3lQ89YmzNgJS42AA3iqk"
         width="264"
         height="69"
         loading="lazy"
         style="aspect-ratio: 264 / 69;"></p>
   <details>
      <summary>
         Random Animation (unchanged, FYI if you dont know. this only updates when the page is refreshed. it is not an active animation.)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-template-card
icon: none
icon_color: red
primary: Random
card_mod:
  style: |
    :host {
      --card-mod-icon: mdi:dice-</span><span class="hljs-template-variable">{{<span class="hljs-name">range</span>(<span class="hljs-name">1</span>, <span class="hljs-number">6</span>) | random}}</span><span class="language-xml">;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/e/a/eeaf902756a4ae4e25a5ff0780cc5d243052cb6d.gif"
         alt="Mushroom Sparkle Animation"
         data-base62-sha1="y3vMmZpsx9mFrVj9rWnJrnPHYKx"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Sparkle Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:shimmer
icon_color: amber
primary: Sparkle
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-disabled), <span class="hljs-number">0.2</span>);
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: stars <span class="hljs-number">4s</span> linear infinite;
      }
      <span class="hljs-keyword">@keyframes</span> stars {
        <span class="hljs-number">0%</span>, <span class="hljs-number">3.1%</span>, <span class="hljs-number">14.1%</span>, <span class="hljs-number">40.1%</span>, <span class="hljs-number">55.1%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">3%</span>, <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">48%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">48%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">0</span> <span class="hljs-number">63%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">99%</span> <span class="hljs-number">100%</span>); }
        <span class="hljs-number">14%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">49%</span> <span class="hljs-number">45%</span>, <span class="hljs-number">48%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">36%</span>); }
        <span class="hljs-number">55%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">60%</span>, <span class="hljs-number">41%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">49%</span> <span class="hljs-number">46%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/0/6/506ef33042b8f47e32a6df06be828befedc7254e.gif"
         alt="Mushroom Eeeew Animation"
         data-base62-sha1="btxUdOffQ6tBCGchdKtful3eMii"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Eeeew Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:bacteria
icon_color: light-green
primary: Eeeew
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: wiggle <span class="hljs-number">0.5s</span> ease infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">80%</span> <span class="hljs-number">80%</span>;
    }
    mushroom-shape-<span class="hljs-attribute">icon</span> {
      <span class="hljs-attribute">display</span>: flex;
      <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">20s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> wiggle {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">1deg</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.04</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">2deg</span>); }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/7/b/07b07fb2775d1a91c3372df731249db94750c0d0.gif"
         alt="Mushroom Sunny Animation"
         data-base62-sha1="161ukJprBAKEFUK1cYePQROjc9a"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Sunny Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Sunny
icon: mdi:weather-sunny
icon_color: amber
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: sunny <span class="hljs-number">8s</span> ease-in-out infinite alternate;
    }
    <span class="hljs-keyword">@keyframes</span> sunny {
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">360deg</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
      <span class="hljs-number">90%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.15</span>); }
      <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/a/4/1a4175814efdcd3d7b07027d3a7b98155bab51f9.gif"
         alt="Mushroom Cloudy Animation"
         data-base62-sha1="3KgET7IkgYBwfOEiNEsry2WwB4d"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Cloudy Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Cloudy
icon: mdi:weather-cloudy
icon_color: grey
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite;
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/b/b/dbbd1d3e8d3113331bf6855fb7c648517193a4aa.gif"
         alt="Mushroom Rainy Animation"
         data-base62-sha1="vlTJXYGTyB0eqVcldoFGs6C1Pdw"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Rainy Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Rainy
icon: mdi:weather-rainy
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, rain <span class="hljs-number">1.5s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> rain {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">39%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">0</span> <span class="hljs-number">73%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/3/2/b32ef92f3eab7937d7644cfd606d420120774936.gif"
         alt="Mushroom Pouring Animation"
         data-base62-sha1="pz86E6njSe7Q9u46YaAQAPbu1fM"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Pouring Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Pouring
icon: mdi:weather-pouring
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, rain <span class="hljs-number">1s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> rain {
      <span class="hljs-number">0%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">47%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">46%</span>, <span class="hljs-number">38%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">0</span> <span class="hljs-number">83%</span>); }
      <span class="hljs-number">75%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">94%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">94%</span>, <span class="hljs-number">46%</span> <span class="hljs-number">46%</span>, <span class="hljs-number">30%</span> <span class="hljs-number">46%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">0</span> <span class="hljs-number">72%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/7/4/27452f0c68db3a59c4343343407b0a535ff430ad.gif"
         alt="Mushroom Tornado Animation"
         data-base62-sha1="5BoQvyyLVcJJHux7Fq5xWgHYcrz"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Tornado Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Tornado
icon: mdi:weather-tornado
icon_color: orange
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: tornado <span class="hljs-number">3s</span> ease-in-out infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> tornado {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>) <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">0deg</span>); }
      <span class="hljs-number">0.1%</span>, <span class="hljs-number">45.1%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>) <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
      <span class="hljs-number">30.1%</span>, <span class="hljs-number">75.1%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">0deg</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>) <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">0deg</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>) <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/d/f/6df3afb289c611e6dd06c555c39ba71ad7d5b38c.gif"
         alt="Mushroom Lightning Animation"
         data-base62-sha1="fGG8Fq1HzHuJBwdsR2YAoeFLhwM"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Lightning Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Lightning
icon: mdi:weather-lightning
icon_color: amber
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, lightning <span class="hljs-number">4s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> lightning {
      <span class="hljs-number">10%</span>, <span class="hljs-number">15%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">48%</span> <span class="hljs-number">39%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.1</span>); }
      <span class="hljs-number">10.1%</span>, <span class="hljs-number">15.1%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/6/f/26faeae0e0d26a301fc6753546768297215789b9.gif"
         alt="Mushroom Clear Night Animation"
         data-base62-sha1="5yPJoiGt8rRi7LwGIZCRhiHvRMd"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Clear Night Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:weather-night
icon_color: amber
primary: Clear Night
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: moon <span class="hljs-number">10s</span> linear infinite, stars <span class="hljs-number">5s</span> linear infinite;
    }
    <span class="hljs-keyword">@keyframes</span> moon {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">12deg</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">6deg</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">8deg</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">10deg</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> stars {
      <span class="hljs-number">0%</span>, <span class="hljs-number">3.1%</span>, <span class="hljs-number">14.1%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">3%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">1%</span> <span class="hljs-number">1%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">99%</span>, <span class="hljs-number">99%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">99%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">99%</span> <span class="hljs-number">0%</span>); }
      <span class="hljs-number">14%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">1%</span> <span class="hljs-number">1%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">99%</span>, <span class="hljs-number">99%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">45%</span>, <span class="hljs-number">38%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">0</span>); }
    } 
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/2/0/0200f30f7a5f02c0a52e8671acc101a7e341ea0e.gif"
         alt="Mushroom Windy Animation"
         data-base62-sha1="hIZkfrHKINBV4jjCqMnPVlowZo"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Windy Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Windy
icon: mdi:weather-windy
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite; 
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1.2</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.9</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1.1</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.8</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/7/4/b74e80b6036dde158f12819a428574ce4529d5d2.gif"
         alt="Mushroom Wind Animation"
         data-base62-sha1="q9Bzfnu8Y5f2657GwnzyZnrdGam"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Wind Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Wind
icon: mdi:weather-windy-variant
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, wind <span class="hljs-number">5s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> wind {
      <span class="hljs-number">0%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">37%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/e/5/de5d519dc79320bcd8eb32f10381660cf5ce0225.gif"
         alt="Mushroom Snow Animation"
         data-base62-sha1="vJ7VQKabILerXpGVYU9FDzv7BFb"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Snow Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Snow
icon: mdi:weather-snowy
icon_color: grey
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, snow <span class="hljs-number">4s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> snow {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">65%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">49%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">26%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">37%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">51%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/8/e/38e02c8c2e2f85015364ec5c67412f62b6104483.gif"
         alt="Mushroom Hail Animation"
         data-base62-sha1="8791NiNfpDJbSzgVC0oZzV1R13Z"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Hail Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Hail
icon: mdi:weather-hail
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, hail <span class="hljs-number">2s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> hail {
      <span class="hljs-number">0%</span>, <span class="hljs-number">26%</span>, <span class="hljs-number">51%</span>, <span class="hljs-number">76%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">43%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">58%</span>, <span class="hljs-number">48%</span> <span class="hljs-number">68%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">86%</span>, <span class="hljs-number">74%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">46%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">87%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">68%</span>, <span class="hljs-number">27%</span> <span class="hljs-number">81%</span>, <span class="hljs-number">37%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/c/4/ec4e56cb790436b8a9cfd21e29b5531970e888d8.gif"
         alt="Mushroom Hurricane Animation"
         data-base62-sha1="xIswsUr90tw5kzMd57z1SB4Jjyo"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Hurricane Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Hurricane</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:weather-hurricane</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
      animation: spin 1.5s linear infinite reverse; 
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/8/b/7/8b75b2c4281d15a6a40c3e43b11ecec2d22e34bc.gif"
         alt="Mushroom Dust Animation"
         data-base62-sha1="jTIxdNRZPe29hYf5Rz49v1TBD2Y"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Dust Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Dust
icon: mdi:weather-dust
icon_color: brown
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: wind <span class="hljs-number">10s</span> ease-in-out infinite, dust <span class="hljs-number">1s</span> infinite; 
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">15%</span> <span class="hljs-number">50%</span>
    }
    <span class="hljs-keyword">@keyframes</span> wind {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1.2</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.9</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1.1</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.8</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> dust {
      <span class="hljs-number">0%</span>, <span class="hljs-number">21%</span>, <span class="hljs-number">41%</span>, <span class="hljs-number">61%</span>, <span class="hljs-number">81%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">69%</span> <span class="hljs-number">0</span>, <span class="hljs-number">72%</span> <span class="hljs-number">27%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">40%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">0</span> <span class="hljs-number">79%</span>); }
      <span class="hljs-number">60%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">30%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">28%</span>, <span class="hljs-number">30%</span> <span class="hljs-number">28%</span>); }
      <span class="hljs-number">80%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">61%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">46%</span>, <span class="hljs-number">0</span> <span class="hljs-number">46%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/2/0/520e0b016fd49c4e00af2473c81a1f9f6da3372e.gif"
         alt="Mushroom Foggy Animation"
         data-base62-sha1="bHTeQOq115nnY2fGkTWRc3oMr6K"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Foggy Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Foggy
icon: mdi:weather-fog
icon_color: grey
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, fog <span class="hljs-number">4s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> fog {
      <span class="hljs-number">0%</span>, <span class="hljs-number">26%</span>, <span class="hljs-number">76%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">26%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">26%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">0</span> <span class="hljs-number">76%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/7/6/7762231e6bc4093266fdc0f342fd5e3a65a8685c.gif"
         alt="Mushroom Partly Cloudy Animation"
         data-base62-sha1="h274LI8DXmjB7i0L5SdUYp7MJR2"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Partly Cloudy Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Cloudy
icon: mdi:weather-partly-cloudy
icon_color: amber
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: cloudy <span class="hljs-number">10s</span> ease-in-out infinite, sun <span class="hljs-number">2s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> cloudy {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">3px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">1px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">1.5px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">3.2px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> sun {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">67%</span>, <span class="hljs-number">18%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">16%</span> <span class="hljs-number">31%</span>, <span class="hljs-number">41%</span> <span class="hljs-number">12%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">24%</span>, <span class="hljs-number">77%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/1/a/a1a845b1fcf638c338fc944b55db2c3c9e6e0dd1.gif"
         alt="Mushroom Fireplace Animation"
         data-base62-sha1="n45orXbVyoKBqdWGaE7AekujKbD"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Fireplace Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Fireplace
icon: mdi:fireplace
icon_color: red
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: fire <span class="hljs-number">800ms</span> infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">85%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> fire {
        <span class="hljs-number">0%</span>, <span class="hljs-number">19%</span>, <span class="hljs-number">23%</span>, <span class="hljs-number">39%</span>, <span class="hljs-number">43%</span>, <span class="hljs-number">49%</span>, <span class="hljs-number">53%</span>, <span class="hljs-number">69%</span>, <span class="hljs-number">73%</span>, <span class="hljs-number">89%</span>, <span class="hljs-number">93%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
        <span class="hljs-number">20%</span>, <span class="hljs-number">40%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">70%</span>, <span class="hljs-number">90%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">65%</span> <span class="hljs-number">99%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">49%</span>, <span class="hljs-number">52%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">33%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">33%</span> <span class="hljs-number">82%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">82%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="63"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/0/4/104bea290004b27e7965734ff25c3fda5ee3da58.gif"
         alt="Mushroom Washing Machine #2 Animation"
         data-base62-sha1="2kahJmW6xz9mGaK3XXT0NsVLc5q"
         width="263"
         height="63"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 63;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Washing Machine #2 Animation (changed, fyi you can even make the drum a different color to the main icon.)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:washing-machine
    icon_color: orange
    primary: <span class="hljs-string">'Washing Machine #2'</span>
    card_mod:
      style: |
          ha-state-icon {
            <span class="hljs-attribute">animation</span>: shake <span class="hljs-number">400ms</span> ease-in-out infinite;
            <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">58%</span>;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">68%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">41%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">65%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>);
          }
          <span class="hljs-keyword">@keyframes</span> shake {
            <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0</span>, <span class="hljs-number">0</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">20%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.4px</span>, -<span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
            <span class="hljs-number">40%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.4px</span>, <span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">4deg</span>); }
            <span class="hljs-number">60%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">0.4px</span>, <span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">4deg</span>); }
            <span class="hljs-number">80%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">0.4px</span>, -<span class="hljs-number">0.4px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">4deg</span>); }
          }
  - type: custom:mushroom-template-card
    icon: mdi:washing-machine
    icon_color: orange
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attribute">background</span>: none <span class="hljs-meta">!important</span>;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite;
            <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">58%</span>;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">21.7%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">58%</span>);
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/b/b/2bbc92e6aada904e5fa86df065736a5e08651099.gif"
         alt="Mushroom Pot Animation"
         data-base62-sha1="6eUy1ALmcKqUSRo2Fs6DYL7u8dP"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Pot Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:pot-steam
icon_color: grey
primary: Pot
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: steam <span class="hljs-number">2s</span> ease-in-out infinite;
    }
    <span class="hljs-keyword">@keyframes</span> steam {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">39%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/9/5/e/95e4e17c4a6e7f5221aefe614b9ab2b57dfaf24a.gif"
         alt="Mushroom Serenity Animation"
         data-base62-sha1="lo1w71f8H3DLqFmjOM2Yid5BSqu"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Serenity Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Serenity
icon: mdi:scent
icon_color: green
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: color <span class="hljs-number">6s</span> ease infinite;
      }
      <span class="hljs-keyword">@keyframes</span> <span class="hljs-attribute">color</span> {
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-cyan), <span class="hljs-number">0.2</span>); }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: wave <span class="hljs-number">6s</span> ease infinite;
      }
      <span class="hljs-keyword">@keyframes</span> wave {
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotatey</span>(<span class="hljs-number">180deg</span>); <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/d/7/fd7141d07aee7e96a4d491b7cd4d240309d44d55.gif"
         alt="Mushroom Music #1 Animation"
         data-base62-sha1="Aa3s2jk5SXGTa3cR14AiWl75UX3"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Music #1 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: <span class="hljs-string">'Music #1'</span>
icon: mdi:music
icon_color: blue
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">perspective</span>: <span class="hljs-number">7px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: music <span class="hljs-number">2s</span> ease-in-out infinite alternate;
        <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">100%</span>
      }
      <span class="hljs-keyword">@keyframes</span> music {
        <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0px</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1</span>); }
        <span class="hljs-number">20%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">2px</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">0.9</span>); }
        <span class="hljs-number">40%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">10deg</span>) <span class="hljs-built_in">rotateZ</span>(-<span class="hljs-number">10deg</span>); }
        <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">4px</span>) <span class="hljs-built_in">scaleX</span>(<span class="hljs-number">1.1</span>); }
        <span class="hljs-number">80%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(-<span class="hljs-number">10deg</span>) <span class="hljs-built_in">rotateZ</span>(<span class="hljs-number">10deg</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/9/2/c/92cd32a540a0cf9da905cd0dd4ee579de824cc03.gif"
         alt="Mushroom Music #2 Animation"
         data-base62-sha1="kWFlofjIRRkoJUvAPC2eD08gOz1"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Music #2 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: <span class="hljs-string">'Music #2'</span>
icon: mdi:music
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: beat <span class="hljs-number">1.3s</span> ease-out infinite both;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">80%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> beat {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.1</span>); }
      <span class="hljs-number">17%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.05</span>); }
      <span class="hljs-number">33%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.25</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/3/4/a341792e86d120b3acfd49db0e284bc8be405d0c.gif"
         alt="Mushroom Playlist Animation"
         data-base62-sha1="nie6qIava9iRCrbMK1Y62AGqigk"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Playlist Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:format-list-bulleted-square
icon_color: purple
primary: Playlist
card_mod:
  style: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: clip <span class="hljs-number">2s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">4</span>) infinite;
      }
      <span class="hljs-keyword">@keyframes</span> clip {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">85%</span> <span class="hljs-number">0</span>); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> -<span class="hljs-number">5%</span> <span class="hljs-number">0</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/e/8/1e80c56177ada29f5c4f060b04d6f5c53366f52e.gif"
         alt="Mushroom Grain Animation"
         data-base62-sha1="4lQdjuvjIipWSHrr6dBtgFcX9YW"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Grain Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:grain
icon_color: brown
primary: Grain
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: flip <span class="hljs-number">1s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite;
    }
    <span class="hljs-keyword">@keyframes</span> flip {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/f/3/bf3957c092a6907aaabbae81d62a66c0807f50c2.gif"
         alt="Mushroom Focus Animation"
         data-base62-sha1="rhE3iv2LGe74ylvcLR1yguTUK8G"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Focus Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:bullseye
icon_color: purple
primary: Focus
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: focus <span class="hljs-number">4s</span> linear infinite alternate;
    }
    <span class="hljs-keyword">@keyframes</span> focus {
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">filter</span>: <span class="hljs-built_in">blur</span>(<span class="hljs-number">10px</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/8/a/48aca787b909e564162ae6c580a698197168baa9.gif"
         alt="Mushroom Access Point Animation"
         data-base62-sha1="amUhS20F3ZzWRcgvx53BNmD5hWh"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Access Point Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:access-point
icon_color: teal
primary: Access Point
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: ping <span class="hljs-number">1.5s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> ping {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">1px</span> <span class="hljs-number">1px</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-teal), <span class="hljs-number">0.3</span>) inset; }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">15px</span> transparent inset; }
        <span class="hljs-number">51%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">1px</span> <span class="hljs-number">1px</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-teal), <span class="hljs-number">0.3</span>); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">15px</span> transparent; }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: clip <span class="hljs-number">1.5s</span> infinite;
      }
      <span class="hljs-keyword">@keyframes</span> clip {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">13.0%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">50%</span>); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">50.0%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">50%</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/6/7/b67fd007439de054720e5b44fad19552eb1083ff.gif"
         alt="Mushroom Alert Animation"
         data-base62-sha1="q2sJGyy0uJs0OlelNwWWtX9XX67"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Alert Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Alert!
icon: mdi:fire
icon_color: red
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attr">--shape-animation</span>: ping <span class="hljs-number">1.5s</span> infinite, blink <span class="hljs-number">1.5s</span> ease-in-out infinite;;
      }
      <span class="hljs-keyword">@keyframes</span> ping {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.7</span>); }
        <span class="hljs-number">100%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">15px</span> transparent; }
      }
      <span class="hljs-keyword">@keyframes</span> blink {
        <span class="hljs-number">100%</span> {<span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>;}
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/9/d/79d9dc50f0fe12ac0ba8662689446f8a4c68a1e1.gif"
         alt="Mushroom Record Animation"
         data-base62-sha1="hnWxmz8El4kySedf2Hc0atFgChX"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Record Animation (unchanged, doesnt work well on a dark background unless you set a --shape-color.)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:record-circle
icon_color: cyan
primary: Record
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(-<span class="hljs-number">45deg</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-black), <span class="hljs-number">0.4</span>) <span class="hljs-number">0%</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-black), <span class="hljs-number">0.6</span>) <span class="hljs-number">50%</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-black), <span class="hljs-number">0.4</span>) <span class="hljs-number">100%</span>);
        <span class="hljs-attr">--shape-animation</span>: spin <span class="hljs-number">400ms</span> linear infinite;
        <span class="hljs-attr">--shape-color</span>: none;
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/e/f/5efec1a11befce93cc58964996c7b6c45debcae7.gif"
         alt="Mushroom Heart Animation"
         data-base62-sha1="dymH6ps7iNtgQbzulBR57eMDj9B"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Heart Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Heart
icon: mdi:heart
icon_color: red
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">60%</span>;
        <span class="hljs-attr">--shape-animation</span>: heart <span class="hljs-number">1.3s</span> ease-out infinite both;
      }
      <span class="hljs-keyword">@keyframes</span> heart {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.2</span>); }
        <span class="hljs-number">10%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">5px</span> transparent; }
        <span class="hljs-number">17%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.2</span>); }
        <span class="hljs-number">33%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">5px</span> <span class="hljs-number">5px</span> transparent; }
        <span class="hljs-number">60%</span> { <span class="hljs-attribute">box-shadow</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-red), <span class="hljs-number">0.2</span>); }
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: beat <span class="hljs-number">1.3s</span> ease-out infinite both;
      }
      <span class="hljs-keyword">@keyframes</span> beat {
        <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
        <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.1</span>); }
        <span class="hljs-number">17%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.05</span>); }
        <span class="hljs-number">33%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.25</span>); }
        <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/d/3/4d37c01ca9f1db1350357a6908a093a4bd94a27b.gif"
         alt="Mushroom Play Animation"
         data-base62-sha1="b16d1busaYXh8hovTVpx3CefQEj"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Play Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:play</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">orange</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Play</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
      animation: spin 4s steps(4) infinite;
    }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/a/0/4a05840bddc1320d8be1f5056259e3be2639b7a3.gif"
         alt="Mushroom Christmas Tree Animation"
         data-base62-sha1="ayP9k29eugQML1qV05OEGkxpmkH"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Christmas Tree Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:pine-tree
    icon_color: green
    primary: Christmas Tree
  - type: custom:mushroom-template-card
    icon: mdi:star-four-points
    icon_color: yellow
    primary: Star
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: star <span class="hljs-number">8s</span> ease infinite alternate;
          }
          <span class="hljs-keyword">@keyframes</span> star {
            <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">10px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0deg</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">0.4</span>); }
            <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">10px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">360deg</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">0.6</span>); }
          }
  - type: custom:mushroom-template-card
    icon: mdi:gift
    icon_color: red
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
            <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">20px</span>;
            <span class="hljs-attribute">top</span>: <span class="hljs-number">16px</span>;
            <span class="hljs-attribute">left</span>: <span class="hljs-number">18px</span>;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">132px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: surprise <span class="hljs-number">4s</span> ease infinite;
          }
          <span class="hljs-keyword">@keyframes</span> surprise {
            <span class="hljs-number">0%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">2.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">27deg</span>); }
            <span class="hljs-number">5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">21deg</span>); }
            <span class="hljs-number">7.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
            <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">9deg</span>); }
            <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">15%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">1.2px</span>) }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/7/f/77f52d44976fcded534fc8b8d8ef14003dd84304.gif"
         alt="Mushroom Doggy Animation"
         data-base62-sha1="h7c6GP3F08NYvRW74Oophx9PGAc"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Doggy Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Doggy
icon: mdi:dog
icon_color: brown
card_mod:
  style: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: huh <span class="hljs-number">4s</span> ease infinite;
        <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">60%</span>;
      }
      <span class="hljs-keyword">@keyframes</span> huh {
        <span class="hljs-number">0%</span>, <span class="hljs-number">10%</span>, <span class="hljs-number">75%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0deg</span>); }
        <span class="hljs-number">15%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">25deg</span>); }
        <span class="hljs-number">30%</span>, <span class="hljs-number">35%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">40deg</span>); }
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">12deg</span>); }
        <span class="hljs-number">65%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">8deg</span>); }
      }
</code></pre>
   </details>
   <p>Updated Posts <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"><br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7717">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7719">Part 2</a>, Part 3, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7725">Part 4</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7726">Part 5</a><br>
      Original Posts by <a class="mention"
         href="/u/rhysb">@rhysb</a> <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"> please only like his posts.<br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3240">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3256">Part 2</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3272">Part 3</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3348">Part 4</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/4043">Part 5</a>
   </p>
   <h2>
      <a name="even-more-mushroom-card-icon-animations-2"
         class="anchor"
         href="#even-more-mushroom-card-icon-animations-2"></a>Even More Mushroom Card Icon Animations
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/2/c/72c1ab23ef76375bcdec68d1db056c7aa7319d55.gif"
         alt="Mushroom HA Animation"
         data-base62-sha1="gnbmBcdQa9qtD0u3VwwHqX09ZRP"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         HA Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:home-assistant
icon_color: blue
primary: Home Assistant
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: boing <span class="hljs-number">3s</span> ease infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">90%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> boing {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">7%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.25</span>, <span class="hljs-number">0.75</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.75</span>, <span class="hljs-number">1.25</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">12%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.15</span>, <span class="hljs-number">0.85</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">16%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.95</span>, <span class="hljs-number">1.05</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">19%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.05</span>, <span class="hljs-number">0.95</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/3/8/f381e2811c6882688bcfb6c202b22915cb1af047.gif"
         alt="Mushroom Surprise Animation"
         data-base62-sha1="yKaiJAwyChqb2rrSIsuFDdM25Yr"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Surprise Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:gift
icon_color: deep-orange
primary: Surprise
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: surprise <span class="hljs-number">3s</span> ease infinite;
    }
    <span class="hljs-keyword">@keyframes</span> surprise {
      <span class="hljs-number">0%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">2.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">6px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">14deg</span>); }
      <span class="hljs-number">5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">6px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">11deg</span>); }
      <span class="hljs-number">7.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">6px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">8deg</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">6px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">5deg</span>); }
      <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
      <span class="hljs-number">15%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">3px</span>) }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/0/e/60e6f16dc8b36da7bf8b75c782e8a1cfacf7b3e6.gif"
         alt="Mushroom Ring Animation"
         data-base62-sha1="dPeD5nRaVZ4bp5hbFjY2ROcoanI"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Ring Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:phone-classic
    icon_color: light-green
    primary: Ring
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">67%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">39%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">0</span> <span class="hljs-number">68%</span>);
        }
  - type: custom:mushroom-template-card
    icon: mdi:phone-hangup
    icon_color: light-green
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">4px</span>;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: ring <span class="hljs-number">1s</span> ease infinite;
          }
          <span class="hljs-keyword">@keyframes</span> ring {
            <span class="hljs-number">0%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">4px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">27deg</span>); }
            <span class="hljs-number">20%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">4px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">21deg</span>); }
            <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">4px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
            <span class="hljs-number">40%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">4px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">9deg</span>); }
            <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2.4px</span>); }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/8/1/5815632498c2dc155a841b44ffee607e34ff0180.gif"
         alt="Mushroom Marker Animation"
         data-base62-sha1="czdQ2LyKN7qspNhRoeUPgWPwX8Q"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Marker Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:map-marker
icon_color: red
primary: Marker
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: boing <span class="hljs-number">3s</span> ease infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">90%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> boing {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">7%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">4px</span>) <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.75</span>, <span class="hljs-number">1.25</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.25</span>, <span class="hljs-number">0.75</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">12%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.85</span>, <span class="hljs-number">1.15</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">16%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.05</span>, <span class="hljs-number">0.95</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">19%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.95</span>, <span class="hljs-number">1.05</span>, <span class="hljs-number">1</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/f/1/2f15d811a2ddf5e0b3f6973b08bdde7e58d3e7c5.gif"
         alt="Mushroom Beat Animation"
         data-base62-sha1="6IxeZ7m1Nfl8miEUHpuHCpwvczP"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Beat Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Beat
icon: mdi:speaker
icon_color: blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: beat <span class="hljs-number">1.3s</span> ease-out infinite both;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">60%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> beat {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.1</span>); }
      <span class="hljs-number">17%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.05</span>); }
      <span class="hljs-number">33%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.25</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/e/a/eea81797bbcd53e6f5d6a435309a618f5613acac.gif"
         alt="Mushroom Door Animation"
         data-base62-sha1="y3fLYjSdQ3hVH6ZaLseSZYi5JGk"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Door Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:door
icon_color: brown
primary: Door
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">perspective</span>: <span class="hljs-number">45px</span>;
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: open <span class="hljs-number">6s</span> ease-in-out infinite;
        <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">30%</span>;
      }
      <span class="hljs-keyword">@keyframes</span> open {
        <span class="hljs-number">0%</span>, <span class="hljs-number">66%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">0deg</span>); }
        <span class="hljs-number">33%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(-<span class="hljs-number">120deg</span>); }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/e/b/1ebf6618397cc797e5f60eb5ff44d22254bce8ca.gif"
         alt="Mushroom Bounce Animation"
         data-base62-sha1="4o0oraVfiqXnsLWAfpRRk4x9FdU"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Bounce Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:tennis-ball
icon_color: amber
primary: Bounce
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: bounce <span class="hljs-number">0.6s</span> <span class="hljs-built_in">cubic-bezier</span>(<span class="hljs-number">0.30</span>, <span class="hljs-number">2.40</span>, <span class="hljs-number">0.85</span>, <span class="hljs-number">2.50</span>) infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">100%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> bounce { 
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0px</span>) <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">0.9</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">3px</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/a/d/ead6d670ec3650469d839d6cd3e9e002b2d92666.gif"
         alt="Mushroom Ghost Animation"
         data-base62-sha1="xvu0Y9PQqh3m0lF5AEKMvHQnWLQ"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Ghost Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Ghost
icon: mdi:ghost-outline
icon_color: grey
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: drift <span class="hljs-number">10s</span> ease-in-out infinite, blink <span class="hljs-number">4s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> drift {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">3px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">1px</span>, <span class="hljs-number">2px</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">1.5px</span>, <span class="hljs-number">0px</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">3.2px</span>, -<span class="hljs-number">3px</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> blink {
      <span class="hljs-number">0%</span>, <span class="hljs-number">24%</span>, <span class="hljs-number">35%</span>, <span class="hljs-number">74%</span>, <span class="hljs-number">85%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">27%</span> <span class="hljs-number">31%</span>, <span class="hljs-number">49%</span> <span class="hljs-number">31%</span>, <span class="hljs-number">49%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">75%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">49%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">52%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">73%</span> <span class="hljs-number">31%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/a/7/7a7e4411f96cae05f88edfbd1fb544bb4c4181da.gif"
         alt="Mushroom Ducky Animation"
         data-base62-sha1="htCM2tbPKH5hgxkX7v7JRjQdC0a"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Ducky Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Rubber Ducky
icon: mdi:duck
icon_color: amber
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: ducky <span class="hljs-number">2s</span> ease-in-out infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">75%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> ducky {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">15deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/8/6/f8611492255f2ddb0653e39ae9d5a5d0efab46ca.gif"
         alt="Mushroom Robot Animation"
         data-base62-sha1="zrgpc5ZPRvz99EF7Jk1IAV2J2Wu"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Robot Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Robot
icon: mdi:robot-outline
icon_color: deep-purple
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: tilt <span class="hljs-number">4s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite, blink <span class="hljs-number">4s</span> infinite; 
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">92%</span>;
    }
    <span class="hljs-keyword">@keyframes</span> tilt {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0deg</span>); }
      <span class="hljs-number">33%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">8deg</span>); }
      <span class="hljs-number">66%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">8deg</span>); }
    }
    <span class="hljs-keyword">@keyframes</span> blink {
      <span class="hljs-number">0%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">30%</span>, <span class="hljs-number">45%</span>, <span class="hljs-number">55%</span>, <span class="hljs-number">70%</span>, <span class="hljs-number">80%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/a/7/da7c03a86058c2a64117b1917dd57b34784b4f15.gif"
         alt="Mushroom Coffee Machine Animation"
         data-base62-sha1="vaNMQRejAFqXCjOrXGFE97FbIQR"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Coffee Machine Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:coffee-maker
icon_color: brown
primary: Coffee Machine
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: java <span class="hljs-number">4s</span> linear infinite;
    }
    <span class="hljs-keyword">@keyframes</span> java {
      <span class="hljs-number">0%</span>, <span class="hljs-number">80%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">80%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">15%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">77%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">80%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">44%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">35%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">44%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">45%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">55%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">65%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">65%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">42%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">56%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/d/f/2df5aa53fe1aee4a643ece41d7038ccd80eb431c.gif"
         alt="Mushroom Apple Animation"
         data-base62-sha1="6yzOWMgcMV5yxSzMl8x7Th8tn8o"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Apple Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Apple
icon: mdi:food-apple
icon_color: green
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: bite <span class="hljs-number">4s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> bite {
      <span class="hljs-number">0%</span>, <span class="hljs-number">19%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">20%</span>, <span class="hljs-number">39%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">78%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">41%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">74%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">74%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">75%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">40%</span>, <span class="hljs-number">59%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">78%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">41%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">59%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">85%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">91%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">60%</span>, <span class="hljs-number">79%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">78%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">41%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">59%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">85%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">91%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">84%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">75%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">71%</span>, <span class="hljs-number">33%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">45%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">0</span> <span class="hljs-number">27%</span>); }
      <span class="hljs-number">80%</span>, <span class="hljs-number">99%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">78%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">41%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">59%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">85%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">91%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">88%</span>, <span class="hljs-number">37%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">67%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">59%</span>, <span class="hljs-number">35%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">45%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">0</span> <span class="hljs-number">27%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/c/6/6c6c6cc38ba2b1cfc09236fc9306097767166188.gif"
         alt="Mushroom Memory Animation"
         data-base62-sha1="ft9RGTm46RdcQfVXdqhY338IW0w"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Memory Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Memory
icon: mdi:memory
icon_color: orange
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: bit <span class="hljs-number">250ms</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> bit {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">30%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">70%</span> <span class="hljs-number">30%</span>, <span class="hljs-number">70%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">70%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/e/c/3/ec328f61704f164ad7bdb8ceba34bdf73b5c6458.gif"
         alt="Mushroom Pump Animation"
         data-base62-sha1="xHv0sPda1wHYfLfOAhnb8G7HROg"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Pump Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Pump
icon: mdi:water-pump
icon_color: light-blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: drip <span class="hljs-number">2s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> drip {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">15%</span>, <span class="hljs-number">85%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">57%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">57%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/6/9/169f466210f4e93188214579813229ab4755f657.gif"
         alt="Mushroom Power Animation"
         data-base62-sha1="3e7Ksoo5NpDZEoIUxd4yx56bNRl"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Power Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Power
icon: mdi:power
icon_color: teal
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: power <span class="hljs-number">1.5s</span> infinite; 
    }
    <span class="hljs-keyword">@keyframes</span> power {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">42%</span> <span class="hljs-number">0</span>, <span class="hljs-number">42%</span> <span class="hljs-number">58%</span>, <span class="hljs-number">58%</span> <span class="hljs-number">58%</span>, <span class="hljs-number">58%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/8/7/9/8799e226eb4798a65ea363f89a6583cb32a7e338.gif"
         alt="Mushroom Garage Animation"
         data-base62-sha1="jlA9r0IahvY9nBW6wRLLZeBd8tG"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Garage Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Garage
icon: mdi:garage
icon_color: amber
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: door <span class="hljs-number">3s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite alternate; 
    }
    <span class="hljs-keyword">@keyframes</span> door {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/3/5/a3555077eb3a8ec729a813759e8a7cefc067dd36.gif"
         alt="Mushroom Coffee Animation"
         data-base62-sha1="niUBZzs0lxhLSvcgWFUu0dJ04ku"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Coffee Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:coffee
    icon_color: brown
    primary: Coffee
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scaleY</span>(<span class="hljs-number">0.8</span>);
          <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">100%</span>;
        }
  - type: custom:mushroom-template-card
    icon: mdi:pot-steam
    icon_color: brown
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">2px</span>;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: steam <span class="hljs-number">2s</span> ease-in infinite;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">61%</span> <span class="hljs-number">0</span>);
          }
          <span class="hljs-keyword">@keyframes</span> steam {
            <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
            <span class="hljs-number">80%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/2/d/d2d9f5218f7daae761f8e4489e7ed1fb22ea23d3.gif"
         alt="Mushroom Auto Fix Animation"
         data-base62-sha1="u5heVa85pxNtN6RMJzK6Oo3jmqn"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Auto Fix Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:auto-fix
icon_color: cyan
primary: Auto Fix
card_mod:
  style: |
    ha-state-icon {
     <span class="hljs-attribute">animation</span>: sparkle <span class="hljs-number">1.8s</span> linear infinite, kadabra <span class="hljs-number">1.8s</span> ease-in-out infinite;
     <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">10%</span> <span class="hljs-number">90%</span>
    }
    <span class="hljs-keyword">@keyframes</span> sparkle {
      <span class="hljs-number">0%</span>, <span class="hljs-number">69%</span>, <span class="hljs-number">74%</span>, <span class="hljs-number">79%</span>, <span class="hljs-number">85%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">76%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">39%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">26%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">100%</span>); }
    } 
    <span class="hljs-keyword">@keyframes</span> kadabra {
      <span class="hljs-number">0%</span>, <span class="hljs-number">65%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">20deg</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">15deg</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">25deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/1/b/11b49f00caa93aaf12e1acf9683eb9c7525fabaf.gif"
         alt="Mushroom Grinder Animation"
         data-base62-sha1="2wD5WLjCACePkuC6jvGbbJn8sa3"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Grinder Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:blender
icon_color: orange
primary: Grinder
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: shake <span class="hljs-number">400ms</span> ease-in-out infinite;
      <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">90%</span>;
      <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">24%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">75%</span>, <span class="hljs-number">33%</span> <span class="hljs-number">62%</span>);
    }
    <span class="hljs-keyword">@keyframes</span> shake {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">3deg</span>); }
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">3deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/b/e/8/be823c2a43a0922e09c39e1b62da231de3f4f75c.gif"
         alt="Mushroom Solar Panel Animation"
         data-base62-sha1="rbjKi2v08Jxsgqv8NS2RKF3wkFe"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Solar Panel Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:solar-power-variant
icon_color: amber
primary: Solar Panel
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: rays <span class="hljs-number">2s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> rays {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">100%</span> <span class="hljs-number">99%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">99%</span>, <span class="hljs-number">11%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">57%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">31%</span>, <span class="hljs-number">41%</span> <span class="hljs-number">31%</span>, <span class="hljs-number">33%</span> <span class="hljs-number">25%</span>, <span class="hljs-number">29%</span> <span class="hljs-number">18%</span>, <span class="hljs-number">27%</span> <span class="hljs-number">11%</span>, <span class="hljs-number">27%</span> <span class="hljs-number">6%</span>, <span class="hljs-number">74%</span> <span class="hljs-number">6%</span>, <span class="hljs-number">73%</span> <span class="hljs-number">15%</span>, <span class="hljs-number">69%</span> <span class="hljs-number">23%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">29%</span>, <span class="hljs-number">71%</span> <span class="hljs-number">42%</span>, <span class="hljs-number">87%</span> <span class="hljs-number">47%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/5/c/b/5cb93651d0c21aa02aa7ae0d6f7f92eed864ea1d.gif"
         alt="Mushroom Light Bulb Animation"
         data-base62-sha1="degK2oIZtP5uKS4L8yPf9MgjaZ7"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Light Bulb Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:lightbulb-on
icon_color: amber
primary: Light Bulb
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: illumination <span class="hljs-number">2s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> illumination {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">99%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">22%</span> <span class="hljs-number">37%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">20%</span>, <span class="hljs-number">61%</span> <span class="hljs-number">21%</span>, <span class="hljs-number">77%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">57%</span>, <span class="hljs-number">99%</span> <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/1/0/3107a59f55744ebeda5cbf776666d943a28ce89d.gif"
         alt="Mushroom Eureka Animation"
         data-base62-sha1="6ZJMkKYGyUYqkG6qcly96WfWfPD"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Eureka Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:lightbulb-on
icon_color: orange
primary: Eureka
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: eureka <span class="hljs-number">1.8s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> eureka {
      <span class="hljs-number">0%</span>, <span class="hljs-number">45%</span>, <span class="hljs-number">55%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">1</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">20%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">21%</span> <span class="hljs-number">38%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">22%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">21%</span>, <span class="hljs-number">79%</span> <span class="hljs-number">37%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">53%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">67%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">46%</span>, <span class="hljs-number">62%</span> <span class="hljs-number">38%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">47%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">37%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">33%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">41%</span> <span class="hljs-number">64%</span>, <span class="hljs-number">45%</span> <span class="hljs-number">66%</span>, <span class="hljs-number">45%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">76%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">10%</span>, <span class="hljs-number">40%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">5px</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">1.12</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/3/e/b/3ebe7b5721adb3005f13fbe5ca28dc76eda38a97.gif"
         alt="Mushroom Trash Animation"
         data-base62-sha1="8X3HVCyBQt4816Rb0T4YWU604rt"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Trash Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:trash-can
    icon_color: green
    primary: Trash
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">26%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>);
        }
  - type: custom:mushroom-template-card
    icon: mdi:trash-can
    icon_color: green
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
            <span class="hljs-attribute">top</span>: <span class="hljs-number">0.3px</span>;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: lid <span class="hljs-number">1s</span> ease infinite;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">75%</span> <span class="hljs-number">0</span>);
            <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">25%</span>;
          }
          <span class="hljs-keyword">@keyframes</span> lid {
            <span class="hljs-number">0%</span>, <span class="hljs-number">50%</span>, <span class="hljs-number">80%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">5px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">37deg</span>); }
            <span class="hljs-number">20%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">5px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">31deg</span>); }
            <span class="hljs-number">30%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">5px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">25deg</span>); }
            <span class="hljs-number">40%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">5px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">19deg</span>); }
            <span class="hljs-number">60%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">3px</span>); }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/f/b/9/fb90f77f79116dd9605bb62e74ae9ff85d3155d0.gif"
         alt="Mushroom Heat Pump Animation"
         data-base62-sha1="zTsqY7zBtjqR8DhxwhK4sCLNB6w"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Heat Pump Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:heat-pump-outline
    icon_color: deep-purple
    primary: Heat Pump
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">23%</span>, <span class="hljs-number">78%</span> <span class="hljs-number">22%</span>, <span class="hljs-number">77%</span> <span class="hljs-number">78%</span>, <span class="hljs-number">23%</span> <span class="hljs-number">78%</span>, <span class="hljs-number">22%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>);
        }
  - type: custom:mushroom-template-card
    icon: mdi:heat-pump-outline
    icon_color: deep-purple
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">position</span>: absolute;
            <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">2s</span> linear infinite;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">27.3%</span> at <span class="hljs-number">50%</span> <span class="hljs-number">50%</span>);
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/9/5/4/9543486a425eaea7a864102044e004c0099bacc0.gif"
         alt="Mushroom Air Purifier Animation"
         data-base62-sha1="lirilLhuncrFQUGW41H5R8lqqS4"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Air Purifier Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:air-purifier
icon_color: cyan
primary: Air Purifier
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: air <span class="hljs-number">1s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> air {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">98%</span> <span class="hljs-number">32%</span>, <span class="hljs-number">63%</span> <span class="hljs-number">42%</span>, <span class="hljs-number">65%</span> <span class="hljs-number">58%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">43%</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">72%</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">78%</span> <span class="hljs-number">38%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">73%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/8/f/7/8f70737f37605b5654ae251043dae92de0521ecc.gif"
         alt="Mushroom Calendar Clock Animation"
         data-base62-sha1="ksVcDiRgQ97bX6SGDOH3dhCMQHi"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Calendar Clock Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:calendar-clock
    icon_color: purple
    primary: Calendar Clock
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">67%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">73%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">59%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">59%</span> <span class="hljs-number">72%</span>, <span class="hljs-number">77%</span> <span class="hljs-number">81%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">68%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">67%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>);
        }
  - type: custom:mushroom-template-card
    icon: mdi:calendar-clock
    icon_color: purple
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">1s</span> linear infinite;
            <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">67%</span> <span class="hljs-number">67%</span>;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">circle</span>(<span class="hljs-number">17%</span> at <span class="hljs-number">67%</span> <span class="hljs-number">67%</span>);
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/c/e/0ceb026fba57b4591e5aa750acc6765f6001a746.gif"
         alt="Mushroom CRT Animation"
         data-base62-sha1="1QheAa71FPZ0daS4yrWf999wgo6"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         CRT Animation (changed. i did also change the if statement structure here because i find this method easier to read and trouble shoot.)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-template-card
primary: CRT
entity: switch.television
icon: mdi:television-classic
icon_color: '</span><span class="hljs-template-variable">{{ <span class="hljs-name">''</span>orange<span class="hljs-string">''</span> if is_state(<span class="hljs-name">entity</span>, <span class="hljs-string">''</span>on<span class="hljs-string">''</span>) }}</span><span class="language-xml">'
card_mod:
  style: |
      ha-state-icon {
      {% if is_state(config.entity, 'on') %}
        animation: tube-on 1s linear, flicker 1s linear 1s infinite alternate;
      {% else %}
        animation: tube-off 2s linear forwards;
      {% endif %}
      }
      @keyframes tube-off {
        1%, 15% { transform: scale(1, 0.2); }
        40%  { transform: scale(0.2); opacity: 1; }
        100%  { transform: scale(0.2); opacity: 0; }
      }
      @keyframes tube-on {
        0% { transform: scale(0.2); opacity: 0; }
        5%  { transform: scale(1, 0.2); opacity: 0.3; }
        15%  { transform: scale(1); opacity: 0.4; }
        100%  { transform: scale(1); opacity: 1; }
      }
      @keyframes flicker {
        0%, 31.98%, 32.98%, 34.98%, 36.98%, 39.98%, 67.98%, 68.98%, 95.98%, 96.98%, 97.98%, 98.98%, 100% { opacity: 0.6; }
        32%, 33%, 35%, 36%, 37%, 40%, 68%, 69%, 96%, 97%, 98%, 99% { opacity: 1; }
      }
</span></code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/a/1/d/a1dd407ccb959223100d8287c45c27f6d82e233b.gif"
         alt="Mushroom Microwave Animation"
         data-base62-sha1="n5UTYdcjEDIYWqxEyCEVyv8ArGz"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Microwave Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:microwave
icon_color: blue
primary: Microwave
card_mod:
  style: |
    ha-state-icon:before {
      <span class="hljs-attribute">content</span>: <span class="hljs-string">""</span>;
      <span class="hljs-attribute">position</span>: absolute;
      <span class="hljs-attribute">width</span>: <span class="hljs-number">25%</span>;
      <span class="hljs-attribute">height</span>: <span class="hljs-number">25%</span>;
      <span class="hljs-attribute">margin</span>: <span class="hljs-number">10%</span>;
      <span class="hljs-attribute">animation</span>: cook <span class="hljs-number">1s</span> linear infinite;
    }
    <span class="hljs-keyword">@keyframes</span> cook { 
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">90deg</span>, white <span class="hljs-number">0%</span>, transparent <span class="hljs-number">50%</span>, transparent <span class="hljs-number">100%</span>); }
      <span class="hljs-number">33%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">90deg</span>, transparent <span class="hljs-number">0%</span>, white <span class="hljs-number">50%</span>, transparent <span class="hljs-number">100%</span>); }
      <span class="hljs-number">66%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">90deg</span>, transparent <span class="hljs-number">0%</span>, transparent <span class="hljs-number">50%</span>, white <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <h2>
      <a name="controlling-the-animation-in-your-card-3"
         class="anchor"
         href="#controlling-the-animation-in-your-card-3"></a>Controlling the Animation in your Card
   </h2>
   <p>The animations can be controlled using a Jinja Template condition on the animation command.</p>
   <p>For example if I wanted an animation when my coffee machine is on I would use an if statement like this:</p>
   <p><code>{{ 'animation: java 4s linear infinite;' if is_state(config.entity, 'on') }}</code></p>
   <p><span class="bbcode-u">Added by Dimitri.</span><br>
      Or you can make your if statement block like this instead. i think this is easier to read. it does take up more space in the code, but easier to see what is happening <img src="https://community.home-assistant.io/images/emoji/twitter/slight_smile.png?v=10"
         title=":slight_smile:"
         class="emoji"
         alt=":slight_smile:"
         loading="lazy"> the <code>{% else %}</code> is technically not even required.
   </p>
   <pre class="codeblock-buttons"><code class="hljs language-php" data-highlighted="yes">{% <span class="hljs-keyword">if</span> <span class="hljs-title function_ invoke__">is_state</span>(config.entity, <span class="hljs-string">'on'</span>) %}
  animation: java <span class="hljs-number">4</span>s linear infinite;
{% <span class="hljs-keyword">else</span> %}

{% <span class="hljs-keyword">endif</span> %}
</code></pre>
   <p>The complete card would look like this:</p>
   <details>
      <summary>
         Coffee Machine Card (new if statements and structure changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-template-card</span>
<span class="hljs-attr">entity:</span> <span class="hljs-string">switch.coffee_machine</span>
<span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:coffee-maker</span>
<span class="hljs-attr">icon_color:</span> <span class="hljs-string">'<span class="hljs-template-variable">{{ ''brown'' if is_state(entity, ''on'') }}</span>'</span>
<span class="hljs-attr">primary:</span> <span class="hljs-string">Coffee</span> <span class="hljs-string">Machine</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
      {% if is_state(config.entity, 'on') %}
        animation: java 4s linear infinite;
      {% else %}
</span>
      {<span class="hljs-string">%</span> <span class="hljs-string">endif</span> <span class="hljs-string">%</span>}
    <span class="hljs-string">}</span>
    <span class="hljs-string">@keyframes</span> <span class="hljs-string">java</span> {
      <span class="hljs-number">0</span><span class="hljs-string">%</span>, <span class="hljs-number">80</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">10</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">79</span><span class="hljs-string">%</span>, <span class="hljs-number">63</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">55</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">77</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">80</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">15</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">79</span><span class="hljs-string">%</span>, <span class="hljs-number">63</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">77</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">80</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">20</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">63</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">55</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">25</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">63</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">76</span><span class="hljs-string">%</span>, <span class="hljs-number">56</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">30</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">64</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">55</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">55</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">69</span><span class="hljs-string">%</span>, <span class="hljs-number">44</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">35</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">64</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">55</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">69</span><span class="hljs-string">%</span>, <span class="hljs-number">44</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">73</span><span class="hljs-string">%</span>, <span class="hljs-number">56</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">40</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">45</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">70</span><span class="hljs-string">%</span>, <span class="hljs-number">56</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">50</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">66</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">65</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">65</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">65</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">55</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">66</span><span class="hljs-string">%</span>, <span class="hljs-number">67</span><span class="hljs-string">%</span> <span class="hljs-number">65</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">65</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">65</span><span class="hljs-string">%</span>, <span class="hljs-number">56</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">60</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">65</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">60</span><span class="hljs-string">%</span>, <span class="hljs-number">56</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">70</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">32</span><span class="hljs-string">%</span>, <span class="hljs-number">47</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">43</span><span class="hljs-string">%</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">57</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
      <span class="hljs-number">75</span><span class="hljs-string">%</span> { <span class="hljs-attr">clip-path:</span> <span class="hljs-string">polygon(0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">66</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">54</span><span class="hljs-string">%</span>, <span class="hljs-number">42</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">56</span><span class="hljs-string">%</span>, <span class="hljs-number">55</span><span class="hljs-string">%</span> <span class="hljs-number">100</span><span class="hljs-string">%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100</span><span class="hljs-string">%);</span> }
    }
</code></pre>
   </details>
   <p>Or if I wanted to have the dryer animate when the load is over 4w I would do this:</p>
   <p><code>{{ 'animation: shake 400ms ease-in-out infinite, drum 1s infinite;' if states('sensor.dryer_power') | float &gt; 4 }}</code></p>
   <p><span class="bbcode-u">Added by Dimitri.</span><br>
      Or you can make your if statement block like this instead. i think this is easier to read. it does take up more space in the code, but easier to see what is happening <img src="https://community.home-assistant.io/images/emoji/twitter/slight_smile.png?v=10"
         title=":slight_smile:"
         class="emoji"
         alt=":slight_smile:"
         loading="lazy"> the <code>{% else %}</code> is technically not even required.
   </p>
   <pre class="codeblock-buttons"><code class="hljs language-php" data-highlighted="yes">{% <span class="hljs-keyword">if</span> <span class="hljs-title function_ invoke__">states</span>(sensor.dryer_power) | <span class="hljs-keyword">float</span> &gt; <span class="hljs-number">4</span>  %}
  animation: shake <span class="hljs-number">400</span>ms ease-in-out infinite, drum <span class="hljs-number">1</span>s infinite;
{% <span class="hljs-keyword">else</span> %}

{% <span class="hljs-keyword">endif</span> %}
</code></pre>
   <p>The complete card would look like this:</p>
   <details>
      <summary>
         Dryer Card (new if statements and structure changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-template-card
entity: switch.dryer
icon: mdi:tumble-dryer
icon_color: '</span><span class="hljs-template-variable">{{ <span class="hljs-name">''</span>teal<span class="hljs-string">''</span> if states(<span class="hljs-name">''</span>sensor.dryer_power<span class="hljs-string">''</span>) | float &gt; <span class="hljs-number">4</span> }}</span><span class="language-xml">'
primary: Dryer
card_mod:
  style: |
    ha-state-icon {
      transform-origin: 50% 65%;
      {% if states('sensor.dryer_power') | float &gt; 4 %}
        animation: shake 400ms ease-in-out infinite, drum 1s infinite;
      {% else %}

      {% end if %}
    }
    @keyframes shake {
      0%, 100% { transform: rotate(4deg); }
      50%  { transform: rotate(-4deg); }
    }
    @keyframes drum {
      50%  { clip-path: polygon(0 0, 0 100%, 35% 100%, 36% 74%, 31% 43%, 61% 40%, 71% 69%, 62% 78%, 36% 73%, 35% 100%, 100% 100%, 100% 0); }
    }
</span></code></pre>
   </details>
   <p>You will need to add the if condition for each <code>animation:</code>, <code>--icon-animation:</code> or <code>--shape-animation:</code> command in the card.</p>
   <p><span class="bbcode-u">Added by Dimitri.</span><br>
      This is not true if you complete the if statements in the way that i have showed. that is unless you need the animations to be based on different conditions.
   </p>
   <h2>
      <a name="using-the-animations-with-tile-card-4"
         class="anchor"
         href="#using-the-animations-with-tile-card-4"></a>Using the Animations with Tile Card
   </h2>
   <p>The structure of the new Tile Card is very similar to the Mushroom Cards, so it is easy to use these animations with it.</p>
   <p>Mushroom Card (changed)</p>
   <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span> <span class="hljs-string">|
    ha-state-icon {
    }
</span></code></pre>
   <p>Tile Card (changed)</p>
   <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span>
    <span class="hljs-string">ha-tile-icon$:</span> <span class="hljs-string">|
      ha-icon {
      }
</span></code></pre>
   <details>
      <summary>
         Animated Tile Card (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: tile
entity: fan.bathroom_fan
color: green
card_mod:
  style:
    ha-tile-icon$: |
      ha-icon {
        <span class="hljs-attribute">animation</span>: rotate <span class="hljs-number">1s</span> linear infinite;
      }
      <span class="hljs-keyword">@keyframes</span> rotate {
         <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">360deg</span>); }
      }
</code></pre>
   </details>
   <p>Updated Posts <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"><br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7717">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7719">Part 2</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7723">Part 3</a>, Part 4, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7726">Part 5</a><br>
      Original Posts by <a class="mention"
         href="/u/rhysb">@rhysb</a> <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"> please only like his posts.<br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3240">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3256">Part 2</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3272">Part 3</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3348">Part 4</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/4043">Part 5</a>
   </p>
   <h2>
      <a name="mushroom-chip-animations-2"
         class="anchor"
         href="#mushroom-chip-animations-2"></a>Mushroom Chip Animations
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="517"
         height="61"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/2/4/7/247cb76d8c3fe0e33d061109ddfd7fc7337ee132.gif"
         alt="Mushroom Chip Animated Scene"
         data-base62-sha1="5cMom4gQaMCipHhndMrSHhod6qm"
         width="517"
         height="61"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 517 / 61;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Chip Animated Scene (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-handlebars" data-highlighted="yes"><span class="language-xml">type: custom:mushroom-chips-card
chips:
  - type: template
    icon: mdi:mushroom
    icon_color: red
  - type: template
    icon: mdi:snail
    icon_color: brown
  - type: template
    icon: mdi:flower
    icon_color: amber
  - type: template
    icon: mdi:butterfly
    icon_color: cyan
card_mod:
  style:
    mushroom-template-chip:nth-child(1)$: |
      ha-state-icon {
        animation: bump 10s infinite;
        transform-origin: 50% 100%;
      }
      @keyframes bump {
        0% { transform: translateX(0); }
        1% { transform: translateX(-0.6px) rotate(-9deg); }
        2% { transform: translateX(0.5px) rotate(7deg); }
        3% { transform: translateX(-0.3px) rotate(-5deg); }
        4% { transform: translateX(0.2px) rotate(3deg); }
        5% { transform: translateX(0); }
      }
    mushroom-template-chip:nth-child(2)$: |
      ha-state-icon {
        animation: slip 0.5s linear infinite alternate;
        transform-origin: 100% 100%;
      }
      @keyframes slip {
        from { transform: scale(1.05, 0.9);}
        to { transform: scale(0.9, 1.05); }
      }
    mushroom-template-chip:nth-child(3)$: |
      ha-state-icon {
        animation: bump 10s infinite;
        transform-origin: 50% 100%;
      }
      @keyframes bump {
        50% { transform: translateX(0); }
        51% { transform: translateX(-0.6px) rotate(-9deg); }
        52% { transform: translateX(0.5px) rotate(7deg); }
        53% { transform: translateX(-0.3px) rotate(-5deg); }
        54% { transform: translateX(0.2px) rotate(3deg); }
        55% { transform: translateX(0); }
      }
    mushroom-template-chip:nth-child(4)$: |
      ha-state-icon {
        animation: flutter 5s infinite alternate;
      }
      @keyframes flutter {
        0% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
        10% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg) scalex(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">3</span>, <span class="hljs-number">7</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">); }
        20% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
        30% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg) scalex(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">3</span>, <span class="hljs-number">7</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">); }
        40% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
        50% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg) scalex(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">3</span>, <span class="hljs-number">7</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">); }
        60% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
        70% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg) scalex(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">3</span>, <span class="hljs-number">7</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">); }
        80% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
        90% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg) scalex(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">3</span>, <span class="hljs-number">7</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">); }
        100% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px, </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-20</span>, <span class="hljs-number">20</span>) | random / <span class="hljs-number">10</span> }}</span><span class="language-xml">px) rotate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">-15</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">deg); }
      }
    .: |
      .chip-container {
        background: radial-gradient(circle, rgba(var(--rgb-light-blue), 0.1) 0%, transparent 100%);
        border-bottom: 3px dotted rgba(var(--rgb-green));
        border-radius: 20%;
        box-shadow: 0 5px 1px 0.1px rgba(var(--rgb-green), 0.2)
      }
      mushroom-template-chip:nth-child(2) {
        animation: slide 10s ease-in-out infinite;
      }
      @keyframes slide {
        0% { transform: translate(0px, 0px) rotateY(0deg); }
        50% { transform: translate(100px, 0px) rotateY(0deg); }
        50.1% { transform: translate(100px, 0px) rotateY(180deg); }
        100% { transform: translate(0px, 0px) rotateY(180deg); }
      }
      mushroom-template-chip:nth-child(3) {
          transform: translate(100px);
      }
      mushroom-template-chip:nth-child(4) {
          animation: by </span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">5</span>, <span class="hljs-number">15</span>) | random }}</span><span class="language-xml">s ease infinite;
      }
      @keyframes by {
        0% { transform: translate(100px, 0px); }
        50% { transform: translate(</span><span class="hljs-template-variable">{{ <span class="hljs-name">range</span>(<span class="hljs-name">110</span>, <span class="hljs-number">150</span>) | random }}</span><span class="language-xml">px, 0px); }
        100% { transform: translate(100px, 0px); }
      }
</span></code></pre>
   </details>
   <p><span class="bbcode-u">All of the below info regarding adding animations to chips is still true.</span></p>
   <h2>
      <a name="adding-animations-to-chips-3"
         class="anchor"
         href="#adding-animations-to-chips-3"></a>Adding Animations to Chips
   </h2>
   <p>Adding an animation to a Mushroom Chip is a bit more complicated than a normal Mushroom Card. You have the Chips ‘parent’ and multiple Chip ‘children’. The <code>card_mod</code> can be applied differently to each.</p>
   <h3>
      <a name="to-the-chip-4"
         class="anchor"
         href="#to-the-chip-4"></a>To the Chip
   </h3>
   <p>The simplest method is to add the <code>card_mod</code> to the Chip. The disadvantage of doing this is that we can’t address the icon directly, so animations such as <code>clip-path</code> will not work and we can’t have any text on the Chip. This method also breaks the GUI editor of the Chips, so you have to configure with YAML.</p>
   <details>
      <summary>
         Chip Animation (unchanged)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-chips-card
chips:
  - type: template
    icon: mdi:mushroom
    icon_color: red
    card_mod:
      style: |
        .content {
          <span class="hljs-attribute">animation</span>: boing <span class="hljs-number">3s</span> ease infinite;
          <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">50%</span> <span class="hljs-number">90%</span>;
        }
        <span class="hljs-keyword">@keyframes</span> boing {
          <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
          <span class="hljs-number">7%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.25</span>, <span class="hljs-number">0.75</span>, <span class="hljs-number">1</span>); }
          <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.75</span>, <span class="hljs-number">1.25</span>, <span class="hljs-number">1</span>); }
          <span class="hljs-number">12%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.15</span>, <span class="hljs-number">0.85</span>, <span class="hljs-number">1</span>); }
          <span class="hljs-number">16%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">0.95</span>, <span class="hljs-number">1.05</span>, <span class="hljs-number">1</span>); }
          <span class="hljs-number">19%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1.05</span>, <span class="hljs-number">0.95</span>, <span class="hljs-number">1</span>); }
          <span class="hljs-number">25%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">scale3d</span>(<span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>); }
        }       
  - type: template
    icon: mdi:mushroom
    icon_color: red
    card_mod:
      style: |
        .content {
          <span class="hljs-attribute">animation</span>: spin <span class="hljs-number">3s</span> ease <span class="hljs-number">1.5s</span> infinite;
        }
        <span class="hljs-keyword">@keyframes</span> spin {
          <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">360deg</span>); }
        } 
</code></pre>
   </details>
   <h3>
      <a name="to-the-chips-5"
         class="anchor"
         href="#to-the-chips-5"></a>To the Chips
   </h3>
   <p>The more complex but correct method is to add the <code>card_mod</code> to the Chips (parent) and then address each Chip (child). This is done by referencing the <code>mushroom-&lt;chip-type&gt;-chip:nth-child(x)</code> where x is the number of the Chip and <code>&lt;chip-type&gt;</code> is type of Chip, such as template, entity, light etc. So, if I wanted to reference the 5th Entity Chip I would use <code>mushroom-entity-chip:nth-child(5)</code> or the 2nd Template Chip <code>mushroom-template-chip:nth-child(2)</code>. The functionality of the GUI editor is retained with this method.</p>
   <details>
      <summary>
         Chips Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-yaml" data-highlighted="yes"><span class="hljs-attr">type:</span> <span class="hljs-string">custom:mushroom-chips-card</span>
<span class="hljs-attr">chips:</span>
  <span class="hljs-bullet">-</span> <span class="hljs-attr">type:</span> <span class="hljs-string">template</span>
    <span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
    <span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
  <span class="hljs-bullet">-</span> <span class="hljs-attr">type:</span> <span class="hljs-string">template</span>
    <span class="hljs-attr">content:</span> <span class="hljs-string">Mushroom</span>
    <span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:mushroom</span>
    <span class="hljs-attr">icon_color:</span> <span class="hljs-string">red</span>
  <span class="hljs-bullet">-</span> <span class="hljs-attr">type:</span> <span class="hljs-string">light</span>
    <span class="hljs-attr">entity:</span> <span class="hljs-string">light.rocket_man</span>
    <span class="hljs-attr">icon:</span> <span class="hljs-string">mdi:rocket-launch</span>
    <span class="hljs-attr">name:</span> <span class="hljs-string">Rocket</span> <span class="hljs-string">Man</span>
    <span class="hljs-attr">content_info:</span> <span class="hljs-string">name</span>
<span class="hljs-attr">card_mod:</span>
  <span class="hljs-attr">style:</span>
    <span class="hljs-string">mushroom-template-chip:nth-child(1)$:</span> <span class="hljs-string">|
      ha-state-icon {
        animation: boing 3s ease infinite;
        transform-origin: 50% 90%;
      }
      @keyframes boing {
        0% { transform: scale3d(1, 1, 1); }
        7% { transform: scale3d(1.25, 0.75, 1); }
        10% { transform: scale3d(0.75, 1.25, 1); }
        12% { transform: scale3d(1.15, 0.85, 1); }
        16% { transform: scale3d(0.95, 1.05, 1); }
        19% { transform: scale3d(1.05, 0.95, 1); }
        25% { transform: scale3d(1, 1, 1); }
      }       
</span>    <span class="hljs-string">mushroom-template-chip:nth-child(2)$:</span> <span class="hljs-string">|
      ha-state-icon {
        animation: spin 3s ease 1.5s infinite;
      }
      @keyframes spin {
        100% { transform: rotate(360deg); }
      }       
</span>    <span class="hljs-string">mushroom-light-chip:nth-child(3)$:</span> <span class="hljs-string">|
      ha-state-icon {
        {{ 'animation: thrust 100ms infinite, motion 3s ease-in-out infinite;' if is_state('light.rocket_man', 'on') }}
      }
      @keyframes thrust {
        0% { clip-path: polygon(0 0, 0 47%, 22% 57%, 28% 63%, 0 91%, 11% 100%, 37% 73%, 45% 77%, 55% 100%, 100% 100%, 100% 0%); }
        33% { clip-path: polygon(0 0, 0 47%, 24% 59%, 42% 76%, 54% 100%, 100% 100%, 100% 0); }
        66% { clip-path: polygon(0 0, 0 92%, 28% 64%, 36% 72%, 9% 100%, 100% 100%, 100% 0%); }
      }
      @keyframes motion {
        0%, 100% { transform: translateY(-2px) translateX(-3px); }
        50% { transform: translateY(3px) translateX(2px); }
      }
</span></code></pre>
   </details>
   <h2>
      <a name="even-more-mushroom-card-icon-animations-6"
         class="anchor"
         href="#even-more-mushroom-card-icon-animations-6"></a>Even More Mushroom Card Icon Animations
   </h2>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/9/7/1979be23b7c7f38d0c61df9caddad29a0a8b4ee9.gif"
         alt="Mushroom Monitor Animation"
         data-base62-sha1="3DmLHqFydVATOcgOgi70QYSrCyd"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Monitor Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:monitor
icon_color: purple
primary: Monitor
card_mod:
  style: |
    ha-state-icon:before {
      <span class="hljs-attribute">content</span>: <span class="hljs-string">""</span>;
      <span class="hljs-attribute">position</span>: absolute;
      <span class="hljs-attribute">width</span>: <span class="hljs-number">40%</span>;
      <span class="hljs-attribute">height</span>: <span class="hljs-number">30%</span>;
      <span class="hljs-attribute">margin</span>: <span class="hljs-number">6%</span>;
      <span class="hljs-attribute">animation</span>: refresh <span class="hljs-number">300ms</span> linear infinite;
    }
    <span class="hljs-keyword">@keyframes</span> refresh { 
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">180deg</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-{{ config<span class="hljs-selector-class">.icon_color</span> }}), <span class="hljs-number">0.2</span>) <span class="hljs-number">0%</span>, transparent <span class="hljs-number">50%</span>, transparent <span class="hljs-number">100%</span>); }
      <span class="hljs-number">25%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">180deg</span>, transparent <span class="hljs-number">0%</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-{{ config<span class="hljs-selector-class">.icon_color</span> }}), <span class="hljs-number">0.2</span>) <span class="hljs-number">25%</span>, transparent <span class="hljs-number">100%</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">180deg</span>, transparent <span class="hljs-number">0%</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-{{ config<span class="hljs-selector-class">.icon_color</span> }}), <span class="hljs-number">0.2</span>) <span class="hljs-number">50%</span>, transparent <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">180deg</span>, transparent <span class="hljs-number">0%</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-{{ config<span class="hljs-selector-class">.icon_color</span> }}), <span class="hljs-number">0.2</span>) <span class="hljs-number">75%</span>, transparent <span class="hljs-number">100%</span>); }
      <span class="hljs-number">100%</span> { <span class="hljs-attribute">background</span>: <span class="hljs-built_in">linear-gradient</span>(<span class="hljs-number">180deg</span>, transparent <span class="hljs-number">0%</span>, transparent <span class="hljs-number">50%</span>, <span class="hljs-built_in">rgba</span>(<span class="hljs-built_in">var</span>(--rgb-{{ config<span class="hljs-selector-class">.icon_color</span> }}), <span class="hljs-number">0.2</span>) <span class="hljs-number">100%</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="66"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/c/a/8/ca81276413e5621fc4a03ac34b925e1f2ad3f856.gif"
         alt="Mushroom Email Animation"
         data-base62-sha1="sTr9UK4k6xCsbw3iS3eja1kFy86"
         width="265"
         height="66"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 66;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Email Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:email
    icon_color: orange
    primary: Email
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">animation</span>: email <span class="hljs-number">4s</span> infinite;
        }
        <span class="hljs-keyword">@keyframes</span> email {
          <span class="hljs-number">0%</span>, <span class="hljs-number">32%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
          <span class="hljs-number">33%</span>, <span class="hljs-number">99%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        }
  - type: custom:mushroom-template-card
    icon: mdi:email-open
    icon_color: orange
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: email-open <span class="hljs-number">4s</span> infinite;
          }
          <span class="hljs-keyword">@keyframes</span> email-open {
            <span class="hljs-number">0%</span>, <span class="hljs-number">32%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
            <span class="hljs-number">33%</span>, <span class="hljs-number">65%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
            <span class="hljs-number">66%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
          }
  - type: custom:mushroom-template-card
    icon: mdi:email-newsletter
    icon_color: orange
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">132px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: email-newsletter <span class="hljs-number">4s</span> infinite;
          }
          <span class="hljs-keyword">@keyframes</span> email-newsletter {
            <span class="hljs-number">0%</span>, <span class="hljs-number">65%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
            <span class="hljs-number">66%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="65"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/0/e/7/0e742b3302f15591d126028d54e2565e0b4f4c1d.gif"
         alt="Mushroom Email #2 Animation"
         data-base62-sha1="23RzEdCNLjmpEuat9KZPIbQ0Qc5"
         width="265"
         height="65"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 65;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Email #2 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:email
    icon_color: orange
    primary: <span class="hljs-string">'Email #2'</span>
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">animation</span>: email <span class="hljs-number">2s</span> infinite;
        }
        <span class="hljs-keyword">@keyframes</span> email {
          <span class="hljs-number">0%</span>, <span class="hljs-number">49%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
          <span class="hljs-number">50%</span>, <span class="hljs-number">99%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        }
  - type: custom:mushroom-template-card
    icon: mdi:email-open
    icon_color: orange
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: email-open <span class="hljs-number">2s</span> infinite;
          }
          <span class="hljs-keyword">@keyframes</span> email-open {
            <span class="hljs-number">0%</span>, <span class="hljs-number">49%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
            <span class="hljs-number">50%</span>, <span class="hljs-number">99%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="265"
         height="69"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/5/b/65b47eb23791ee5f2f38a592eb9d2cbc50598cbd.gif"
         alt="Mushroom Christmas Tree #2 Animation"
         data-base62-sha1="evIVQIFItENi4hXXG1JZ9R368XP"
         width="265"
         height="69"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 265 / 69;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Christmas Tree #2 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:pine-tree
    icon_color: green
    primary: <span class="hljs-string">'Christmas Tree #2'</span>
  - type: custom:mushroom-template-card
    icon: mdi:star-four-points
    icon_color: yellow
    primary: Star
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: star <span class="hljs-number">8s</span> ease infinite alternate;
          }
          <span class="hljs-keyword">@keyframes</span> star {
            <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">10px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">0deg</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">0.4</span>); }
            <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">10px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">360deg</span>) <span class="hljs-built_in">scale</span>(<span class="hljs-number">0.6</span>); }
          }
  - type: custom:mushroom-template-card
    icon: mdi:grain
    icon_color: red
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">132px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: flash <span class="hljs-number">2s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite, lights <span class="hljs-number">2s</span> infinite;
            <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">51%</span> <span class="hljs-number">15%</span>, <span class="hljs-number">24%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">74%</span> <span class="hljs-number">74%</span>);
          }
          <span class="hljs-keyword">@keyframes</span> flash {
            <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotateY</span>(<span class="hljs-number">180deg</span>); }
          }
          <span class="hljs-keyword">@keyframes</span> lights {
            <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> {<span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-red)); }
            <span class="hljs-number">6.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-orange)); }
            <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-orange)); }
            <span class="hljs-number">18.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-amber)); }
            <span class="hljs-number">25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-yellow)); }
            <span class="hljs-number">31.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-lime)); }
            <span class="hljs-number">37.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-green)); }
            <span class="hljs-number">43.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-green)); }
            <span class="hljs-number">50%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-teal)); }
            <span class="hljs-number">56.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-cyan)); }
            <span class="hljs-number">62.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-light-blue)); }
            <span class="hljs-number">68.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-blue)); }
            <span class="hljs-number">75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-indigo)); }
            <span class="hljs-number">81.25%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-deep-purple)); }
            <span class="hljs-number">87.5%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-purple)); }
            <span class="hljs-number">93.75%</span> { <span class="hljs-attribute">color</span>: <span class="hljs-built_in">rgb</span>(<span class="hljs-built_in">var</span>(--rgb-pink)); }
          }
  - type: custom:mushroom-template-card
    icon: mdi:gift
    icon_color: red
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
            <span class="hljs-attr">--icon-size</span>: <span class="hljs-number">18px</span>;
            <span class="hljs-attribute">top</span>: <span class="hljs-number">18px</span>;
            <span class="hljs-attribute">left</span>: <span class="hljs-number">18px</span>;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">198px</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: surprise <span class="hljs-number">4s</span> ease infinite;
          }
          <span class="hljs-keyword">@keyframes</span> surprise {
            <span class="hljs-number">0%</span>, <span class="hljs-number">20%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">2.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">27deg</span>); }
            <span class="hljs-number">5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">21deg</span>); }
            <span class="hljs-number">7.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
            <span class="hljs-number">10%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">2px</span>) <span class="hljs-built_in">rotate</span>(<span class="hljs-number">9deg</span>); }
            <span class="hljs-number">12.5%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(<span class="hljs-number">0</span>); }
            <span class="hljs-number">15%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateY</span>(-<span class="hljs-number">1.2px</span>) }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="266"
         height="65"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/4/5/9/459b7a2b0d45ffc4608775d6ab22d0f0b64bb1a0.gif"
         alt="Mushroom 3D Printing Animation"
         data-base62-sha1="9VM3l45tM6ILbFuWkkT2uujK5JC"
         width="266"
         height="65"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 266 / 65;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         3D Printing Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:stack-in-card
cards:
  - type: custom:mushroom-template-card
    icon: mdi:printer-<span class="hljs-number">3</span>d-nozzle
    icon_color: cyan
    primary: <span class="hljs-number">3</span>D Printing
    card_mod:
      style: |
        ha-state-icon {
          <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">83%</span> <span class="hljs-number">72%</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>);
        }
        ha-card {
          <span class="hljs-attr">--ha-card-border-width</span>: <span class="hljs-number">0</span>;
        }
  - type: custom:mushroom-template-card
    icon: mdi:printer-<span class="hljs-number">3</span>d-nozzle
    icon_color: cyan
    primary: <span class="hljs-string">''</span>
    card_mod:
      style:
        mushroom-shape-icon$: |
          .shape {
            <span class="hljs-attr">--shape-color</span>: none;
          }
        .: |
          ha-card {
            <span class="hljs-attribute">width</span>: <span class="hljs-number">66px</span>;
            <span class="hljs-attribute">top</span>: -<span class="hljs-number">66px</span>;
            <span class="hljs-attr">--ha-card-border-width</span>: <span class="hljs-number">0</span>;
          }
          ha-state-<span class="hljs-attribute">icon</span> {
            <span class="hljs-attribute">animation</span>: print <span class="hljs-number">1s</span> linear infinite alternate;
          }
          <span class="hljs-keyword">@keyframes</span> print {
            <span class="hljs-number">0%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(<span class="hljs-number">4px</span>); }
            <span class="hljs-number">30%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">26%</span>); }
            <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translateX</span>(-<span class="hljs-number">4px</span>); <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">40%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">26%</span>); }
          }
card_mod:
  style: |
    ha-card {
      <span class="hljs-attribute">height</span>: <span class="hljs-number">66px</span>;
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/6/d/2/6d2323792803264dfe733add6103b7ba7b08323f.gif"
         alt="Mushroom 3D Printer Animation"
         data-base62-sha1="fztkm23Ne3YVxf7G1igZGXGvhfh"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         3D Printer Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: <span class="hljs-number">3</span>D Printer
icon: mdi:printer-<span class="hljs-number">3</span>d
icon_color: light-blue
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: print <span class="hljs-number">2s</span> infinite;
    }
    <span class="hljs-keyword">@keyframes</span> print {
      <span class="hljs-number">0%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">51%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">10%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">49%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">49%</span> <span class="hljs-number">98%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">89%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">82%</span>, <span class="hljs-number">46%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">17%</span> <span class="hljs-number">82%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">20%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">46%</span> <span class="hljs-number">79%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">17%</span> <span class="hljs-number">82%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">30%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">45%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">36%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">17%</span> <span class="hljs-number">82%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">40%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">83%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">73%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">45%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">63%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">50%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">63%</span>, <span class="hljs-number">54%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">45%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">34%</span> <span class="hljs-number">63%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">60%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">66%</span> <span class="hljs-number">63%</span>, <span class="hljs-number">55%</span> <span class="hljs-number">69%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">32%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">54%</span>, <span class="hljs-number">20%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">76%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">68%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">60%</span> <span class="hljs-number">55%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">61%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">50%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">37%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">30%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">51%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">90%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">77%</span> <span class="hljs-number">51%</span>, <span class="hljs-number">67%</span> <span class="hljs-number">42%</span>, <span class="hljs-number">64%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">34%</span>, <span class="hljs-number">50%</span> <span class="hljs-number">36%</span>, <span class="hljs-number">39%</span> <span class="hljs-number">40%</span>, <span class="hljs-number">31%</span> <span class="hljs-number">44%</span>, <span class="hljs-number">30%</span> <span class="hljs-number">35%</span>, <span class="hljs-number">41%</span> <span class="hljs-number">33%</span>, <span class="hljs-number">85%</span> <span class="hljs-number">53%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">52%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/7/b/5/7b5fe3884a04409fd0a4ed73a09df90da62b1796.gif"
         alt="Mushroom Auto Fix #2 Animation"
         data-base62-sha1="hBqawcGMEvB1uWcGBaG541zR1jg"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Auto Fix #2 Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:auto-fix
icon_color: cyan
primary: <span class="hljs-string">'Auto Fix #2'</span>
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: sparkle <span class="hljs-number">2s</span> linear infinite, kadabra <span class="hljs-number">2s</span> ease-in-out infinite;
     <span class="hljs-attribute">transform-origin</span>: <span class="hljs-number">10%</span> <span class="hljs-number">90%</span>
    }
    <span class="hljs-keyword">@keyframes</span> sparkle {
      <span class="hljs-number">0%</span>, <span class="hljs-number">68%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">1%</span> <span class="hljs-number">75%</span>, <span class="hljs-number">56%</span> <span class="hljs-number">22%</span>, <span class="hljs-number">80%</span> <span class="hljs-number">43%</span>, <span class="hljs-number">26%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">69%</span>, <span class="hljs-number">74%</span>, <span class="hljs-number">79%</span>, <span class="hljs-number">85%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">76%</span>, <span class="hljs-number">75%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">39%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">62%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>, <span class="hljs-number">100%</span> <span class="hljs-number">26%</span>, <span class="hljs-number">25%</span> <span class="hljs-number">100%</span>); }
    } 
    <span class="hljs-keyword">@keyframes</span> kadabra {
      <span class="hljs-number">0%</span>, <span class="hljs-number">65%</span>, <span class="hljs-number">100%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(-<span class="hljs-number">15deg</span>); }
      <span class="hljs-number">70%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">20deg</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">15deg</span>); }
      <span class="hljs-number">80%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">rotate</span>(<span class="hljs-number">25deg</span>); }
    }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="263"
         height="67"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/d/3/0/d30a8ffae0a7ac54a580792457ac42fef0453fab.gif"
         alt="Mushroom Vroom Animation"
         data-base62-sha1="u6XnjUSw0VSRsfkul2Dwz4ac54v"
         width="263"
         height="67"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 263 / 67;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Vroom Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
icon: mdi:car-hatchback
icon_color: red
primary: Vroom
card_mod:
  style:
    mushroom-shape-icon$: |
      .shape {
        <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>);
      }
    .: |
      ha-state-icon {
        <span class="hljs-attribute">animation</span>: vroom <span class="hljs-number">2s</span> ease-in-out infinite;
      }
      <span class="hljs-keyword">@keyframes</span> vroom {
        <span class="hljs-number">49%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>;}
        <span class="hljs-number">50%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(<span class="hljs-number">32px</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">51%</span> { <span class="hljs-attribute">transform</span>: <span class="hljs-built_in">translate</span>(-<span class="hljs-number">32px</span>); <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>; }
        <span class="hljs-number">52%</span> { <span class="hljs-attribute">opacity</span>: <span class="hljs-number">1</span>; }
      }
</code></pre>
   </details>
   <p>
   <div class="pausable-animated-image paused-animated-image">
      <canvas width="264"
         height="64"
         aria-hidden="true"
         role="presentation"></canvas>
      <img src="https://community-assets.home-assistant.io/original/4X/1/8/d/18d01fa7551d8f0b9cfa64e5a9f2171de7369e97.gif"
         alt="Mushroom Double Garage Animation"
         data-base62-sha1="3xvms61ISmeJiJHIZem7n44Jwz5"
         width="264"
         height="64"
         class="animated"
         loading="lazy"
         style="aspect-ratio: 264 / 64;">
      <div class="animated-image-overlay"
         aria-hidden="true"
         role="presentation">
         <svg class="fa d-icon d-icon-pause svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#pause"></use>
         </svg>
         <svg class="fa d-icon d-icon-play svg-icon svg-string"
            xmlns="http://www.w3.org/2000/svg">
            <use href="#play"></use>
         </svg>
      </div>
   </div>
   </p>
   <details>
      <summary>
         Double Garage Animation (changed)
      </summary>
      <pre class="codeblock-buttons"><code class="hljs language-css" data-highlighted="yes">type: custom:mushroom-template-card
primary: Double Garage
icon: mdi:garage-variant
icon_color: amber
card_mod:
  style: |
    ha-state-icon {
      <span class="hljs-attribute">animation</span>: door <span class="hljs-number">3s</span> <span class="hljs-built_in">steps</span>(<span class="hljs-number">1</span>) infinite alternate; 
    }
    <span class="hljs-keyword">@keyframes</span> door {
      <span class="hljs-number">0%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">inset</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">25%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">19%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">19%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">74%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">50%</span>  { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">19%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">19%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">60%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
      <span class="hljs-number">75%</span> { <span class="hljs-attribute">clip-path</span>: <span class="hljs-built_in">polygon</span>(<span class="hljs-number">0</span> <span class="hljs-number">0</span>, <span class="hljs-number">0</span> <span class="hljs-number">100%</span>, <span class="hljs-number">19%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">19%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">48%</span>, <span class="hljs-number">81%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">100%</span>, <span class="hljs-number">100%</span> <span class="hljs-number">0</span>); }
    }
</code></pre>
   </details>
   <p>Updated Posts <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"><br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7717">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7719">Part 2</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7723">Part 3</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/7725">Part 4</a>, Part 5<br>
      Original Posts by <a class="mention"
         href="/u/rhysb">@rhysb</a> <img src="https://community.home-assistant.io/images/emoji/twitter/point_down.png?v=10"
         title=":point_down:"
         class="emoji"
         alt=":point_down:"
         loading="lazy"> please only like his posts.<br>
      <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3240">Part 1</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3256">Part 2</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3272">Part 3</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/3348">Part 4</a>, <a href="https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/4043">Part 5</a>
   </p>
</div>
