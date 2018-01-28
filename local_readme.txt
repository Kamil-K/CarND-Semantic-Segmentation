shells --> cmd(admin)

cd /mnt/d/Studies-MOOCs/2017-02_Self-Driving-Car_NanoDegree_Udacity/Self_Driving_Car_Projects/11_Semantic_Segmentation
cd D:\Studies-MOOCs\2017-02_Self-Driving-Car_NanoDegree_Udacity\Self_Driving_Car_Projects\11_Semantic_Segmentation

To run the code:
activate carnd-advdl-odlab
python main.py

shells --> cmd(admin)

cd /mnt/d/Studies-MOOCs/2017-02_Self-Driving-Car_NanoDegree_Udacity/Self_Driving_Car_Projects/11_Semantic_Segmentation
cd D:\Studies-MOOCs\2017-02_Self-Driving-Car_NanoDegree_Udacity\Self_Driving_Car_Projects\11_Semantic_Segmentation

cd /mnt/d/Dane/amazon-AWS/SemanticSegmentationProject.pem

To run the code:
activate carnd-advdl-odlab
python main.py

---
to install tqdm
pip install tqdm


---
Working attempt below:
---


sudo chmod 600 SemanticSegmentationProject.pem
sudo ssh -i "SemanticSegmentationProject.pem" root@ec2-18-216-202-224.us-east-2.compute.amazonaws.com
sudo ssh -i "SemanticSegmentationProject.pem" ubuntu@ec2-18-216-202-224.us-east-2.compute.amazonaws.com

sudo chmod 400 SemanticSegmentationProject.pem
sudo ssh -i "SemanticSegmentationProject.pem" root@ec2-13-59-139-187.us-east-2.compute.amazonaws.com

Spot request with id: sfr-b53dbeb4-185a-4603-841b-a7900852df8f
cd /mnt/d/Dane/amazon-AWS
sudo chmod 600 SemanticSegmentationProject.pem
sudo ssh -i "SemanticSegmentationProject.pem" root@ec2-18-218-244-36.us-east-2.compute.amazonaws.com
sudo ssh -i "SemanticSegmentationProject.pem" ubuntu@ec2-18-218-244-36.us-east-2.compute.amazonaws.com

---
Failed attempts below:
---

AWS Spot request ID: sfr-6c6c6717-d83e-45bf-b522-99087a605fc6
cd /mnt/d/Dane/amazon-AWS
chmod 400 SemanticSegmentationProject.pem
ssh -i "SemanticSegmentationProject.pem" root@ec2-18-216-166-224.us-east-2.compute.amazonaws.com

AWS Spot request ID: sfr-51567b7c-4a81-4ce2-b545-78379e917b59
cd /mnt/d/Dane/amazon-AWS
chmod 400 SemanticSegmentationProject.pem
ssh -i "SemanticSegmentationProject.pem" root@ec2-18-218-105-60.us-east-2.compute.amazonaws.com

---

Copy to AWS instance
$scp -i ~/Desktop/amazon.pem ~/Desktop/test.txt ubuntu@ec2-54-166-128-20.compute-1.amazonaws.com:~/data/

scp -i ~/Desktop/SemanticSegmentationProject.pem ~/Desktop/test.txt ubuntu@ec2-13-59-139-187.us-east-2.compute.amazonaws.com:~/test/

$scp -i /mnt/d/Dane/amazon-AWS/SemanticSegmentationProject.pem /mnt/d/Studies-MOOCs/2017-02_Self-Driving-Car_NanoDegree_Udacity/Self_Driving_Car_Projects/11_Semantic_Segmentation/data/data_road ubuntu@ec2-13-59-139-187.us-east-2.compute.amazonaws.com:~/semantic_segmentation_project/data/


Copy from AWS instance
$scp -i ~/Desktop/amazon.pem ubuntu@ec2-54-166-128-20.compute-1.amazonaws.com:/data/ecoli_ref-5m-trim.fastq.gz ~/Download/

---