# install virtualenv
pip install virtualenv

# create virtual env
virtualenv env

# activate venv
source ./env/Scripts/Activate

# install requirements
pip install -r requirements.txt

# run yolo_video example usage 
python yolo_video.py -i ./examples/test_ship.mp4 -o ./output/video_out.avi

python yolo_video.py -i ./examples/test_human.mp4 -o ./output/video_out.avi