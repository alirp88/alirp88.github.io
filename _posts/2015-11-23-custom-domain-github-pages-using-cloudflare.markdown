---
published: true
title: Custom domain Github pages using Cloudflare
layout: post
tags: [Ali, Riahipour, iOS, cloudflare, DNS, custom, domain]
---
Today i begin to struggle with github.io and how to show my content inside github.io in my own custom domain. and find very good solution named [Cloudflare](https://www.cloudflare.com). A company that provides a content delivery network and distributed domain name server services, sitting between the visitor and the CloudFlare user's hosting provider, acting as a reverse proxy for websites. [Wikipedia](https://en.wikipedia.org/wiki/CloudFlare)

To do that just open a new account on cloudflare.com then add your domain there.
![alt text](https://raw.githubusercontent.com/alirp88/alirp88.github.io/master/public/images/Cloudflare/addDomainToCloudFlare.png "Add domain to cloudflare.com")

Then in DNS section, remove all of your `A` DNS record, add a new `CNAME` record and point it to (your-account.github.io). that's it. that is just that simple.
![alt text](https://raw.githubusercontent.com/alirp88/alirp88.github.io/master/public/images/Cloudflare/addDNSRecord.png "Add DNS record")