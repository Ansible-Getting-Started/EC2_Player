# EC2 Player

This is a very simple, basic, and fast provisioner of an EC2 instance that is then configured to play an mp4 video using a popular html5 player.

<h3>Vars</h3>

For calot.yml
```
  vars:
    - region: us-east
    - project_name: Woola
    - which_subnet: subnet-yoursubnetidgoeshere
    - base_image: ami-youramiidgoeshere
    - mysecuritygroup: vpcsecuritygroup
```

For harness.yml
```
  vars:
    - player_files:
    - video_source:
    - video_cover:
```
