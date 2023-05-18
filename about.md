---
layout: page
title: About
permalink: /about/
---

This is the blog about PWNC4M. We are a ctf team of University of Camerino
You can find out in different social:<br /><br />
  {%- if site.github_username -%}<a href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg> <span class="username">{{ site.github_username| escape }}</span></a>{%- endif -%}
  <br /> <br />


team_members = [ <br />
&nbsp;&nbsp;&nbsp;&nbsp;["giorgiosld"](https://github.com/giorgiosld) <br /> 
&nbsp;&nbsp;&nbsp;&nbsp;["Feedz"](https://github.com/FeeeDz) <br />
&nbsp;&nbsp;&nbsp;&nbsp;"Retr0mus" <br />
&nbsp;&nbsp;&nbsp;&nbsp;["popoff"](https://github.com/flaviopopoff) <br />
&nbsp;&nbsp;&nbsp;&nbsp;"Foxyy" <br /> 
&nbsp;&nbsp;&nbsp;&nbsp;["HTTPiego"](https://github.com/HTTPiego) <br /> 
&nbsp;&nbsp;&nbsp;&nbsp;["turtulin"](https://github.com/turtulin) <br /> 
&nbsp;&nbsp;&nbsp;&nbsp;"404" <br />
]

print(team_members)
