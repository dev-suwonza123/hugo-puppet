+++
title = "รวมเว็บเครดิตฟรี 50 พร้อมโค้ด"
date = 2022-08-09T15:38:30+08:00
header_img = ""
toc = true
tags = ["documentation", "guide"]
categories = []
series = ["Themes Guide"]
+++

รวมเว็บเครดิตฟรีล่าสุด ไม่ต้องทำกิจกรรม พร้อมโค้ดลับทั้งหมด

<!--more-->

## FULLSLOTPG
![img](https://fullslotpg.com/wp-content/uploads/2022/12/fullslotpg-เครดิตฟรี-1-1.jpg)  

fullslotpg แจกเครดิตฟรี สมาชิกใหม่ 50 เครดิต  
พิเศษ สายฟาร์ม เก็บเพชร หมุนวงล้อได้ฟรีทุกวัน  
 [สมัคร](https://game.fullslotpg.com/register?token=uDRo5gWYMTJPY46Q)  

```
โค้ดฟรี 50: AFWT-Y74W-8CN0  
💎     300     💎
💎 QGK5-AB3R-XXCV
➡️ โค้ดเพชร 100 💎  
💎 L6NH-H5G2-30KA
💎 9NVE-T7AV-PH67
💎 ANV3-YDG0-GNK6
💎 F9N5-T5W9-3E4D
💎 XKX7-3MKW-JMBK

```

## Add the Theme

You can download and unpack the theme manually from Github or use git to clone the theme into your site's `themes` directory.

```bash
cd mysite
git init
git clone https://github.com/roninro/hugo-theme-puppet.git themes/puppet
```

Or you can add the theme as a submodule.

```bash
cd mysite
git init
git submodule add https://github.com/roninro/hugo-theme-puppet.git themes/puppet
git submodule update --init --recursive
```

That’s all, Puppet is ready to be used.


## Add Config Files

For getting started, you can copy the `config.toml` file from the theme's exampleSite directory to the root directory of your site.

```bash
cp themes/puppet/exampleSite/config.toml .
```

> Note: You may need to delete the `themesDir` line in the config file.

## Add Some Content

Create a new post with the following command.

```bash
hugo new posts/my-first-post.md
```

Edit the content of the post.

```markdown
+++
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
description = ""
draft = true
subtitle = ""
header_img = ""
toc = true
tags = []
categories = []
series = []
comment = true
+++

Your content here...
```

Some front-matter used for SEO, others used for displaying contents, configuration, etc.

## Run example site

From the root of themes/puppet/exampleSite:

```bash
hugo server --themesDir ../..
```
