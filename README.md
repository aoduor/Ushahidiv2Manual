![image alt text](../Images/image_0.png)

Ushahidi v2.7.4 Manual

[[TOC]]

# About Ushahidi

Ushahidi which means "testimony" in Swahili, was a website that was initially developed to map reports of violence in Kenya after the post-election fallout at the beginning of 2008. Since then, the name “Ushahidi” has come to represent the people behind the “Ushahidi Platform”.

The Ushahidi platform is an open source software for information collection, visualization, and interactive mapping. People can send in information from multiple channels including SMS, email, Twitter and web reports. The platform timestamps each report and allows you to geotag them and organize them in a simple to use Data Management System, and displays the crowdsourced information on a map and timeline. The platform has been used around the world because of it’s ability to easily integrate simple communication tools like SMS with digital channels like Twitter to be able to access all types of people through the means of communication they are most accustomed with.

Over the last seven years,  Ushahidi has grown into a global non-profit technology company, whose mission is to change the way information flows in the world and empower people to make an impact with open source technologies, cross-sector partnerships, and ground-breaking ventures.

Ushahidi is responsible for founding the [iHub](http://ihub.co.ke), a technology hub in Nairobi which has helped build the technology community in East Africa, growing to over 14,000 members, has incubated 150 tech startups that have created over 1000 jobs. Ushahidi, together with partners Hivos and the Institute of Development Studies, implements the [Making all Voices Count Grand Challenge](http://makingallvoicescount.com/), a $55 million fund which focuses global attention on creative and cutting-edge solutions to transform the relationship between citizens and their governments including seeding innovative solutions.

Lastly, as a group of technologists spread around the world who get really frustrated when the internet doesn’t work, Ushahidi built and spun out [BRCK](https://brck.com), which builds rugged internet for people and things.

# About this Guide

This guide will give you a step-by-step overview on how to set up your own Ushahidi version 2.x map and how to make full use of all the features that the Ushahidi platform software offers. If you’d like to learn more, we have additional resources available online for you-

* [https://forums.ushahidi.com](https://forums.ushahidi.com)

* [https://wiki.ushahidi.com](https://wiki.ushahidi.com)

* [http://www.ushahidi.com/get-help/](http://www.ushahidi.com/get-help/)

This guide will show you how to install the ushahidi platform, customize it to the needs of your project, and process the incoming information. It is meant to be a comprehensive learning guide for brand new users of the Ushahidi platform as well as a reference for those who are more technically savvy or have used it in the past in an administrative capacity.

* **If you’re a user, go to ****[Section 4: The User Interfac**e](#heading=h.4vxhy7xlldns)

* **If you’re an administrator and want to process information coming into the platform, go to ****[Section 3: Processing Incoming Informatio**n](#heading=h.pmihqnhbe5fn)

* **If you’re an administrator and want to customize your platform, go to ****[Section 2: Customizing your deploymen**t](#heading=h.rd4rpl44wkqw)

If you’re a developer looking to make functional customisations to the Ushahidi platform, [please see our detailed developer guide for insights](https://wiki.ushahidi.com/display/WIKI/Ushahidi+v2.X+Developer+Guide).

If you have any problems and need some guidance or help, reach out to us via:-

* info[at]ushahidi[dot]com

* [Ushahidi Mailing Lists](http://list.ushahidi.com/)

* [Ushahidi Forums](https://wiki.ushahidi.com/display/WIKI/Report+a+bug)

* Ushahidi Skype dev chat

* [IRC Channel](http://irc.lc/freenode/ushahidi)/ [Gitter Channel](https://gitter.im/ushahidi/Community)/ [Hipchat Channel](https://www.hipchat.com/g9I7z8M9a)(Note that posting on any one of these channels will display on all three)

If you bump into a bug on the platform or have a feature you would like to request, please file it on our github issues page([https://github.com/ushahidi/Ushahidi_Web/issues](https://github.com/ushahidi/Ushahidi_Web/issues)). [Here’s a guide on how to file a good bug report](https://wiki.ushahidi.com/display/WIKI/Report+a+bug). 

We also recommend going through the [Ushahidi toolkits](https://wiki.ushahidi.com/display/WIKI/Ushahidi+Toolkits), aside from this manual, for insights on strategic planning around your deployment.

* [Assessment Tool](http://www.slideshare.net/Ushahidi/ush-kenya-assessmenttool101launchfinal11)

* [Implementation Tool](http://www.slideshare.net/Ushahidi/ushahidi-deployment-implementation-toolbox)

* [Output Tool](http://www.slideshare.net/Ushahidi/ushahidi-deployment-output-toolbox)

**_This guide has been updated and adapted based on content provided from the first version of the Ushahidi manual by Anahi Ayala Iacucci (to whom we are grateful for all the amazing work), the Ushahidi Wiki, and also contains new content from features that were previously undocumented for Ushahidi version 2.x by Angela Oduor Lungati._**

**_Feedback is welcome, and will be incorporated into this guide moving forward._**
