# Clustered Nanopore Reads (CNR) Dataset

We release the dataset of clustered nanopore DNA reads together with our paper:

**Trellis BMA: coded trace reconstruction on IDS channels for DNA storage**  
*Sundara Rajan Srinivasavaradhan, Sivakanth Gopi, Henry D. Pfisterz, and Sergey Yekhanin*  
Proceedings of the International Symposium on Information Theory (ISIT), 2021. [[Paper]](link)

Our hope is that this dataset will enable further research progress by allowing objective comparisons between the algorithms. The dataset is represented by two files:

- **Centers.txt** This files contains 10,000 random strings of length $110$ in the alphabet {A,C,G,T}.
- **Clusters.txt** This file contains 269,709 noisy nanopore reads of DNA sequences corresponding to strings in the file **Centers.txt**. Reads are arranged into clusters separated by lines of multiple "=" signs. Clusters follow the same order as the strings in the file **Centers.txt**, i.e., the first cluster contains reads corresponding to the DNA sequence represented by first string in *Centers.txt*, the second cluster contains reads corresponding to the DNA sequence resented by the second string in **Centers.txt**, etc.


DNA sequences were synthesized by Twist Bioscience and amplified using polymerase chain reaction. The amplified products were ligated to Oxford Nanopore Technologies (ONT) sequencing adapters by following the manufacturer’s protocol (LQK-LSK 109 kit). Finally, ligated samples were sequenced using ONT MinION. Clusters of noisy reads have been recovered using the algorithm from [1].

> [1] Cyrus Rashtchian, Konstantin Makarychev, Miklos Rácz, Sienna Dumas Ang, Djordje Jevdjic, Sergey Yekhanin, Luis Ceze, and Karin Strauss, “Clustering billions of reads for DNA data storage,” in Proceedings of the 30th Annual Conference on Neural Information Processing Systems (NIPS), 2017, pp. 3360–3371.


## Acknowledgement
We thank Karin Strauss, Yuan-Jyue Chen, and the Molecular Information Systems Laboratory at the University of Washington for providing the dataset to us.


## Citation
If you find this dataset useful for your research, please cite the paper

...(Insert bibtex entry)...


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
