CUDA_VISIBLE_DEVICES=7  python tools/train.py project/our/configs/multiclass_usis_train.py

CUDA_VISIBLE_DEVICES=7  python tools/test.py project/our/configs/multiclass_usis_train.py /data/hotaru/projects/USIS10K/work_dirs/USIS10KDataset/huge/best_coco_segm_mAP_epoch_24.pth  --show --show-dir /data/hotaru/projects/USIS10K/work_dirs/USIS10KDataset/test

CUDA_VISIBLE_DEVICES=5  python tools/train.py project/our/configs/foreground_monuseg_train.py