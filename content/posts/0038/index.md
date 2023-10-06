---
title: "Fonts in Different Mediums"
date: 2023-10-05T00:40:00-07:00
description: "Why you shouldn't use serif fonts on the web."
author: "Hayaan Rizvi"
showToc: false
TocOpen: false
draft: false
---

Look at these two bits of text.[^1] The one on the left is written in EB Garamond, the most popular font for typesetting books. If you go to your library right now and pick out a book at random, chances are it will be written using this font. The text on the right is written in Helvetica, a font so ubiquitous in digital design that it's installed on nearly every computer in existence (even this blog uses it).

{{< rawhtml >}}
<style>
	.box {
		display: flex;
		text-align: justify;
		gap: 5%;
	}
	@media screen and (max-width: 600px) {
		.box {
			flex-direction: column;
			text-align: left;
		}
	}
</style>
<div class="box">
	<div style="flex: 50%;">
		<b>EB Garamond</b>
		<p style="font-family: EB Garamond; font-size: 19px;">
			Alice was beginning to get very tired of sitting by her sister on the bank, and of having nothing to do: once or twice she had peeped into the book her sister was reading, but it had no pictures or conversations in it, "and what is the use of a book," thought Alice "without pictures or conversations?"
		</p>
	</div>
	<div style="flex: 50%;">
		<b>Helvetica</b>
		<p style="font-family: Helvetica;">
			Alice was beginning to get very tired of sitting by her sister on the bank, and of having nothing to do: once or twice she had peeped into the book her sister was reading, but it had no pictures or conversations in it, "and what is the use of a book," thought Alice "without pictures or conversations?"
		</p>
	</div>
</div>
{{< /rawhtml >}}

The fact that each of these fonts are popular in different mediums is no mistake. Serif fonts, like EB Garamond, feature ornamental additions to letters that have the side-effect of increasing readability. You can see it very clearly in the word sitting:

{{< rawhtml >}}
	<center>
	<span style="font-family: EB Garamond; font-size: 50px;">
		sitting
	</span>
	vs&nbsp;
	<span style="font-family: Helvetica; font-size: 45px;">
		sitting
	</span>
	</center>
<br>
{{< /rawhtml >}}

If I could, I would use serif fonts everywhere. But, when shown at a small font size on digital displays, serif fonts like EB Garamond end up looking muddy. Many displays just don't have the resolution to show serifs in all their glory. So, on the screen, adding serifs actually _decreases_ readability.

{{< rawhtml >}}
	<center>
	<span style="font-family: EB Garamond; font-size: 12px;">
		sitting
	</span>
	vs
	<span style="font-family: Helvetica; font-size: 10px;">
		sitting
	</span>
	</center>
<br>
{{< /rawhtml >}}

This isn't as much of an issue on modern, high-density displays. But it's still good practice to use serif fonts in print and sans-serif fonts digitally, unless you have a really good excuse not to.

[^1]: This post makes use of fancy fonts and clever formatting. If you are reading this on an RSS aggregator, please take a look at [the web version]() instead.
