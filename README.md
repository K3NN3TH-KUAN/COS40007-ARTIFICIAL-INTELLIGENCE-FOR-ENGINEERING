# COS40007-ARTIFICIAL-INTELLIGENCE-FOR-ENGINEERING
Welcome to GitHub Repository for COS40007 ARTIFICIAL INTELLIGENCE FOR ENGINEERING

In this repo contains 5 YOLO versions (YOLOv8, YOLOv8 OBB, YOLOv9, YOLOv11, YOLOv12). For each datasets contains 5 car type models (Perodua Axia, Perodua Ativa, Perodua Bezza, Perodua Myvi, Toyota Vios)

Inside each YOLO version contains the following datasets and yaml file:
1. data.yaml
2. train dataset
3. test dataset
4. valid dataset

Each data samples are go through data preprocesssing like resize input size to 640x640 pixels and auto-oriented. Data augementation (+/-50%) also applied to all th samples to simulate different light conditions for the model to detect.
