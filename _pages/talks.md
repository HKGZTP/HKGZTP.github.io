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

**Title: ** Proving Information Inequalities by Gaussian Elimination

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

Bio
-----
Chia-Han Lee received the B.S. degree from National Taiwan University in 1999, the M.S. degree from the University of Michigan, Ann Arbor, in 2003, and the Ph.D. degree from Princeton University in 2008, all in electrical engineering. From 1999 to 2001, he served in the ROC Army as a Missile Operation Officer. From 2008 to 2009, he was a Postdoctoral Research Associate with the University of Notre Dame, USA. From 2010 to 2016, he was with Academia Sinica as an Assistant Research Fellow and then an Associate Research Fellow. In 2016, he joined National Yang Ming Chiao Tung University as an Associate Professor and Hwa Tse Roger Liang Junior Chair Professor (2018-2019), and became a Professor in 2019. Since 2022, he is an Associate Chairman of the Department of Electronics and Electrical Engineering. He received Intel Labs Distinguished Collaborative Research Awards in 2014 and was named Intel Labs Distinguished Collaborator in 2015 (for years 2010-2015). He serves as TPC Co-Chair for IEEE GLOBECOM 2025, Tutorials Co-Chair for IEEE GLOBECOM 2020, Symposium Co-Chair for IEEE GLOBECOM 2019, ICC 2021, ICC 2022, and ICC 2023, and Industry Presentations and Demonstrations Co-Chair for IEEE GLOBECOM 2017. His research focuses deep learning-based wireless communications and networks. He is an Editor of IEEE Communications Letters from 2014 to 2018, an Editor of IEEE Transactions on Wireless Communications from 2014 to 2019, an Editor of IEEE Transactions on Communications from 2019 to 2023, and an Editor of IEEE Transactions on Cognitive Communications and Networking since 2024. He is the Chair of IEEE ComSoc Taipei Chapter from 2021 to 2022.


Prof. Antoni B. Chan
=====

Title
-----
Towards Explainable AI that Promotes AI-human Mutual Understanding

Abstract
-----
Recent advances in deep learning-based AI has necessitated better explanations on AI’s operations to enhance transparency of AI’s decisions, especially in critical systems such as self-driving car or medical diagnosis applications, to ensure safety, user trust and user satisfaction. However, current Explainable AI (XAI) solutions focus on using more AI to explain AI, without considering users’ mental processes. Here we use cognitive science theories and methodologies to develop a next-generation XAI framework that promotes human-AI mutual understanding, using computer vision AI models as examples due to its importance in critical systems. Specifically, we propose to equip XAI with an important cognitive capacity in human social interaction: theory of mind (ToM), i.e., the capacity to understand others’ behaviour by attributing mental states to them. We focus on two ToM abilities: (1) Inferring human strategy and performance (i.e., Machine’s ToM), and (2) Inferring human understanding of AI strategy and trust towards AI (i.e., to infer Human’s ToM). Computational modeling of human cognition and experimental psychology methods play an important role for XAI to develop these two ToM abilities to provide user-centered explanations through comparing users’ strategy with AI’s strategy and estimating user’s current understanding of AI’s strategy, similar to real-life teachers. Enhanced human-AI mutual understanding can in turn lead to better adoption and trust of AI systems. This framework thus highlights the importance of cognitive science approaches to XAI.

Bio
-----
Prof. Antoni B. Chan received the B.S. and M.Eng. degrees in electrical engineering from Cornell University, Ithaca, NY, USA, in 2000 and 2001, respectively, and the Ph.D. degree in electrical and computer engineering from University of California at San Diego (UCSD), La Jolla, CA, USA, in 2008. He was a Visiting Scientist with the Vision and Image Analysis Laboratory, Cornell University, from 2001 to 2003, and a Post-Doctoral Researcher with the Statistical Visual Computing Laboratory, UCSD, in 2009. In 2009 he joined the Department of Computer Science, City University of Hong Kong, Hong Kong, where he is currently a Professor. His research interests include computer vision, machine learning, explainable AI (XAI), eye-gaze analysis, and music analysis. Prof. Chan received the National Science Foundation Integrative Graduate Education and Research Training Fellowship from 2006 to 2008, and an Early Career Award from the Research Grants Council of the Hong Kong Special Administrative Region, China, in 2012. He is currently an associate editor for IEEE Transactions on Pattern Analysis and Machine Intelligence, and serves as area chair for computer vision and machine learning conferences, including CVPR, ICCV, ECCV, NeurIPS, ICML, and ICLR.





Prof. Qianqian Yang
=====

Title
-----
Highly Efficient Semantics-Oriented Communications with Generative Modeling

Abstract
-----
In recent years, there has been a significant surge in the development and application of generative models for content generation, transforming fields such as image creation, text generation, and multimodal synthesis. This talk will showcase Dr. Yang's latest work on highly efficient semantics-oriented communications, highlighting the transformative potential of generative modeling techniques. Specifically, Dr. Yang will introduce research on semantic communication for efficient speech and image transmission, leveraging generative models to reduce the amount of transmitted information to less than 1% compared to existing methods. Additionally, we will explore a generative modeling-based evolving semantic communication system that demonstrates continuously improving performance through a caching mechanism. Finally, Dr. Yang will present a knowledge-aided semantic communication method that utilizes the correlation between semantic features captured by a probabilistic graphical model to further enhance transmission efficiency.

