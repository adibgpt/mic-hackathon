---
title: Submit a Project
menu_title: Submission
menu_icon: cloud-arrow-up
---


## Hackathon Navigation Guide:

**[Link]((https://join.slack.com/t/mic-hackathon/shared_invite/zt-2t3ftu8vr-cnXAfhxZ1wdvkOzUo4_1~w)) to join slack group**.


**[Link](https://miro.com/app/board/uXjVLN06K4Y=/?share_link_id=419763633861) to access miro board**. Edit access will be provided after joining the slack. 


Q1. Already have a team and project idea?
1. Head to Miro and add your team name, members, and project idea on the board. This helps everyone see what’s happening and encourages collaboration!

Q2. Have a project idea but need teammates?
1. Visit Miro and post your idea with a note that you’re seeking contributors! Be sure to include any specific skills or interests you’re looking for in teammates.

Q3. Don’t have a team or project idea yet?
1. Explore Miro – Check out existing projects and reach out to teams that interest you.
2. Browse Project Suggestions – Take a look at our curated list of potential projects listed in below section.
3. Post on Slack – Share your skills, interests, or the projects you’d like to join. Connect with others who may also be looking for teams!


In case of any confusion please reach out to us on slack!
## Topics

While a list of topics is provided, we are open to new ideas. If you have a project in mind that doesn't fit into one of the topics below, you are welcome and encouraged to submit a project proposal for it.

### Topic 1: Image and Hyperspectral Image Analysis

We provide a set of open electron and scanning probe microscopy datasets and describe the relevant physical problem. Your job will be to choose a package or algorithm and apply it to the task of your choice, ideally melding the ML methods with physics. For several of these datasets, we will provide the references, but there may be (and most likely are) new physical insights in this data that await exploration! Remember that microscopy data matters in the context of specific physical problems, and machine learning can help make the connection. If you are interested in forming a team around exploring your own data, go to the “New problems” topic. If you are interested in real-time analytics and active learning, go to the “Active learning” section.

### Topic 2: New Problems for Real-world Materials Imaging and Spectroscopy

If you are interested in exploring ML for your own datasets—whether this is a particularly interesting static and dynamic STEM dataset, AFM image of butterfly wings or working catalyst, or mass-spectrometry dataset—this section is for you. 

### Topic 3: Creating Instructional Tutorials

We have a set of examples of ML applications for image and spectroscopy analysis, and your job will be to create a tutorial that introduces the topic conceptually and provides a hands-on example for provided or own data. Topics other than the ones listed are also fair game. These are meant to be “gentle introduction” tutorials which assume beginner Python knowledge and beginner machine learning background.

### Topic 4: Active Learning and Real-time Analysis

The key value proposition of machine learning is the real-time analysis of data streaming from microscopes. This can be used for image and spectroscopy parameter optimization (or microscope tuning), visualization of large or high-dimensional datasets to assist human decision-making, or to make decisions automatically in real-time. Here we provide several data sources that emulate the operation of the real microscope, to use for building real-time microscope operations. These include:

- Pre-acquired data (STEM EELS, PFM, 4D STEM) that is not available to the operator in full but can be queried sequentially much like a real experiment, with the goal of building algorithms that can learn structure-property relationships in the smallest number of steps.
- SPM optimizer that provides access to images with different microscope control parameters, with the goal of fastest imaging optimizers.
- Real-time reconstruction and segmentation, when the data is streamed one line at a time and the goal is to build real-time denoiser and image reconstructor.

### Topic 5: Simulators for Active Learning


### Topic 6: From Microscopy to ML and Back

The machine learning community currently covers a broad range of analysis and decision-making algorithms, from simple linear methods to A* and Monte Carlo Decision Trees. Many of these algorithms have enabled successes such as AlphaFold, MuZero, and many others. However, applications of these algorithms to microscopy require abstracting real-world problems in a language that ML algorithms can interpret. This topic solicits projects in two complementary areas:

- Casting real-world microscope operations in terms of ML problems, e.g., identifying states, actions, reward functions, and objectives.
- ML solutions for microscopy problems.

Submissions to this topic can vary from manual analysis of microscopy workflows, crowdsourcing, or using LLMs.

### Topic 7: Grand Challenge Problems

- Domain assembly 
- Atomic motion 

### Topic 8: General

This category is for projects that don’t fit into the special topics listed above but are relevant for microscopy in all its embodiments. Projects in this context are **welcome!** If you’re unsure about a project, feel free to reach out to sergei2@utk.edu.

