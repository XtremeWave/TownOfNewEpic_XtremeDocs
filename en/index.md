---
title: Home
layout: home
hero:
  name: "TONEX Role Docs"
  tagline: The i18n supported and most complete official docs.
  actions:
    - theme: brand
      text: Donate
      link: https://www.xtreme.net.cn/donate
    - theme: alt
      text: Impostor
      link: /en/Role/Impostor/
features:
  - title: Vigilante
    details: You can kill 1 player
  - title: Yandere
    details: I Love You
  - title: Akujo
    details: Use your wiles to manipulate the crews into helping you
  - title: Vagator
    details: Nothing can be accomplished without rules or standards
---

---
> [!WARNING] Pilot site
> Trial runs of the site may be unstable, and you might encounter [502 Bad Gateway](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/502) errors.

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://cn-sy1.rains3.com/xtremewave/QingFeng.png',
    name: 'QingFeng',
    title: 'Creator',
    links: [
      { icon: 'github', link: 'https://github.com/QingFeng-awa' }
    ]
  },
  {
    avatar: 'https://cn-sy1.rains3.com/xtremewave/ynjq.jpg',
    name: "一念旧情",
    title: 'Role Story Author',
    links: [
      { icon: 'github', link: 'https://github.com/ynjq' }
    ]
  },
  {
    avatar: 'https://cn-sy1.rains3.com/xtremewave/ChatGPT.png',
    name: "ChatGPT",
    title: 'Translate',
  }
]
</script>
<div align="center">

<h2>Contributors to this docs</h2>

<VPTeamMembers size="medium" :members="members" />
</div>