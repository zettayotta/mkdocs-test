---
status: new
# date: 2024-06-01
created: 2025-06-16
# updated: 2024-06-10

title: Page title here!
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
authors:
  - Axel Bjelke

#hide:
#  - toc
#  - navigation

# icon: material/emoticon-happy
tags:
  - tag1
---

# This is the first section
'ødalm¨dvnk¨
ælckndonkcvå

## Second section
cakmc¨kan
dcækl c¨kn

==The end==



# This is a header


*06/2025 Started a new instance of a cloud server based on Ubuntu 24.04 with Docker CE.*

## H2
### H3
#### H4
##### H5

The server is defined in `IT.ods/Devices`.

``` yaml
theme:
  features:
    - content.code.annotate #
```
KJpbpib[^1]

[^1]: man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

## To-do

- [ ]  Check docker stats
- [x]  Obtain root password (password is not sent via e-mail when the server is initially configured with SSH keys)
- [x]  Connect with SSH
    - [ ]  check settings, auth
- [x]  Update
- [ ]  Linux hardening

- **Setting up a production ready VPS**
    
    YouTube: [Setting up a production ready VPS is a lot easier than I thought.](https://www.youtube.com/watch?v=F-9KWQByeU0)
    
    Requirements:
    
    - [ ]  Domain name
    - [ ]  App running (what’s this?)
    - [ ]  TLS + HTTPS + autorenew
    - [ ]  OpenSSH hardening
    - [ ]  Firewall
    - [ ]  Load balancer + HA
    - [ ]  Automated deploys
    - [ ]  Monitoring
    
    To-do:
    
    - [x]  Add a new user account: `adduser <name>`
        - [x]  Elevate new users privileges with sudo: `usermod -aG sudo <username>` add the user to to sudo group
        - [x]  Test new user: `su - <usename>` switches user, and type a sudo command to verify it’s working
    - [ ]  

## Use cases and considerations

*A platform for technical documentation (and possibly other things as well).*

Initially my thought was to rent a new VPS instance for a new documentation system available from the internet. This would succeed my current Wiki.js instance hosted on DigitalOcean.

[**Wiki.js**](https://js.wiki) is very good looking and with a nice set of features, so I’ve been very reluctant to abandon this platform. The major downsides for me though, is the lack of active development. The developer promises huge improvements with the next major release (3.x) but it’s not happening and I’ve been waiting for years now…

→ So what’s the alternatives?

[**Notion**](https://www.notion.so) is really nice, and where I have most of my written documentation (as of 2025). The reason I wan’t to migrate away from Notion over time is the lack of control and ownership of my data (and possibly privacy). On top of that the service is really slow.

[**Anytype**](https://anytype.io) is the new kid on the block with promises of real data ownership, privacy first and E2E encryption. The problem is, it’s still in beta and under heavy development. But I’m paying for the app and hope the future is bright!

[**WordPress**](https://nb.wordpress.org) is where my old blog lives, dating back to at least 2011. For me it’s a bit clunky with all the plugins, themes and shit. Hard to decide on all the options. And good themes/plugins are often pricey.

[**Hugo**](https://gohugo.io) looks good, as presented in the [Cavelab](https://blog.cavelab.dev/2019/01/platform-hopping-hello-hugo/) blog by Thomas Jensen. But probably way to technical for me.

[**Material for MkDocs**](https://squidfunk.github.io/mkdocs-material/) 

[**BookStack**](https://www.bookstackapp.com) 

[**Outline**](https://www.getoutline.com) 

[**Obsidian**](https://obsidian.md) 

These are probably my best (known) options, but the field is vast and ever changing…

---