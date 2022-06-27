## Tải model này về bỏ vào thư mục source_yolo_v5 
[https://drive.google.com/file/d/1ht4vmaXjEqHX1YKuPisYVCHSTJLoXMeE/view?usp=sharing]

## Run on terminal

1. pip install -r requirements.txt

2. python path/to/detect.py --weights yolov5s.pt --source 0              # webcam
    - Có thể thay 0 thành các tham số sau đây 
    - img.jpg        # đường dẫn đến file ảnh cần nhận diện
    - vid.mp4        # đường dẫn đến file video cần nhận diện
    - path/          # đường dẫn đến thư mục cần nhận diện 
    - 'https://youtu.be/Zgi9g1ksQHc'  # đường link youtube
    -  'rtsp://example.com/media.mp4' # liên kết đến ảnh hoặc video cần nhận diện ( RTSP, RTMP, HTTP stream ) 
