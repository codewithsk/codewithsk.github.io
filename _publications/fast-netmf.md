---
title: "Fast-NetMF: Graph Embedding Generation on Single GPU and Multi-core CPUs with NetMF"
collection: publications
permalink: /publication/fast-netmf
excerpt: 'There is growing interest for learning representations for nodes in a network. Several embedding generation algorithms have been proposed in the last few years that generate high quality representations for downstream tasks like node classification and link prediction.'
date: 2019-08-01
venue: 'The Ohio State University'
paperurl: "https://etd.ohiolink.edu/!etd.send_file?accession=osu1557162076041442&disposition=inline"
---

There is growing interest for learning representations for nodes in a network. Several embedding generation algorithms have been proposed in the last few years that generate high quality representations for downstream tasks like node classification and link prediction. NetMF is one such algorithm that provides the theoretical foundations for proving that several network representation learning techniques implicitly factorize a closed form matrix derived from the graph. However, the NetMF algorithm is slow and does not scale well, owing to the multiple dense matrix multiplication steps and Singular Value Decomposition (SVD). We present Fast-NetMF, a fast, highly scalable version of the NetMF algorithm with reduced running time. In this work, we investigate the acceleration of NetMF under single-GPU and multi-core CPU settings. We also investigate replacing the
slow SVD based matrix factorization step for faster and more parallel-friendly factorization techniques like Non-negative Matrix Factorization (NMF).

[Download paper here](https://etd.ohiolink.edu/!etd.send_file?accession=osu1557162076041442&disposition=inline)
