# James M. Greene [<img class="emoji" title="GitHub" alt=":octocat:" src="https://a248.e.akamai.net/assets.github.com/images/icons/emoji/octocat.png" height="20" width="20" align="absmiddle" />][me/gh] [<img class="emoji" title="Twitter" alt=":bird:" src="https://a248.e.akamai.net/assets.github.com/images/icons/emoji/bird.png" height="20" width="20" align="absmiddle" />][me/t] [<img class="emoji" title="Email" alt=":e-mail:" src="https://a248.e.akamai.net/assets.github.com/images/icons/emoji/e-mail.png" height="20" width="20" align="absmiddle" />][me/email] [<img class="emoji" title="Website" alt=":earth_americas:" src="https://a248.e.akamai.net/assets.github.com/images/icons/emoji/earth_americas.png" height="20" width="20" align="absmiddle" />][me/site]  

---

## Best Project

### New Feature: User Annotations
The best project that I have had the honor of spearheading was the prototyping, refining, and implementing of the "User Annotations" feature for my employer's latest flagship product for legal research, [WestlawNext][wlnext/product] (also, [its marketing site][wlnext/promo]). This feature enabled users to:
 1. Highlight text within our legal documents.
 2. Highlight text within our legal documents and attach a inline note to it.
 3. Attach document-level notes when no associated text needs to be highlighted.


### Why?
So why was this feature the best project I've worked on to date?  It was:
 - "Impossible": When our Information Architect originally brought the idea to me and my team on a Friday afternoon, we all thought it was impossible to achieve, especially cross-browser (IE >= 7, and friends). None of us had ever seen such functionality on the web at that point, only in desktop applications like Adobe Reader/Acrobat&mdash;and it is still quite rare even today.
 - Agile: ?
 - Unique Knowledge: what we didn't know, even as seasoned web developers, was that the browsers did each offer _one of two_ Selection & Range DOM APIs: IE's proprietary model or the W3C standardized model. However, both had their pros and cons but were certainly not equivalent morels. The work I had to do to bridge the gaps was effectively a proprietary precursor to the [Rangy][rangy] JavaScript library.
 - Challenging: ?


### Sharing
Unfortunately, I have never been able to acquire permission from my employer to open source the overall annotations workflow. However, I have been "allowed" to open source several smaller pieces of it by deciding that sharing them with the world was important enough to me to warrant the extra effort required to rewrite them from scratch. Thus, I have since released initial versions of the "jquery.textSelect" and "jWalker" JavaScript libraries (see [OPEN-SOURCE.md][cover-letter/open-source] for more details), though more work remains to get them up to par with the robustness and completeness of their proprietary counterparts.


[me/gh]: http://github.com/JamesMGreene "GitHub"
[me/t]: http://twitter.com/_JamesMGreene "Twitter"
[me/email]: mailto:james.m.greene@gmail.com "Email"
[me/site]: http://about.me/JamesMGreene "Website"
[wlnext/product]: http://next.westlaw.com
[wlnext/promo]: http://westlawnext.com
[rangy]: http://code.google.com/p/rangy
[cover-letter/open-source]: OPEN-SOURCE.md
