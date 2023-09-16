# Glycolysis and Glyconeogenesis Motif Detection

This project explores transcription factor binding site (TFBS) motifs in the Glycolysis and Glyconeogenesis pathways, examining their correlation and the genes they share.

## Motivation

Transcription factors (TFs) regulate gene expression by binding to TFBS on DNA. We investigate TFBS sequence motifs in Glycolysis and Glyconeogenesis for insights into their regulatory mechanisms.

## Data Preparation

We start by obtaining gene IDs for both pathways and find common genes between them. We also collect upstream sequences for genes involved in both processes and sample random sequences as background.

## Motif Analysis

We identify unique substrings (motifs) in foreground and background sequences for further analysis.

## Motif Scoring

We calculate scores for each sequence using Position Weight Matrices (PWMs) built from the best motifs. Sequences scoring above a threshold are potential TFBS.

## Cross-Comparison

Surprisingly, the motifs for Glycolysis and Glyconeogenesis show significant overlap. Scoring with each other's PWMs reveals a high similarity, indicating shared TFBS.

This suggests that both pathways employ very similar sequences to regulate gene expression.

## Conclusion

The analysis reveals a close relationship between Glycolysis and Glyconeogenesis, with shared TFBS motifs. This information can be valuable for understanding the regulatory networks of these vital metabolic pathways.

For detailed code and results, refer to the R Markdown document.

## Author

- [Nikolaos Barmparousis](https://github.com/nikbarb810)

## License

This project is licensed under the [MIT License](LICENSE).

