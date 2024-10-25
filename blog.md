---
layout: default
---

<div style="clear:both"></div>
<hr>


<div class = "container content">
<!--Make this an RSS Feed and import all articles over from https://www.ryanjaharden.com-->
<h2>Forthcoming Articles</h2>
<ul>
<li>Bring Back the DoDo! (forthcoming)</li>
<li>Where are all the USAFA Realtors? (forthcoming)</li>
</ul>

<hr>

<H2>On Writing</H2>
<ul> 
<li></li>
</ul>

<h2>Poetry</h2>
<ul>
<li>My Favorite Poems: A Curated List</li>
<li>I heard Heaven's bells</li>
<li>rain's fall</li>
<li>on happiness</li>
<li>serotonin</li>
<li>love & rage</li>
</ul>

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>



<h2>Published Works & Quotes</h2>
<ol>
<li><a href="https://nationalinterest.org/blog/buzz/biden-signs-ndaa-law-avoiding-effects-delayed-signing-198651">Biden Signs NDAA Into Law, Avoiding Effects of Delayed Signing</a></li>
<li><a href="https://inews.co.uk/news/analysis/china-hypersonic-missiles-balance-military-power-1313758">China's hypersonic missiles are raising questions in the US and beyond about the balance of military power</a></li>
<li><a href="https://www.rusi.org/explore-our-research/publications/commentary/chinas-hypersonic-missile-test-does-not-change-nuclear-calculus">China's Hypersonic Missile Test Does Not Change the Nuclear Calculus</a></li>
<li><a href="https://www.linkedin.com/news/story/one-table-isnt-big-enough-4584241/">One table isn't big enough</a></li>
<li><a href="https://www.ft.com/content/924c8163-60ac-404a-bc8b-29fd534b1c0d?accessToken=zwAAAXy6CCdIkdOSTIFjYKxAStO8iyn9U0scDQ.MEUCIFXNN7f-sCXSZiPoR03GdRZpwqw6TE6WfWiu0csDvSBIAiEA3raEmbb4ejMYnBsIcN0tUDoW1-7sR7MLPP53a0IgN0c&sharetype=gift?token=581de2cc-1b4b-4f2b-aa2e-bce6499203bc">Letter: China's hypersonic missiles do not change the nuclear calculus</a></li>
<li><a href="https://loneconservative.com/2021/05/28/the-gop-2024-president-trumps-post-presidency-future/">The GOP, 2024, & President Trump's Post-Presidency Future</a></li>
<li><a href="https://loneconservative.com/2019/01/31/the-conservative-case-for-conservation/">The Conservative Case for Conservation</a></li>
<li><a href="https://loneconservative.com/2019/02/09/candace-owens-mistakenly-defends-nationalist-socialist-ideology/">Candace Owens Mistakenly Defends Nationalist-Socialist Ideology</a></li>
<li><a href="https://loneconservative.com/2019/02/07/theres-no-room-for-governor-northams-intolerance/">There's No Room for Governor Northam's Intolerance</a></li>
<li><a href="https://bestdelegate.com/the-u-s-air-force-academy-approach-to-model-united-nations/">The U.S. Air Force Academy Approach to Model United Nations</a></li>
</ol>