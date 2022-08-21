# demo

Blog Post https://dev.to/bronifty/pulumi-ffmpeg-automation-2o7o
Youtube Video https://youtu.be/CYlaO4kDQQ8

<img src="./ffmpeg.png">

```
yarn

pulumi config set aws:region us-east-1

aws s3 cp ./sample/cat.mp4 s3://$(pulumi stack output bucketName)/cat_00-01.mp4
```
