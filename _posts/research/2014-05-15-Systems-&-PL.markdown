---
layout: post
tag: pl
img: programming.png
summary: better programming for better systems building
---


<div class="row-fluid">
<i>
<p>
Writing correct programs is the foundation of building reliable software systems.
Programming language designers constantly seeks new approaches to improve the efficiency, 
relability, and flexibility of software programming.
However, less is known about how effective these new approaches are in the real world.
We take an empirical view of new programming languages features
by studying real-world usages and issues (i.e., bugs)
and by building tools that can help programmers avoid or detect bugs.
</p>
</i>
</div>

<hr>
<hr>

<div class="row-fluid">
<h3>Empirical Study on Rust Safety Bugs</h3>
<div class="span6">
<p class="text-left">
Rust is a young programming language designed for systems software development. It aims to provide safety guarantees like high-level languages and performance efficiency like low-level languages. The core design of Rust is a set of strict safety rules enforced by compile-time checking. To support more low-level controls, Rust allows programmers to bypass these compiler checks to write unsafe code.
</p>
<p>
It is important to understand what safety issues exist in real Rust programs and how Rust safety mechanisms impact programming practices. We performed the first empirical study of Rust by close, manual inspection of 850 unsafe code usages and 170 bugs in five open-source Rust projects, five widely-used Rust libraries, two online security databases, and the Rust standard library. Our study answers three important questions: how and why do programmers write unsafe code, what memory-safety issues real Rust programs have, and what concurrency bugs Rust programmers make. Our study reveals interesting real-world Rust program behaviors and new issues Rust programmers make.
</p>
</div>
	  <!--
<div class="span4">
<img height="150" src="img/research/Rust.png">
</div>
	  -->
</div>

<hr>

<div class="row-fluid">
<h3>Empirical Study on Go Concurrency Bugs</h3>
<div class="span6">
<p class="text-left">
Go is a statically-typed programming language that aims
to provide a simple, efficient, and safe way to build multithreaded software. Since its creation in 2009, Go has matured and gained significant adoption in production and
open-source software. Go advocates for the usage of message passing as the means of inter-thread communication
and provides several new concurrency mechanisms and libraries to ease multi-threading programming. It is important
to understand the implication of these new proposals and the
comparison of message passing and shared memory synchronization in terms of program errors, or bugs. Unfortunately,
as far as we know, there has been no study on Go’s concurrency bugs.
</p>
<p>
We performed the first systematic study on
concurrency bugs in real Go programs. We studied six popular Go software including Docker, Kubernetes, and gRPC.
We analyzed 171 concurrency bugs in total, with more than
half of them caused by non-traditional, Go-specific problems.
Our study provides a better understanding on Go’s
concurrency models and can guide future researchers and
practitioners in writing better, more reliable Go software
and in developing debugging and diagnosis tools for Go.
</p>
</div>
	  <!--
<div class="span5">
<img height="150" src="img/research/gopher.png">
</div>
	  -->
</div>
