---
title: Building Blocks
author: Leo
layout: post
permalink: /2011/01/31/building-blocks/
dsq_thread_id:
  - 219630633
image:
  - 
embed:
  - This is the default text
seo_follow:
  - 'false'
seo_noindex:
  - 'false'
dsq_needs_sync:
  - 1
categories:
  - The Algorithm Design Manual
---
<figure id="attachment_96" style="width: 300px" class="wp-caption aligncenter">[<img class="size-medium wp-image-96" title="Logarithmic" src="http://i2.wp.com/leogau.org/blog/wp-content/uploads/2011/01/logarithmic-300x225.jpg?fit=300%2C225" alt="Logarithmic" srcset="http://i2.wp.com/leogau.org/blog/wp-content/uploads/2011/01/logarithmic.jpg?resize=300%2C225 300w, http://i2.wp.com/leogau.org/blog/wp-content/uploads/2011/01/logarithmic.jpg?w=640 640w" sizes="(max-width: 300px) 100vw, 300px" data-recalc-dims="1" />][1]<figcaption class="wp-caption-text">via flickr/quapan</figcaption></figure> 

**Chapters 2-3 of the The Algorithm Design Manual**

This week, I finished the Algorithm Analysis chapter and started Data Structures. Here are some ideas that grabbed me.

<p style="text-align: left;">
  ***
</p>

Going through the book and the course, I&#8217;ve found that Skiena is really good at describing technical subjects. He makes very good analogies that give you an intuitive feel for whatever he&#8217;s describing. Last week it was his description of algorithms. This week he tackles logarithms and pointers.

**Logarithms**

A major part thinking like a computer scientist is mapping problems into a class of algorithm. We care about the class of an algorithm because it governs the size of the input. How large of a problem can this algorithm solve? Can it handle 100 objects? 100,000,000?

Logarithms play a large part algorithm classes, so it&#8217;s important to get a deep &#8211; in your bones &#8211; kind of understanding of what logarithms are and how to use them. Logarithms are an inverse exponential functions but, what does that really mean?<sup>[<a href="#footnote_0_87" id="identifier_0_87" class="footnote-link footnote-identifier-link" title="Radiolab produced an amazing episode on the topic of Numbers and the first segment touches on logarithms. It&rsquo;s a fun look at how we (humans) think logarithmically. You can listen to that segment here but, I highly recommend the whole thing.">1</a>]</sup>

Here&#8217;s how Skiena puts it:

> &#8220;Logarithms reflect how many times we can double something until we get to n, or halve something until we get to 1.&#8221;

This is unbelievably useful to think about binary search, tree, and basically everything else.

For example, if you are doing a <a href="http://en.wikipedia.org/wiki/Binary_search_algorithm" target="_blank">binary search</a> on a NYC phone book, how many times do you have to halve the book until you get to a specific name? Log n.

I know this is baby stuff but, I think it&#8217;s a great way of looking at logarithms.

**Pointers**

Basic data structures are the building blocks we use to build more complex algorithms. When we can begin to think in terms of stacks and dictionaries, it allows us to solve more complex problems without worrying about the details.

Data structures fall into two categories &#8211; contiguous (arrays) and linked (pointers). They both have their own pros and cons.

Skiena talks a lot about the technical differences  and in doing so, he reveals a great analogy for thinking about pointers.

A pointer represents the address of a location in memory. His analogy is: a cell phone number. A cell phone number can be thought of as a pointer to its owner as they move about the world.

How great is that? Taking the analogy further, just like a pointer doesn&#8217;t need to know the contents of what it&#8217;s pointing to to be used, a cell phone number can be copied and shared. The caller doesn&#8217;t even need to know anything about the person, he just needs the cell phone number to reach the person.

Pointers will still be complex but it&#8217;s a little something to ease the confusion.

**Bonus notable idea**

When should you use stacks and queues and when should you use dictionaries?

Stacks and queues support data retrieval independent of its content &#8211; they retrieve data based on the time they came in.

Dictionaries support data based on content.

Explicitly stating this gives me a more intuitive feel for when to use these different data structures.

<ol class="footnotes">
  <li id="footnote_0_87" class="footnote">
    <a href="http://www.radiolab.org/" target="_blank">Radiolab</a> produced an amazing episode on the topic of <a href="http://www.radiolab.org/2009/nov/30/" target="_blank">Numbers</a> and the first segment touches on logarithms. It&#8217;s a fun look at how we (humans) think logarithmically. You can listen to that segment <a href="http://www.radiolab.org/2009/nov/30/innate-numbers/" target="_blank">here</a> but, I highly recommend <a href="http://www.radiolab.org/2009/nov/30/" target="_blank">the whole thing</a>. [<a href="#identifier_0_87" class="footnote-link footnote-back-link">&#8617;</a>]
  </li>
</ol>

 [1]: http://i2.wp.com/leogau.org/blog/wp-content/uploads/2011/01/logarithmic.jpg