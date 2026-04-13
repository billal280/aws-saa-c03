# ☁️ AWS Solutions Architect Associate — Kit de préparation complet

> Ressources de révision pour la certification **AWS SAA-C03** : fiche de révision PDF, examens blancs, et tests ciblés par bloc certifiant.

---

## 📋 Description

Ce repo contient un kit de préparation complet et structuré pour obtenir la certification **AWS Certified Solutions Architect – Associate (SAA-C03)**. L'objectif est de couvrir l'intégralité du programme officiel AWS avec des ressources pratiques, directement exploitables sans autre matériel.

La certification SAA-C03 valide la capacité à **concevoir des architectures AWS résilientes, performantes, sécurisées et économiquement optimisées**. Elle est reconnue mondialement comme l'une des certifications cloud les plus valorisées sur le marché.

**Seuil de passage : 720 / 1000 — durée : 130 minutes — ~65 questions**

---

## 📁 Structure du repo

```
aws-saa-c03-prep/
│
├── 📄 README.md
│
├── 📚 fiche-revision/
│   └── AWS_SAA-C03_Fiche_Revision.pdf      # Fiche complète — tous les services et domaines
│
├── 📝 examens-blancs/
│   ├── examen-blanc-01.md                  # 65 questions — format officiel
│   ├── examen-blanc-02.md
│   └── ...
│
└── 🎯 tests-par-domaine/
    ├── 01-resilient-architectures.md       # Domaine 1 — 26% de l'examen
    ├── 02-high-performing-architectures.md # Domaine 2 — 24% de l'examen
    ├── 03-secure-architectures.md          # Domaine 3 — 30% de l'examen
    └── 04-cost-optimized-architectures.md  # Domaine 4 — 20% de l'examen
```

---

## 📚 Contenu de la fiche de révision PDF

La fiche couvre **11 sections** et l'intégralité des services testés à l'examen :

| # | Section | Services couverts |
|---|---------|-------------------|
| 1 | Fondamentaux AWS | Régions, AZ, Edge Locations, modèle de responsabilité partagée |
| 2 | Calcul | EC2 (types, achat, ASG), ELB (ALB/NLB/GWLB), Lambda, ECS, EKS, Fargate |
| 3 | Stockage | S3 (classes, lifecycle, replication, sécurité), EBS, EFS, FSx, Storage Gateway |
| 4 | Base de données | RDS, Aurora, DynamoDB, ElastiCache, Redshift, Neptune, DocumentDB... |
| 5 | Réseau & CDN | VPC complet, Route 53, CloudFront, Transit Gateway, Direct Connect |
| 6 | Sécurité | IAM, KMS, CloudHSM, Secrets Manager, WAF, Shield, GuardDuty, Cognito |
| 7 | Messagerie | SQS, SNS, EventBridge, Kinesis, Step Functions, Amazon MQ |
| 8 | Monitoring | CloudWatch, CloudTrail, AWS Config, Trusted Advisor, Organizations |
| 9 | Migration | Famille Snow, DataSync, DMS, MGN, Transfer Family |
| 10 | Architecture | Well-Architected (6 piliers), stratégies DR, 10 patterns clés |
| 11 | Anti-pièges | Top 20 pièges d'examen + comparatifs de services + stratégies J-day |

---

## 🎯 Domaines de l'examen SAA-C03

| Domaine | Poids | Focus |
|---------|-------|-------|
| Design Resilient Architectures | **26%** | Multi-AZ, Auto Scaling, ELB, RDS HA, Route 53 failover |
| Design High-Performing Architectures | **24%** | Cache, CDN, scaling, Kinesis, choix du bon service |
| Design Secure Architectures | **30%** | IAM, KMS, VPC, WAF, Shield, Cognito — **domaine le plus important** |
| Design Cost-Optimized Architectures | **20%** | Spot, Reserved, Savings Plans, S3 Lifecycle, rightsizing |

---

## 🚀 Comment utiliser ce repo

**Phase 1 — Apprentissage (1-2 semaines)**
1. Lire la fiche PDF de bout en bout une première fois sans prendre de notes
2. Relire section par section en notant les services inconnus
3. Consulter la documentation officielle AWS pour les points flous

**Phase 2 — Tests ciblés (1 semaine)**
1. Faire les tests par domaine dans l'ordre du poids décroissant (Sécurité en premier)
2. Pour chaque mauvaise réponse : relire la section correspondante dans la fiche
3. Refaire les tests jusqu'à obtenir 80%+ sur chaque domaine

**Phase 3 — Examens blancs (3-5 jours avant)**
1. Faire chaque examen blanc en conditions réelles (130 minutes, sans aide)
2. Analyser les erreurs par domaine pour identifier les lacunes
3. Réviser les sections faibles dans la fiche

**Le jour J**
- Lire chaque question **deux fois** avant de répondre
- Éliminer les réponses clairement fausses en premier
- `"Least operational overhead"` → services managés AWS
- `"Most cost-effective"` → Reserved/Spot/S3 Lifecycle selon le cas
- `"Highly available"` → Multi-AZ + Auto Scaling

---

## 📊 Score indicatif

| Score aux examens blancs | Interprétation |
|--------------------------|----------------|
| < 55% | Continuer à réviser — relire la fiche |
| 55% – 71% | Proche — cibler les domaines faibles |
| ≥ 72% | Niveau certifiable — passer l'examen |

> Le seuil officiel AWS est de **720/1000**, soit environ **72%**.

---

## 🔗 Ressources officielles complémentaires

- [Guide d'examen officiel SAA-C03](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [AWS Free Tier](https://aws.amazon.com/free/) — pour pratiquer sur de vrais services
- [AWS Skill Builder](https://skillbuilder.aws/) — labs et cours officiels

---

## 🤝 Contributions

Les contributions sont les bienvenues ! Si tu trouves une erreur, un service manquant ou tu veux ajouter des questions d'examen blanc :

1. Fork le repo
2. Crée une branche (`git checkout -b fix/nom-du-fix`)
3. Commit tes changements (`git commit -m 'fix: correction question domaine 3'`)
4. Ouvre une Pull Request

---

## ⚠️ Disclaimer

Ce repo est une ressource de révision personnelle et communautaire. Il n'est pas affilié à Amazon Web Services. Le contenu est basé sur le guide d'examen officiel SAA-C03 et les meilleures pratiques AWS documentées publiquement.

---

<div align="center">

**Bonne chance pour ta certification ! ☁️**

*Si ce repo t'a aidé à l'obtenir, laisse une ⭐ et partage-le !*

</div>
