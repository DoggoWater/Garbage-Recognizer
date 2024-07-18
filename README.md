# Garbage-Recognizer
Using Jetson Nano &amp; classifications to identify trash
1. Use folders train & val
2. run through module "Re-Training Image Classification Models"
3. if images are corrupted, throw them out.
4. if you find one good one, use this command & substitute the jpg with yours.
5. imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/cat/01.jpg cat.jpg
