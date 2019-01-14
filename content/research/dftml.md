---
author: "Karan Shah"
date: 2017-09-23
linktitle: dftml
menu:
  main:
    parent: research

title: Machine Learning approaches to Density Functional Theory
weight: 10
---

**Still under construction**

Density Functional Theory(DFT) is one of the most popular and successful methods for quantum mechanical simulations of matter because of its relatively lower computational costs. While it is formally exact, approximations of eXchange Correlation(XC) functionals have to be made. These calculations are highly time consuming and scale poorly with system size. The prospect of combining computer vision and deep learning is a fundamentally new approach to designing these XC functionals. This approach combines the intuitive power of physical insight with the flexibility of machine learning and high-quality training data in order to develop new routes to approximating exchange-correlation energies. A parameterized function is first fit on the data and the resulting residuals are used for bootstrap aggregating via an ensemble of neural networks. This two-stage method provides robust uncertainty quantification on the predicted XC energies and can be automated for many systems without significant manual intervention.

Undergraduate Thesis: __“Analysis of Uncertainty in Machine Learned Density Functionals”__

#### Poster

<object data="/research/res/DFTPoster.pdf" type="application/pdf"  height="768px" width="1152px">
    <embed src="http://localhost:1313/research/res/DFTPoster.pdf">
        This browser does not support PDFs. Please download the PDF to view it: <a href="http://localhost:1313/research/res/DFTPoster.pdf">Download PDF</a>.</p>
    </embed>
</object>