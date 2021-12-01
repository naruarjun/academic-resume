---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Work Experience
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
    company_logo: iiid
    location: Delhi
    date_start: '2020-10-19'
    date_end: ''
    description: |2-
        Working on the development and testing of the Perception software stack for the autonomous vehicle:
    
        * Created camera-based object detection and tracking module.
        * Created camera-based traffic light detection and tracking module.
        * Setup infrastructure for benchmarking several state-of-the-art 2D object detectors on autonomous driving datasets such as BDD100K and Indian Driving Dataset.
        * Created ROS nodes for deploying these detectors on a Jetson AGX Xavier as part of the autonomous stack of the car using Torchscript and OpenCV with a frame rate of 22 FPS.
        * Position and speed of detected objects were estimated by fusing Camera and LIDAR data using a Kalman Filter and calibration information.
        * Created a Traffic Light color classifier using Gaussian Mixture Models.
        * Working on an annotation tool that uses calibration information to facilitate multi-sensor annotation.

  - title: Student Trainee
    company: Samsung R&D Institute India - Bangalore Pvt. Ltd.
    company_url: ''
    company_logo: samsung
    location: Bangalore
    date_start: '2020-01-06'
    date_end: '2020-06-18'
    description: |2-
        Worked on the development of Near Real-Time RAN Intelligence Controller (RIC)

        * Brought up the Near Real-Time RAN Intelligence Controller(RIC) Kubernetes cluster.
        * Established connection between Near Real-Time RIC cluster and RIC dashboard to facilitate deployment of xApps and creation of new policies.
        * Wrote xApp components to communicate between xApp and the Near Real-Time RIC A1-Mediator.
        * Used RIC Message Router APIs to facilitate movement of policies across the cluster components.
        * Created Helm charts and Docker images for the xApps.

  - title: Research Intern
    company: Robotics Research Center, IIIT Hyderabad
    company_url: ''
    company_logo: iiith
    location: Hyderabad
    date_start: '2019-05-15'
    date_end: '2019-07-15'
    description: Created a ROS-aware Gazebo plugin to incorporate path planning for actors in Gazebo. The actor is treated as a mobile base by the plugin. The costmap is  retrieved via the costmap\_2d node. The A-star algorithm is then applied on the retrieved costmap for generating paths via the navfn package.

  - title: Data Science Intern
    company: Symbl.ai(Formerly known as Rammer.ai)
    company_url: ''
    company_logo: symbl
    location: Pune, Maharashtra
    date_start: '2018-12-01'
    date_end: '2019-01-03'
    description: |2-
        Worked on using deep neural networks for Natural Language Processing

        * Extracted 'action items' and filtered out chit-chat from meeting transcripts.
        * Trained Bidirectional GRU with attention mechanism for punctuation restoration model.
        * Designed and trained a two-layer GRU model in Keras to classify an input sentence as relevant or not.
        * Augmented training data by analyzing constituency tree and part-of-speech tags and inserting synonyms.
        * Used Google Sentence Encoder to extract sentences with the same semantic meaning by using similarity metrics such as a cosine similarity for targeted training.

design:
  columns: '2'
---
