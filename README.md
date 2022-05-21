# Awesome Conformal Prediction [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) [![DOI](https://zenodo.org/badge/436989758.svg)](https://zenodo.org/badge/latestdoi/436989758)

The most comprehensive professionally curated list of Awesome Conformal Prediction tutorials, videos, books, papers and open-source libraries in Python and R.

Please star 🌟 the repo and spread the word. If you use the repository in a scientific publication, we would appreciate citations of Awesome Conformal Prediction to help promote this amazing framework in academia and industry:

Manokhin, Valery. (2022). Awesome Conformal Prediction (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.6467205

Bibtex entry - Zenodo
@article{
 author = {Manokhin, Valery },
 title={Awesome Conformal Prediction},
 DOI={10.5281/zenodo.6467205},
 note={"If you use Awesome Conformal Prediction, please cite it as below."},
 publisher={Zenodo},
 year={2022},
 month={Apr}}

Bibtex entry - Awesome Conformal Prediction (Github)
@misc{title={Awesome Conformal Prediction: A professionally curated list of awesome conformal prediction videos, tutorials, books, papers, Phd theses, articles and open-source libraries.}, url={https://github.com/valeman/awesome-conformal-prediction}, journal={GitHub}, author={Manokhin, Valery}} 

Slack for Awesome Conformal Prediction -> https://join.slack.com/t/awesomeconformalpred/shared_invite/zt-193zf5qwx-uW7z9RWlB~_cUQq6iVIPyg
----------------------------------------------------------------------------------------------------------------------------------------------------------
Why Conformal Prediction?

One of the most influential and celebrated machine learning researchers - Professor Michael I. Jordan:

'𝗖𝗼𝗻𝗳𝗼𝗿𝗺𝗮𝗹 𝗣𝗿𝗲𝗱𝗶𝗰𝘁𝗶𝗼𝗻 𝗶𝗱𝗲𝗮𝘀 𝗮𝗿𝗲 𝗧𝗛𝗘 𝗮𝗻𝘀𝘄𝗲𝗿 𝘁𝗼 𝗨𝗤 (𝘂𝗻𝗰𝗲𝗿𝘁𝗮𝗶𝗻𝘁𝘆 𝗾𝘂𝗮𝗻𝘁𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻), 𝗜 𝘁𝗵𝗶𝗻𝗸 𝗶𝘁'𝘀 𝘁𝗵𝗲 𝗯𝗲𝘀𝘁 𝗜 𝗵𝗮𝘃𝗲 𝘀𝗲𝗲𝗻 - 𝗶𝘁𝘀 𝘀𝗶𝗺𝗽𝗹𝗲, 𝗴𝗲𝗻𝗲𝗿𝗮𝗹𝗶𝘀𝗮𝗯𝗹𝗲 𝗲𝘁𝗰.' (ICML 2021 UQ workshop). 🔥🔥🔥🔥🔥

One the most influential statistics Professors - Larry Wasserman (Carnegie Mellon): 

'𝗦𝗼 𝘁𝗵𝗲 𝗯𝗲𝗮𝘂𝘁𝘆 𝗼𝗳 𝘁𝗵𝗲 𝗰𝗼𝗻𝗳𝗼𝗿𝗺𝗮𝗹 𝘁𝗵𝗶𝗻𝗴 𝗶𝘀 𝗵𝗼𝘄 𝘀𝗶𝗺𝗽𝗹𝗲 𝗶𝘁 𝗶𝘀 𝘁𝗼 𝗱𝗼 𝗶𝘁 𝗮𝗻𝗱 𝗵𝗼𝘄 𝗴𝗲𝗻𝗲𝗿𝗮𝗹 𝗶𝘁 𝗶𝘀. 𝗦𝗼 𝗜 𝘁𝗵𝗶𝗻𝗸 𝘆𝗼𝘂 𝗸𝗻𝗼𝘄 𝗶𝗱𝗲𝗮𝘀 𝘁𝗵𝗮𝘁 𝗰𝗮𝘁𝗰𝗵 𝗼𝗻, 𝗴𝗲𝗻𝗲𝗿𝗮𝗹 𝗶𝗱𝗲𝗮𝘀 𝘁𝗵𝗮𝘁 𝗮𝗿𝗲 𝗽𝗿𝗲𝘁𝘁𝘆 𝗴𝗲𝗻𝗲𝗿𝗮𝗹 𝗮𝗻𝗱 𝐞𝐚𝐬𝐲 𝐭𝐨 𝐢𝐦𝐩𝐥𝐞𝐦𝐞𝐧𝐭 𝐭𝐡𝐚𝐭 𝐲𝐨𝐮 𝐜𝐚𝐧 𝐩𝐢𝐜𝐭𝐮𝐫𝐞 𝐲𝐨𝐮𝐫𝐬𝐞𝐥𝐟 𝐮𝐬𝐢𝐧𝐠 𝐢𝐧 𝐫𝐞𝐚𝐥 𝐚𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧𝐬 𝐚𝐫𝐞 𝐭𝐡𝐞 𝐫𝐞𝐚𝐬𝐨𝐧 𝐭𝐡𝐚𝐭 𝐩𝐞𝐨𝐩𝐥𝐞 𝐮𝐬𝐢𝐧𝐠 𝐜𝐨𝐧𝐟𝐨𝐫𝐦𝐚𝐥 𝐩𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧.' 🚀🚀🚀🚀🚀 

https://slideslive.com/icml-2021/workshop-on-distributionfree-uncertainty-quantification


When both the top machine learning and the top statistic professors from the best research labs in the world say this about conformal prediction it is quite an endorsement.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Conformal_prediction_growth](https://github.com/valeman/awesome-conformal-prediction/blob/main/Conformal%20prediction%20growth.png) 

In 2022 conformal prediction research experienced exponential growth in academia and with the availabity of open-source libaries the industry is positioned to replicate this growth in the industry. Awesome Conformal Prediction DOI is https://doi.org/10.5281/zenodo.6467205


📢📢Industry take notice. The revolution in Uncertainty Quantification / Probabilistic Prediction / Forecasting is already here 📢📢  A big one  🔥🔥🔥🔥🔥

🌟 🌟 🌟 🌟 🌟 

Featured resources:

[A Gentle Introduction to Conformal Prediction and Distribution-Free Uncertainty Quantification](https://people.eecs.berkeley.edu/~angelopoulos/publications/downloads/gentle_intro_conformal_dfuq.pdf)

This is newest version of the super-popular tutorial on Conformal Prediction (over 3,500 stars on YouTube) now significantly expanded (2x), including advanced techniques such as covariate shift conformal, as well as a super fun history and literature review in Section 7.

[A Tutorial on Conformal Prediction](https://www.youtube.com/watch?v=nql000Lu_iE&t=1786s) by Anastasios Angelopoulos and Stephen Bates (2021) 🔥🔥🔥🔥🔥

[A Tutorial on Conformal Prediction Part 2: Conditional Coverage and Diagnostics](https://www.youtube.com/watch?v=TRx4a2u-j7M) by Anastasios Angelopoulos and Stephen Bates (2022)

⭐⭐️⭐️⭐️⭐️


![modrian](mondrian.jpg) 

## [Table of Contents]()

* [Events](#Events)

* [Books](#Books)

* [PhD and MSc Theses](#Theses)

* [Videos](#Videos) 
 
* [Papers](#Papers)

* [Articles](#Articles)

* [Tutorials](#Tutorials)

* [Presentation_slides](#Presentation_slides)

* [Researchers](#Researchers)

* [Websites](#Websites)

* [Twitter](#Twitter)

* [Conferences](#Conferences)

* [Code Python](#Code-Python)  

* [Code R](#Code-R)

* [Code Julia](#Code-Julia) 

* [Code Other Languages](#Code-Other)

* [Miscellaneous](#Miscellaneous)

* [Contributing](#Contributing) 

<a href="https://www.buymeacoffee.com/valeman" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

## Events


![Featured Event - Workshop on Distribution-Free Uncertainty Quantification
at ICML 2021](https://github.com/valeman/awesome-conformal-prediction/blob/main/ICML%20DFUQ%2022%20rocks!.jpeg)

1. [Workshop on Distribution-Free Uncertainty Quantification at ICML 2022](https://sites.google.com/berkeley.edu/dfuq-22/home)
2. [11th Symposium on Conformal and Probabilistic Prediction with Applications](http://copa-conference.com)

## Books

1. [Algorithmic Learning in a Random World](https://link.springer.com/book/10.1007/b106715) by Vladimir Vovk and Alex Gammerman, also Glenn Shafer (2005). Second edition in progress. 🔥🔥🔥🔥🔥
2. [Conformal Prediciton for Reliable Machine Learning](https://www.elsevier.com/books/conformal-prediction-for-reliable-machine-learning/balasubramanian/978-0-12-398537-8) by Vineeth Balasubramanian, Shen-Shyang Ho, Vladimir Vovk (2014) 🔥🔥🔥🔥🔥
3. [Conformal predictive distributions with kernels](https://link.springer.com/chapter/10.1007/978-3-319-99492-5_4) by Vladimir Vovk, Ilia Nouretdinov, Valery Manokhin, Alex Gammerman (Chapter in 'Braverman Readings in Machine Learning. Key Ideas from Inception to Current State', Springer, 2018). 🔥🔥🔥🔥🔥
4. [Confidence, Likelihood, Probability](https://www.cambridge.org/core/books/confidence-likelihood-probability/143A34F11FB3D6F611F78E27C6D2CA5A) by Tore Schweder and Nils Lid Hjort (University of Oslo, 2016). Not directly about Conformal Prediction but a great book about modern frequentist methods. 🔥🔥🔥🔥🔥

## Theses
1. [Conformal and Venn Predictors for large, imbalanced and sparse chemoinformatics data](https://pure.royalholloway.ac.uk/portal/files/41316291/2021toccacelipphd.pdf) by Paolo Toccaceli (Royal Holloway, UK, 2021)
2. [Competitive online algorithms for probabilistic prediction](https://pure.royalholloway.ac.uk/portal/files/36216771/Thesis_Raisa.pdf) by Raisa Dzhamtyrova (Royal Holloway, UK, 2020)
3. [Conformal Prediction and Testing under On-line Compression Models](https://pure.royalholloway.ac.uk/portal/files/20318074/2014fedorovavphd.pdf) by Valentina Fedorova (Royal Holloway, UK, 2014)
4. [Adaptive Online Learning](https://pure.royalholloway.ac.uk/portal/files/17462972/adamskiy_thesis.pdf) by Dmitry Adamskiy (Royal Holloway, UK, 2013)
5. [On discovery and exploitation of temporal structure in data sets](https://pure.royalholloway.ac.uk/portal/files/24367944/Thesis.pdf) by Scarfe, Tim (Royal Holloway, UK, 2015)
6. [Black-box Security Measuring Black-box Information Leakage via Machine Learning](https://pure.royalholloway.ac.uk/portal/files/33806285/thesis_final_after_amendments.pdf) by Giovanni Cherubin (Royal Holloway, UK, 2019)
7. [Small and Large Scale Probabilistic Classifiers with Guarantees of Validity](https://pure.royalholloway.ac.uk/portal/files/30400650/2018PetejIPhd.pdf) by Ivan Petej (Royal Holloway, UK, 2019)
8. [Towards a Question Answering View of Natural Language Processing](https://pure.royalholloway.ac.uk/portal/files/35163753/Towards_a_Question_Answering_View_of_Natural_Language_Processing_3.pdf) by Zukov Gregoric, Andrej (Royal Holloway, UK, 2019)
9. [Confidence and Venn Machines and Their Applications to Proteomics](https://pure.royalholloway.ac.uk/portal/files/1402925/PhD_Thesis_Final_Dmitry_Devetyarov.pdf) by Devetyarov, Dmitry (Royal Holloway, UK, 2019)
10. [Conformal Anomaly Detection - detecting abnormanl trajectories in surveillance applications](https://www.diva-portal.org/smash/get/diva2:690997/FULLTEXT02.pdf) by Rikard Laxhammar (University of Skoeve, Sweden, 2014)
11. [Inductive Confidence Machine for Pattern Recognition - is it the next step towards AI](https://github.com/eghamtech/AIOS/blob/master/notebooks/David_Surkov-RHUL-thesis-2004.pdf) by David Surkov (Royal Holloway, UK, 2004)
12. [Distribution Free Prediction Intervals for Multiple Functional Regression](http://d-scholarship.pitt.edu/39495/1/RMK%20Dissertation%20Final.pdf) by Ryan Kelly (University of Pittsburgh, 2020).
13. [Probabilistic Load Forecasting with Deep Conformalized Quantile Regression](https://munin.uit.no/bitstream/handle/10037/21914/thesis.pdf?sequence=2) by Vilde Jensen (Artcic University of Norway, 2021)

## Tutorials

1. [A Gentle Introduction to Conformal Prediction and Distribution-Free Uncertainty Quantification](https://arxiv.org/pdf/2107.07511.pdf) by Anastasios N. Angelopoulos and Stephen Bates (2021) 🔥🔥🔥🔥🔥
2. [A Tutorial on Conformal Prediction](https://www.youtube.com/watch?v=nql000Lu_iE&t=1786s) by Anastasios Angelopoulos and Stephen Bates (2021) 🔥🔥🔥🔥🔥
3. [A Tutorial on Conformal Predictive Distributions](https://www.youtube.com/watch?v=FUi5jklGvvo&t=3s) by Paolo Toccaceli (2020) 🔥🔥🔥🔥🔥
4. [Conformal Prediciton Tutorial](https://www.youtube.com/watch?v=0MsGri8nmJQ) by Henrik Linusson (2021) 🔥🔥🔥🔥🔥
5. [Henrik Linusson: Conformal Prediction](https://www.youtube.com/watch?v=lQxH-zXrOwI&t=1522s) by Henrik Linusson (2020)
6. [Predicting with Confidence - Henrik Boström](https://www.youtube.com/watch?v=eXU-64dwHmA) by Henrik Boström (2016)
7. [Venn Predictors Tutorial](https://www.youtube.com/watch?v=KsQpkjl7u1w) by Ulf Johansson, Cecilia Sönströd, Tuve Löfström, and Henrik Boström (2021)
8. [Ulf Johansson: Venn Predictors](https://www.youtube.com/watch?v=xxZOLo8wxe0&t=98s) by Ulf Johansson (2020)
9. [A Tutorial on Conformal Prediction](https://jmlr.org/papers/v9/shafer08a.html) by Glenn Shafer and Vladimir Vovk (2008) 🔥🔥🔥🔥🔥
10. [Conformal Prediction: a Unified Review of Theory and New Challenges](https://www.e-publications.org/ims/submission/BEJ/user/submissionFile/46245?confirm=193b4e5b) by Gianluca Zeni, Matteo Fontana1 and Simone Vantini (Politecnico di Milano, Italy, 2021)
11. [Conformal Prediction in Spark](https://docs.google.com/presentation/d/1eD1vUJVR3nejyJZsOMfxL-NxrLy7K2UUMSAEMHYLfek/edit#slide=id.g2276269343_0_129) by Marco Capuccini (Uppsala University, 2017)
12. [Tutorial on Venn-ABERS prediction](https://cml.rhul.ac.uk/copa2017/presentations/VennTutorialCOPA2017.pdf) by Paolo Toccaceli (Royal Holloway, UK, 2017) 🔥🔥🔥🔥🔥
13. [An Introduction to Conformal Prediction](https://cml.rhul.ac.uk/copa2017/presentations/CP_Tutorial_2017.pdf) by Henrik Linusson (2017) 🔥🔥🔥🔥🔥
14. [Introduction to Conformal Prediction](https://www.iith.ac.in/~vineethnb/indoukworkshop2015/assets/files/IntroToCP.pdf) by Vineeth N Balasubramanian (Indian Ins)tute of Technology, Hyderabad, 2015) 
15. [Conformal prediction A Tiny Tutorial on Predicting with Confidence](https://people.dsv.su.se/~henke/DSWS/johansson.pdf) by Henrik Linusson and Ulf Johansson (2014)
16.[Introduction to Conformal Prediction and Distribution-Free Uncertainty Quantification](https://www.youtube.com/watch?v=usaHyuu2TzY) by Anastasios Angelopoulos (Berkeley, 2022)

## Videos 

1. [Treatment of Uncertainty in the Foundations of Probability](https://www.youtube.com/watch?v=B7E-QJ9fm4w&t=2297s) by Vladimir Vovk (Royal Holloway, UK, 2017)
2. [Large-Scale Probabilistic Prediction With and Without Validity Guarantees](https://www.youtube.com/watch?v=ksrUJdb2tA8) by Vladimir Vovk (Royal Holloway, UK, NeurIPS 2015) 🔥🔥🔥🔥🔥
3. [Conformal testing in a binary model situation](https://www.youtube.com/watch?v=RTcT4YXRdMg) by Vladimir Vovk (Royal Holloway, UK, 2021)
4. [Protected probabilistic classification](https://www.youtube.com/watch?v=MpP-3suUoLY) by Vladimir Vovk (Royal Holloway, UK, 2021)
5. [Retrain or not retrain: conformal test martingales for change-point detection](https://www.youtube.com/watch?v=4Ra5KnDEfkw&t=1s) by Vladimir Vovk (Royal Holloway, UK, 2021) 🔥🔥🔥🔥🔥
6. [A Tutorial on Conformal Prediction](https://www.youtube.com/watch?v=nql000Lu_iE&t=1786s) by Anastasios Angelopoulos and Stephen Bates (Berkeley, ICML 2021) 🔥🔥🔥🔥🔥
7. [Steps Toward Trustworthy Machine Learning](https://www.youtube.com/watch?v=2iNRSgS7-L4) by Tom Dietterich (2021)
8. [A Tutorial on Conformal Predictive Distributions](https://www.youtube.com/watch?v=FUi5jklGvvo&t=3s) by Paolo Toccaceli (Royal Holloway, UK, 2020) 🔥🔥🔥🔥🔥
9. [Conformal Prediciton Tutorial](https://www.youtube.com/watch?v=0MsGri8nmJQ) by Henrik Linusson (2021) 🔥🔥🔥🔥🔥
10. [Henrik Linusson: Conformal Prediction](https://www.youtube.com/watch?v=lQxH-zXrOwI&t=1522s) by Henrik Linusson (2020)
11. [Predicting with Confidence - Henrik Boström](https://www.youtube.com/watch?v=eXU-64dwHmA) by Henrik Boström (2016)
12. [How to increase certainty in predictive modeling](https://www.youtube.com/watch?v=fQQP84yxCRs&t=1277s) by Emmanuel Candes (Stanford, 2021) 🔥🔥🔥🔥🔥
13. [Recent Progress in Predictive Inference](https://www.youtube.com/watch?v=tY73G_UvkAE&t=833s) by Emmanuel Candes (Stanford, 2020) 🔥🔥🔥🔥🔥
14. [Some recent progress in predictive inference" (Stanford) @ MAD+](https://www.youtube.com/watch?v=djgxwpJQyAA) by Emmanuel Candes (Stanford, 2020)
15. [Conformal Prediciton in 2020](https://www.youtube.com/watch?v=61tpigfLHso&t=1507s) by Emmanuel Candes (Stanford, 2020) 🔥🔥🔥🔥🔥
16. [Assumption-free prediction intervals for black-box regression algorithms](https://www.youtube.com/watch?v=GMnCO7_HIOY&t=3943s) by Aaditya Ramdas (Carnegie Mellon, 2020) 🔥🔥🔥🔥🔥
17. [Maria Navarro: Quantifying uncertainty in Machine Learning predictions | PyData London 2019](https://www.youtube.com/watch?v=r6bhm_A-YcQ&t=12s) by Maria Navarro (2019)
18. [Conformal Prediction: Enhanced Method for Understanding the Prediction Quality](https://www.youtube.com/watch?v=_ZVuEWEfwuw&t=948s) by Artem Ryasik and Greg Landrum
19. [Venn Predictors Tutorial](https://www.youtube.com/watch?v=KsQpkjl7u1w) by Ulf Johansson, Cecilia Sönströd, Tuwe Löfström, and Henrik Boström (2021)
20. [Mondrian conformal predictive distributions](https://www.youtube.com/watch?v=dHNZxw8WQrs) by Henrik Boström, Ulf Johansson, and Tuwe Löfström (2021) 🔥🔥🔥🔥🔥
21. [Calibrating Multi-Class Models](https://www.youtube.com/watch?v=uCnFgTjUYto) by Ulf Johansson, Tuwe Löfström, and Henrik Boström (2021)
22. [Conformal testing in a binary model situation](https://www.youtube.com/watch?v=RTcT4YXRdMg) by Vladimir Vovk (Royal Holloway, UK, 2021)
23. [Conformal prediction in Orange](https://www.youtube.com/watch?v=qI1jOEour1g&t=14s) by Tomaž Hočevar and Blaž Zupan (2021)
24. [Distribution-Free, Risk-Controlling Prediction Sets](https://www.youtube.com/watch?v=ITJAR3fcNuI) by Anastasios Angelopoulos (Stanford, 2021) 🔥🔥🔥🔥🔥
25. [Conformal Prediction and Distribution-Free Calibration](https://synapse.math.univ-toulouse.fr/s/KDcWmmU9j9zk0rm) by Aaditya Ramdas (Carnegie Mellon, 2021) 🔥🔥🔥🔥🔥
26. [Reliable Diagnostics by Conformal Predictors](https://www.youtube.com/watch?v=zW3R-vbLw58) by Alexander Gammerman (Royal Holloway, UK, 2015)
27. [Distribution-Free, Risk-Controlling Prediction Sets](https://www.youtube.com/watch?v=ITJAR3fcNuI) by Anastasios Angelopoulos (Stanford, 2021) 🔥🔥🔥🔥🔥
28. [Conformal Inference of Counterfactuals and Time-to-event Outcomes](https://www.youtube.com/watch?v=nfD3mrSefbI) by Lihua Lei (Stanford, 2021)
29. [Algo Hour – Conformal Inference of Counterfactuals and Individual Treatment Effect](https://www.youtube.com/watch?v=COW2QNBmEMw) by Lihua Lei (Stanford, 2021)
30. [Conformal Inference of Counterfactuals and Individual Treatment effects(Stanford)](https://www.youtube.com/watch?v=8tM4BhONHms) by Lihua Lei (Stanford, 2021)
31. [Approximation to object conditional validity with inductive conformal predictors](https://www.youtube.com/watch?v=pUf7z2vxdi8) by Anthony Bellotti (University of Nottingham Ningbo, China, 2021)
32. [Ulf Johansson: Venn Predictors](https://www.youtube.com/watch?v=xxZOLo8wxe0&t=40s) by Ulf Johansson (Jönköping University, Sweden, 2021) 🔥🔥🔥🔥🔥
33. [Transformer-based conformal predictors for paraphrase detection](https://www.youtube.com/watch?v=HYP1ypxywWo) by Patrizio Giavannotti and Prof. Alexander Gammerman (Royal Holloway, UK, 2021)
34. [Conformal Inference of Counterfactuals and Individual Treatment Effects](https://www.youtube.com/watch?v=jkFs6pLZXBQ) by Lihua Lei (Stanford, 2020)
35. [Model-Free Predictive Inference](https://www.youtube.com/watch?v=8GkhRuWcd0w) by Larry Wasserman (Carnegie Mellon, 2020) 🔥🔥🔥🔥🔥
36. [Shapley-value based inductive conformal prediction](https://www.youtube.com/watch?v=6XUc3HFa_5Q&t=1094s) by William Lopez Jaramillo (2021)
37. [Conformal Training: Learning Optimal Conformal Classifiers | DeepMind](https://www.youtube.com/watch?v=XMa1glDpVtQ&t=318s) by David Stutz (2021) 🔥🔥🔥🔥🔥
38. [Distribution-Free, Risk-Controlling Prediction Sets](https://www.youtube.com/watch?v=z8WDmD5D-I0) by Anastasios Angelopoulos (2021) 🔥🔥🔥🔥🔥
39. [Assumption-Free, High-Dimensional Inference](https://www.youtube.com/watch?v=UOMvUaYfpH4) by Larry Wasserman (2016)
40. [Neural Predictive Monitoring under Partial Observability](https://www.youtube.com/watch?v=JhJXUDPoKCc) by Francesca Cairolli (2021)
41. [Conformalized Kernel Ridge Regression and Its Efficiency](https://www.youtube.com/watch?v=OLeu9TXE5n4) by Evgeny Burnaev (Skolkovo, Russia, 2015)
42. [Fast conformal classification using influence functions](https://www.youtube.com/watch?v=LRwm976poDE) by Giovanni Cherubin (Alan Turing Institute, UK, 2021)
43. [Valid inferential models and conformal prediction](https://www.youtube.com/watch?v=egrLw0CmXTs) by Ryan Martin (North Carolina State University, USA, 2021)
44. [Mondrian conformal predictive distributions](https://www.youtube.com/watch?v=dHNZxw8WQrs&t=1415s) by Henrik Boström, Ulf Johansson and Tuwe Löfström (KTH Royal Institute of Technology, Sweden, 2021) 🔥🔥🔥🔥🔥
45. [Evaluation of updating strategies for conformal predictive systems in the presence of extreme events](https://www.youtube.com/watch?v=Xgs0JqDw8lA) by Hugo Werner, Lars Carlsson, Ernst Ahlberg and and Henrik Boström (KTH Royal Institute of Technology, Sweden, 2021)
46. [Exact and Robust Conformal Inference Methods for Predictive Machine Learning With Dependent Data](https://www.youtube.com/watch?v=Wcm9Uw0YL8A) by Victor Chernozhukov (MIT, USA, 2019) 🔥🔥🔥🔥🔥
47. [Ulf Johansson: Venn Predictors](https://www.youtube.com/watch?v=xxZOLo8wxe0&t=98s) by Ulf Johansson (Jönköping University, Sweden, 2020) 🔥🔥🔥🔥🔥
48. [Class-wise confidence for debt prediction in real estate management](https://www.youtube.com/watch?v=ZVhA8LGXWpc) by Soundouss Messoudi (2021)
49. [How Nonconformity Functions and Difficulty of Datasets Impact the Efficiency of Conformal Classifiers](https://www.youtube.com/watch?v=lLtZkVwxMNw) by Marharyta Aleksandrova (2021)
50. [Nested conformal prediction and quantile out-of-bag ensemble methods](https://www.youtube.com/watch?v=NlUlelNWVMQ) by Chirag Gupta (Carnegie Mellon, 2020) 🔥🔥🔥🔥🔥
52. [Panel with Michael I. Jordan, Vladimir Vovk, and Larry Wasserman, moderated by Aaditya Ramdas](https://slideslive.com/38964850/panel-with-michael-i-jordan-vladimir-vovk-and-larry-wasserman-moderated-by-aaditya-ramdas?ref=account-folder-87373-folders) by Vladimir Vovk, Larry Wasserman, Michael I. Jordan, Aaditya Ramdas, ICML 2021 🔥🔥🔥🔥🔥 🔥🔥🔥🔥🔥
53. [Black-box uncertainty - Anastasios Angelopoulos](https://www.youtube.com/watch?v=jW-mbsVgcIc) by Anastasios Angelopoulos (Berkeley, USA, 2021) 🔥🔥🔥🔥🔥 
54. [P.C. Mahalanobis Memorial Lectures 2020-21](https://www.isibang.ac.in/~statmath/pcm2020/) by Vladimir Vovk (Royal Holloway, UK, 2021)
55. [Rahul Vishwakarma: New Perspective on Machine Learning Predictions Under Uncertainty | SNIA Storage Developer Conference, Santa Clara 2019](https://www.youtube.com/watch?v=T-hG1JyAk4E) by Rahul Vishwakarma (2019)
56. [Fast conformal classification using influence functions](https://www.youtube.com/watch?v=LRwm976poDE) by Umang Bhatt, Adrian Weller and Giovanni Cherubin (Cambridge / Alan Turinig Institute, 2021).

## Papers

1. [Introducing Conformal Prediction in Predictive Modeling. A Transparent and Flexible Alternative to Applicability Domain Determination](https://pubs.acs.org/doi/10.1021/ci5001168) by Ulf Norinder, Lars Carlsson, Scott Boyer, and Martin Eklund (2014)
2. [Uncertainty Sets for Image Classifiers using Conformal Prediction](https://arxiv.org/pdf/2009.14193.pdf) by Anastasios N. Angelopoulos, Stephen Bates, Jitendra Malik, & Michael I. Jordan (Berkeley, 2021) 🔥🔥🔥🔥🔥
3. [Conformal Prediction Under Covariate Shift](https://arxiv.org/abs/1904.06019) by Ryan Tibshirani, Rina Foygel Barber, Emmanuel Candes, Aaditya Ramdas (Carnegie Mellon, Stanford, Chicago, 2019) 🔥🔥🔥🔥🔥
4. [Regression Conformal Prediction with Nearest Neighbours](https://arxiv.org/pdf/1401.3880.pdf) by Harris Papadopoulos, Vladimir Vovk and Alex Gammerman (Royal Holloway, UK, 2014)
5. [Nested conformal prediction and quantile out-of-bag ensemble methods](https://arxiv.org/pdf/1910.10562.pdf) by Chirag Gupta, Arun Kuchibhotla and Aaditya  Ramdas (Carnegie Mellon, 2021) 🔥🔥🔥🔥🔥
6. [Cross-conformal predictive distributions](http://proceedings.mlr.press/v91/vovk18a.html) by Vladimir Vovk, Ilia Nouretdinov, Valery Manokhin and Alexander Gammerman (Royal Holloway, UK, 2018) 🔥🔥🔥🔥🔥 🔥🔥🔥🔥🔥
7. [Criteria of Efficiency for Conformal Prediction](https://arxiv.org/pdf/1603.04416.pdf) by Vladimir Vovk, Ilia Nouretdinov, Valentina Fedorova,
Ivan Petej, and Alex Gammerman ((Royal Holloway, UK, 2016)
7. [Conformal Prediction for Simulation Models](https://benjaminleroy.github.io/documents/icml2021/conformal_prediction_for_simulation_models.pdf) by Benjamin LeRoy and Chad Schafer (Carnegie Mellon, 2021)
8. [Distribution-free, risk-controlling prediction sets](https://arxiv.org/pdf/2101.02703) Stephen Bates, Anastasios Angelopoulos, Lihua Lei, Jitendra Malik and  Michael I Jordan (Berkeley, 2021) 🔥🔥🔥🔥🔥
9. [Conditional calibration for false discovery rate control under dependence](https://arxiv.org/abs/2007.10438) by William Fithian and Lihua Lei (Stanford, 2021)
10. [Conformal Prediction: a Unified Review of Theory and New Challenges](https://www.e-publications.org/ims/submission/BEJ/user/submissionFile/46245?confirm=193b4e5b) by Gianluca Zeni, Matteo Fontana and S. Vantini (2021) 🔥🔥🔥🔥🔥
11. [Regression conformal prediction with random forests](https://link.springer.com/content/pdf/10.1007%2Fs10994-014-5453-0.pdf) by Ulf Johansson, Henrik Boström,  Tuve Löfström and Henrik Linusson (2014)
12. [A conformal prediction approach to explore functional data](https://arxiv.org/pdf/1302.6452.pdf) by Jing Lei, Alessandro Rinaldo, Larry Wasserman (Carnegie Mellon, 2013)
13. [An electronic nose-based assistive diagnostic prototype for lung cancer detection with conformal prediction](https://pure.royalholloway.ac.uk/portal/files/37171406/Measurement_Manuscript_unmarked_R4.pdf) by Xianghao Zhana,c, Zhan Wanga, Meng Yangb, Zhiyuan Luod, You Wanga, Guang Li (2020)
14. [Predicting the Rate of Skin Penetration Using an Aggregated Conformal Prediction Framework](https://pubmed.ncbi.nlm.nih.gov/28335598/) by Martin Lindh, A. Karlén, Ulf Norinder (2017)
15. [The application of conformal prediction to the drug discovery process](https://link.springer.com/article/10.1007%2Fs10472-013-9378-2) by Martin Eklund, Ulf Norinder, Scott Boyer & Lars Carlsson (2014) 🔥🔥🔥🔥🔥
16. [Distributional conformal prediction](https://arxiv.org/pdf/1909.07889.pdf) by Victor Chernozhukov, Kaspar Wüthrich, Yinchu Zhu (2021) 🔥🔥🔥🔥🔥
17. [Anomaly Detection of Trajectories with Kernel Density Estimation by Conformal Prediction](https://link.springer.com/content/pdf/10.1007%2F978-3-662-44722-2_29.pdf) by James Smith, Ilia Nouretdinov, Rachel Craddock, Charles Offer, and Alexander Gammerman (2009)
18. [Conformal prediction interval estimation and applications to day-ahead and intraday power markets](https://arxiv.org/pdf/1905.07886.pdf) by Christopher Kath, Florian Ziel (2019) 🔥🔥🔥🔥🔥
19. [The application of conformal prediction to the drug discovery process](https://link.springer.com/article/10.1007%2Fs10472-013-9378-2) by Martin Eklund, Ulf Norinder, Scott Boyer & Lars Carlsson (2013)
20. [Anomaly Detection of Trajectories with Kernel Density Estimation by Conformal Prediction](https://link.springer.com/chapter/10.1007%2F978-3-662-44722-2_29) by James Smith, Ilia Nouretdinov, Rachel Craddock, Charles Offer, Alexander Gammerman (Royal Holloway, UK, 2014)
21. [Conformal Prediction: a Unified Review of Theory and New Challenges](https://www.e-publications.org/ims/submission/BEJ/user/submissionFile/46245?confirm=193b4e5b) by Gianluca Zeni, Matteo Fontana1 and Simone Vantini (Politecnico di Milano, Italy, 2021)
22. [Exchangeability, Conformal Prediction, and Rank Tests](https://arxiv.org/pdf/2005.06095.pdf) by Arun Kuchibhotla (Carnegie Mellon, 2021)
23. [Conformal prediction with localization](https://arxiv.org/pdf/1908.08558.pdf) by Leying Guan (Yale, 2020)
24. [Predicting skin sensitizers with confidence - Using conformal prediction to determine applicability domain of GARD](https://pubmed.ncbi.nlm.nih.gov/29374571/) by Andy Forreryd, Ulf Norinder, Tim Lindberg, Malin Lindstedt (2018)
25. [Binary classification of imbalanced datasets using conformal prediction](https://pubmed.ncbi.nlm.nih.gov/28135672/) by 
Ulf Norinder, Scott Boyer (2017)
26. [Discretized conformal prediction for efficient distribution-free inference](https://arxiv.org/pdf/1709.06233.pdf) by Wenyu Chen, Kelli-Jean Chun, and Rina Foygel Barber (2017)
27. [Validity, consonant plausibility measures, and conformal prediction](https://www.sciencedirect.com/science/article/abs/pii/S0888613X21001195?via%3Dihub) by Leonardo Cella. and Ryan Martin (2021)
28. [Conformal Prediction Classification of a Large Data Set of Environmental Chemicals from ToxCast and Tox21 Estrogen Receptor Assays](https://pubmed.ncbi.nlm.nih.gov/27152554/) by Ulf Norinder, Scott Boyer (2016)
29. [Conformal prediction to define applicability domain – A case study on predicting ER and AR binding](https://www.tandfonline.com/doi/full/10.1080/1062936X.2016.1172665) by U. Norinder, A. Rybacka, P.Andersson (2016)
30. [Conformal prediction of biological activity of chemical compounds](https://link.springer.com/article/10.1007%2Fs10472-017-9556-8) by Paolo Toccaceli, Ilia Nouretdinov, Alex Gammerman (Royal Holloway, UK, 2017) 🔥🔥🔥🔥🔥
31. [Introducing conformal prediction in predictive modeling for regulatory purposes. A transparent and flexible alternative to applicability domain determination](https://pubmed.ncbi.nlm.nih.gov/25559551/) by Ulf Norinder, Lars Carlsson, Scott Boyer, Martin Eklund (2015)
32. [Aggregated Conformal Prediction](https://link.springer.com/chapter/10.1007%2F978-3-662-44722-2_25) by Lars CarlssonMartin EklundUlf Norinder (2014)
33. [Interpretation of Conformal Prediction Classification Models](https://link.springer.com/chapter/10.1007%2F978-3-319-17091-6_27) by Ernst Ahlberg, Ola Spjuth, Catrin Hasselgren, Lars Carlsson (2015)
34. [Cross-Conformal Prediction with Ridge Regression](https://link.springer.com/chapter/10.1007%2F978-3-319-17091-6_21) by Harris Papadopoulos (2015)
35. [Sparse conformal prediction for dissimilarity data](https://link.springer.com/article/10.1007%2Fs10472-014-9402-1) by Frank-Michael Schleif, Xibin Zhu and Barbara Hammer (2015)
36. [Effective utilization of data in inductive conformal prediction using ensembles of neural networks](https://ieeexplore.ieee.org/document/6706817) by Tuve Löfström, Ulf Johansson and Henrik Boström (2013)
37. [Beyond the Basic Conformal Prediction Framework](https://www.sciencedirect.com/science/article/pii/B978012398537800002X?via%3Dihub) by Vladimir Vovk (2014)
38. [An electronic nose-based assistive diagnostic prototype for lung cancer detection with conformal prediction](https://pure.royalholloway.ac.uk/portal/files/37171406/Measurement_Manuscript_unmarked_R4.pdf) by Xianghao Zhan, Zhan Wang, Meng Yang, Zhiyuan Luo, You Wang, Guang Li (Stanford, Royal Holloway, China University of Mining and Technology, 2020)
39. [Predicting with confidence: Using conformal prediction in drug discovery](https://jpharmsci.org/article/S0022-3549(20)30589-X/fulltext) by Jonathan Alvarsson, Staffan Arvidsson McShane, Ulf Norinder, Ola Spjuth (2021)
40. [Inductive conformal prediction for silent speech recognition](https://pubmed.ncbi.nlm.nih.gov/32120355/) by Ming Zhang, You Wang, Zhang Wei, Meng Yang, Zhiyuan Luo, Guang Li (2020)
41. [Large scale comparison of QSAR and conformal prediction methods and their applications in drug discovery](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0325-4) by Nicolas Bosc, Francis Atkinson, Eloy Felix, Anna Gaulton, Anne Hersey and Andrew R. Leach (2019)
42. [Deep Conformal Prediction for Robust Models](https://link.springer.com/chapter/10.1007%2F978-3-030-50146-4_39) by Soundouss Messoudi, Sylvain Rousseau and Sébastien Destercke (2020)
43. [Strong validity, consonance, and conformal prediction](https://arxiv.org/abs/2001.09225) by Leonardo Cella and Ryan Martin (2020)
44. [Skin Doctor CP: Conformal Prediction of the Skin Sensitization Potential of Small Organic Molecules](https://pubs.acs.org/doi/10.1021/acs.chemrestox.0c00253) by Anke Wilm, U. Norinder, M. Agea, Christina de Bruyn Kops, Conrad Stork, J. Kühnl, J. Kirchmair (2020)
47. [Conformal prediction based active learning by linear regression optimization](https://www.sciencedirect.com/science/article/abs/pii/S0925231220300461?via%3Dihub) by Sergio Matiz, Kenneth E.Barner (2020)
48. [Conformal prediction intervals for the individual treatment effect](https://arxiv.org/pdf/2006.01474.pdf) by Danijel Kivaranovic, Robin Ristl, Martin Poschb, Hannes Leeb (2020)
49. [Nearest neighbor based conformal prediction](https://www.f08.uni-stuttgart.de/.content/media/downloads/Mathematik/mathematische_berichte/2020/2020-002.pdf) by László Györfi and Harro Walk (2020)
50. [Concepts and Applications of Conformal Prediction in Computational Drug Discovery](https://arxiv.org/pdf/1908.03569.pdf) by Isidro Cortés-Ciriano and Andreas Bender (2019) 🔥🔥🔥🔥🔥
51. [Predicting Ames Mutagenicity Using Conformal Prediction in the Ames/QSAR International Challenge Project](https://academic.oup.com/mutage/article/34/1/33/5239859) by Ulf Norinder,  Ernst Ahlberg,  Lars Carlsson (2018)
52. [Nested Conformal Prediction and the Generalized Jackknife](https://arxiv.org/pdf/1910.10562v1.pdf) by Arun Kuchibhotla and Aaditya Ramdas (Carnegie Mellon, 2019)
53. [Predictive inference with the jackknife+](https://arxiv.org/abs/1905.02928) by Rina Foygel Barber, Emmanuel Candès, Aaditya Ramdas, and Ryan Tibshirani (2020) 🔥🔥🔥🔥🔥
54. [Nonparametric predictive distributions based on conformal prediction](https://link.springer.com/article/10.1007%2Fs10994-018-5755-8) by Vladimir Vovk, Jieli Shen, Valery Manokhin and Min-ge Xie (Royal Holloway, UK, Rutgers, USA, 2018) 🔥🔥🔥🔥🔥
55. [A Distribution-Free Test of Covariate Shift Using Conformal Prediction](https://arxiv.org/pdf/2010.07147.pdf) by Xiaoyu Hu and Jing Lei (Peking Univerity, China and Carnegie Mellon, USA, 2020) 🔥🔥🔥🔥🔥
56. [Exchangeability, Conformal Prediction, and Rank Tests](https://arxiv.org/pdf/2005.06095.pdf) by Arun Kuchibhotla (Carnegie Mellon, 2021)
57. [Conformal prediction with localization](https://arxiv.org/pdf/1908.08558.pdf) by Leying Guan (2020)
58. [Multitask Modeling with Confidence Using Matrix Factorization and Conformal Prediction](https://pubmed.ncbi.nlm.nih.gov/30908915/) by Ulf Norinder, Fredrik Svensson 
59. [Conformal prediction of HDAC inhibitors](https://www.tandfonline.com/doi/abs/10.1080/1062936X.2019.1591503?journalCode=gsar20) by U. Norinder, J.J.Navaka, E. Lopez-Lopez, D. Mucs & J.L. Medina-Franco (2019)
60. [Computing Full Conformal Prediction Set with Approximate Homotopy](https://arxiv.org/pdf/1909.09365.pdf) by Eugene Ndiaye, Ichiro Takeuchi (2019)
61. [Conformal Prediction Based on Raman Spectra for the Classification of Chinese Liquors](https://journals.sagepub.com/doi/10.1177/0003702819831017) by
Jiao Gu, Huaibo Liu, Chaoqun Ma, Lei Li, Chun Zhu, Christ Glorieux, Guoqing Chen (2019)
60. [Efficient and minimal length parametric conformal prediction regions](https://export.arxiv.org/pdf/1905.03657) by Daniel Eck and Forrest Crawford (2019)
61. [Conformal Prediction for Students' Grades in a Course Recommender System](http://proceedings.mlr.press/v105/morsomme19a/morsomme19a.pdf) by Raphael Morsomme and Evgueni Smirnov (2019)
62. [Efficient iterative virtual screening with Apache Spark and conformal prediction](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0265-z) by Laeeq Ahmed, Valentin Georgiev, Marco Capuccini, Salman Toor, Wesley Schaal, Erwin Laure and Ola Spjuth (2018)
63. [Predicting Off-Target Binding Profiles With Confidence Using Conformal Prediction](https://pubmed.ncbi.nlm.nih.gov/30459617/) by Samuel Lampa, Jonathan Alvarsson, Staffan Arvidsson Mc Shane, Arvid Berg, Ernst Ahlberg, Ola Spjuth (2018)
64. [Maximizing gain in high-throughput screening using conformal prediction](https://jcheminf.biomedcentral.com/track/pdf/10.1186/s13321-018-0260-4.pdf) by Fredrik Svensson, Avid M. Afzal1, Ulf Norinder and Andreas Bender (2018)
65. [Conformalized Survival Analysis](https://arxiv.org/pdf/2103.09763.pdf) by Emmanuel Candès, Lihua Lei and Zhimei Ren (2021) 🔥🔥🔥🔥🔥
66. [Random Forest Prediction Intervals](https://haozhestat.github.io/files/manuscript_RFIntervals_FinalVersion.pdf) by Haozhe Zhang†, Joshua Zimmerman†, Dan Nettleton† and Daniel J. Nordman† (Iowa State University, USA, 2019)
67. [Conformal Training: Learning Optimal Conformal Classifiers | DeepMind](https://arxiv.org/pdf/2110.09192.pdf) by David Stutz (DeepMind), Krishnamurthy Dvijotham, Ali Taylan Cemgil and Arnaud Doucet (2021)
68. [Comparing the Bayes and typicalness frameworks](https://link.springer.com/content/pdf/10.1007%2F3-540-44795-4_31.pdf) by Thomas Melluish, Craig Saunders, Ilia Nouretdinov, and Volodya Vovk (Royal Holloway, UK, 2001). 🔥🔥🔥🔥🔥
69. [Large-scale probabilistic predictors with and without guarantees of validity](https://papers.nips.cc/paper/2015/file/a9a1d5317a33ae8cef33961c34144f84-Paper.pdf) by Vladimir Vovk, Ivan Petej, and Valentina Fedorova (Royal Holloway, Yandex, NeurIPS) 🔥🔥🔥🔥🔥
70. [Inductive conformal prediction for silent speech recognition](https://iopscience.iop.org/article/10.1088/1741-2552/ab7ba0) by Ming Zhang, You Wang, Wei Zhang, Meng Yang, Zhiyuan Luo and Guang Li (2020)
71. [Conformal Prediction using Conditional Histograms](https://papers.nips.cc/paper/2021/file/31b3b31a1c2f8a370206f111127c0dbd-Paper.pdf) by Matteo Sesia and Yaniv Romano (NeurIPS 2021 paper). 🔥🔥🔥🔥🔥
72. [Valid prediction intervals for regression problems](https://arxiv.org/abs/2107.00363) by Nicolas Dewolf, Bernard De Baets, Willem Waegeman (2021) 🔥🔥🔥🔥🔥
73. [Application of conformal prediction interval estimations to market makers’ net positions](http://proceedings.mlr.press/v128/wisniewski20a.html) by Wojciech Wisniewski, David Lindsay, Sian Lindsay (Royal Holloway, UK, 2020)
74. [Locally Valid and Discriminative Prediction Intervals for Deep Learning Models](https://papers.nips.cc/paper/2021/hash/46c7cb50b373877fb2f8d5c4517bb969-Abstract.html) by Zhen Lin, Shubhendu Trivedi, Jimeng Sun (NeurIPS, 2021) 🔥🔥🔥🔥🔥
75. [Distribution-Free Federated Learning with Conformal Predictions](https://arxiv.org/pdf/2110.07661.pdf) by Charles Lu and Jayashree Kalpathy-Cramer (2022)
76. [Coreset-based Conformal Prediction for Large-scale Learning](https://proceedings.mlr.press/v105/riquelme-granada19a.html) by Nery Riquelme-Granada, Khuong Nguyen, Zhiyuan Luo (Royal Holloway, UK, 2019)
77. [Fast probabilistic prediction for kernel SVM via enclosing balls](https://proceedings.mlr.press/v128/riquelme-granada20a.html) by Nery Riquelme-Granada, Khuong Nguyen, Zhiyuan Luo (Royal Holloway, UK, 2020)
78. [Conformalized density- and distance-based anomaly detection in time-series data](https://arxiv.org/abs/1608.04585) by Evgeny Burnaev, Vladislav Ishimtsev (2016) 
79. [Predictive Inference with Weak Supervision](https://arxiv.org/pdf/2201.08315.pdf) by Maxime Cauchois, Suyash Gupta, Alnur Ali and John Duchi (Stanford, 2022)
80. [Conformal Prediction in Clinical Medical Sciences](https://link.springer.com/10.1007/s41666-021-00113-8) by Janette Vazquez and Julio C. Facelli University of Utah, 2022)
81. [Provably Improving Expert Predictions with Conformal Prediction](https://arxiv.org/pdf/2201.12006.pdf) by Eleni Straitouri, Lequng Wang,  Nastaran Okati and Manuel Gomez Rodriguez (Max Planck Institute for Software Systems / Cornell University, 2021).
82. [Conformal predictive distributions with kernels](https://arxiv.org/abs/1710.08894) by Vladimir Vovk, Ilia Nouretdinov, Valery Manokhin, Alex Gammerman (Royal Holloway, UK, 2017)
83. [Multi-class probabilistic classification using inductive and cross Venn–Abers predictors](https://proceedings.mlr.press/v60/manokhin17a.html) by Valery Manokhin (Royal Holloway, UK, 2017). 🔥🔥🔥🔥🔥
84. [Computationally efficient versions of conformal predictive distributions](https://arxiv.org/abs/1911.00941) by Vladimir Vovk, Ivan Petej, Ilia Nouretdinov, Valery Manokhin, Alex Gammerman (Royal Holloway, UK, 2019).
85. [Cover your cough: detection of respiratory events with confidence using a smartwatch](https://proceedings.mlr.press/v91/nguyen18a.html) by Khuong An Nguyen, Zhiyuan Luo (Royal Holloway, 2019).
86. [Predicting Amazon customer reviews with deep confidence using deep learning and conformal prediction](https://www.tandfonline.com/doi/full/10.1080/23270012.2022.2031324) by Ulf Norinder and Petra Norinder (2022)
87. [Conformal Prediction for the Design Problem](https://arxiv.org/pdf/2202.03613.pdf) by Clara Fannjianga, Stephen Batesa, Anastasios Angelopoulosa, Jennifer Listgartena and Michael I. Jordan (Berkeley, 2022) 🔥🔥🔥🔥🔥
88. [Image-to-Image Regression with Distribution-Free Uncertainty Quantification and Applications in Imaging](https://arxiv.org/pdf/2202.05265.pdf) by Anastasios N. Angelopoulos, Amit Kohli, Stephen Bates, Michael I. Jordan, Jitendra Malik, Thayer Alshaabi, Srigokul Upadhyayula, Yaniv Romano (Berkeley and Technion, 2022) 🔥🔥🔥🔥🔥
89. [Conformal predictive decision making](http://proceedings.mlr.press/v91/vovk18b/vovk18b.pdf) by Vladimir Vovk and Claus Bendtsen (2018).
90. [The Lifecycle of a Statistical Model: Model Failure Detection, Identification, and Refitting](https://arxiv.org/pdf/2202.04166.pdf) by Alnur Ali1, Maxime Cauchois and John C. Duchi (Stanford, 2022)
91. [E-values: Calibration, combination, and applications](https://arxiv.org/pdf/1912.06116.pdf) by Vladimir Vovk (Royal Holloway) and Ruodu Wang (University of Waterloo) (2019)
92. [Conformal Prediction Sets with Limited False Positives](https://arxiv.org/pdf/2202.07650.pdf) by Adam Fisch, Tal Schuster, Tommi Jaakkola and Regina Barzilay (MIT / Google Research, 2022)
93. [Adaptive Conformal Predictions for Time Series](https://arxiv.org/pdf/2202.07282.pdf) by Margaux Zaffran, Aymeric Dieuleveut, Olivier Fe ́ron, Yannig Goude,  and Julie Josse (EDF / INRIA / CMAP, France, 2022) 🔥🔥🔥🔥🔥
94. [Ensemble Conformalized Quantile Regression for
Probabilistic Time Series Forecasting](https://arxiv.org/pdf/2202.08756v1.pdf) by Vilde Jensen, Filippo Maria Bianchi, Stian Norman Anfinsen (Arctic University of Norway, 2022) TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
95. [Prediction of Metabolic Transformations using Cross Venn-ABERS Predictors](http://proceedings.mlr.press/v60/arvidsson17a/arvidsson17a.pdf) by Staffan Arvidsson, Ola Spjuth, Lars Carlsson and Paolo Toccaceli (University of Uppsala, Astra Zeneca, Royal Holloway, 2017)
96. [Probabilistic Prediction in scikit-learn](https://www.diva-portal.org/smash/get/diva2:1603345/FULLTEXT01.pdf) by Sweidan, Dirar and Ulf Johansson. 🔥🔥🔥🔥🔥
97. [Ensemble Conformalized Quantile Regression for Probabilistic Time Series Forecasting](https://arxiv.org/pdf/2202.08756.pdf) by Vilde Jensen, Filippo Maria Bianchi, Stian Norman Anfinsen (2022). TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
98. [Conformalized Online Learning: Online Calibration Without a Holdout Set](https://arxiv.org/pdf/2205.09095.pdf) by Shai Feldman, Stephen Bates and Yaniv Romano (2022). TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥


## Presentation_slides
1. [Adaptive Conformal Anomaly Detection for Time-series](https://cml.rhul.ac.uk/copa2017/presentations/burnaev.pdf) by Evgeny Burnaev, Alexander Bernstein, Vlad Ishimtsev and Ivan Nazarov (Skoltech, Moscow, Russia, 2017)
2. [Nonparametric predictive distributions based on conformal prediction](https://cml.rhul.ac.uk/copa2017/presentations/vovk.pdf) by Vladimir Vovk, Jieli Shen, Valery Manokhin, Min-ge Xie, Ilia Nouretdinov and Alex Gammerman (Royal Holloway, University of London Rutgers University, 2017)
3. [What Can Conformal Inference Offer to Statistics?](https://lihualei71.github.io/Job_Talk_Lihua_Lei.pdf) by Lihua Lei, Stanford University 


## Researchers
1. [Vladimir Vovk](vovk.net), Royal Holloway, United Kingdom 
2. [Alexander Gammerman](https://cml.rhul.ac.uk/people/alex/), Royal Holloway, United Kingdom 
3. [Glenn Shafer](http://www.glennshafer.com), Rutgers University, USA
4. [Emmanuel Candès](https://candes.su.domains), Stanford, USA
5. [Ryan Tibshiriani](https://www.stat.cmu.edu/~ryantibs/), Carnegie Mellon, USA
6. [Yaniv Romano](https://sites.google.com/view/yaniv-romano/), Technion—Israel Institute of Technology
7. [Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/), Berkeley, USA
8. [Jitendra Malik](https://people.eecs.berkeley.edu/~malik/), Berkeley, USA 
9. [Anastasios Angelopoulos](https://people.eecs.berkeley.edu/~angelopoulos/), Berkeley, USA
10. [Lihua Lei](https://lihualei71.github.io), Stanford, USA
11. [Henrik Boström](https://www.kth.se/profile/henbos), KTH, Sweden
12. [Ulf Johansson](https://scholar.google.com/citations?user=OZjCgIsAAAAJ&hl=en), Jönköping University, Sweden
13. [Henrik Linusson](https://scholar.google.se/citations?user=Xl8W39cAAAAJ&hl=en), University of Borås, Sweden
14. [Harris Papadopoulos](http://staff.fit.ac.cy/com.ph/), Frederick University, Cyprus
15. [Vladimir V'yugin](http://iitp.ru/ru/users/125.htm), Institute for Information Transmission Problems (IITP), Russia
16. [Evgeny Burnaev](https://faculty.skoltech.ru/people/evgenyburnaev), Skoltech, Russia
17. [Aaditya Ramdas](http://stat.cmu.edu/~aramdas/), Carnegie Mellon, USA
18. [Benjamin LeRoy](https://benjaminleroy.github.io), Carnegie Mellon, USA
19. [Victor Chernozhukov](https://www.mit.edu/~vchern/), MIT, USA
20. [Ulf Norinder](https://scholar.google.com/citations?user=i5hUEFwAAAAJ&hl=en), Stockholm University, Sweden
21. [Ola Spjuth](https://pharmb.io), Uppsala University, Sweden
22. [Ilia Nouretdinov](https://cml.rhul.ac.uk/people/nouretdinov/index.htm), Royal Holloway, United Kingdom

## Articles
1. [Measuring Models' Uncertainty: Conformal Prediction](https://blog.dataiku.com/measuring-models-uncertainty-conformal-prediction) by 
Leo Dreyfus-Schmidt (Dataiku, 2020). 🔥🔥🔥🔥🔥
2. [Conformal Prediction for Neural Regression Model](https://pkghosh.wordpress.com/2021/12/30/conformal-prediction-for-a-neural-regression-model/) by Pranab Ghosh (2021). 🔥🔥🔥🔥🔥
3. [How to Handle Uncertainty in Forecasts](https://towardsdatascience.com/how-to-handle-uncertainty-in-forecasts-86817f21bb54) by Michael Berk (2021)
4. [How to Add Uncertainty Estimation to your Models with Conformal Prediction](https://towardsdatascience.com/how-to-add-uncertainty-estimation-to-your-models-with-conformal-prediction-a5acdb86ea05) by Zachary Warnes (2021)
5. [nonconformist: An easy way to estimate prediction intervals](https://medium.com/spikelab/nonconformist-an-easy-way-to-estimate-prediction-intervals-b0ded1eb066f) by Maria Jesus Ugarte (2021).
6. [Detecting Weird Data: Conformal Anomaly Detection](https://towardsdatascience.com/detecting-weird-data-conformal-anomaly-detection-20afb36c7bcd) by Matthew Burruss (2020).
7. [“MAPIE” Explained Exactly How You Wished Someone Explained to You](https://towardsdatascience.com/mapie-explained-exactly-how-you-wished-someone-explained-to-you-78fb8ce81ff3) by Samuele Mazzanti (2022). 🔥🔥🔥🔥🔥
8. [With MAPIE, uncertainties are back in machine learning](https://towardsdatascience.com/with-mapie-uncertainties-are-back-in-machine-learning-882d5c17fdc3) by Vianney Taquet (2021) 🔥🔥🔥🔥🔥
9. [How to Predict Risk-Proportional Intervals with Conformal Quantile Regression](https://towardsdatascience.com/how-to-predict-risk-proportional-intervals-with-conformal-quantile-regression-175775840dc4) by Samuele Mazzanti (2022). 🔥🔥🔥🔥🔥
10. [Stanford statisticians and Washington Post data scientists build more honest prediction models](https://news.stanford.edu/2021/03/19/honesty-statistical-models/#) Stanford (2021) 🔥🔥🔥🔥🔥
11. [How to Detect Anomalies — state-of-the-art methods using Conformal Prediction](https://valeman.medium.com/how-to-detect-anomalies-state-of-the-art-methods-using-conformal-prediction-e02691659412) by Valery Manokhin (2021) 🔥🔥🔥🔥🔥

## Websites
1. [Main website with research from Prof. Vladimir (Volodya) Vovk](http://alrw.net) 🔥🔥🔥🔥🔥
2. [Conformal Prediction - Prediction with guaranteed performance](https://cml.rhul.ac.uk/cp.html) Royal Holloway, United Kingdom
3. [A Gentle Introduction to Conformal Prediction and Distribution-Free Uncertainty Quantification](https://people.eecs.berkeley.edu/~angelopoulos/blog/posts/gentle-intro/) by Anastasios N. Angelopoulos 🔥🔥🔥🔥🔥
4. [Reliable Predictive Inference](https://sites.google.com/view/cqr) by Yaniv Romano 🔥🔥🔥🔥🔥

## Twitter
1. [Title: What Can *Conformal Inference* Offer to Statistics?](https://t.co/znZHcyyknV) by Lihua Lei, Stanford, 2022
2. [Conformalized survival analysis](https://twitter.com/lihua_lei_stat/status/1381418936739098630?s=20&t=PnfV8wnLV2bThXcKdFFbRg


## Conferences
1. https://icml.cc/Conferences/2021/ScheduleMultitrack?event=8373 🔥🔥🔥🔥🔥
2. https://cml.rhul.ac.uk/copa2021/ 🔥🔥🔥🔥🔥
3. https://cml.rhul.ac.uk/copa2020/ 🔥🔥🔥🔥🔥
4. https://cml.rhul.ac.uk/copa2019/ 🔥🔥🔥🔥🔥
5. https://cml.rhul.ac.uk/copa2018/ 🔥🔥🔥🔥🔥
6. https://cml.rhul.ac.uk/copa2017/ 🔥🔥🔥🔥🔥

## Code-Python

1. [Nonconformist](https://github.com/donlnz/nonconformist) by Henrik Linusson (2015) 🔥🔥🔥🔥🔥
2. [Venn-ABERS Predictor](https://github.com/ptocca/VennABERS) by Paolo Toccaceli (2019), based on NeurIPS 2015 paper 'Large-scale probabilistic predictors with and without guarantees of validity' (#69 on papers list) 🔥🔥🔥🔥🔥
3. [MAPIE - Model Agnostic Prediction Interval Estimator](https://github.com/scikit-learn-contrib/MAPIE) (2021) 🔥🔥🔥🔥🔥 
4. ['Crêpes' - Conformal regressors and predictive systems](https://github.com/henrikbostrom/crepes) by Henrik Boström (2021)
5. [Conformalized Quantile Regression](https://github.com/yromano/cqr) by Yaniv Romano (2019) 🔥🔥🔥🔥🔥
6. [Conformal Classification](https://github.com/aangelopoulos/conformal_classification) by Anastasios N. Angelopoulos (2021)
7. [Orange3 Conformal Prediction](https://github.com/biolab/orange3-conformal)
8. [EnbPI](https://github.com/hamrel-cxu/EnbPI) by Chen Xu (2021) TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
9. [Conformal: an R package to calculate prediction errors in the conformal prediction framework](https://github.com/isidroc/conformal/) by Isidro Cortes, 2019 
10. [Copula Conformal Multi Target Regression](https://github.com/M-Soundouss/CopulaConformalMTR) by Soundouss Messoudi (2021)
11. [Uncertainty Toolbox](https://github.com/uncertainty-toolbox/uncertainty-toolbox) by Youngseog Chung, Willie Neiswanger, Ian Char and Han Guo (2021)
12. [Conformal Histogram Regression: efficient conformity scores for non-parametric regression problems](https://github.com/msesia/chr) by Mateo Sesia and Yaniv Romano (NeurIPS 2021). 🔥🔥🔥🔥🔥
13. [Conformalized density- and distance-based anomaly detection in time-series data (KNN-CAD)](https://github.com/numenta/NAB/tree/master/nab/detectors/knncad) by Evgeny Burnaev, Vladislav Ishimtsev (2016). Top #3 winning solution in Numenta competition 🔥🔥🔥🔥🔥
14. [TorchUQ is an extensive library for uncertainty quantification (UQ) based on pytorch](https://github.com/TorchUQ/torchuq) (2022)
15. [Conformal time-series forecasting"](https://github.com/kamilest/conformal-rnn) by Kamile ̇ Stankeviciute (Cambridge, NeurIPS 2021) TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
16. [Valid Prediction Intervals](https://github.com/nmdwolf/ValidPredictionIntervals/tree/main/Code) by Nicolas Dewolf, Bernard DeBaets, Willem Waegeman (2022) 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
17. [Adaptive Conformal Predictions for Time Series](https://github.com/mzaffran/AdaptiveConformalPredictionsTimeSeries) by Margaux Zaffran,  Aymeric Dieuleveut,  Olivier Fe ́ron, Yannig Goude, and Julie Josse (2022) TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
18. [Conformal learning from scratch](https://github.com/marharyta-aleksandrova/conformal-learning/blob/main/theory/conformal_learning_from_scratch.ipynb) by Marharyta Aleksandrova (2021)
19. [Multi-class-probabilistic-classification using Venn-ABERS (Conformal) prediction](https://github.com/valeman/Multi-class-probabilistic-classification) by Valery Manokhin (Royal Holloway, 2022)
20. [Ensemble Conformalized Quantile Regression for Probabilistic Time Series Forecasting](https://github.com/FilippoMB/Ensemble-Conformalized-Quantile-Regression) Vilde Jensen, Filippo Maria Bianchi and Stian Norman Anfinsen (2022) TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥
21. [Conformalized Online Learning: Online Calibration Without a Holdout Set](https://github.com/Shai128/rci by Shai Feldman, Stephen Bates and Yaniv Romano (2022). TIME SERIES 🚀🚀🚀🚀🚀 🔥🔥🔥🔥🔥

## Code-R
1. [Conformal Inference R Project](https://github.com/ryantibs/conformal) maintained by Ryan Tibshirani (2016) 🔥🔥🔥🔥🔥
2. [Prediction Bands](https://github.com/rizbicki/predictionBands) by Rafael Izbicki and Benjamin LeRoy (2019)
3. [Conformal: an R package to calculate prediction errors in the conformal prediction framework](https://github.com/isidroc/conformal/) by Isidro Cortes, 2019
4. [Online Time Series Anomaly Detectors](https://github.com/valeman/otsad) by Alaine Iturria, 2021 🔥🔥🔥🔥🔥
5. [piRF - Prediction Intervals for Random Forests](https://github.com/chancejohnstone/piRF) by Chancellor Johnstone and Haozhe Zhang (2019)
6. [conformalClassification: Transductive and Inductive Conformal Predictions for Classification Problems](https://cran.r-project.org/web/packages/conformalClassification/) by Niharika Gauraha and Ola Spjuth (2019)

## Code-Julia

1. [RandomForest](https://github.com/henrikbostrom/RandomForest) by Henrik Boström (2017) 🔥🔥🔥🔥🔥

## Code-Other
1. [LibCP -- A Library for Conformal Prediction](https://github.com/fated/libcp) 🔥🔥🔥🔥🔥
2. [An Implementation of Venn-ABERS predictor](https://github.com/fated/venn-abers-predictor) 🔥🔥🔥🔥🔥
3. [LibVM -- A Library for Venn Machine](https://github.com/fated/libvm)
4. [Scala-CP](https://github.com/mcapuccini/scala-cp) by Marco Capuccini (2017)' 🔥🔥🔥🔥🔥 (see tutorial section 'Conformal Prediction in Spark')



    
