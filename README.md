# Animal Intrusion Alerting System For Crop Protection

## About
The Animal Intrusion Alerting System for Crop Protection represents a significant advancement in agricultural technology, aimed at addressing the pressing issue of animal intrusion and its detrimental impact on crop yields. By harnessing cutting-edge technology such as computer vision and email notification capabilities, the system provides farmers with a proactive solution to detect and respond to animal intrusions in real-time.At the core of this system lies the utilization of deep learning algorithms, specifically the YOLO (You Only Look Once) object detection framework. This enables the system to accurately identify various animals commonly found in agricultural environments, regardless of their size, shape, or movement patterns. By analyzing video footage captured by strategically placed surveillance cameras in fields, the system continuously monitors for any signs of animal intrusion.
Upon detecting an animal, the system promptly triggers an alert mechanism designed to notify farmers. This includes activating an alarm to deter the intruding animal and sending an email notification directly to the farmer's inbox. The email notification contains detailed information about the detected animal, including its species, and provides a snapshot of the intrusion captured by the surveillance camera. This allows farmers to quickly assess the situation and take appropriate action to mitigate any potential damage to their crops.
Overall, the Animal Intrusion Alerting System for Crop Protection offers farmers a comprehensive and effective means of safeguarding their crops against animal intrusions. By combining advanced technology with real-time monitoring and alerting capabilities, the system empowers farmers to protect their agricultural investments and optimize their yields.


## Features
The Animal Intrusion Alerting System for Crop Protection incorporates several features to enhance its effectiveness in detecting animal intrusions and notifying farmers. Here are the key features of the system:

Real-time Animal Detection: 

Utilizes the YOLO (You Only Look Once) algorithm for real-time detection of animals in video streams captured by cameras placed in agricultural fields.

Alerting Mechanisms:

Audible Alerts: Plays alarm sounds to alert farmers immediately upon detecting animal intrusions, ensuring prompt attention.
Email Notifications: Sends email notifications to farmers with detailed information about the detected animals, including images captured during the intrusion.
Multiple Animal Classifications: Supports detection and classification of various animal species relevant to agricultural settings, such as birds, cats, dogs, sheep, horses, cows, elephants, zebras, bears, and giraffes.

Non-Maximum Suppression (NMS): Applies NMS to suppress weak, overlapping bounding boxes and retain only the most confident detections, improving the accuracy of the detection results.

User-friendly Interface: Provides a user-friendly interface for configuring system parameters, monitoring real-time detection results, and managing alert settings.

Scalability: Designed to be scalable, allowing for integration with multiple cameras across large agricultural areas to provide comprehensive coverage and protection against animal intrusions.

Customizable Alerts: Enables users to customize alert preferences, including the choice of alarm sounds, email notification recipients, and frequency of notifications.

Continuous Monitoring: Supports continuous monitoring of video streams, ensuring ongoing surveillance of agricultural fields and timely response to any detected animal intrusions.

Integration with Existing Infrastructure: Easily integrates with existing surveillance systems, enabling seamless deployment and integration into farmers' existing workflows and infrastructure.

By combining these features, the Animal Intrusion Alerting System offers a comprehensive solution for protecting crops from wildlife intrusion, empowering farmers to take proactive measures to safeguard their agricultural investments and livelihoods.

## Requirements
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks and video processing.
* Development Environment: Python 3.6 or later is necessary for coding the animal intrusion alerting system.
* Deep Learning Frameworks: Utilizes OpenCV's DNN module for implementing the YOLO algorithm and TensorFlow for any additional deep learning tasks.
* Audio Processing: Requires Pygame for playing alarm sounds.
* Email Communication: Utilizes SMTP protocol for sending email notifications, requiring smtplib and email.message modules.
* Multithreading: Utilizes threading module for asynchronous email sending to avoid blocking the main thread.
* Video Processing: Requires OpenCV for video capture, processing, and displaying output frames.
* External Libraries: Playsound for playing alarm sounds, imghdr for image attachment verification in email notifications.
* Dependencies: NumPy for numerical computations, scikit-learn for any machine learning tasks, and playsound for audio playback.
* Integrated Development Environment (IDE): Supports any Python-compatible IDE, such as VSCode or PyCharm, for coding, debugging, and version control integration.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![flow chart](https://github.com/Dineshkumar200/Animal-Intrusion-Alerting-System-For-Crop-Protection/assets/75235789/391ac41c-d83c-4fd9-a4f9-cfc80473131e)


## Output

#### Output1 - Detecting The Animal

![111111](https://github.com/Dineshkumar200/Animal-Intrusion-Alerting-System-For-Crop-Protection/assets/75235789/c9132773-b3cd-4457-9de7-8ccd5eef6342)
![Screenshot 2024-03-22 114015](https://github.com/Dineshkumar200/Animal-Intrusion-Alerting-System-For-Crop-Protection/assets/75235789/2bb69d4f-78a4-4a5a-8d87-0afd30303ee5)



#### Output2 - Sending Mail TO The Land Owner

![8888888](https://github.com/Dineshkumar200/Animal-Intrusion-Alerting-System-For-Crop-Protection/assets/75235789/4cc02053-3711-49c7-92c7-3e87e2599a94)
![7777777](https://github.com/Dineshkumar200/Animal-Intrusion-Alerting-System-For-Crop-Protection/assets/75235789/bc028ef0-2c6f-4c77-806a-2ec3dc810b7f)

![555555555](https://github.com/Dineshkumar200/Animal-Intrusion-Alerting-System-For-Crop-Protection/assets/75235789/0f723a26-10b2-4b1a-ad25-aa20f9325cf3)



## Results and Impact
The system successfully detects animal intrusions in real-time, allowing farmers to promptly respond to potential threats to their crops. By leveraging computer vision algorithms, the system accurately identifies animals within video streams, enabling timely intervention.

Upon detecting an animal intrusion, the system issues timely alerts to farmers through audible alarms and email notifications. These alerts ensure that farmers are promptly informed about the presence of animals in their fields, empowering them to take immediate action to protect their crops.

Overall, the Animal Intrusion Alerting System enhances security and surveillance in agricultural settings. By providing early warnings and enabling proactive management of wildlife intrusion, the system contributes to safeguarding crops and preserving agricultural livelihoods.






