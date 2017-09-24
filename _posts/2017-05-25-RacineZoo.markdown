---
layout: post
title:  "Racine Zoo"
subtitle: "The Perfect Companion for a Trip to the Zoo"
date:   2017-05-25 00:30:00
categories: iphone
permalink: "Zoo"
device: "iphone"
app_preview: "/images/Zoo/preview-Zoo.png"
name: "Racine Zoo"
tagline: "A Visitor's Guide"
app_icon: "/images/Zoo/icon-Zoo.png"
---

{% img center | /images/Zoo/Zoo_1.png | IOU Bank %}

{% textalign left %}
Developed through Software Engineering 2/App Factory  
**Initial Release:** August 23, 2017  
**iOS Team Size:** 5
{% endtextalign %}


{% section_title Contributions & Takeaways %}

{% textalign left %}
The Racine Zoo app was developed in our Software Engineering 2 class and transferred into the App Factory to finish. It is an informative application that zoo-goers can utilize during their time exploring. It includes animal facts, a map detailing the exhibits and locations, an event list, and an interactive component featuring beacons! The beacons use BLE to connect with the beacons which display exhibit information when a user walks within range. I mostly worked on the event manager and beacons. I also helped new developers troubleshoot when they encountered problems.  
**Takeaways**  
* Override **drawRect** to create custom views. If two events fall on the same day, the cell will expand to include both of them beside a single date view.  
* View debugging while implementing these custom views with the help of **View Hierarchy Debugging**  
* Logic using **Calendar** and **Date** classes to determine which events should be displayed and in which groups. 
* **Unit Testing** the event manager class to ensure edge cases of events work properly  
* **EKEventStore** allow users to easily add zoo events to their Calendar app  
* Use of **CoreLocation** to create a BeaconManager class to determine when a beacon comes into range to display exhibit information. 

{% endtextalign %}

{% textalign left %}
This was app was a great learning experience. It was the largest iOS team that I've had to collaberate with. We experienced the woes of merge conflicts that come with multiple developers and storyboard development. We decided to make use of Storyboard references to keep everyone's UI dev separate. It also led me to investigating programmatic vs Storyboard development and design patterns to avoid these problems such as coordinators. It also emphasized the importance of project architecture and organization to ensure modularity and ease of navigation for our team.  
**Moving Forward**: Maintenance
{% endtextalign %}

{% youtube Q79JlTdbvlg %}


{% download app_store | https://itunes.apple.com/us/app/racine-zoo/id1224785219?mt=8 %}

{% textalign center %}
[Client Website](http://www.racinezoo.org "http://www.racinezoo.org")
{% endtextalign %}


