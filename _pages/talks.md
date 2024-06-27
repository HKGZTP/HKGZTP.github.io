---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: false
---


Speakers
=====

| Candidate                | Institute                                       |
|--------------------------|-------------------------------------------------|
| Raymond W. Yeung         | The Chinese University of Hong Kong             |
| Antoni B. Chan           | City University of Hong Kong                    |
| Cheuk Ting Li            | The Chinese University of Hong Kong             |
| Shih-Chun Lin            | National Taiwan University                      |
| Yao-Win Peter Hong       | National Tsing Hua University                   |
|Yu-Chih Huang  | National Yang Ming Chiao Tung University |
|Chia-Han Lee   | National Yang Ming Chiao Tung University |
| En-Hui Yang | University of Waterloo |
| Wenrui Dai | Shanghai Jiao Tong University |
| Qianqian Yang | Zhejiang University |
| Qiaosheng Zhang | Shanghai Artificial Intelligence Laboratory|
|Xueyan Niu | Theory Lab, 2012 Labs, Huawei Technologies |


Prof. Raymond W. Yeung (Keynote)
=====

Title
-----
Proving Information Inequalities by Gaussian Elimination

Abstract
------

Proving information inequalities and identities under linear constraints on the information measures is an important problem in information theory. For this purpose, ITIP and other variant algorithms have been developed and implemented, which are all based on solving a linear program (LP). We have recently developed a symbolic computation approach that can solve such LPs very efficiently. In some cases, only the Gaussian elimination is needed without having to solve an LP. In other cases, the original LP is reduced to a much smaller LP.

Brief Biography
-----
Raymond W. Yeung is a Choh-Ming Li Professor of Information Engineering at The Chinese University of Hong Kong (CUHK). He received his B.S., M.Eng., and Ph.D. degrees from Cornell University in Electrical Engineering in 1984, 1985, and 1988, respectively. Before joining CUHK in 1991, he was a Member of Technical Staff at AT&T Bell Laboratories. He has been serving as Co-Director of the Institute of Network Coding at CUHK since 2010. He is the author of the books A First Course in Information Theory (Kluwer Academic/Plenum Publishers, 2002) and Information Theory and Network Coding (Springer 2008), which have been adopted by over 100 institutions around the world. In spring 2014, he gave the first MOOC in the world on information theory that reached over 60,000 students to date.

He is a recipient of the 2005 IEEE Information Theory Society Paper Award, the Friedrich Wilhelm Bessel Research Award from the Alexander von Humboldt Foundation in 2007, the 2016 IEEE Eric E. Sumner Award, the 2018 ACM SIGMOBILE Test-of-Time Paper Award, the 2021 IEEE Richard W. Hamming Medal, and the 2022 Claude E. Shannon Award. In 2015, he was named an Outstanding Overseas Chinese Information Theorist by the China Information Theory Society. He is a Fellow of the IEEE, Hong Kong Academy of Engineering Sciences, Hong Kong Institution of Engineers, and the US National Academy of Inventors.

Prof. En-Hui Yang (Online, Keynote)
=====
Title
-----
Information Theory Inspired Deep Learning

Abstract
-----
As deep learning-based artificial intelligence (AI) pushes our information age to a new high, is it possible for information theory (IT) to jump on the bandwagon? In this talk, we will provide an affirmative answer to this question by introducing IT concepts and optimization techniques into deep learning (DL) and presenting several IT inspired deep learning paradigms. It is shown that (1) conditional mutual information (CMI) can be used to measure the concentration of a classification deep neural network (DNN) in the output probability distribution space of the DNN, and (2) optimization techniques in rate distortion function and channel capacity can be modified to minimize (maximize, resp.) CMI along with minimizing the standard cross entropy function in DL, yielding CMI constrained deep learning (CMIC-DL), knowledge distillation (KD) resistant DL, and KD-amplifying DL. Extensive experiment results show that DNNs trained within these IT inspired DL paradigms outperform the state-of-the-art models trained within the standard DL and other loss functions in the literature.

