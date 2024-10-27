# Report on the Project: "How Humans Populated the Earth"

## Introduction

This project explores the phylogenetics and human evolution, focusing on the origins and migration patterns of *Homo sapiens*. The study is rooted in the "Out of Africa" hypothesis, which posits that modern humans originated in Africa and later dispersed across the globe. The project aims to construct evolutionary trees using mitochondrial DNA (mtDNA) data to understand the relationships between modern humans, Neanderthals, and Denisovans.

## Results

### 1. Constructing an Evolutionary Tree Based on Human mtDNA Data

#### 1.1. First Tree

Using the MAFFT algorithm for alignment and the Neighbour Joining method for phylogeny, we constructed an evolutionary tree based on human mtDNA data. The tree was generated using IQTree. The ITOL (Interactive Tree Of Life) online resource was used to visualize the data obtained using IQTree. This database of mitochondrial DNA from various human populations was used to build the first tree: [https://figshare.com/ndownloader/files/30768763](https://figshare.com/ndownloader/files/30768763)

*First tree based on MtDNA*

#### 1.2. Rooting the Tree

After adding this datasets with mtDNA of Neandertal ([https://figshare.com/ndownloader/files/30768766](https://figshare.com/ndownloader/files/30768766)) and Denisovans ([https://figshare.com/ndownloader/files/30768775](https://figshare.com/ndownloader/files/30768775)) we got a tree with an outgroup of Neanderthals and Denisovans:

*Rooted tree with Neanderthal/Denisova*

#### 1.3. Discussion

According to haplogroups, the tree has formed well. Denisovans and Neanderthals were clustered side by side, while there is a clear separation from modern humans, the hypothesis that Denisovans and Neanderthals are separate species from *Homo Sapiens* is clearly confirmed.

### 2. Estimating the Age of Mitochondrial Eve and the Most Recent Ancestor of All Non-Africans

The age of Mitochondrial Eve was estimated using the multiple alignment constructed in Task 1. By calculating the average number of point mutations and applying a known mutation rate, we estimated the age of Mitochondrial Eve.

**Results:**

For the average number of mutations per year in the mitochondrial genome, we took the value \(1.3 \times 10^{-8}\) per 1 nucleotide per year. (According to this article [https://www.pnas.org/doi/full/10.1073/pnas.1409328111](https://www.pnas.org/doi/full/10.1073/pnas.1409328111)) The reference genome is Central African, in comparison with which we count the number of mutations. A calculation script was written in R (it is given in this repository under the name `MtEve_Age_RScript`). The average age of MtEve turned out to be 209,482 years old.

### 3. Adding Neanderthal and Denisovan Samples to the Evolutionary Tree

We incorporated five Neanderthal and three Denisovan mtDNA samples into the existing human dataset to construct an augmented evolutionary tree. This allowed us to estimate the age of the most recent common ancestor of modern humans and Neanderthals.

**Results:**

For the average number of mutations per year in the mitochondrial genome, we took the value \(1.3 \times 10^{-8}\) per 1 nucleotide per year. The reference genome is KX198087.1 *Homo sapiens neanderthalensis* isolate GoyetQ305-4, in comparison with which we count the number of mutations. A calculation script was written in R (it is given in this repository under the name `Neaderthal_Age_RScript`). The most recent common ancestor of modern humans and Neanderthals is estimated to have lived approximately 469,862 years ago.
