# Quantum Machine Learning: Breaking Classical Barriers with Qudits

**Authors**: Vinicius Cesar D. Dias & Alice P. G. Valle (PUCMG, Brazil)  
**Language Note**: This article is currently written in Portuguese. An English translation and reformatting are planned for future release.

## 🔬 Key Contributions
Investigates **qudit-based QNNs** (multi-level quantum systems) for efficient multiclass classification. Demonstrates:
- **Drastic parameter reduction**: `Qudit-NN` architecture with **852 parameters** (vs 11.2M in ResNet) achieving 93.1% accuracy (MNIST)
- **Hybrid framework**: SVM + QNN combination reduces quantum operations by 40%
- **Real-world applications**: Medical diagnosis and genomics (88.4% accuracy on 62-class EMNIST)
- **NISQ challenges**: Analysis of quantum noise (decoherence, gate fidelity) and mitigation techniques

## 📊 Performance Comparison
| Architecture      | Parameters (MNIST) | Accuracy |
|-------------------|--------------------|----------|
| ResNet-18         | 11.2M              | 94.5%    |
| QCNN (Li et al.)  | 1,540              | 92.3%    |
| **Qudit-NN**      | **852**            | **93.1%** |

## 📁 Repository Structure
├── artigo_revolucao_quantica.tex # Main LaTeX document

├── referencias.bib # Bibliography database

└── template/ # SBC template files

├── sbc-template.cls

└── sbc.bst

## ⚙️ Compilation Instructions
1. Install LaTeX distribution (TeX Live or MiKTeX)
2. Run:
```bash
pdflatex artigo_revolucao_quantica.tex
bibtex artigo_revolucao_quantica
pdflatex artigo_revolucao_quantica.tex  # Run twice
pdflatex artigo_revolucao_quantica.tex  # For references

🔜 Future Plans
English translation of full paper
Journal formatting for international publication
Experimental validation on trapped-ion hardware
Extension to CIFAR-100 and genomics datasets

📚 Key References
Nikolaeva et al. (2024) - Qudit implementations
Zheng et al. (2022) - Hybrid SVM-QNN framework
Preskill (2018) - NISQ era challenges
Li et al. (2020) - Quantum CNN efficiency

# Quebrando-Barreiras-Classicas
QNNs with qudits: Drastic parametric reduction (852 vs 11.2M in ResNet) for multiclass classification. Audit-NN achieves 93.1% on MNIST. Hybrid SVM-QNN framework reduces quantum operations by 40%. Discusses NISQ challenges (decoherence, fidelity) and applications in medical imaging/genomics. Authors: Dias &amp; Valle.
