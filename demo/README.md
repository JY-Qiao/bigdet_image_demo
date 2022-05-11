This is a bigdetection demo. 

#### Steps:

Replace 'bigdetection/mmdet/apis/inference.py' in original bigdetection program with new inference.py.



Checkpoint file download link: 

[model](https://download.openmmlab.com/mmdetection/v2.0/yolo/yolov3_d53_fp16_mstrain-608_273e_coco/yolov3_d53_fp16_mstrain-608_273e_coco_20210517_213542-4bc34944.pth)   --Offered by mmdetection official contributor

​               -- Offered by our bigdetection contributor



Put the .checkpoint file in the checkpoints dictionary

——bigdetection——**checkpoints**——.checkpoint

​             ——configs

​							——demo

​             ——......



Run the following code in cmd terminal(using mmdetection official checkpoint file)

```
python demo/image_demo.py demo/demo.jpg configs/BigDetection/yolov3/yolov3_d53_mstrain-608_1x_coco.py checkpoints/yolov3_d53_fp16_mstrain-608_273e_coco_20210517_213542-4bc34944.pth
```

