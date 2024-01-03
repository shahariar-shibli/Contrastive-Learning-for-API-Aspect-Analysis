# Contrastive Learning for API Aspect Analysis - ASE 2023
We present a novel approach - CLAA - for API aspect detection in API reviews that utilizes transformer models trained with a supervised contrastive loss objective function. We evaluate CLAA using performance and impact analysis. For performance analysis, we utilized a benchmark dataset on developer discussions collected from Stack Overflow and compare the results to those obtained using state-of-the-art transformer models. Our experiments show that contrastive learning can significantly improve the performance of transformer models in detecting aspects such as Performance, Security, Usability, and Documentation. For impact analysis, we performed empirical and developer study. On a randomly selected and manually labeled 200 online reviews, CLAA achieved 92% accuracy while the SOTA baseline achieved 81.5%. According to our developer study involving 10 participants, the use of Stack Overflow + CLAA resulted in increased accuracy and confidence during API selection.

## Repository Structure
The repository has three folders:
1. Code: All the codes for seven pre-trained transformers are available.
2. Dataset: Contains two datasets (a) Opiner dataset (b) Empirical dataset.
3. Result: Contains two folders and one file.
   - WCL: Contains the result of CLAA on Empirical dataset.
   - WOCL: Contains the result of baseline RoBERTa on Empirical dataset.
   - The Detail Performance Comparison.pdf contains a table with detailed performance comparison between CLAA and the baseline model on all eleven aspects.
