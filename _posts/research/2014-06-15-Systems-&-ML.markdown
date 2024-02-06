---
layout: post
tag: ml
img: ML.jpg
summary: building smart systems and building systems smartly
---

<div class="row-fluid">
<i>
<p>
Modern machine-learning and artificial intelligence problems are not (only) algorithmetic ones
but (also) systems ones.
We are seeking solutions for both building better systems for ML/AI 
and using ML/AI to build systems.
</p>
</i>
</div>

<hr>
<hr>

<div class="row-fluid">
<h3>Efficient Serving for API-Augmented LLMs</h3>
<div class="span6">
<p class="text-left">
Large language models are increasingly integrated with external tools and APIs like ChatGPT plugins to extend their capability beyond language-centric tasks. However, today's LLM inference systems are designed for standalone LLMs. They treat API calls as new requests, causing unnecessary recomputation of already computed contexts, which accounts for 37-40% of total model forwarding time. 
</p>
<p>
We built <b>APIServe</b>, the first LLM inference framework targeting API-augmented LLMs. APIServe minimizes the GPU resource waste caused by API calls and dedicates saved memory for serving more requests. APIServe improves the overall serving throughput by 1.6x and completes 2x more requests per second compared to the state-of-the-art LLM inference systems.
</p>
</div>

<hr>

<div class="row-fluid">
<h3>Using ML to Build OS</h3>
<div class="span6">
<p class="text-left">
With operating systems being at the core of computer systems, decades of research and engineering efforts have been
put into the development of OSes. To keep pace with the
speed of modern hardware and application evolvement, we
argue that a different approach should be taken in future OS
development. Instead of relying solely on human wisdom, we
should also leverage AI and machine learning techniques to
automatically “learn” how to build and tune an OS. This paper
explores the opportunities and challenges of the “learned” OS
approach and makes recommendation for future researchers
and practitioners on building such an OS.
</p>
</div>