Bio
-----
Qianqian Yang received the Ph.D. degree in electrical and electronic engineering from Imperial College London, U.K. She has held visiting positions at CentraleSupelec in 2016 and the New York University Tandon School of Engineering from 2017 to 2018. After her Ph.D., she served as a Post-Doctoral Research Associate at Imperial College London and as a Machine Learning Researcher for Sensyne Health Plc.

She is currently a Tenure-Tracked Professor with the Department of Information Science and Electronic Engineering, Zhejiang University, China. Her main research interests include information theory, wireless AI, and semantic communication. She has served as a Symposium Chair for IEEE ICCT 2023, a local Co-Chair for IEEE WCSP 2023, and a Finance Chair for IEEE ICCC 2024. She has co-chaired a number of workshops at top conferences, including IEEE ICC 2023, ICCC 2023, VTC 2022, WCNC 2022, and HPCC 2021. She is a founding member of the IEEE SIG on Qualitative and Semantic Communication. She is the recipient of the Science and Technology Innovation First Prize from the China Technology Industrialization Promotion Association, the Outstanding Young Researcher Award from Huawei, and the ICC 2024 Workshop Best Paper Award.








Prof. Yu-Chih Huang
=====

Title
-----
Diminishing Exploration: A Minimalist Approach to Piecewise Stationary Multi-Armed Bandits

Abstract
-----
The piecewise-stationary bandit problem is an important variant of the multi-armed bandit problem that further considers abrupt changes in the reward distributions. The main theme of the problem is the trade-off between exploration for detecting environment changes and exploitation of traditional bandit algorithms. While this problem has been extensively investigated, existing works either assume knowledge about the number of change points $M$ or require extremely high computational complexity. In this work, we revisit the piecewise-stationary bandit problem from a minimalist perspective. We propose a novel and generic exploration mechanism, called diminishing exploration, which eliminates the need for knowledge about $M$ and can be used in conjunction with an existing change detection-based algorithm to achieve near-optimal regret scaling. Simulation results show that despite oblivious of $M$, equipping existing algorithms with the proposed diminishing exploration generally achieves better empirical regret than existing approaches.

Bio
-----
Yu-Chih Huang received the Ph.D. degree in electrical and computer engineering from Texas A&M University (TAMU), College Station, TX, USA, in 2013. From 2013 to 2015, he was a Postdoctoral Research Associate with TAMU. In 2015, he joined the Department of Communication Engineering, National Taipei University, Taipei, Taiwan, as an Assistant Professor and was promoted to Associate Professor in 2018. In 2020, he joined the Institute of Communications Engineering, National Yang Ming Chiao Tung University, Taiwan, where he is currently a Professor. His research interests include information theory, coding theory, wireless communications, and machine learning. He was the recipient of the National Science and Technology Council Wu Ta-You Memorial Award in 2023, Ministry of Science and Technology Young Scholar Fellowship in 2020, and the 2018 IEEE Information Theory Society Taipei Chapter and IEEE Communications Society Taipei/Tainan Chapter’s Best Paper Award for Young Scholars. He is currently an Associate Editor for IEEE Transactions on Communications and IEEE Communications Letters.


Dr. Xueyan Niu
=====

Title
-----
Exploring Strengths and Weaknesses of Transformers Through the Lens of Information Theory 

Abstract
-----
With the advent of ChatGPT, Transformer-based Large Language Models (LLMs) are receiving widespread attention from both academia and industry. OpenAI's scaling law predicts that training larger models with more data can lead to better performance. Based on this, the parameter scale of recent large models can reach the level of hundreds of billions and are trained on text data at the scale of hundreds of billions. However, increasing the size of the Transformer model does not always lead to performance improvement—a phenomenon that cannot be explained by the empirical scaling law. In addition, when the model memorizes training samples, its generalization ability is enhanced. This report will briefly introduce our preliminary exploration in the theoretical modeling of Transformer models. We simulate the behavior of Transformers using Hopfield networks, linking them to associative memory, allowing each Transformer block to perform approximate nearest neighbor searches. Based on this, we propose a new energy function that reveals a dependency between model size and datasets under certain conditions. We also discuss our recent work on extending the context window of LLMs through the lens of information theory. 

Bio
-----
Xueyan Niu is a Principal Engineer at Theory Lab, 2012 Labs, Huawei Technologies. She received the Ph.D. degree from Purdue University in 2021, and the B.S. degree in Mathematics and Applied Mathematics from Peking University in 2016. She was previously affiliated with the Cognitive Computing Lab at Baidu Research. Her research is centered on information theory and semantic communication, encompassing machine learning domains such as language models, image processing, and video compression. Her work has been published in top information theory journals like IEEE Transactions on Information Theory and at leading artificial intelligence conferences such as IJCAI and ACL. Her research in partial information decomposition has been recognized with an Outstanding Early Career Researcher Paper Award. She serves as a guest editor for the special issue on Goal-Oriented Semantic Communication in IEEE Network and as a reviewer for international conferences such as NeurIPS, ICML, ICLR, ISIT, and GLOBECOM. 


