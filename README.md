Download Link: https://assignmentchef.com/product/solved-machinelearning-homework-3
<br>
Homework 3

Problem. 1.

(A) Consider any Mercer kernel defined by = We are given a sample  S .Tn} of n inputs. We can form the Kernel (Gram) matrix K as an n x n matrix  of kernel evaluations between all pairs of examples i.e., Ka J

Mercer’s Theorem  states that a symmetric function k(., .) is a kernel iff for any finite sample S the kernel matrix K is  positive semi-definite. Recall that a matrix K IRnxn is positive semi-definite iff c Kc 2 0 for all  real-valued vectors c e kn. Prove Mercer’s theorem in one direction: for any Mercer kernel k(., . )  and finite sample S, the kernel matrix K is positive semi-definite.

Given any two Mercer kernels kl . ) and k2(., .), prove that the following are also Mercer kernels:

<ol>

 <li>a) Okl (:r, i:) + i) for a, {3 0</li>

 <li>c) f (kl (x, i)) where f is any polynomial with positive coefficients</li>

</ol>

(B) For the kernel K(:r, y) = exp(4 Il — y 112) = • v(y), write an explicit formula for p.

Problem. 2.

You will build an SVM to classify data and use cross-validation to find the best SVNI kernel and  regularization value. Try different polynomials and RBF kernels (varying polynomial order from 1  to 5) and varying sigma in the RBF kernel. Also, try different values of C in the SYM. First, extract  the support vector machine Matlab code from Steve Gunn’s software package here:

http : / /www.isis.ecs.soton. ac. uk/resources/svminfo/

In svc.m replace [alpha lambda how] = qp(… ) ;

[alpha lambda how] = quadprog(H,c, , ,A,b,v1b,vub,xO) ; with  Clearly denote the various components and the function calls or scripts that execute your Matlab functions. Note, to save the current figure in Matlab as a postscript file you can type:

print —depsc filename. eps

To test your SVNI, you will build a simple object recognition system. Download the data file dataset.mat.

This loads a matrix X of size 100 x 4 and a vector Y of size 100 x 1. The X matrix consists of 100 data points of dimensionality 4 that belong to one of two classes. Their actual labels are given in the Y vector. Train your SVM on half of the examples and test on the other half (or other random subsets of the examples if you see fit). Show performance of the SVM for linear, polynomial and RBF kernels with different settings of the polynomial order, sigma and C value. Try to hunt for a good setting of these parameters to obtain high recognition accuracy.

Problem. 3.

Suppose Xl, X2, … , Xn are i.i.d. samples from a population with pdf  f (xla)

Find the maximum likelihood estimator for .

0.25, .T2 = 0.75, = 1.50, .T4 2.5, = 2.0.

Calculate an estimate using this estimator when