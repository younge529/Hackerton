# Hackerton-KUAI(가상 얼굴 검출 프로그램)
## Requirements
python 3.5.2  

future==0.18.2  
joblib==0.14.1  
numpy==1.18.5  
Pillow==7.2.0  
scikit-learn==0.22.2.post1  
scipy==1.4.1  
six==1.15.0  
sklearn==0.0  
torch==1.2.0  
torchvision==0.4.0  
tqdm==4.51.0  

## Inference
There are two way to run test your image.  
You can pick one of these two ways:    
1.run bash file  
```bash
$ chmod +x run.sh
$ ./run.sh
```
2. put your images in dataset/test/fake folder and run  
```bash
$ python test.py --dataset dataset --test_set test --outf checkpoints/deepfakes --id 95
```
## Reference
H. H. Nguyen, J. Yamagishi, and I. Echizen, “Capsule-Forensics: Using Capsule Networks to Detect Forged Images and Videos,” Proc. of the 2019 International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2019), 5 pages, (May 2019)  
<https://github.com/nii-yamagishilab/Capsule-Forensics>  
