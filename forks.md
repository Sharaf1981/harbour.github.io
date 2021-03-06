---
layout: default
title: "Forks"
---
<div markdown="1" class="components">

# Harbour Forks

## [Harbour](https://vszakats.github.io/harbour-core/) by [vszakats](https://github.com/vszakats) (version 3.4)

Forked in April of 2013 in an attempt to focus on a narrower set of platforms
and contrib libraries while also freeing up resources by distancing from
project/community management tasks. This fork focuses on Linux, Windows (64-bit)
and macOS, and some selected C compilers (clang, gcc/MinGW). It has the stated
goal to adapt all mainline (non-fork) updates with minimal delay. To ease
maintenance, this fork has the policy to disable all deprecated components by
default (they can be enabled though, with no promises). Other goals are
compatibility with mainline core, continuous maintenance, build automation and
security ([`hbcrypto`]({% if site.fork %}{{ site.baseurl }}{% else %}https://vszakats.github.io/harbour-core{% endif %}/contribs#hbcrypto)
contrib and [curl/OpenSSL builds](https://github.com/vszakats/harbour-deps)).
It also features a large number of fixes and cleanups, many of which are
eventually retrofitted to mainline.

This fork accepts
[donations]({% if site.fork %}{{ site.baseurl }}{% else %}https://vszakats.github.io/harbour-core{% endif %}/#this-fork).

* [Repository](https://github.com/vszakats/harbour-core)

This fork is largely compatible with mainline, with the notable exception
for deprecated parts, which are disabled by default.

## xHarbour

Forked in 2001 with the goal of providing a more aggressive development path
with a different approach to language extensions and compatibility and more
focus on the Windows platform along with commercial offerings.

* [Repository](https://sourceforge.net/projects/xharbour/)
* [Community](https://groups.google.com/forum/#!forum/comp.lang.xharbour)

Technical details on how this fork differs from the other variations,
[here](https://raw.githubusercontent.com/{{ site.repo_slug }}/master/doc/xhb-diff.txt).

{% if site.fork %}
## [Mainline](https://harbour.github.io/) (non-fork) Harbour

This is the non-fork, original version of Harbour, started in 1999.

* [Repository](https://github.com/harbour/core)
* [Community](https://groups.google.com/group/harbour-users/)
{% endif %}

</div>
