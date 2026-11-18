# Tajamul Bashir

M.Tech in Computer Science and Engineering at **IIT Jammu** (2025–2027). I work on computer vision,
mainly continual and few-shot learning: models that learn new classes from a handful of examples
without forgetting old ones. My thesis is on class-incremental few-shot object detection.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tajammulbasheer-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tajammulbasheer/)
[![Email](https://img.shields.io/badge/Email-tajammulbasheer.one%40gmail.com-c14438?style=flat-square&logo=gmail&logoColor=white)](mailto:tajammulbasheer.one@gmail.com)

## Featured work

**[Leaf disease detection: beyond in-distribution accuracy](https://github.com/tajammulbasheer/plant_leaf_diseases_detection)**  
*PyTorch · EfficientNet · U-Net · Grad-CAM*  
A classifier that scores 99.9% on PlantVillage lab photos gets 18.6% on real field photos from PlantDoc. The repository measures that gap and tests few-shot, semi-supervised and class-incremental training, plus weakly supervised lesion localization. Results tables are generated from the runs, with tests and CI.

**[Reproducing Table-Specialist (EMNLP 2025)](https://github.com/tajammulbasheer/table_specialist_repair)**  
*LLMs · Llama-3.1-8B · QLoRA · DPO · vLLM*  
A fourteen-day reproduction of the paper's self-trained NL-to-SQL results on one workstation. The README's base checkpoint does not match the paper, but the Instruct checkpoint does (0.611 against 0.598). I also tested two ways to reuse rejected training data: DPO hurt, and repairing rejected pairs gained +0.042 on the base model. [Report](https://github.com/tajammulbasheer/table_specialist_repair/blob/main/report/main.pdf)

**[Secure end-to-end encrypted chat](https://github.com/tajammulbasheer/secure_chat_app)**  
*Python · cryptography · TLS · PyQt6*  
Peer-to-peer chat with ECDHE key exchange, a Double Ratchet, certificate-based authentication and encrypted group chats. Includes a [security audit](https://github.com/tajammulbasheer/secure_chat_app/blob/main/docs/SECURITY_AUDIT.md) of the first version and a record of how each finding was fixed.

## Tools

Python, C++, C · PyTorch, TensorFlow/Keras, scikit-learn, OpenCV, NumPy, pandas · Git, Linux, Docker
