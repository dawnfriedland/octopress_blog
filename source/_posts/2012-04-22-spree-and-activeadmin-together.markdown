---
layout: post
title: "Spree and ActiveAdmin Together"
date: 2012-04-22 17:08
comments: true
categories: [rails, spree, activeadmin]
---
First I installed Spree (see [installing spree]()). Then I installed activeadmin. Whoops, the activeadmin uses the "/admin" directory, which is what Spree uses for it's admin. Well, I went into this file ____ and changed the ____. It worked! Now I have two admin areas: one for spree and the other for activeadmin. 