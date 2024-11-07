# SeGraM
SeGraM: Spherical Coordinate System based Semantic Graph Matching Method for Loop Closure Detection
## Dataset
The dataset is available at: [dataset_scenenet_209](https://drive.google.com/file/d/1TMKp0iFraOTDhiLa-xvTD_-svpn5nyM8/view?usp=drive_link)

## Note
1. The dataset path should be modified in this line: [dataset_path](https://github.com/BIT-TYJ/SeGraM/blob/4191628d98c36061eb8ae99883b14b712241857d/SeGraM.py#L806)

2. A folder named 'on_scenenet_209' needs to be newed in the current location.  (or use another name of the folder and change this line: [result_path](https://github.com/BIT-TYJ/SeGraM/blob/4191628d98c36061eb8ae99883b14b712241857d/SeGraM.py#L31C30-L31C45))

## Quickstart
Assume the current directory is the root of this repository.

> Run
```sh
$ python SeGraM.py
```

> Evaluate
```sh
$ python analyze-scenenet-209.py
```
## OutDoor Evaluation
Please see the other branch: [SeGraM-outdoor](https://github.com/BIT-TYJ/SeGraM/tree/SeGraM-outdoor).
