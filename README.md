Download Link: https://assignmentchef.com/product/solved-stat-547-homework4
<br>
<ol>

 <li>Consider the univariate nonparametric regression setting where we have a sample (<em>X<sub>i</sub>,Y<sub>i</sub></em>), <em>i </em>= 1<em>,…,n</em>, which satisfies , and the error variance is a constant. Assume the density of <em>X<sub>i </sub></em>is positive, continuous, and supported on [0<em>,</em>1].</li>

</ol>

The kernel <em>K</em>(·) is a symmetric continous density function supported on [−1<em>,</em>1] with

.              The regression function <em>µ </em>is assumed to be twice differentiable

with a bounded second derivative. Derive the asymptotic bias and variance for the Nadaraya–Watson estimator at a left boundary point <em>x</em><sub>0 </sub>= <em>ch</em>, where <em>c </em>∈ [0<em>,</em>1), as <em>h </em>→ 0 and <em>nh </em>→ ∞.

[For example, <em>c </em>= 0 implies <em>x</em><sub>0 </sub>= 0, so only design points falling within [0<em>,h</em>] willl be utilized.]

<ol start="2">

 <li>Investigate the scallop abundance data.</li>

</ol>

library (SemiPar)

data ( scallop )

Perform bivariate smoothing with the total catch as the response using local polynomial. Vary the bandwidths and degrees and visualize the results.

<ol start="3">

 <li>Consider again the yeast gene expression data used in Homework 2. The gene expression profiles may be slightly noisy, so before performing an FPCA we may want to presmooth the individual curves.

  <ul>

   <li>Perform smoothing for each gene expression profile using appropriate smoothing parameters (bandwidth, roughness penalty, etc), and then apply FPCA on the presmoothed curved. Visualize and compare the functional data input, mean functions, and eigenfunctions obtained with and without presmoothing.</li>

   <li>Estimate the derivative curve of each raw gene expression profile. To use local polynomials, one can use the deriv=1 argument of locfit. Then apply FPCA to analyze the estimated derivative curves.</li>

  </ul></li>

</ol>