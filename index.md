---
layout: page
title: AI and ML for Microscopy, Hackathon
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}

<div class="lead" markdown="1">
Participation is FREE and open. Let’s build the future of microscopy together!

The closing date for applications is November 1 2024.



</div>

<div class="aside">
    <div id="countdown" class="text-center"></div>
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
    <dl>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dd>
                Applications open for participants<br>
                {% if site.registration_status == 'open' %}
                    <a href="{{ site.baseurl }}{% link registration.md %}" class="btn">Registration page</a>
                {% elsif site.registration_status == 'closed' %}
                    <a class="btn disabled">Registration has closed</a>
                {% elsif site.registration_status == 'soon' %}
                    <a class="btn disabled">Registration opens soon</a>
                {% endif %}
            </dd>
        {% endif %}

        <dt>{{ site.registration_closes_date }}</dt>
        <dd>Applications close</dd>

        <dt>{{ site.event_date }}</dt>
        <dd>Hackathon date</dd>
    </dl>
</div>

{% if site.event_status != "over" %}




The hackathon is open to everyone, regardless of background or experience. Our North Star goal is to build the bridge between microscopy and machine learning communities. For microscopists, we welcome participation from all field - electron, scanning probe, chemical imaging, and all stages of the microscope workflow from sample selection to microscope optimization, data analytics, in-line analysis, automated experimentation, and interpretation. From machine learning community, we welcome experts in image analysis, optimization, and active learning. Let’s build the window between machine learning and nanoscale world together!

Prior programming experience is not required, but it is recommended for coding projects. We provide the starting materials on the resource page, To learn about the types of projects within the scope of the hackathon, go to the submission page.  During the hackathon, the organizers will be available to support you. After the hackathon, we plan to integrate the projects in scholarly publication. If you are interested in supporting the hackathon as an organizer or acting as a judge, please indicate so on the registration form.

## Logistics

The event will take place virtually, using a combination of **video conferencing** (Zoom) for meetings and seminars, and **discussion forums** (Slack, Miro). Slack, Miro, and Zoom links will be shared upon registration. 

## Prizes

Will be announced soon! 

{% else %}

{% endif %}

##  Gold Sponsor 

<div style="display: flex; align-items: center; justify-content: center;">
    <a href="https://research.utk.edu/oried/research-innovation-initiatives/ai-tennessee-initiative/">
        <img src="./assets/ai_tenn_logo.png" alt="AI Tennessee Initiative" style="width:230px; margin-right: 20px;">
    </a>
    <a href="https://www.onr.navy.mil/">
        <img src="./assets/ONR.png" alt="Office of Naval Research" style="width:400px; margin-left: 20px;">
    </a>
</div>

## Silver Sponsor

<div style="display: flex; align-items: center; justify-content: center;">
    <a href="https://www.thermofisher.com/">
        <img src="./assets/tf_logo.png" alt="ThermoFisher scientific" style="width:300px;">
    </a>
</div>

## Partners

<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">
    <a href="https://www.pnnl.gov/">
        <img src="./assets/pnnl_logo.jpg" alt="Pacific Northwest National Laboratory" style="width:200px;">
    </a>
    <a href="https://www.zyvexlabs.com/">
        <img src="./assets/zyvex_logo.png" alt="Zyvex Labs" style="width:300px;">
    </a>
    <a href="https://www.nrel.gov/">
        <img src="./assets/nrel_logo.png" alt="National Renewable Energy Laboratory" style="width:300px;">
    </a>
    <a href="https://foundry.lbl.gov/">
        <img src="./assets/mf_logo.png" alt="The Molecular Foundry" style="width:300px;">
    </a>
    <a href="https://www.ornl.gov/">
        <img src="./assets/ornl_logo.png" alt="Oak Ridge National Laboratory" style="width:280px;">
    </a>
</div>


#### Please get in touch if you would like to be a sponsor at [sergei2@utk.edu](mailto:sergei2@utk.edu)