## Tải model này về bỏ vào thư mục source_yolo_v5 
[https://drive.google.com/file/d/1ht4vmaXjEqHX1YKuPisYVCHSTJLoXMeE/view?usp=sharing]

## Run on terminal

1. pip install -r requirements.txt

2. python path/to/detect.py --weights yolov5s.pt --source 0              # webcam
                                                          img.jpg        # image
                                                          vid.mp4        # video
                                                          path/          # directory
                                                          path/*.jpg     # glob
                                                          'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                                                          'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