Short Bio
-----
Since 1997, he has been with the Dept. of Electrical and Computer Engineering, University of Waterloo, Ontario, Canada, where he is now a University Professor and former Canada Research Chair in information theory and applications. He is the founding director of the Leitch-University of Waterloo multimedia communications lab, a co-founder of SlipStream Data Inc. (now a subsidiary of BlackBerry), and the founder of BicDroid Inc. He also serves as an Executive Council Member of China Overseas Friendship Association, an Expert Advisor for the Overseas Chinese Affairs Office of the State Council of China, an Overseas Advisor for the Overseas Chinese Affairs Office of the City of Shanghai, a Board Trustees of Huaqiao University, China, and a member of IEEE Eric E. Sumner Award Committee.

He served, inter alia, as a member of Presidential Nominating Committee of the Academy of Science of Royal Society of Canada; a Board Governor of the University of Waterloo; a member of IEEE Founders Medal Committee; a review panel member for the International Council for Science; an Evaluator for the 2017 Japan Prize; an Associate Editor for IEEE Transactions on Information Theory; a general co-chair of the 2008 IEEE International Symposium on Information Theory; a technical program vice-chair of the 2006 IEEE International Conference on Multimedia & Expo (ICME); the chair of the award committee for the 2004 Canadian Award in Telecommunications; a co-editor of the 2004 Special Issue of the IEEE Transactions on Information Theory; a co-chair of the 2003 US National Science Foundation (NSF) workshop on the interface of Information Theory and Computer Science; and a co-chair of the 2003 Canadian Workshop on Information Theory.


Prof. Cheunk Ting Li
=====

Title
-----
One-shot Coding using Poisson Processes

Abstract
-----
Finite blocklength analysis is applicable to practical communication scenarios where the message length does not approach infinity. We present an approach to proving finite blocklength coding theorems via the Poisson functional representation, which can be regarded as a mechanism capable of answering queries. Encoding and decoding operations can be performed using queries, and the error probability can be bounded via the Poisson matching lemma. This approach provides tight one-shot and finite blocklength results in various multiuser communication settings, with proofs even shorter than conventional asymptotic techniques in certain settings. This talk is based on a joint work with Venkat Anantharam (UC Berkeley): C. T. Li and V. Anantharam, "A Unified Framework for One-Shot Achievability via the Poisson Matching Lemma," IEEE Trans. Inf. Theory, vol. 67, no. 5, pp. 2624-2651, 2021.


Bio
-----
Cheuk Ting Li received the B.Sc. degree in mathematics and B.Eng. degree in information engineering from The Chinese University of Hong Kong, Hong Kong SAR, China, in 2012, and the M.S. and Ph.D. degree in electrical engineering from Stanford University, Stanford, USA, in 2014
and 2018, respectively. He was a postdoctoral scholar at the Department of Electrical Engineering and Computer Sciences, University of California, Berkeley, USA. He joined the Department of Information Engineering, The Chinese University of Hong Kong, in January 2020. His research interests include simulation of random sources and channels, one-shot and finite-blocklength schemes in information theory, network information theory, and automated theorem proving. He was awarded the 2016 IEEE Jack Keil Wolf ISIT Student Paper Award, and the 2023 Information Theory Society Paper Award.


Dr. Qiaosheng Zhang
=====

Title
-----
Information-Directed Sampling: An Information-Theoretic Method for Reinforcement Learning

Abstract
-----
Reinforcement learning (RL) is a crucial and rapidly developing field in modern AI, with applications spanning various real-world scenarios such as LLMs, games, and robotics. A central challenge in RL is to address the exploration-exploitation tradeoff, which is not only an elegant theoretical problem but also a key factor affecting its practicality and efficiency. This talk will introduce an information-theory-inspired method, called information-directed sampling (IDS), that effectively addresses the exploration-exploitation tradeoff. In this method, we use mutual information to measure the amount of information that can be learned about the environment, and leverage rate-distortion theory to compress the environment to reduce complexity. IDS then seeks a balance between the amount of learned information (exploration) and the immediate reward (exploitation). Theoretically, IDS is nearly order-optimal in terms of data efficiency in RL and related problems like multi-armed bandits and multi-agent RL, in the sense that its regret approaches information-theoretic lower bounds. This practice not only advances the development of efficient algorithms for RL, but also showcases how information-theoretical insights can drive practical advancements in modern AI.

