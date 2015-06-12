---
layout: default
title: ATX Preemie Warmer Main Page
---

# ATX Preemie Warmer v 0.1 Alpha

<a title="By Polihale (Own work) [CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0) or GFDL (http://www.gnu.org/copyleft/fdl.html)], via Wikimedia Commons" href="http://commons.wikimedia.org/wiki/File%3AMom_and_Premature_Baby_at_Kapiolani.jpg"><img width="512" alt="Mom and Premature Baby at Kapiolani" src="//upload.wikimedia.org/wikipedia/commons/2/20/Mom_and_Premature_Baby_at_Kapiolani.jpg"/></a>

## Purpose

Every year across the world, many low-birth weight babies die, in part because they do not have access to advanced medicine.

The ATX Preemie Warmer project is an open-source hardware and software project to try to address this problem. All work here is sharable under the GPL (for source code) or the Creative Commons Share Alike license (for hardware designs).

The ATX Preemie Warmer may be valuable:

* When [Kangaroo Care](https://en.wikipedia.org/wiki/Kangaroo_care) is impossible or as a temporary complement to Kangaroo Care,
* As an open-source example from which other low-cost, low-power medical projects may be developed, and
* As an example of using inexpensive technology to address other real world problems, such as a petrifilm incubator.

## Approach and History

An Arduino-based, heating pad-style solution was originally suggested by Stewart Holloway of the Austin Chapter of Engineers without Borders.

Robert L. Read developed a prototype, and then led a team to improve it a the [ATX Hack for Change](http://publicinvention.blogspot.com/2015/06/report-atx-hack-for-change-2015-preemie.html) Hackathon.

## Status

Version 0.1 Alpha of the ATX Preemie Warmer:

* Is able to maintain body temperature of realistic masses with 6-12 Volt battery power,
* Currently has a $49 Bill-of-materials that can be decreased with further development,
* Is constructable with basic, commonly available tools and materials, and
* Is potentially applicable to other problems, such as incubating Petrifilm for water quality testing.

Although partically successful in the sense that it is working and inexpensive, many obstacles exist to deploying this in a way that actually saves lives.
We have spoken to three medical professionals with experience in developing nations. They are somewhat skeptical of the usefulness of this device.  Our most pressing need right now is for more discussion with experienced health professionals to learn if, and how, the ATX Preemie Warmer could be a practical benefit. If you have relevant knowledge or experience, please contact us.

## Duplication and Getting Involved

In this repo, you will find a wealth of information about both the hardware, sewing, and software components of the project.  We are currently endeavoring to make it entirely possible to completely reproduce this work.

If you want to potentially save lives, empower people with limited resources, and have fun building Arduino projects, please contact me (Robert L. Read, <read.robert@gmail.com>, @RobertLRead) and lets figure out how you can have fun helping with this project. The [issues](https://github.com/PIFAH/ATX-Preemie/issues) represent a variety of valuble ways to hack this project forward.

## Other Solutions

### Kangaroo Care

[Kangaroo Care](https://en.wikipedia.org/wiki/Kangaroo_care) is an approach that emphasized early and continuous skin-to-skin contact with the parent. We do not wish this project to discourage Kangaroo Care. Hopefully our project provides a helpful alternative when Kangaroo Care is not possible.


### Embrace

The project is begin addressed by [Embrace Global](http://embraceglobal.org). However, that project supports a for-profit company, and it is not an open-source solution. 

### IncuBaby

A team of students at Rice University has designed a low-cost (< $250) box-style [incubator](http://oedk.rice.edu/Sys/PublicProfile/25543138/3637470) that can be inexpensively shipped.  This approach is more expensive but perhaps complementary to the ATX Preemie Warmer. It is unclear if their design is open source, and if it uses grid-based power or battery power. I would like a member of this team to contact me.

### Image Attributions

"Mom and Premature Baby at Kapiolani" --
By Polihale (Own work) [CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0) or GFDL (http://www.gnu.org/copyleft/fdl.html)], via Wikimedia Commons

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
