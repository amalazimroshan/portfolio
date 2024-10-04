---
title: "Safepass"
date: 2024-10-04T21:16:08+05:30
draft: true
# weight: 1
# aliases: ["/first"]
tags: ["computer vision"]
description: "Desc Text."
ShowBreadCrumbs: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
# editPost:
#     URL: "https://github.com/<path_to_repo>/content"
#     Text: "Suggest Changes" # edit text
#     appendFilePath: true # to append file path to Edit link
---

SafePass is a project aimed at enhancing road safety by providing real-time information to drivers about the feasibility of overtaking a large vehicle, such as a truck. The system utilizes machine learning, computer vision, and vehicle dynamics to calculate and display a safety signal on the back of the truck, helping following drivers make informed decisions.

### Features

- **Object Detection**: Utilizes PyTorch and OpenCV for real-time detection of vehicles in front of the large vehicle.

- **Distance and Speed Calculation**: Determines the distance between the large vehicle and the detected vehicles, as well as the speed of the large vehicle.

- **Safety Signal**: Displays a dynamic red or green signal on the back of the large vehicle based on calculated safety parameters, indicating whether it's safe to overtake.