Bio:
-----
Qiaosheng (Eric) Zhang is a Researcher at the Shanghai Artificial Intelligence Laboratory. He received his B.Eng. (Hons.) and Ph.D. degrees from the Department of Information Engineering at the Chinese University of Hong Kong (CUHK) in 2015 and 2019, respectively. From 2019 to 2022, he was a Research Fellow at the National University of Singapore (NUS) and subsequently a researcher at Huawei Theory Lab. He is a recipient of Excellent Young Scientists Fund Program (Overseas) of NSFC. His research interests lie broadly in the span of information theory and machine learning. His recent work primarily focuses on exploring the mathematical underpinnings and developing novel algorithms for data science problems such as reinforcement learning and community detection.


Prof. Shih-Chun Lin  
=====

Title
-----
Optimal Finite-length Linear Codes for Broadcast Packet Erasure Channels with Feedback

Abstract
-----
With the recent emergence of many low-latency applications over wireless networks, the need for accurate finite-length analysis of channel coding over multi-user wireless channels is ever increasing. This talk focuses exclusively on the two-user broadcast packet erasure channel (PEC) with causal feedback, for which existing results show that various linear network coding (LNC) schemes can attain the broadcast capacity region when the block length approaches infinity. Complementing the well known asymptotic capacity based analysis, this work derives the exact value of the optimal second-order achievabilty among all possible LNCs which closes the gap between the state-of-the-art LNC second-order inner and outer bounds. A byproduct of the results is to show that among many existing asymptotically capacity-achieving LNC schemes, one (class) of them is provably finite-length optimal and should be the default design choice for any two-user broadcast PECs. Extensions to vector LNCs as well as their connections to finite-length non-linear codes will also be explored.

Bio
-----
Shih-Chun Lin (Senior Member, IEEE) received the B.S. and Ph.D. degrees in electrical engineering from National Taiwan University, Taipei, Taiwan, in 2000 and 2007, respectively. He was a Visiting Student with The Ohio State University, Columbus, OH, USA, in 2007. From 2011 to 2012, he was with the National Taipei University of Technology. From 2012 to 2021, he was with the National Taiwan University of Science and Technology, Taipei, Taiwan. In August 2021, he joined National Taiwan University, where he is currently a Professor. His research interests include information theory, communications, and cyber-physical security. He received the Best Paper Award for Young Authors from the IEEE IT/COM Society Taipei/Tainan Chapter in 2015 and twice the Project for Excellent Junior Research Investigators from the Ministry of Science and Technology, Taiwan, in 2015 and 2018. In 2024, he also received award from MediaTek Inc. due to outstanding research achievements. He served as the TPC Co-Chair for IEEE ICC Workshop on B5G-URLLC 2019 and the Publication Chair for the IEEE ISIT 2023 and IEEE Globecom 2020.


Prof. Shenghui Song
=====

Title
-----
Fundamental Limits of Large-Scale MIMO Systems: A Random Matrix Theory Perspective

Abstract
-----
Wireless communications have evolved through several generations and the basic trend is to explore more spectrum (from sub-6G to mmWave and THz) and improve the spectral efficiency (denser cells and larger antenna arrays, e.g., massive/extra-large/holographic MIMO). To fully exploit the potential of large-scale MIMO systems, we need to accurately characterize their fundamental limits. However, the high dimensionality makes performance evaluation and system design very challenging. Fortunately, many information-theoretic problems for MIMO systems resort to the spectral analysis of channel matrices, which can be tackled by asymptotic random matrix theory (RMT). Notably, the mutual information (MI) of MIMO fading channels is a special case of linear spectral statistics where the ergodic MI and outage probability can be approximated by the central limit theorem (CLT) for the random channel matrix. In this talk, we will introduce the CLT for random matrices and its applications in large-scale MIMO systems. Specifically, we will share our results regarding the fundamental limits of several large-scale MIMO channels, including the non-Gaussian fading channels, the two-hop channels, and the two-hop wiretap channels. Furthermore, we will show how asymptotic RMT can facilitate the finite block-length (FBL) analysis of large-scale MIMO systems. The RMT framework introduced for the performance analysis and system design of large-scale MIMO systems can be applied to other high-dimensional problems such as chaotic physics, signal processing, and theoretical machine learning.

