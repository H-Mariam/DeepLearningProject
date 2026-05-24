Donut Document Classification

Projet de classification automatique de documents avec le modèle DONUT de NAVER Clova AI et Hugging Face Transformers.

📌 Description

Ce projet utilise le modèle :

naver-clova-ix/donut-base-finetuned-rvlcdip

afin de classifier automatiquement des documents à partir d’images telles que :

* Factures

* Formulaires

* Lettres

* Reçus

* Rapports

* Documents administratifs

Le modèle est basé sur l’architecture DONUT (Document Understanding Transformer), une approche OCR-free permettant de comprendre et classifier les documents directement à partir des images, sans extraction OCR traditionnelle.

🚀 Fonctionnalités

* Chargement automatique du modèle DONUT

* Classification automatique de documents

* Support GPU avec CUDA si disponible

Compatible avec :

* Google Colab

* Jupyter Notebook

* Environnement local Python

🛠️ Technologies utilisées

* Python

* PyTorch

* Hugging Face Transformers

* Pillow (PIL)
