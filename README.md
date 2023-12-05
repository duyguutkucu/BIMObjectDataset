# BIMObjectDataset
AI classification tools rely on extensive datasets, and if BIM (Building Information Modeling) objects are classified for building performance analyses, the dataset must exhibit a finer granularity than the IFC schema classes. As no such dataset was readily available, we compiled an extensive BIM object dataset, containing 40 classes with diverse feature data for each instance stored in IFC, PLY, and PNG formats. 

Here is the link to the BIMObjectDataset: https://drive.google.com/drive/folders/1bJPoJd5DdIpD0B7WVmOaM3ej_krw8yiU

## Reference Publication
Reference to the __*"Classification of Architectural and MEP BIM Objects for Building Performance Evaluation"*__ paper TBD.

The authors of this study are Duygu Utkucu, Huaquan Ying, Zijian Wang, and Rafael Sacks, from Technion – Israel Institute of Technology, Haifa, Israel.

## Dataset Development
The dataset encompasses objects from four building systems (furnishing, mechanical, electrical, and plumbing), providing insights into heating, ventilation, and air conditioning, visual quality, acoustic performance, water supply, and fire protection. This culminated in the identification of 40 fine-grained object classes, comprising seven furnishing classes and 33 MEP (Mechanical, Electrical, and Plumbing) classes following the IFC4 Addendum 2 data schema.

During the compilation of the BIM object dataset, we employed two approaches: (i) extracting relevant objects from an open-source dataset (IFCNetCore) in IFC, PLY, and image formats, and (ii) gathering pertinent objects from open-source BIM object libraries and constructing IFC, PLY, and image formats within the VCLAB (Virtual Construction Laboratory at Technion) repository.

In total, 4,045 BIM object instances were gathered – 1,946 (48%) from IFCNetCore and 2,099 (52%) from the VCLAB repository. Rigorous checks for duplicates and quality assurance resulted in the removal of 635 instances (73 from IFCNetCore and 562 from VCLAB). The resultant BIM objects dataset comprises 3,410 valid instances, each accompanied by its IFC and PLY geometry files, along with 12 rendered images for each valid object sample, totaling 40,920 images.