Bio
-----
Dr. S.H. Song is now an Assistant Professor jointly appointed by the Division of Integrative Systems and Design (ISD) and the Department of Electronic and Computer Engineering (ECE) at the Hong Kong University of Science and Technology (HKUST). His research is primarily in the areas of Wireless Communications and Machine Learning with current focus on Distributed Intelligence, Semantic Communications, Machine Learning for Communications, Integrated Sensing and Communication, and Information Theory. He was named the Exemplary Reviewer for IEEE Communications Letter and served as the Tutorial Program Co-Chairs of the 2022 IEEE International Mediterranean Conference on Communications and Networking.

Dr. Song is also interested in the research on Engineering Education and served as an Associate Editor for the IEEE Transactions on Education. He has won several teaching awards at HKUST, including the Michael G. Gale Medal for Distinguished Teaching in 2018, the Best Ten Lecturers in 2013, 2015, and 2017, the School of Engineering Distinguished Teaching Award in 2012, the Teachers I Like Award in 2013, 2015, 2016, and 2017, and the MSc(Telecom) Teaching Excellent Appreciation Award in 2020-21 and 2022-23. Dr. Song was one of the honorees of the Third Faculty Recognition at HKUST in 2021.



Prof. Chia-Han Lee
=====
Title
-----
Generative AI for Wireless Communications

Abstract
-----
The success of large language models has significantly raised interest in generative models. In this talk, we will present our recent progress in utilizing generative models for the physical layer design of wireless communication systems. We will discuss various generative models including generative adversarial networks (GANs), variational autoencoders (VAEs), and diffusion models, and demonstrate their applications in federated learning, semantic communication, and joint source-channel coding for image data.

Bio:
Chia-Han Lee received the B.S. degree from National Taiwan University in 1999, the M.S. degree from the University of Michigan, Ann Arbor, in 2003, and the Ph.D. degree from Princeton University in 2008, all in electrical engineering. From 1999 to 2001, he served in the ROC Army as a Missile Operation Officer. From 2008 to 2009, he was a Postdoctoral Research Associate with the University of Notre Dame, USA. From 2010 to 2016, he was with Academia Sinica as an Assistant Research Fellow and then an Associate Research Fellow. In 2016, he joined National Yang Ming Chiao Tung University as an Associate Professor and Hwa Tse Roger Liang Junior Chair Professor (2018-2019), and became a Professor in 2019. Since 2022, he is an Associate Chairman of the Department of Electronics and Electrical Engineering. He received Intel Labs Distinguished Collaborative Research Awards in 2014 and was named Intel Labs Distinguished Collaborator in 2015 (for years 2010-2015). He serves as TPC Co-Chair for IEEE GLOBECOM 2025, Tutorials Co-Chair for IEEE GLOBECOM 2020, Symposium Co-Chair for IEEE GLOBECOM 2019, ICC 2021, ICC 2022, and ICC 2023, and Industry Presentations and Demonstrations Co-Chair for IEEE GLOBECOM 2017. His research focuses deep learning-based wireless communications and networks. He is an Editor of IEEE Communications Letters from 2014 to 2018, an Editor of IEEE Transactions on Wireless Communications from 2014 to 2019, an Editor of IEEE Transactions on Communications from 2019 to 2023, and an Editor of IEEE Transactions on Cognitive Communications and Networking since 2024. He is the Chair of IEEE ComSoc Taipei Chapter from 2021 to 2022.




