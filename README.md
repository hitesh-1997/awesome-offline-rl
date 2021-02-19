# awesome-offline-rl
This is a collection of research and review papers for **offline reinforcement learning (offline rl)**. Feel free to star and fork.


Maintainers:
- Haruka Kiyohara (Tokyo Institute of Technology)
- [Yuta Saito](http://usaito.github.io/) (Hanjuku-kaso Co., Ltd.)

We are looking for more contributors and maintainers! Please feel free to [pull requests](https://github.com/usaito/awesome-offline-rl/pulls).

```
format: [title](paper link) by authors, arXiv/conferences/jornals/, year. [links]
```

For any question, feel free to contact: saito@hanjuku-kaso.com


## Papers

### Review Papers

- [Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems](https://arxiv.org/abs/2005.01643) by Sergey Levine, Aviral Kumar, George Tucker, and Justin Fu, arXiv2020.

### Offline RL: Theory/Methods
- [Continuous Doubly Constrained Batch Reinforcement Learning](https://arxiv.org/abs/2102.09225) by Rasool Fakoor, Jonas Mueller, Pratik Chaudhari and Alexander J. Smola, arXiv2021.
- [COMBO: Conservative Offline Model-Based Policy Optimization](https://arxiv.org/abs/2102.08363) by Tianhe Yu, Aviral Kumar, Rafael Rafailov, Aravind Rajeswaran, Sergey Levine and Chelsea Finn, arXiv2021.
- [Representation Matters: Offline Pretraining for Sequential Decision Making](https://arxiv.org/abs/2102.05815) by Mengjiao Yang and Ofir Nachum, arXiv2021.
- [Q-Value Weighted Regression: Reinforcement Learning with Limited Data](https://arxiv.org/abs/2102.06782) by Piotr Kozakowski, Łukasz Kaiser, Henryk Michalewski, Afroz Mohiuddin and Katarzyna Kańska, arXiv2021.
- [PerSim: Data-Efficient Offline Reinforcement Learning with Heterogeneous Agents via Personalized Simulators](https://arxiv.org/abs/2102.06961) by Anish Agarwal, Abdullah Alomar, Varkey Alumootil, Devavrat Shah, Dennis Shen, Zhi Xu and Cindy Yang, arXiv2021.
- [Risk-Averse Offline Reinforcement Learning](https://arxiv.org/abs/2102.05371) by Núria Armengol Urpí, Sebastian Curi and Andreas Krause, arXiv2021.
- [Finite Sample Analysis of Minimax Offline Reinforcement Learning: Completeness, Fast Rates and First-Order Efficiency](https://arxiv.org/abs/2102.02981) by Masatoshi Uehara, Masaaki Imaizumi, Nan Jiang, Nathan Kallus, Wen Sun and Tengyang Xie, arXiv2021.
- [Fast Rates for the Regret of Offline Reinforcement Learning](https://arxiv.org/abs/2102.00479) by Yichun Hu, Nathan Kallus and Masatoshi Uehara, arXiv2021.
- [Near-Optimal Offline Reinforcement Learning via Double Variance Reduction](https://arxiv.org/abs/2102.01748) by Ming Yin, Yu Bai and Yu-Xiang Wang, arXiv2021.
- [Identifying Decision Points for Safe and Interpretable Reinforcement Learning in Hypotension Treatment](https://arxiv.org/abs/2101.03309) by Kristine Zhang, Yuanheng Wang, Jianzhun Du, Brian Chu, Leo Anthony Celi, Ryan Kindle and Finale Doshi-Velez, arXiv2021.
- [Batch Reinforcement Learning Through Continuation Method](https://openreview.net/forum?id=po-DLlBuAuz) by Yijie Guo, Shengyu Feng, Nicolas Le Roux, Ed Chi, Honglak Lee and Minmin Chen, ICLR2021.
- [Model-Based Visual Planning with Self-Supervised Functional Distances](https://openreview.net/forum?id=UcoXdfrORC) by Stephen Tian, Suraj Nair, Frederik Ebert, Sudeep Dasari, Benjamin Eysenbach, Chelsea Finn and Sergey Levine, ICLR2021.
- [Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://openreview.net/forum?id=3hGNqpI4WS) by Tatsuya Matsushima, Hiroki Furuta, Yutaka Matsuo, Ofir Nachum and Shixiang Gu, ICLR2021.
- [Efficient Fully-Offline Meta-Reinforcement Learning via Distance Metric Learning and Behavior Regularization](https://openreview.net/forum?id=8cpHIfgY4Dj) by Lanqing Li, Rui Yang and Dijun Luo, ICLR2021.
- [DeepAveragers: Offline Reinforcement Learning by Solving Derived Non-Parametric MDPs](https://openreview.net/forum?id=eMP1j9efXtX) by Aayam Kumar Shrestha, Stefan Lee, Prasad Tadepalli and Alan Fern, ICLR2021.
- [What are the Statistical Limits of Offline RL with Linear Function Approximation?](https://openreview.net/forum?id=30EvkP2aQLD) by Ruosong Wang, Dean Foster and Sham M. Kakade, ICLR2021.
- [Reset-Free Lifelong Learning with Skill-Space Planning](https://openreview.net/forum?id=HIGSa_3kOx3) by Kevin Lu, Aditya Grover, Pieter Abbeel and Igor Mordatch, ICLR2021. [[website](https://sites.google.com/berkeley.edu/reset-free-lifelong-learning)]
- [Exploration by Maximizing Rényi Entropy for Reward-Free RL Framework](https://arxiv.org/abs/2006.06193) by Chuheng Zhang, Yuanying Cai, Longbo Huang and Jian Li, AAAI2021.
- [Finite-Sample Analysis For Decentralized Batch Multi-Agent Reinforcement Learning With Networked Agents](https://arxiv.org/abs/1812.02783) by Kaiqing Zhang, Zhuoran Yang, Han Liu, Tong Zhang and Tamer Başar, IEEE T AUTOMATIC CONTROL2021.
- [Exponential Lower Bounds for Batch Reinforcement Learning: Batch RL can be Exponentially Harder than Online RL](https://arxiv.org/abs/2012.08005) by Andrea Zanette, arXiv2020.
- [Sparse Feature Selection Makes Batch Reinforcement Learning More Sample Efficient](https://arxiv.org/abs/2011.04019) by Botao Hao, Yaqi Duan, Tor Lattimore, Csaba Szepesvári and Mengdi Wang, arXiv2020.
- [A Variant of the Wang-Foster-Kakade Lower Bound for the Discounted Setting](https://arxiv.org/abs/2011.01075) by Philip Amortila, Nan Jiang and Tengyang Xie, arXiv2020.
- [Batch Reinforcement Learning with a Nonparametric Off-Policy Policy Gradient](https://arxiv.org/abs/2010.14771) by Samuele Tosatto, João Carvalho and Jan Peters, arXiv2020.
- [Batch Value-function Approximation with Only Realizability](https://arxiv.org/abs/2008.04990) by Tengyang Xie and Nan Jiang, arXiv2020.
- [DRIFT: Deep Reinforcement Learning for Functional Software Testing](https://arxiv.org/abs/2007.08220) by Luke Harries, Rebekah Storan Clarke, Timothy Chapman, Swamy V. P. L. N. Nallamalli, Levent Ozgur, Shuktika Jain, Alex Leung, Steve Lim, Aaron Dietrich, José Miguel Hernández-Lobato, Tom Ellis, Cheng Zhang and Kamil Ciosek, arXiv2020.
- [Causality and Batch Reinforcement Learning: Complementary Approaches To Planning In Unknown Domains](https://arxiv.org/abs/2006.02579) by James Bannon, Brad Windsor, Wenbo Song and Tao Li, arXiv2020.
- [Goal-conditioned Batch Reinforcement Learning for Rotation Invariant Locomotion](https://arxiv.org/abs/2004.08356) by Aditi Mavalankar, arXiv2020. [[code](https://github.com/aditimavalankar/gc-batch-rl-locomotion)]
- [Semi-Supervised Reward Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2012.06899) by Ksenia Konyushkova, Konrad Zolna, Yusuf Aytar, Alexander Novikov, Scott Reed, Serkan Cabi and Nando de Freitas, arXiv2020.
- [Sample-Efficient Reinforcement Learning via Counterfactual-Based Data Augmentation](https://arxiv.org/abs/2012.09092) by Chaochao Lu, Biwei Huang, Ke Wang, José Miguel Hernández-Lobato, Kun Zhang and Bernhard Schölkopf, arXiv2020.
- [Offline Reinforcement Learning from Images with Latent Space Models](https://arxiv.org/abs/2012.11547) by Rafael Rafailov, Tianhe Yu, Aravind Rajeswaran and Chelsea Finn, arXiv2020. [[website](https://sites.google.com/view/lompo/)]
- [POPO: Pessimistic Offline Policy Optimization](https://arxiv.org/abs/2012.13682) by Qiang He and Xinwen Hou, arXiv2020.
- [Is Pessimism Provably Efficient for Offline RL?](https://arxiv.org/abs/2012.15085) by Ying Jin, Zhuoran Yang and Zhaoran Wang, arXiv2020.
- [Reinforcement Learning with Videos: Combining Offline Observations with Interaction](https://arxiv.org/abs/2011.06507) by Karl Schmeckpeper, Oleh Rybkin, Kostas Daniilidis, Sergey Levine and Chelsea Finn, arXiv2020.
- [Recovery RL: Safe Reinforcement Learning with Learned Recovery Zones](https://arxiv.org/abs/2010.15920) by Brijen Thananjeyan, Ashwin Balakrishna, Suraj Nair, Michael Luo, Krishnan Srinivasan, Minho Hwang, Joseph E. Gonzalez, Julian Ibarz, Chelsea Finn and Ken Goldberg, arXiv2020. [[website](https://sites.google.com/berkeley.edu/recovery-rl/)]
- [Implicit Under-Parameterization Inhibits Data-Efficient Deep Reinforcement Learning](https://arxiv.org/abs/2010.14498) by Aviral Kumar, Rishabh Agarwal, Dibya Ghosh and Sergey Levine, arXiv2020.
- [OPAL: Offline Primitive Discovery for Accelerating Offline Reinforcement Learning](https://arxiv.org/abs/2010.13611) by Anurag Ajay, Aviral Kumar, Pulkit Agrawal, Sergey Levine and Ofir Nachum, arXiv2020. [[website](https://sites.google.com/view/opal-iclr)]
- [Batch Exploration with Examples for Scalable Robotic Reinforcement Learning](https://arxiv.org/abs/2010.11917) by Annie S. Chen, HyunJi Nam, Suraj Nair and Chelsea Finn, arXiv2020.
- [Learning Dexterous Manipulation from Suboptimal Experts](https://arxiv.org/abs/2010.08587) by Rae Jeong, Jost Tobias Springenberg, Jackie Kay, Daniel Zheng, Yuxiang Zhou, Alexandre Galashov, Nicolas Heess and Francesco Nori, arXiv2020. [[website](https://sites.google.com/view/rlfse)]
- [The Reinforcement Learning-Based Multi-Agent Cooperative Approach for the Adaptive Speed Regulation on a Metallurgical Pickling Line](https://arxiv.org/abs/2008.06933) by Anna Bogomolova, Kseniia Kingsep and Boris Voskresenskii, arXiv2020.
- [Offline Meta-Reinforcement Learning with Advantage Weighting](https://arxiv.org/abs/2008.06043) by Eric Mitchell, Rafael Rafailov, Xue Bin Peng, Sergey Levine and Chelsea Finn, arXiv2020.
- [Model-Based Offline Planning](https://arxiv.org/abs/2008.05556) by Arthur Argenson and Gabriel Dulac-Arnold, arXiv2020. [[video](https://www.youtube.com/watch?v=nxGGHdZOFts&feature=youtu.be)]
- [Overcoming Model Bias for Robust Offline Deep Reinforcement Learning](https://arxiv.org/abs/2008.05533) by Phillip Swazinna, Steffen Udluft and Thomas Runkler, arXiv2020.
- [Offline Meta Learning of Exploration](https://arxiv.org/abs/2008.02598) by Ron Dorfman, Idan Shenfeld and Aviv Tamar, arXiv2020.
- [EMaQ: Expected-Max Q-Learning Operator for Simple Yet Effective Offline and Online RL](https://arxiv.org/abs/2007.11091) by Seyed Kamyar Seyed Ghasemipour, Dale Schuurmans and Shixiang Shane Gu, arXiv2020.
- [Hyperparameter Selection for Offline Reinforcement Learning](https://arxiv.org/abs/2007.09055) by Tom Le Paine, Cosmin Paduraru, Andrea Michi, Caglar Gulcehre, Konrad Zolna, Alexander Novikov, Ziyu Wang and Nando de Freitas, arXiv2020.
- [Interpretable Control by Reinforcement Learning](https://arxiv.org/abs/2007.09964) by Daniel Hein, Steffen Limmer and Thomas A. Runkler, arXiv2020.
- [Efficient Evaluation of Natural Stochastic Policies in Offline Reinforcement Learning](https://arxiv.org/abs/2006.03886) by Nathan Kallus and Masatoshi Uehara, arXiv2020. [[code](https://github.com/CausalML/NaturalStochasticOPE)]
- [Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359) by Ashvin Nair, Murtaza Dalal, Abhishek Gupta and Sergey Levine, arXiv2020. [[website](https://awacrl.github.io/)]
- [DisCor: Corrective Feedback in Reinforcement Learning via Distribution Correction](https://arxiv.org/abs/2003.07305) by Aviral Kumar, Abhishek Gupta and Sergey Levine, arXiv2020.
- [Doubly Robust Off-Policy Value and Gradient Estimation for Deterministic Policies](https://papers.nips.cc/paper/2020/hash/75df63609809c7a2052fdffe5c00a84e-Abstract.html) by Nathan Kallus and Masatoshi Uehara, NeurIPS2020.
- [Critic Regularized Regression](https://proceedings.neurips.cc/paper/2020/hash/588cb956d6bbe67078f29f8de420a13d-Abstract.html) by Ziyu Wang, Alexander Novikov, Konrad Zolna, Josh S. Merel, Jost Tobias Springenberg, Scott E. Reed, Bobak Shahriari, Noah Siegel, Caglar Gulcehre, Nicolas Heess and Nando de Freitas, NeurIPS2020
- [Provably Good Batch Off-Policy Reinforcement Learning Without Great Exploration](https://papers.nips.cc/paper/2020/hash/0dc23b6a0e4abc39904388dd3ffadcd1-Abstract.html) by Yao Liu, Adith Swaminathan, Alekh Agarwal and Emma Brunskill, NeurIPS2020.
- [Conservative Q-Learning for Offline Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/0d2b2061826a5df3221116a5085a6052-Abstract.html) by Aviral Kumar, Aurick Zhou, George Tucker, and Sergey Levine, NeurIPS2020. [[website](https://sites.google.com/view/cql-offline-rl)] [[code](https://github.com/aviralkumar2907/CQL)]
- [BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/d55cbf210f175f4a37916eafe6c04f0d-Abstract.html) by Xinyue Chen, Zijian Zhou, Zheng Wang, Che Wang, Yanqiu Wu and Keith Ross, NeurIPS2020.
- [MOPO: Model-based Offline Policy Optimization](https://papers.nips.cc/paper/2020/hash/a322852ce0df73e204b7e67cbbef0d0a-Abstract.html) by Tianhe Yu, Garrett Thomas, Lantao Yu, Stefano Ermon, James Y. Zou, Sergey Levine, Chelsea Finn and Tengyu Ma, NeurIPS2020. [[code](https://github.com/tianheyu927/mopo)]
- [MOReL: Model-Based Offline Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/f7efa4f864ae9b88d43527f4b14f750f-Abstract.html) by Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli and Thorsten Joachims, NeurIPS2020.
- [Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation](https://papers.nips.cc/paper/2020/hash/daf642455364613e2120c636b5a1f9c7-Abstract.html) by Aaron Sonabend, Junwei Lu, Leo Anthony Celi, Tianxi Cai and Peter Szolovits, NeurIPS2020.
- [Multi-task Batch Reinforcement Learning with Metric Learning](https://papers.nips.cc/paper/2020/hash/4496bf24afe7fab6f046bf4923da8de6-Abstract.html) by Jiachen Li, Quan Vuong, Shuang Liu, Minghua Liu, Kamil Ciosek, Henrik Christensen and Hao Su, NeurIPS2020.
- [Counterfactual Data Augmentation using Locally Factored Dynamics](https://papers.nips.cc/paper/2020/hash/294e09f267683c7ddc6cc5134a7e68a8-Abstract.html) by Silviu Pitis, Elliot Creager and Animesh Garg, NeurIPS2020. [[code](https://github.com/spitis/mrl)]
- [On Reward-Free Reinforcement Learning with Linear Function Approximation](https://papers.nips.cc/paper/2020/hash/ce4449660c6523b377b22a1dc2da5556-Abstract.html) by Ruosong Wang, Simon S. Du, Lin Yang and Russ R. Salakhutdinov, NeurIPS2020.
- [Constrained Policy Improvement for Safe and Efficient Reinforcement Learning](https://www.ijcai.org/Proceedings/2020/396) by Elad Sarafian, Aviv Tamar and Sarit Kraus, IJCAI2020.
- [BRPO: Batch Residual Policy Optimization](https://www.ijcai.org/Proceedings/2020/391) by Sungryull Sohn, Yinlam Chow, Jayden Ooi, Ofir Nachum, Honglak Lee, Ed Chi and Craig Boutilier, IJCAI2020. [[code](https://github.com/eladsar/rbi)]
- [From Importance Sampling to Doubly Robust Policy Gradient](http://proceedings.mlr.press/v119/huang20b.html) by Jiawei Huang and Nan Jiang, ICML2020.
- [Batch Stationary Distribution Estimation](http://proceedings.mlr.press/v119/wen20a.html) by Junfeng Wen, Bo Dai, Lihong Li and Dale Schuurmans, ICML2020.
- [GradientDICE: Rethinking Generalized Offline Estimation of Stationary Values](http://proceedings.mlr.press/v119/zhang20r.html) by Shangtong Zhang, Bo Liu and Shimon Whiteson, ICML2020.
- [GenDICE: Generalized Offline Estimation of Stationary Values](https://openreview.net/forum?id=HkxlcnVFwB) by Ruiyi Zhang, Bo Dai, Lihong Li and Dale Schuurmans, ICLR2020.
- [Keep Doing What Worked: Behavior Modelling Priors for Offline Reinforcement Learning](https://openreview.net/forum?id=rke7geHtwH) by Noah Siegel, Jost Tobias Springenberg, Felix Berkenkamp, Abbas Abdolmaleki, Michael Neunert, Thomas Lampe, Roland Hafner, Nicolas Heess and Martin Riedmiller, ICLR2020.
- [Accelerating Reinforcement Learning with Learned Skill Priors](https://arxiv.org/abs/2010.11944) by Karl Pertsch, Youngwoon Lee and Joseph J. Lim, CoRL2020.
- [Scaling data-driven robotics with reward sketching and batch reinforcement learning](https://arxiv.org/abs/1909.12200) by Serkan Cabi, Sergio Gómez Colmenarejo, Alexander Novikov, Ksenia Konyushkova, Scott Reed, Rae Jeong, Konrad Zolna, Yusuf Aytar, David Budden, Mel Vecerik, Oleg Sushkov, David Barker, Jonathan Scholz, Misha Denil, Nando de Freitas and Ziyu Wang, RSS2020. [[website](https://sites.google.com/view/data-driven-robotics/)]
- [Quantile QT-Opt for Risk-Aware Vision-Based Robotic Grasping](https://arxiv.org/abs/1910.02787) by Cristian Bodnar, Adrian Li, Karol Hausman, Peter Pastor and Mrinal Kalakrishnan, RSS2020.
- [Defining Admissible Rewards for High Confidence Policy Evaluation in Batch Reinforcement Learning](https://dl.acm.org/doi/abs/10.1145/3368555.3384450) by Niranjani Prasad, Barbara E Engelhardt and Finale Doshi-Velez, CHIL2020.
- [Learning When-to-Treat Policies](https://arxiv.org/abs/1905.09751) by Xinkun Nie, Emma Brunskill and Stefan Wager, JASA2020.
- [Batch-Constrained Reinforcement Learning for Dynamic Distribution Network Reconfiguration](https://arxiv.org/abs/2006.12749) by Yuanqi Gao, Wei Wang, Jie Shi and Nanpeng Yu, IEEE T SMART GRID2020.
- [Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog](https://arxiv.org/abs/1907.00456) by Natasha Jaques, Asma Ghandeharioun, Judy Hanwen Shen, Craig Ferguson, Agata Lapedriza, Noah Jones, Shixiang Gu and Rosalind Picard, arXiv2019.
- [Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/abs/1911.11361) by Yifan Wu, George Tucker and Ofir Nachum, arXiv2019.
- [Off-Policy Policy Gradient Algorithms by Constraining the State Distribution Shift](https://arxiv.org/abs/1911.06970) by Riashat Islam, Komal K. Teru, Deepak Sharma and Joelle Pineau, arXiv2019.
- [Advantage-Weighted Regression: Simple and Scalable Off-Policy Reinforcement Learning](https://arxiv.org/abs/1910.00177) by Xue Bin Peng, Aviral Kumar, Grace Zhang and Sergey Levine, arXiv2019.
- [AlgaeDICE: Policy Gradient from Arbitrary Experience](https://arxiv.org/abs/1912.02074) by Ofir Nachum, Bo Dai, Ilya Kostrikov, Yinlam Chow, Lihong Li and Dale Schuurmans, arXiv2019.
- [Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://papers.nips.cc/paper/2019/hash/c2073ffa77b5357a498057413bb09d3a-Abstract.html) by Aviral Kumar, Justin Fu, George Tucker,  and Sergey Levine, NeurIPS2019. [[website](https://sites.google.com/view/bear-off-policyrl)] [[code](https://github.com/aviralkumar2907/BEAR)]
- [Off-Policy Deep Reinforcement Learning without Exploration](http://proceedings.mlr.press/v97/fujimoto19a.html) by Scott Fujimoto, David Meger and Doina Precup, ICML2019.
- [Safe Policy Improvement with Baseline Bootstrapping](http://proceedings.mlr.press/v97/laroche19a.html) by Romain Laroche, Paul Trichelair and Remi Tachet Des Combes, ICML2019.
- [Information-Theoretic Considerations in Batch Reinforcement Learning](http://proceedings.mlr.press/v97/chen19e.html) by Jinglin Chen and Nan Jiang, ICML2019.
- [Batch Recurrent Q-Learning for Backchannel Generation Towards Engaging Agents](https://arxiv.org/abs/1908.02037) by Nusrah Hussain, Engin Erzin, T. Metin Sezgin and Yucel Yemez, ACII2019.
- [Safe Policy Improvement with Soft Baseline Bootstrapping](https://arxiv.org/abs/1907.05079) by Kimia Nadjahi, Romain Laroche and Rémi Tachet des Combes, ECML2019.
- [Importance Weighted Transfer of Samples in Reinforcement Learning](http://proceedings.mlr.press/v80/tirinzoni18a.html) by Andrea Tirinzoni, Andrea Sessa, Matteo Pirotta and Marcello Restelli, ICML2018.
- [Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation](http://proceedings.mlr.press/v87/kalashnikov18a.html) by Dmitry Kalashnikov, Alex Irpan, Peter Pastor, Julian Ibarz, Alexander Herzog, Eric Jang, Deirdre Quillen, Ethan Holly, Mrinal Kalakrishnan, Vincent Vanhoucke and Sergey Levine, CoRL2018. [[website](https://sites.google.com/view/qtopt)]
- [Off-Policy Policy Gradient with State Distribution Correction](https://arxiv.org/abs/1904.08473) by Yao Liu, Adith Swaminathan, Alekh Agarwal and Emma Brunskill, UAI2018.
- [Deep Exploration via Bootstrapped DQN](https://papers.nips.cc/paper/2016/hash/8d8818c8e140c64c743113f563cf750f-Abstract.html) by Ian Osband, Charles Blundell, Alexander Pritzel and Benjamin Van Roy, NeurIPS2016.
- [Safe Policy Improvement by Minimizing Robust Baseline Regret](https://proceedings.neurips.cc/paper/2016/hash/9a3d458322d70046f63dfd8b0153ece4-Abstract.html) by Mohammad Ghavamzadeh, Marek Petrik and Yinlam Chow, NeurIPS2016.
- [Residential Demand Response Applications Using Batch Reinforcement Learning](https://arxiv.org/abs/1504.02125) by Frederik Ruelens, Bert Claessens, Stijn Vandael, Bart De Schutter, Robert Babuska and Ronnie Belmans, arXiv2015.
- [Structural Return Maximization for Reinforcement Learning](https://arxiv.org/abs/1405.2606) by Joshua Joseph, Javier Velez and Nicholas Roy, arXiv2014.
- [Simultaneous Perturbation Algorithms for Batch Off-Policy Search](https://arxiv.org/abs/1403.4514) by Raphael Fonteneau and L.A. Prashanth, CDC2014.
- [Guided Policy Search](http://proceedings.mlr.press/v28/levine13.html) by Sergey Levine and Vladlen Koltun, ICML2013.
- [Off-Policy Actor-Critic](https://dl.acm.org/doi/10.5555/3042573.3042600) by Thomas Degris, Martha White and Richard S. Sutton, ICML2012.
- [PAC-Bayesian Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/1202.3717) by Mahdi MIlani Fard, Joelle Pineau and Csaba Szepesvari, UAI2011.
- [Tree-Based Batch Mode Reinforcement Learning](https://www.jmlr.org/papers/v6/ernst05a.html) by Damien Ernst, Pierre Geurts and Louis Wehenkel, JMLR2005.
- [Neural Fitted Q Iteration–First Experiences with a Data Efficient Neural Reinforcement Learning Method](https://dl.acm.org/doi/10.1007/11564096_32) by Martin Riedmiller, ECML2005.
- [Off-Policy Temporal-Difference Learning with Function Approximation](https://dl.acm.org/doi/10.5555/645530.655817) by Doina Precup, Richard S. Sutton and Sanjoy Dasgupta, ICML2001.

### Offline RL: Benchmarks/Experiments/Applications
- [Personalization for Web-based Services using Offline Reinforcement Learning](https://arxiv.org/abs/2102.05612) by Pavlos Athanasios Apostolopoulos, Zehui Wang, Hanson Wang, Chad Zhou, Kittipat Virochsiri, Norm Zhou and Igor L. Markov, arXiv2021.
- [NeoRL: A Near Real-World Benchmark for Offline Reinforcement Learning](https://arxiv.org/abs/2102.00714) by Rongjun Qin, Songyi Gao, Xingyuan Zhang, Zhen Xu, Shengkai Huang, Zewen Li, Weinan Zhang and Yang Yu, arXiv2021. [[website](http://polixir.ai/research/neorl)]
- [Batch-Constrained Distributional Reinforcement Learning for Session-based Recommendation](https://arxiv.org/abs/2012.08984) by Diksha Garg, Priyanka Gupta, Pankaj Malhotra, Lovekesh Vig and Gautam Shroff, arXiv2020.
- [An Empirical Study of Representation Learning for Reinforcement Learning in Healthcare](https://arxiv.org/abs/2011.11235) by Taylor W. Killian, Haoran Zhang, Jayakumar Subramanian, Mehdi Fatemi and Marzyeh Ghassemi, arXiv2020.
- [Learning from Human Feedback: Challenges for Real-World Reinforcement Learning in NLP](https://arxiv.org/abs/2011.02511) by Julia Kreutzer, Stefan Riezler and Carolin Lawrence, arXiv2020.
- [Remote Electrical Tilt Optimization via Safe Reinforcement Learning](https://arxiv.org/abs/2010.05842) by Filippo Vannella, Grigorios Iakovidis, Ezeddin Al Hakim, Erik Aumayr and Saman Feghhi, arXiv2020.
- [Offline Reinforcement Learning Hands-On](https://arxiv.org/abs/2011.14379) by Louis Monier, Jakub Kmec, Alexandre Laterre, Thomas Pierrot, Valentin Courgeau, Olivier Sigaud, Karim Beguir, arXiv2020.
- [D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://arxiv.org/abs/2004.07219) by Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker and Sergey Levine, arXiv2020. [[code](https://github.com/rail-berkeley/d4rl)]
- [RL Unplugged: Benchmarks for Offline Reinforcement Learning](https://arxiv.org/abs/2006.13888) by Caglar Gulcehre, Ziyu Wang, Alexander Novikov, Tom Le Paine, Sergio Gomez Colmenarejo, Konrad Zolna, Rishabh Agarwal, Josh Merel, Daniel Mankowitz, Cosmin Paduraru, Gabriel Dulac-Arnold, Jerry Li, Mohammad Norouzi, Matt Hoffman, Ofir Nachum, George Tucker, Nicolas Heess and Nando de Freitas, arXiv2020. [[code](https://github.com/deepmind/deepmind-research/tree/master/rl_unplugged)]
- [An Optimistic Perspective on Offline Reinforcement Learning](http://proceedings.mlr.press/v119/agarwal20c.html) by Rishabh Agarwal, Dale Schuurmans, and Mohammad Norouzi, ICML2020. [[website](https://offline-rl.github.io/)]
- [Policy Teaching via Environment Poisoning: Training-time Adversarial Attacks against Reinforcement Learning](http://proceedings.mlr.press/v119/rakhsha20a.html) by Amin Rakhsha, Goran Radanovic, Rati Devidze, Xiaojin Zhu and Adish Singla, ICML2020.
- [Off-policy Learning in Two-stage Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3366423.3380130) by Jiaqi Ma, Zhe Zhao, Xinyang Yi, Ji Yang, Minmin Chen, Jiaxi Tang, Lichan Hong and Ed H Chi, WWW2020.
- [Human-centric Dialog Training via Offline Reinforcement Learning](https://arxiv.org/abs/2010.05848) by Natasha Jaques, Judy Hanwen Shen, Asma Ghandeharioun, Craig Ferguson, Agata Lapedriza, Noah Jones, Shixiang Shane Gu and Rosalind Picard, EMNLP2020.
- [Definition and evaluation of model-free coordination of electrical vehicle charging with reinforcement learning](https://arxiv.org/abs/1809.10679) by Nasrin Sadeghianpourhamami, Johannes Deleu and Chris Develder, IEEE T SMART GRID2020.
- [Optimal Tap Setting of Voltage Regulation Transformers Using Batch Reinforcement Learning](https://arxiv.org/abs/1807.10997) by Hanchen Xu, Alejandro D. Domínguez-García and Peter W. Sauer, IEEE T POWER SYSTEMS2020.
- [Benchmarking Batch Deep Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.01708) by Scott Fujimoto, Edoardo Conti, Mohammad Ghavamzadeh and Joelle Pineau, arXiv2019.
- [Top-K Off-Policy Correction for a REINFORCE Recommender System](https://arxiv.org/abs/1812.02353) by Minmin Chen, Alex Beutel, Paul Covington, Sagar Jain, Francois Belletti, and Ed Chi, WSDM2019.
- [A Clustering-Based Reinforcement Learning Approach for Tailored Personalization of E-Health Interventions](https://arxiv.org/abs/1804.03592) by Ali el Hassouni, Mark Hoogendoorn, Martijn van Otterlo, A. E. Eiben, Vesa Muhonen and Eduardo Barbaro, arXiv2018.
- [Generating Interpretable Fuzzy Controllers using Particle Swarm Optimization and Genetic Programming](https://arxiv.org/abs/1804.10960) by Daniel Hein, Steffen Udluft and Thomas A. Runkler, GECCO2018.
- [End-to-End Offline Goal-Oriented Dialog Policy Learning via Policy Gradient](https://arxiv.org/abs/1712.02838) by Li Zhou, Kevin Small, Oleg Rokhlenko and Charles Elkan, arXiv2017.
- [Batch Reinforcement Learning on the Industrial Benchmark: First Experiences](https://arxiv.org/abs/1705.07262) by Daniel Hein, Steffen Udluft, Michel Tokic, Alexander Hentschel, Thomas A. Runkler and Volkmar Sterzing, IJCNN2017.
- [Policy Networks with Two-Stage Training for Dialogue Systems](https://arxiv.org/abs/1606.03152) by Mehdi Fatemi, Layla El Asri, Hannes Schulz, Jing He and Kaheer Suleman, SIGDial2016.
- [Adaptive Treatment of Epilepsy via Batch-mode Reinforcement Learning](https://www.aaai.org/Library/IAAI/2008/iaai08-008.php) by Arthur Guez, Robert D. Vincent, Massimo Avoli and Joelle Pineau, IAAI2008.

### Off-Policy Evaluation: Theory/Methods
#### Contextual Bandits

- [Piecewise-Stationary Off-Policy Optimization](https://arxiv.org/abs/2006.08236) by Joey Hong, Branislav Kveton, Manzil Zaheer, Yinlam Chow, and Amr Ahmed, AISTATS2021.
- [High-Confidence Off-Policy (or Counterfactual) Variance Estimation](https://arxiv.org/abs/2101.09847) by Yash Chandak, Shiv Shankar, and Philip S. Thomas. AAAI2021.
- [Off-Policy Evaluation of Slate Policies under Bayes Risk](https://arxiv.org/abs/2101.02553) by Nikos Vlassis, Fernando Amat Gil, and Ashok Chandrashekar, arXiv2021.
- [Doubly Robust Off-Policy Learning on Low-Dimensional Manifolds by Deep Neural Networks](https://arxiv.org/abs/2011.01797) by Minshuo Chen, Hao Liu, Wenjing Liao, and Tuo Zhao, arXiv2020.
- [Bandit Overfitting in Offline Policy Learning](https://arxiv.org/abs/2006.15368) by David Brandfonbrener, William F. Whitney, Rajesh Ranganath, and Joan Bruna, arXiv2020.
- [Counterfactual Learning of Continuous Stochastic Policies](https://arxiv.org/abs/2004.11722) by Houssam Zenati, Alberto Bietti, Matthieu Martin, Eustache Diemert, and Julien Mairal, arXiv2020.
- [Optimal Off-Policy Evaluation from Multiple Logging Policies](https://arxiv.org/abs/2010.11002) by Nathan Kallus, Yuta Saito, and Masatoshi Uehara, arXiv2020. [[code](https://github.com/CausalML/MultipleLoggers)]
- [A Practical Guide of Off-Policy Evaluation for Bandit Problems](https://arxiv.org/abs/2010.12470) by Masahiro Kato, Kenshi Abe, Kaito Ariu, and Shota Yasui, arXiv2020.
- [Off-Policy Evaluation and Learning for External Validity under a Covariate Shift](https://papers.nips.cc/paper/2020/hash/0084ae4bc24c0795d1e6a4f58444d39b-Abstract.html) by Masatoshi Uehara, Masahiro Kato, and Shota Yasui, NeurIPS2020.
- [Counterfactual Evaluation of Slate Recommendations with Sequential Reward Interactions](https://arxiv.org/abs/2007.12986) by James McInerney, Brian Brost, Praveen Chandar, Rishabh Mehrotra, and Ben Carterette, KDD2020.
- [Off-policy Bandits with Deficient Support](https://dl.acm.org/doi/abs/10.1145/3394486.3403139) by Noveen Sachdeva, Yi Su, and Thorsten Joachims, KDD2020.
- [Doubly robust off-policy evaluation with shrinkage](http://proceedings.mlr.press/v119/su20a.html) by Yi Su, Maria Dimakopoulou, Akshay Krishnamurthy, and Miroslav Dudik, ICML2020.
- [Adaptive Estimator Selection for Off-Policy Evaluation](http://proceedings.mlr.press/v119/su20d.html) by Yi Su, Pavithra Srinath, and Akshay Krishnamurthy, ICML2020.
- [Off-policy Bandit and Reinforcement Learning](https://arxiv.org/abs/2002.08536) by Yusuke Narita, Shota Yasui, and Kohei Yata, arXiv2020.
- [Distributionally Robust Policy Evaluation and Learning in Offline Contextual Bandits](http://proceedings.mlr.press/v119/si20a.html) by Nian Si, Fan Zhang, Zhengyuan Zhou, and Jose Blanchet, ICML2020.
- [Efficient Policy Learning from Surrogate-Loss Classification Reductions](http://proceedings.mlr.press/v119/bennett20a.html) by Andrew Bennett and Nathan Kallus, ICML2020. [[code](https://github.com/CausalML/ESPRM)]
- [More Efficient Policy Learning via Optimal Retargeting](https://www.tandfonline.com/doi/abs/10.1080/01621459.2020.1788948?journalCode=uasa20) by Nathan Kallus, JASA2020.
- [Semi-Parametric Efficient Policy Learning with Continuous Actions](https://papers.nips.cc/paper/2019/hash/08b7dc6e8b36bcaac15847827b7951a9-Abstract.html) by Victor Chernozhukov, Mert Demirer, Greg Lewis, and Vasilis Syrgkanis, NeurIPS2019.
- [Balanced Off-Policy Evaluation in General Action Spaces](http://proceedings.mlr.press/v108/sondhi20a.html) by Arjun Sondhi, David Arbour, and Drew Dimmery, AISTATS2019.
- [Policy Evaluation with Latent Confounders via Optimal Balance](https://papers.nips.cc/paper/2019/hash/7c4bf50b715509a963ce81b168ca674b-Abstract.html) by Andrew Bennett and Nathan Kallus, NeuIPS2019.
- [Focused Context Balancing for Robust Offline Policy Evaluation](https://dl.acm.org/doi/10.1145/3292500.3330852) by Hao Zou, Kun Kuang, Boqi Chen, Peixuan Chen, and Peng Cui, KDD2019.
- [On the Design of Estimators for Bandit Off-Policy Evaluation](http://proceedings.mlr.press/v97/vlassis19a.html) by Nikos Vlassis, Aurelien Bibaut, Maria Dimakopoulou, and Tony Jebara, ICML2019.
- [CAB: Continuous Adaptive Blending for Policy Evaluation and Learning](http://proceedings.mlr.press/v97/su19a.html) by Yi Su, Lequn Wang, Michele Santacatterina, and Thorsten Joachims, ICML2019.
- [Efficient Counterfactual Learning from Bandit Feedback](https://arxiv.org/abs/1809.03084) by Yusuke Narita, Shota Yasui, and Kohei Yata, AAAI2019.
- [Policy Evaluation and Optimization with Continuous Treatments](http://proceedings.mlr.press/v84/kallus18a.html) by Nathan Kallus and Angela Zhou, AISTATS2019.
- [Offline Evaluation of Ranking Policies with Click Models](https://dl.acm.org/doi/10.1145/3219819.3220028) by Shuai Li, Yasin Abbasi-Yadkori, Branislav Kveton, S. Muthukrishnan, Vishwa Vinay, and Zheng Wen, KDD2018.
- [Effective Evaluation using Logged Bandit Feedback from Multiple Loggers](https://arxiv.org/abs/1703.06180) by Aman Agarwal, Soumya Basu, Tobias Schnabel, and Thorsten Joachims, KDD2018.
- [Deep Learning with Logged Bandit Feedback](https://openreview.net/forum?id=SJaP_-xAb) by Thorsten Joachims, Adith Swaminathan, and Maarten de Rijke, ICLR2018.
- [Off-policy Evaluation for Slate Recommendation](https://papers.nips.cc/paper/2017/hash/5352696a9ca3397beb79f116f3a33991-Abstract.html) by Adith Swaminathan, Akshay Krishnamurthy, Alekh Agarwal, Miroslav Dudík, John Langford, Damien Jose, and Imed Zitouni, NeurIPS2017.
- [Optimal and Adaptive Off-policy Evaluation in Contextual Bandits](https://arxiv.org/abs/1612.01205) by Yu-Xiang Wang, Alekh Agarwal, and Miroslav Dudik, ICML2017.
- [Data-Efficient Policy Evaluation Through Behavior Policy Search](http://proceedings.mlr.press/v70/hanna17a.html) by Josiah P. Hanna, Philip S. Thomas, Peter Stone and Scott Niekum, ICML2017.
- [The Self-Normalized Estimator for Counterfactual Learning](https://papers.nips.cc/paper/2015/hash/39027dfad5138c9ca0c474d71db915c3-Abstract.html) by Adith Swaminathan and Thorsten Joachims, NeurIPS2015.
-  [Doubly Robust Policy Evaluation and Optimization](https://arxiv.org/abs/1503.02834) by Miroslav Dudík, Dumitru Erhan, John Langford, and Lihong Li, ICML2011.
- [Unbiased Offline Evaluation of Contextual-bandit-based News Article Recommendation Algorithms](https://dl.acm.org/doi/10.1145/1935826.1935878) by Lihong Li, Wei Chu, John Langford, and Xuanhui Wang, WSDM2011.
#### Reinforcement Learning

- [Off-policy Evaluation in Infinite-Horizon Reinforcement Learning with Latent Confounders](https://arxiv.org/abs/2007.13893) by Andrew Bennett, Nathan Kallus, Lihong Li, and Ali Mousavi, AISTATS2021.
- [Bootstrapping Statistical Inference for Off-Policy Evaluation](https://arxiv.org/abs/2102.03607) by Botao Hao, Xiang (Jack)Ji, Yaqi Duan, Hao Lu, Csaba Szepesvári and Mengdi Wang, arXiv2021.
- [Average-Reward Off-Policy Policy Evaluation with Function Approximation](https://arxiv.org/abs/2101.02808) by Shangtong Zhang, Yi Wan, Richard S. Sutton, and Shimon Whiteson, arXiv2021.
- [Near-Optimal Provable Uniform Convergence in Offline Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/2007.03760) by Ming Yin, Yu Bai and Yu-Xiang Wang, arXiv2020.
- [Optimal Mixture Weights for Off-Policy Evaluation with Multiple Behavior Policies](https://arxiv.org/abs/2011.14359) by Jinlin Lai, Lixin Zou, and Jiaxing Song, arXiv2020.
- [Kernel Methods for Policy Evaluation: Treatment Effects, Mediation Analysis, and Off-Policy Planning](https://arxiv.org/abs/2010.04855) by Rahul Singh, Liyuan Xu, and Arthur Gretton, arXiv2020.
- [Off-policy Policy Evaluation For Sequential Decisions Under Unobserved Confounding](https://papers.nips.cc/paper/2020/hash/da21bae82c02d1e2b8168d57cd3fbab7-Abstract.html) by Hongseok Namkoong, Ramtin Keramati, Steve Yadlowsky, and Emma Brunskill, NeurIPS2020.
- [CoinDICE: Off-Policy Confidence Interval Estimation](https://papers.nips.cc/paper/2020/hash/6aaba9a124857622930ca4e50f5afed2-Abstract.html) by Bo Dai, Ofir Nachum, Yinlam Chow, Lihong Li, Csaba Szepesvari, and Dale Schuurmans, NeurIPS2020.
- [Off-Policy Interval Estimation with Lipschitz Value Iteration](https://papers.nips.cc/paper/2020/hash/59accb9fe696ce55e28b7d23a009e2d1-Abstract.html) by Ziyang Tang, Yihao Feng, Na Zhang, Jian Peng, and Qiang Liu, NeurIPS2020.
- [Off-Policy Evaluation via the Regularized Lagrangian](https://papers.nips.cc/paper/2020/hash/488e4104520c6aab692863cc1dba45af-Abstract.html) by Mengjiao Yang, Ofir Nachum, Bo Dai, Lihong Li, and Dale Schuurmans, NeurIPS2020.
- [Minimax Value Interval for Off-Policy Evaluation and Policy Optimization](https://papers.nips.cc/paper/2020/hash/1cd138d0499a68f4bb72bee04bbec2d7-Abstract.html) by Nan Jiang and Jiawei Huang, NeurIPS2020.
- [Statistical Bootstrapping for Uncertainty Estimation in Off-Policy Evaluation](https://arxiv.org/abs/2007.13609) by Ilya Kostrikov and Ofir Nachum, arXiv2020.
- [Confident Off-Policy Evaluation and Selection through Self-Normalized Importance Weighting](https://arxiv.org/abs/2006.10460) by Ilja Kuzborskij, Claire Vernade, András György, and Csaba Szepesvári, arXiv2020.
- [Infinite-horizon Off-Policy Policy Evaluation with Multiple Behavior Policies](https://iclr.cc/virtual_2020/poster_rkgU1gHtvr.html) by Xinyun Chen, Lu Wang, Yizhe Hang, Heng Ge, and Hongyuan Zha, ICLR2020.
- [Doubly Robust Bias Reduction in Infinite Horizon Off-Policy Estimation](https://iclr.cc/virtual_2020/poster_S1glGANtDr.html) by Ziyang Tang, Yihao Feng, Lihong Li, Dengyong Zhou, and Qiang Liu, ICLR2020.
- [Black-box Off-policy Estimation for Infinite-Horizon Reinforcement Learning](https://iclr.cc/virtual_2020/poster_S1ltg1rFDS.html) by Ali Mousavi, Lihong Li, Qiang Liu, and Denny Zhou, ICLR2020.
- [Minimax-Optimal Off-Policy Evaluation with Linear Function Approximation](http://proceedings.mlr.press/v119/duan20b.html) by Yaqi Duan, Zeyu Jia, and Mengdi Wang, ICML2020.
- [Interpretable Off-Policy Evaluation in Reinforcement Learning by Highlighting Influential Transitions](http://proceedings.mlr.press/v119/gottesman20a.html) by Omer Gottesman, Joseph Futoma, Yao Liu, Sonali Parbhoo, Leo Celi, Emma Brunskill, and Finale Doshi-Velez, ICML2020.
- [Double Reinforcement Learning for Efficient and Robust Off-Policy Evaluation](http://proceedings.mlr.press/v119/kallus20b.html) by Nathan Kallus and Masatoshi Uehara, ICML2020.
- [Understanding the Curse of Horizon in Off-Policy Evaluation via Conditional Importance Sampling](http://proceedings.mlr.press/v119/liu20a.html) by Yao Liu, Pierre-Luc Bacon, and Emma Brunskill, ICML2020.
- [Minimax Weight and Q-Function Learning for Off-Policy Evaluation](http://proceedings.mlr.press/v119/uehara20a.html) by Masatoshi Uehara, Jiawei Huang, and Nan Jiang, ICML2020.
- [Accountable Off-Policy Evaluation With Kernel Bellman Statistics](http://proceedings.mlr.press/v119/feng20d.html) by Yihao Feng, Tongzheng Ren, Ziyang Tang, and Qiang Liu, ICML2020.
- [Asymptotically Efficient Off-Policy Evaluation for Tabular Reinforcement Learning](http://proceedings.mlr.press/v108/yin20b.html) by Ming Yin and Yu-Xiang Wang, ICML2020.
- [Efficiently Breaking the Curse of Horizon in Off-Policy Evaluation with Double Reinforcement Learning](https://arxiv.org/abs/1909.05850) by Nathan Kallus and Masatoshi Uehara, arXiv2019.
- [Off-Policy Evaluation in Partially Observable Environments](https://ojs.aaai.org//index.php/AAAI/article/view/6590) by Guy Tennenholtz, Uri Shalit, and Shie Mannor, AAAI2019.
- [Intrinsically Efficient, Stable, and Bounded Off-Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/1906.03735) by Nathan Kallus, Masatoshi Uehara, NeurIPS2019.
- [Towards Optimal Off-Policy Evaluation for Reinforcement Learning with Marginalized Importance Sampling](https://papers.nips.cc/paper/2019/hash/4ffb0d2ba92f664c2281970110a2e071-Abstract.html) by Tengyang Xie, Yifei Ma, and Yu-Xiang Wang, NeuIPS2019.
- [Off-Policy Evaluation via Off-Policy Classification](https://papers.nips.cc/paper/2019/hash/b5b03f06271f8917685d14cea7c6c50a-Abstract.html), Alexander Irpan, Kanishka Rao, Konstantinos Bousmalis, Chris Harris, Julian Ibarz, and Sergey Levine, NeuIPS2019.
- [Off-Policy Evaluation and Learning from Logged Bandit Feedback: Error Reduction via Surrogate Policy](https://openreview.net/forum?id=HklKui0ct7) by Yuan Xie, Boyi Liu, Qiang Liu, Zhaoran Wang, Yuan Zhou, and Jian Peng, ICLR2019.
- [More Efficient Off-Policy Evaluation through Regularized Targeted Learning](http://proceedings.mlr.press/v97/bibaut19a.html) by Aurelien Bibaut, Ivana Malenica, Nikos Vlassis, and Mark Van Der Laan, ICML2019.
- [Combining parametric and nonparametric models for off-policy evaluation](http://proceedings.mlr.press/v97/gottesman19a.html) by Omer Gottesman, Yao Liu, Scott Sussex, Emma Brunskill, and Finale Doshi-Velez, ICML2019.
- [Counterfactual Off-Policy Evaluation with Gumbel-Max Structural Causal Models](http://proceedings.mlr.press/v97/oberst19a.html) by Michael Oberst and David Sontag, ICML2019.
- [Importance Sampling Policy Evaluation with an Estimated Behavior Policy](http://proceedings.mlr.press/v97/hanna19a.html) by Josiah Hanna, Scott Niekum, and Peter Stone, ICML2019.
- [When People Change their Mind: Off-Policy Evaluation in Non-Stationary Recommendation Environments](https://dl.acm.org/doi/10.1145/3289600.3290958) by Rolf Jagerman, Ilya Markov, and Maarten de Rijke, WSDM2019.
- [Representation Balancing MDPs for Off-policy Policy Evaluation](https://papers.nips.cc/paper/2018/hash/980ecd059122ce2e50136bda65c25e07-Abstract.html) by Yao Liu, Omer Gottesman, Aniruddh Raghu, Matthieu Komorowski, Aldo A. Faisal, Finale Doshi-Velez, and Emma Brunskill, NeuIPS2018.
- [Breaking the Curse of Horizon: Infinite-Horizon Off-Policy Estimation](https://papers.nips.cc/paper/2018/hash/dda04f9d634145a9c68d5dfe53b21272-Abstract.html) by Qiang Liu, Lihong Li, Ziyang Tang, and Dengyong Zhou, NeuIPS2018.
- [Confounding-Robust Policy Improvement](https://papers.nips.cc/paper/2018/hash/3a09a524440d44d7f19870070a5ad42f-Abstract.html) by Nathan Kallus and Angela Zhou, NeuIPS2018.
- [Balanced Policy Evaluation and Learning](https://papers.nips.cc/paper/2018/hash/6616758da438b02b8d360ad83a5b3d77-Abstract.html) by Nathan Kallus, NeuIPS2018.
- [More Robust Doubly Robust Off-policy Evaluation](https://arxiv.org/abs/1802.03493) by Mehrdad Farajtabar, Yinlam Chow, and Mohammad Ghavamzadeh, ICML2018.
- [Importance Sampling for Fair Policy Selection](https://people.cs.umass.edu/~pthomas/papers/Doroudi2017.pdf) by Shayan Doroudi, Philip Thomas, and Emma Brunskill, UAI2017.
- [Predictive Off-Policy Policy Evaluation for Nonstationary Decision Problems, with Applications to Digital Marketing](https://people.cs.umass.edu/~pthomas/papers/Thomas2017.pdf) by Philip S. Thomas, Georgios Theocharous, Mohammad Ghavamzadeh, Ishan Durugkar, and Emma Brunskill, AAAI2017.
- [Consistent On-Line Off-Policy Evaluation](http://proceedings.mlr.press/v70/hallak17a.html) by Assaf Hallak and Shie Mannor, ICML2017.
- [Bootstrapping with Models: Confidence Intervals for Off-Policy Evaluation](https://arxiv.org/abs/1606.06126) by Josiah P. Hanna, Peter Stone, and Scott Niekum, AAAMS2016.
- [Doubly Robust Off-policy Value Evaluation for Reinforcement Learning](http://proceedings.mlr.press/v48/jiang16.html) by Nan Jiang and Lihong Li, ICML2016.
- [Data-Efficient Off-Policy Policy Evaluation for Reinforcement Learning](http://proceedings.mlr.press/v48/thomasa16.html) by Philip Thomas and Emma Brunskill, ICML2016.
- [High Confidence Off-Policy Evaluation](https://people.cs.umass.edu/~pthomas/papers/Thomas2015.pdf) by Philip S. Thomas, Georgios Theocharous, and Mohammad Ghavamzadeh.
- [Eligibility Traces for Off-Policy Policy Evaluation](https://dl.acm.org/doi/10.5555/645529.658134) by Doina Precup, Richard S. Sutton and Satinder P. Singh, ICML2000.
 

### Off-Policy Evaluation: Benchmarks/Experiments/Applications
- [Benchmarks for Deep Off-Policy Evaluation](https://openreview.net/forum?id=kWSeGEeHvF8) by Justin Fu, Mohammad Norouzi, Ofir Nachum, George Tucker, ziyu wang, Alexander Novikov, Mengjiao Yang, Michael R Zhang, Yutian Chen, Aviral Kumar, Cosmin Paduraru, Sergey Levine and Thomas Paine, ICLR2021. [[code](https://github.com/google-research/deep_ope)]
- [Large-scale Open Dataset, Pipeline, and Benchmark for Bandit Algorithms](https://arxiv.org/abs/2008.07146) by Yuta Saito, Shunsuke Aihara, Megumi Matsutani, and Yusuke Narita, arXiv2020. [[software](https://github.com/st-tech/zr-obp)] [[public dataset](https://research.zozo.com/data.html)]
- [Off-Policy Evaluation of Probabilistic Identity Data in Lookalike Modeling](https://dl.acm.org/doi/10.1145/3289600.3291033) by Randell Cotta, Dan Jiang, Mingyang Hu, and Peizhou Liao, WSDM2019.
- [Offline Evaluation to Make Decisions About Playlist Recommendation](https://dl.acm.org/doi/10.1145/3289600.3291027) by Alois Gruson, Praveen Chandar, Christophe Charbuillet, James McInerney, Samantha Hansen, Damien Tardieu, and Ben Carterette, WSDM2019.
- [Evaluating Reinforcement Learning Algorithms in Observational Health Settings]https://arxiv.org/abs/1805.12298) by Omer Gottesman, Fredrik Johansson, Joshua Meier, Jack Dent, Donghun Lee, Srivatsan Srinivasan, Linying Zhang, Yi Ding, David Wihl, Xuefeng Peng, Jiayu Yao, Isaac Lage, Christopher Mosch, Li-wei H. Lehman, Matthieu Komorowski, Matthieu Komorowski, Aldo Faisal, Leo Anthony Celi, David Sontag and Finale Doshi-Velez, arXiv2018.
- [Towards a Fair Marketplace: Counterfactual Evaluation of the trade-off between Relevance, Fairness & Satisfaction in Recommendation Systems](https://dl.acm.org/doi/10.1145/3269206.3272027) by Rishabh Mehrotra, James McInerney, Hugues Bouchard, Mounia Lalmas, Fernando Diaz, CIKM2018.
- [Offline A/B testing for Recommender Systems](https://dl.acm.org/doi/10.1145/3159652.3159687) by Alexandre Gilotte, Clément Calauzènes, Thomas Nedelec, Alexandre Abraham, and Simon Dollé, WSDM2018.
- [Offline Comparative Evaluation with Incremental, Minimally-Invasive Online Feedback](https://dl.acm.org/doi/10.1145/3209978.3210050) by Ben Carterette and Praveen Chandar, SIGIR2018.

### Open Source Software

## Related Workshops

- [Reinforcement Learning Day 2021](https://www.microsoft.com/en-us/research/event/reinforcement-learning-day-2021/)
- [Offline Reinforcement Learning Workshop (NeurIPS 2020)](https://offline-rl-neurips.github.io/)
- [Reinforcement Learning from Batch Data and Simulation](https://simons.berkeley.edu/workshops/schedule/14240)
- [Virtual Conference on Reinforcement Learning for Real Life (RL4RealLife 2020)](https://sites.google.com/view/RL4RealLife)
- [Safety and Robustness in Decision Making (NeurIPS 2019)](https://sites.google.com/view/neurips19-safe-robust-workshop)

## Tutorials/Talks/Lectures

- [Offline RL](https://slideslive.com/38938455/offline-rl) by Nando de Freitas, NeurIPS2020 OfflineRL Workshop.
- [Learning a Multi-Agent Simulator from Offline Demonstrations](https://slideslive.com/38938458/learning-a-multiagent-simulator-from-offline-demonstrations) by Brandyn White, NeurIPS2020 OfflineRL Workshop.
- [Towards Reliable Validation and Evaluation for Offline RL](https://slideslive.com/38938459/towards-reliable-validation-and-evaluation-for-offline-rl) by Nan Jiang, NeurIPS2020 OfflineRL Workshop.
- [Batch RL Models Built for Validation](https://slideslive.com/38938457/batch-rl-models-built-for-validation) by Finale Doshi-Velez, NeurIPS2020 OfflineRL Workshop.
- [Offline Reinforcement Learning: From Algorithms to Practical Challenges](https://sites.google.com/view/offlinerltutorial-neurips2020/home) by Aviral Kumar and Sergey Levine, NeurIPS2020.
- [Statistically Efficient Offline Reinforcement Learning](https://youtu.be/n5ZoxT_WmHo) by Nathan Kallus, ARL Seminor2020.
- [Near Optimal Provable Uniform Convergence in Off-Policy Evaluation for Reinforcement Learning](https://youtu.be/FWZewbQykv4) by Yu-Xiang Wang, RL Theory Seminar2020.
- [Minimax-Optimal Off-Policy Evaluation with Linear Function Approximation](https://youtu.be/TX9KBofFZ8s) by Mengdi Wang, RL Theory Seminar2020.
- [Exponential Lower Bounds for Batch Reinforcement Learning: Batch RL can be Exponentially Harder than Online RL](https://www.youtube.com/watch?v=YktnEdsxYfc&feature=youtu.be) by Andrea Zanette, RL Theory Seminar2020.
- [Beyond the Training Distribution: Embodiment, Adaptation, and Symmetry](https://www.youtube.com/watch?v=wv1zXnxRCCM&feature=youtu.be) by Chelsea Finn, EI Seminar2020.
- [Combining Statistical methods with Human Input for Evaluation and Optimization in Batch Settings](https://slideslive.com/38922630/combining-statistical-methods-with-human-input-for-evaluation-and-optimization-in-batch-settings) by Finale Doshi-Velez, NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
- [Efficiently Breaking the Curse of Horizon with Double Reinforcement Learning](https://slideslive.com/38922636/efficiently-breaking-the-curse-of-horizon-with-double-reinforcement-learning) by Nathan Kallus, NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
- [Scaling Probabilistically Safe Learning to Robotics](https://slideslive.com/38922637/scaling-probabilistically-safe-learning-to-robotics?locale=en) by Scott Niekum, NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
