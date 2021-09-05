---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant, Vision & Learning
    company: IIITD Autonomous Last mIle VEhicle (ALIVE)
    company_url: 'https://sites.google.com/iiitd.ac.in/iiitd-alive'
    company_logo: "https://www.iiitd.ac.in/sites/default/files/images/logo/logo.jpg"
    location: Delhi
    date_start: '2020-10-19'
    date_end: ''
    description: |2-
        Working on the development and testing of the Perception software stack for the autonomous vehicle:
    
        * Worked on the camera-based object detection, traffic light detection and classification and tracking module.
        * Setup infrastructure for benchmarking several state-of-the-art 2D object detectors on autonomous driving datasets such as BDD100K.
        * Created a novel metric for evaluating detection of traffic lights as a function of the distance to the traffic light.
        * Created ROS nodes for deploying these detectors on a Jetson AGX Xavier as part of the autonomousstack of the car using Torchscript and OpenCV.
        * Currently benchmarking and hypothesizing multi-task models for object detection, lane detection and object tracking.
        * Settign up infrastructure for scenario-based performance and safety testing of the perception stack.

  - title: Student Trainee
    company: Samsung R&D Institute India - Bangalore Pvt. Ltd.
    company_url: ''
    company_logo: org-gc
    location: Bangalore
    date_start: '2020-01-06'
    date_end: '2020-06-18'
    description: |2-
        Worked on the development of Near Real-Time RAN Intelligence Controller (RIC)

        * Brought up the Near Real-Time RAN Intelligence Controller(RIC) Kubernetes cluster.
        * Established connection between Near Real-Time RIC cluster and RIC dashboard to facilitate deployment of xApps and creation of new policies.
        * Wrote xApp components to achieve communication between xApp and the Near Real-Time RIC A1-Mediator via RIC Message RouterAPIs to facilitate movement of policies across the cluster components.

  - title: Research Intern
    company: Robotics Research Center, IIIT Hyderabad
    company_url: ''
    company_logo: org-x
    location: Hyderabad
    date_start: '2019-05-15'
    date_end: '2019-05-15'
    description: Created a ROS-aware Gazebo plugin to incorporate path planning for actors in Gazebo. The actor is treated as a mobile base by the plugin. The costmap is  retrieved via the costmap\_2d node. The A-star algorithm is then applied on the retrieved costmap for generating paths via the navfn package.

  - title: Data Science Intern
    company: Symbl.ai(Formerly known as Rammer.ai)
    company_url: ''
    company_logo: org-x
    location: Pune, Maharashtra
    date_start: '2018-12-01'
    date_end: '2019-01-03'
    description: |2-
        Worked on using deep neural networks for Natural Language Processing

        * Extracted ’action items’ and filtered out chit-chat in speech to text data gathered from meetings via a text classification model.
        * Trained Bidirectional GRU with attention mechanism for punctuation restoration model.

design:
  columns: '2'
---
