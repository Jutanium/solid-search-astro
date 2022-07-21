---
layout: "../../layouts/BlogPost.astro"
title: "Hello galaxy of possibilities!"
description: "Take your blog to astronomical heights"
publishDate: "12 Sep 2021"
followMe:
  username: "bholmesdev"
  href: "https://twitter.com/bholmesdev"
halfTheMeaning: 21
heroImage:
  src: "/assets/blog/introducing-astro.jpg"
  alt: "Space shuttle leaving curved trail in the sky"
setup: |
  import LikeButton from "../../components/LikeButton"
  import FollowMe from "../../components/FollowMe.astro"
---

From frontmatter: **{frontmatter.halfTheMeaning * 2}**

If this seems cool, consider giving my post a like with this Solid component: <LikeButton pageUrl={frontmatter.url} client:load />
