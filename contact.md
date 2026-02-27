---
layout: page
title: Contact
permalink: /contact
---

<div class="center">
<img src="/assets/me.jpg#avatar-home" title="That's me"/>
<p class="contact">Here's where you can find me online:</p>
<ul class="social-media-list">
  {%- if site.github_username -%}<li><a href="https://github.com/{{ site.github_username| cgi_escape | escape }}" target="_blank"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg> <span class="username">{{ site.github_username| escape }}</span></a></li>{%- endif -%}

  {%- if site.linkedin_username -%}<li><a href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}" target="_blank"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg> <span class="username">{{ site.linkedin_username| escape }}</span></a></li>{%- endif -%}

  {%- if site.email -%}<li><a href="mailto:{{ site.email| cgi_escape | escape }}"><svg class="svg-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#828282" width="18px" height="18px"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/><path d="M0 0h24v24H0z" fill="none"/></svg> <span class="username">{{ site.email| escape }}</span></a></li>{%- endif -%}
</ul>
</div>
