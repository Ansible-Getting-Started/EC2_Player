# EC2 Player

This is a very simple, basic, and fast demonstration of provisioning an EC2 instance then configuring it to play an mp4 video using a popular html5 player. 

<h3>Vars</h3>
The variables you have to change are below.

For calot.yml
```
  vars:
    - region: YourAWSRegion (us-east; us-west)
    - project_name: IntanceName
    - which_subnet: subnet-YourSubnetIDGoesHere
    - base_image: ami-YouramiIDGoesHere
    - mysecuritygroup: VPCSecurityGroup
```

For harness.yml
```
  vars:
    - player_files: path/to/player
    - video_source: path/to/videos
    - video_cover: path/to/coverart
```
