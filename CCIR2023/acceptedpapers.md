---
title: 论文录用
---

{% capture c1 %}

{% include conference_leftlist_CCIR2023.html %}

{% endcapture %}

{% capture c2 %}

<h1 style="text-align: center;">论文录用</h1>

<div style="margin-left: 20%;font-family: 'Times New Roman', 'Microsoft YaHei','serif'"> 
<div style="font-weight: bold">一种注意力引导知识增强的事件因果关系识别方法</div>
<div>事件因果关系识别是自然语言处理领域重要任务，由于因果关系表达方式多样且以隐式表达为主，现有方法难以进行准确识别。本文将外部结构化知识融入事件因果关系识别任务，提出一种注意力引导知识增强的事件因果关系识别模型。首先，通过BERT模型对事件对及其上下文进行编码；然后，提出零跳混合匹配方案挖掘事件相关的描述型知识和关系型知识，通过注意力机制对事件的描述型知识序列进行编码，通过稠密图神经网络对事件对的关系型知识进行编码。最后，融合前三个编码模块识别事件因果关系。基于EventStoryLine数据集的实验结果表明本文所构建模型的识别效果优于现有模型，在零跳概念匹配、描述性和关系型知识编码等层面均获得了识别性能的提升。</div>
<div>Bo Xu (Dalian University of Technology), Jinchen Sun (University of Science and Technology of China), Hongfei Lin (Dalian University Of Technology) and Linlin Zong (Dalian University of Technology)</div>
<p></p>
<div style="font-weight: bold">App搜索场景下的意图推荐方法研究</div>
<div>主动搜索和被动推荐是移动互联网用户在应用市场(apps market)中用户获取应用(apps)的两条主要途径，为了解决移动界面输入不便的问题，当用户点击搜索输入框后，应用市场软件通常会直接给用户推荐合适应用，被称为搜索场景下的意图推荐。如何准确地在App搜索场景中进行意图推荐已经成为当前应用市场软件的一项重要功能。在实践中，该文发现用户在应用市场软件中的主动搜索数据可以为精准的搜索意图推荐供帮助，而现有的App推荐模型并未充分考虑用户的主动搜索行为。本文提出了一个基于多任务学习的用户在搜索场景下的意图推荐方法，其核心是将该用户的历史搜索行为数据融入意图推荐的过程中，简称IRMT。具体地，IRMT基于Transformer对用户搜索行为进行特征提取，并基于多任务的优化算法采用端到端式的训练方式，即直接在搜索和推荐数据上进行交替优化训练。基于华为应用市场真实数据集的实验表明IRMT能有效提升推荐模型精度，在华为应用市场的线上A/B测试表明IRMT在eCPM指标上相较基线模型提升了0.51%。</div>
<div>Yuqi Zhou (Renmin University of China), Sunhao Dai (Renmin University of China), Chaoliang Zhang (Huawei Noah'S Ark Lab), Gang Wang (Huawei Noah'S Ark Lab), Baotian Hu (Harbin Institute of Technology) and Jun Xu (Renmin University of China)</div>
<p></p>
<div style="font-weight: bold">自适应的流水线式无监督问题生成方法</div>
<div>在传统的问答任务中，模型一般需要大量的数据进行训练，而标注这些数据需要较多的时间和人力成本。无监督问题生成是解决问答任务训练数据匮乏的一种有效方法，但是目前使用该方法生成出的问题存在着难以回答、种类单一、语义不明等问题。针对这些问题，该文提出了一个自适应的多模块流水线式模型ADVICE，多个模块分别从问题可回答性、问题多样性和语法规范性对现有方法进行改进。在问题可回答性模块中，该文使用了共指消解和命名实体识别技术来提升问题的可回答性。在问题多样性模块中，该文针对不同提问方式的问题设计了不同的规则来提升问题类型多样性与答案类型多样性。在语法规范性模块中，该文基于T5训练了一个针对问句的语法错误纠正模型，并设计了一个筛选模块对纠正后的问答数据进行过滤。最后，该文训练了一个分类器自动选择所需要的模块。实验表明，使用改进后的问题生成方法，下游的问答模型在SQuAD数据集上的EM值平均提升了2.9%，F1值平均提升了4.4%。</div>
<div>李昆泽 (哈尔滨工业大学) and张宇 (哈尔滨工业大学)</div>
<p></p>
<p></p>
<div style="font-weight: bold">Opinion Evolution Model based on Long-Term and Short-Term Opinions</div>
<div>Opinion Evolution Model based on Long-Term and Short-Term Opinions.</div>
<div>Opinion dynamics can help analyze and predict the spread of information in social networks, which is beneficial for social media marketing and public opinion monitoring. This paper combines deep learning and opinion dynamics models, considering social interaction mechanisms and data-driven approaches. It introduces a data augmentation module and integrates long-term and short-term opinions. The model utilizes a self-attention network to learn long-term opinion features and employs gated recurrent units (GRUs) to capture short-term opinion features. Experimental results demonstrate that the proposed model based on long-term and short-term opinions(LST-OD) outperforms other baseline methods in predicting user opinions on synthetic datasets and real-world dataset. Ablation experiments also confirm the effectiveness of each module in the proposed model.</div>
<div>Yitong Wang (Xihua University), Xianyong Li (Xihua University), Yuhang Cheng (Xihua University), Yajun Du (Xihua University), Xiaoliang Chen (Xihua University) and Yongquan Fan (Xihua University)</div>
<p></p>
<div style="font-weight: bold">层次化推理链驱动的多被告法律判决预测</div>
<div>刑事事实描述中的多名被告通常存在复杂的互动关系，这给法律判决预测任务带来了挑战。现有的法律判决预测方法主要针对单被告案件，无法有效区分多被告案件中每个被告的判决结果（法律条文、罪名、刑期）。针对这一问题，该文提出了多被告法律判决预测任务，并设计了一种基于层次化推理网络的多被告判决预测方法。层次化推理网络将多被告判决过程形式化为层次化推理链，并根据该推理链确定每个被告的犯罪关系、量刑情节、法律条文、罪名、刑期。此外，该文还收集了一个真实世界的多被告数据集，以便进行训练和评估。在多被告数据集上的实验结果表明，该文提出的层次化推理网络方法能够有效地预测多被告案件中每个被告的判决结果，并优于现有的法律判决预测方法。</div>
<div>吕由钢 (Shandong University),郝继泰 (Shandong University),王梓涵 (Shandong University),高莘 (Shandong University),任鹏杰 (Shandong University),陈竹敏 (Shandong University),马军 (Shandong University) and任昭春 (Shandong University)</div>
<p></p>
<div style="font-weight: bold">基于因果常识的事件共指消解技术研究</div>
<div>事件共指消解针对事件识别指代之间的等价关系。传统的事件共指消解方法基于文本特征建模事件关系，主要来自于语法结构和上下文文本。现有方法缺少对事件逻辑常识的利用和大规模语言模型中隐含知识的开发。该文提出了一种结合因果常识的事件共指消解模型ECE。模型首先通过大规模生成式语言模型和单样本提示学习技术为特定事件生成因果常识，再将因果常识转化为特征向量，最后结合其他特征共同建模事件共指关系。该文在统一注释的事件关系抽取数据集MAVEN-ERE上验证了因果常识对事件共指消解的有效性，并在跨文档事件共指消解数据集ECB+上进行了进一步实验，实验结果表明，该文方法在多项度量指标F1值的非加权和CoNLL指标上达到了67.27，比基线方法提升了14.61%。</div>
<div>王禹琦 (哈尔滨工业大学) and张宇 (哈尔滨工业大学)</div>
<p></p>
<div style="font-weight: bold">结合局部与全局信息关联的相关工作生成</div>
<div>学术论文中“相关工作”部分是当前研究工作的综述，使读者快速了解当前研究的进展。本文针对基于多个参考文献自动生成学术论文“相关工作”部分展开研究。传统方法在处理大量参考引文和复杂关系时存在局限，尤其是常规神经网络在面对复杂多引文的相关工作生成时的输入长度限制。为解决这一问题，我们提出了一个结合局部与全局信息关联的相关工作生成模型。具体而言，我们根据局部性原理将多文档引文输入进行分页处理，并在编码和解码过程中对这些页面进行独立处理，以保证局部关联的同时避免全局上下文的复杂性。同时，我们引入了对比学习的方法来保持全局信息的一致性，避免主题偏离。通过实证研究，我们发现结合局部与全局信息关联的方法能更好地理解引文并生成相关工作。实验结果表明，相较于采用高效注意力与全注意力的强基线模型，我们的模型表现更为出色。</div>
<div>Kaixin Niu (Soochow University), Zhongqing Wang (Soochow University), Hongling Wang (Soochow University) and Mengling Han (Soochow University)</div>
<p></p>
<div style="font-weight: bold">基于多模态特征融合的对话回复生成方法</div>
<div>近年来，基于多模态特征的对话回复生成任务受到广泛关注。但是，现有的研究主要关注基于文本和图像的对话回复生成任务，没有使用完整的视频信息，且忽略了包含丰富信息的语音模态。为此，该文研究基于对齐文本、语音和视觉信息的多模态对话回复生成任务，并提出一种基于多模态特征融合的对话回复生成方法。首先，为了融合多模态特征，该文探索了平均融合法和注意力机制融合法两种融合方法。然后，考虑到无关多模态特征对生成结果的干扰，该文引入门控机制来控制是否需要关注多模态特征。最后，该文将输入模态扩展到文本、语音和视觉三种模态上。实验结果表明，该文提出的两种融合方法和门控机制可以有效融合语音和视觉特征，并且能显著提升对话回复生成的性能。</div>
<div>Linqin Li (School of Computer Science and Technology, Soochow University), Dong Zhang (School of Computer Science and Technology, Soochow University), Suyang Zhu (School of Computer Science and Technology, Soochow University) and Shoushan Li (School of Computer Science and Technology, Soochow University)</div>
<p></p>
<div style="font-weight: bold">一种融合位置信息和交互注意力的方面级情感分析方法</div>
<div>社交媒体和电商平台中涌现了大量的评论性文本，基于注意力的方面级情感分析方法已经被广泛用于对这些文本进行分析。现有的方法在实现方面词和上下文的交互注意时，存在没有利用上下文和方面词的相对位置关系，只关注方面词对上下文的影响导致语义交互不够充分，和将方面词作为一个整体进行计算等问题。本文提出一种融合相对位置信息的交互注意力的方面级情感分析模型。首先利用双向长短期记忆网络学习融合位置信息的上下文和方面词的语义特征，然后融入可学习的参数矩阵将上下文与方面词的语义特征进行交互学习，并使用交互注意力在字词粒度上分别计算方面词对上下文的影响以及上下文对方面词的影响，最后进行情感分类。在SemEval 2014 Task4基准数据集上进行了多个实验，实验结果表明，本文的模型取得的性能优于比较方法。</div>
<div>Jiajing Li (中国矿业大学（北京）机电与信息工程学院，北京 100083；南京网感至察信息科技有限公司，江苏 南京 210001), Sheng Li (中国矿业大学（北京）机电与信息工程学院，北京 100083), Yuanyuan Dai (中国矿业大学（北京）机电与信息工程学院，北京 100083), Tao Meng (南京网感至察信息科技有限公司，江苏 南京 210001), Xiaoqing Luo (北京大学经济学院 北京 100871) and Hongfei Yan (北京大学计算机学院 北京 100871)</div>
<p></p>
<div style="font-weight: bold">基于稳定学习的多兴趣序列推荐网络</div>
<div>多兴趣网络以多个表示向量来提取用户多个兴趣，在序列推荐中展现了优秀的表现。然而，用户多个兴趣通常高度相关，模型可能学习到噪声兴趣与目标物品之间的虚假相关性。一旦数据分布变化，兴趣之间的相关性也会改变，虚假相关性将误导模型做出错误预测。为了缓解这个问题，本文提出了一种新的基于稳定学习的多兴趣网络，试图消除模型提取的兴趣之间的相关性，来避免模型捕获虚假相关性。本文采用注意力模块提取多个兴趣，并选择最重要的兴趣进行最终预测。同时，基于独立性准则对训练样本进行加权，以最小化提取到兴趣之间的相关性。本文进行了大量实验显示，在集外（Out-Of-Distribution，OOD）和随机设置下，分别取得了36.8%和21.7%的相对提升。</div>
<div>刘昭呈 (快手科技),朱振熙 (快手科技) and刘强 (中国科学院自动化研究所 多模态人工智能系统国家重点实验室 智能感知与计算研究中心)</div>
<p></p>
<div style="font-weight: bold">面向排序学习的概率分布优化模型研究</div>
<div>现有的许多排序学习模型都是将模型输出的评分看作确定的数，依据该评分表示文档间的偏序关系。考虑到这种将评分看作单一数值的限制，该文提出了一种概率分布排序学习模型优化方法，以概率分布的形式对排序分数进行平滑，进而将排序分数大小的比较变成了对分数偏序关系的概率估计。在此基础上，将该方法应用于排序学习模型RankNet、LambdaRank以及LambdaMART，更合理地拟合了模型概率与目标概率之间的差距，从而对排序学习模型进行优化。该文在多个大规模真实数据集上进行了实验，最终结果都表明模型优化后的性能比优化前的性能更好，验证了该文方法的有效性。</div>
<div>Fengxu Zhao (School of Computer Science and Technology, Dalian University of Technology), Jian Wang (School of Computer Science and Technology, Dalian University of Technology), Yuan Lin (School of Public Administration, Dalian University of Technology) and Hongfei Lin (School of Computer Science and Technology, Dalian University of Technology)</div>
<p></p>
<div style="font-weight: bold">基于对抗型排序学习的混合推荐算法</div>
<div>推荐系统可以帮助用户过滤海量信息，单一的推荐算法存在一定的缺陷，基于深度学习的混合推荐通过融入辅助信息可以有效缓解传统推荐算法中数据稀疏的问题，往往可以取得更好的推荐效果。在目前大多数的研究中，针对不同的算法都采用了具体的辅助信息，没有一个统一的混合推荐框架。该文提出了一种基于对抗型排序学习的混合推荐算法——MRecGAN；利用排序学习的思想将多个基础推荐算法融合，构建统一的辅助数据，挖掘特征之间的深层关系；并利用生成式对抗网络（GANs）学习排序函数，通过一个判别器与两个生成器与之间的协同对抗，提升各自性能，获得推荐序列；最后利用真实电影Movielens数据集结合辅助数据进行测试。实验结果表明，该模型较好综合了各基础模型的优点，NDCG等指标改善显著。</div>
<div>Kan Xu (Dalian University of Technology), Xinzhuo Wu (Dalian University of Technology), Yuan Lin (Dalian University of Technology), Qian Gu (Dalian University of Technology), Hongfei Lin (Dalian University of Technology) and Zhang Xie (Dalian University of Technology)</div>
<p></p>
<div style="font-weight: bold">Multimodal sentiment analysis method based on comparative learning</div>
<div>Multimodal emotion analysis refers to the classification of emotion tendency based on multi-modal data such as audio, image and video, which has become a research hotspot in the field of emotion analysis. Classification technology is the key technology of multimodal sentiment analysis. In recent years, classification methods based on neural network have shown high performance and strong robustness. However, neural networks do not make full use of existing information resources. This paper defines multi-modal emotion classification as a comparison problem, and proposes a multi-modal emotion analysis model (CE-MSA-TFFE), which uses transformer feature fusion and enhancement technology to enhance the level of audio-visual features and then organically integrate text features. In order to verify the validity of the model, we conducted experiments on the CMU-MOSEI dataset, and the experimental results show that the performance of the model is better than RAVEN GraphMFN and so on.</div>
<div>Yipeng Wei (Dalian University of Technology), Yuan Lin (Dalian University of Technology), Fushun E (Dalian University of Technology), Tianyu Xiang (Dalian University of Technology), Yinglin Wang (Dalian University of Technology), Kan Xu (Dalian University of Technology) and Hongfei Lin (Dalian University of Technology)</div>
<p></p>
<div style="font-weight: bold">上下文感知增强的多轮个性化对话检索方法研究</div>
<div>个性化回复检索系统通常使用对话者画像（persona）作为额外的知识来保持回复的一致性，并通过对话历史来共同选择符合语境的个性化回复。然而，以前的工作在进行这两者与回复的深层交互中，仍存在选择与对话历史矛盾或不符合画像的回复。针对上述问题，该文提出了上下文感知增强的多轮个性化对话检索模型SP2S。该模型使用提示学习将个性化回复检索任务重述为掩码语言模型和连续语句检测的任务形式，并融入说话人及画像表征（speaker&persona-embedding）增强多轮对话的句子间、句子内，以及对话场景的上下文对于选择回复的指导作用。此外，还利用多级注意力模块进行全局和局部的对话关键特征提取。在PERSONA-CHAT数据集上的实验结果表明，我们提出的上下文感知增强模型的性能在召回率（hits@1）和均值倒数序位（MRR）方面都优于之前的方法，在回复者自身原始画像上优于之前的方法0.7%，在对话搭档原始画像上优于之前的方法2.4%，在PERSONA-CHAT数据集上实现了新的最先进的性能。</div>
<div>Yanbing Chen (Wuhan University of Technology) and Lin Li (Wuhan University of Technology)</div>
<p></p>
<div style="font-weight: bold">基于大型语言模型的无监督细粒度长文本会议摘要框架</div>
<div>近年来，在线会议的形式愈发成为了人们信息交流的主要方式。然而，冗长的会议形式与频繁的会议安排导致人们无法对每个会议进行深入细致的了解。长文本会议摘要技术的引入则可以帮助用户快速凝练会议的关键信息，但其发展却一直受限于数据稀缺和模型限制等原因，无法实现有效且精准的摘要效果。针对上述问题，本文提出了一种基于大型语言模型的无监督细粒度长文本会议摘要框架，该框架在通过掩码替换对会议隐私信息进行保护的前提下，将给定的长文本会议文档经过“主题分割-文本顺滑-摘要生成”流程，最终分别以主题级别细粒度摘要（关键词、提纲、总结）和会议级别融合摘要的形式进行呈现。本文在公开的会议摘要数据集和长文档摘要数据集上进行了实验，分别以自动化评价和人工评价的方式验证了本工作的可行性和有效性。</div>
<div>Yangfan Ye (Research Center for Social Computing and Information Retrieval, Harbin Institute of Technology), Xiaocheng Feng (Research Center for Social Computing and Information Retrieval, Harbin Institute of Technology), Xiachong Feng (Research Center for Social Computing and Information Retrieval, Harbin Institute of Technology), Xinmiao Yu (Research Center for Social Computing and Information Retrieval, Harbin Institute of Technology) and Bing Qin (Research Center for Social Computing and Information Retrieval, Harbin Institute of Technology)</div>
<p></p>
<div style="font-weight: bold">Gender Biased Legal Case Retrieval System on Users' Decision Process</div>
<div>In the last decade, legal case search has become an important part of a legal practitioner's work. During legal case search, search engines retrieval a number of relevant cases from huge amounts of data and serve them to users. However, it is uncertain whether these cases are gender-biased and whether such bias has impact on user perceptions. We designed a new user experiment framework to simulate the judges' reading of relevant cases. 72 participants with backgrounds in legal affairs invited to conduct the experiment. Participants were asked to sim-ulate the role of the judge in conducting a legal case search on 3 assigned cases and determine the sentences of the defendants in these cases. Gender of the defendants in both the task and relevant cases was edited to statistically measure the effect of gender bias in the legal case search results on participants' perceptions. The results showed that gender bias in the legal case search results did not have a significant effect on judges' perceptions.</div>
<div>Ruizhe Zhang (Tsinghua University), Qingyao Ai (Tsinghua University), Yiqun Liu (Tsinghua University), Yueyue Wu (Tsinghua University) and Beining Wang (Tsinghua University)</div>
<p></p>
<div style="font-weight: bold">基于提示增强原型网络的小样本多标签方面类别检测</div>
<div>小样本多标签方面类别检测是细粒度情感分析的研究热点。在基于原型网络的方法中，训练数据缺乏以及与当前方面类别无关的噪音词严重影响了采用注意力机制生成原型向量的质量。针对这一问题，该文提出了基于提示增强原型网络模型，首先，利用提示学习对齐预训练任务与下游任务，同时借助提示信息指导模型进行句子表示，从而学习到更具有辨别性的向量，有效地促使类别信息更易区分，并采用余弦相似度计算损失函数，降低高维向量空间的影响；其次，设计了减轻噪音对句子向量表示干扰的优化模型，促进相同方面类别的句子在嵌入空间中聚集。实验结果表明：该模型在三个公开数据集的F1值比SOTA模型分别提升了4.35%，8.62%，8.39%,可以有效的检测方面类别。</div>
<div>Bai Yu (SHENYANG AEROSPACE UNIVERSITY), Chaofeng Guan (SHENYANG AEROSPACE UNIVERSITY) and Xianlei Zhou (SHENYANG AEROSPACE UNIVERSITY)</div>
<p></p>
<div style="font-weight: bold">基于提示学习的电信网络诈骗案件分类方法</div>
<div>诈骗案件分类是打击电信网路诈骗犯罪过程中的关键一环，分类结果有助于公安部门掌握当前电信网络诈骗案件的分布特点，进而对不同类别的诈骗案件作出针对性的预防、监管、制止、侦查等措施。本文针对电信诈骗案件自动分类技术进行了研究，制定了基于情境分析的电信网络诈骗分类体系，实现了案件文本去标识化隐私保护方法，提出了一种基于提示学习的电信网络诈骗案件分类方法，实验结果显示该方法在论文构建的数据集上效果平均高于基于BERT的分类方法1至2个百分点。</div>
<div>Jie Ji (Harbin Institute of Technology), Chengjie Sun (Harbin Institute of Technology), Lili Shan (Harbin Institute of Technology), Boyue Shang (Harbin Public Security Bureau Xiangfang branch) and Lei Lin (Harbin Institute of Technology)</div>
<p></p>
<p></p>
<div style="font-weight: bold">Matrix Product Operator based Sequential Recommendation Model</div>
<div>The task of sequential recommendation confronts challenges characterized by high complexity and substantial diversity. The paradigm of pre-training and fine-tuning is extensively employed for learning item representations based on sequential data in recommendation scenarios. However, prevalent approaches tend to disregard the potential underfitting and overfitting issues that may arise during model fine-tuning in new domains. To address this concern, we introduce a novel neural network architecture grounded in the framework of matrix product operator (MPO). Additionally, the study presents two versatile fine-tuning strategies. Firstly, a lightweight fine-tuning approach that involves updating only a subset of parameters is proposed to effectively mitigate the problem of overfitting during the fine-tuning process. Secondly, an over-parameterization fine-tuning strategy is introduced by augmenting the number of trainable parameters, robustly addressing the issue of underfitting during fine-tuning. Through extensive experimentation on well-established open-source datasets, the efficacy of the proposed approach is demonstrated by achieving performance achievements. This serves as a compelling testament to the effectiveness of the proposed approach in addressing the challenge of general item representation in recommendation systems.</div>
<div>Peiyu Liu (Renmin University of China), Bowen Yao (Renmin University of China), Ze-Feng Gao (Renmin University of China) and Wayne Xin Zhao (Renmin University of China)</div>
<p></p>
<div style="font-weight: bold">基于自监督的预训练在推荐系统中的研究综述</div>
<div>预训练模型旨在通过自监督学习从大规模无标签的数据中获得与具体任务无关的表征。伴随着深度学习的迅猛发展以及强有力的算力支持，预训练技术在自然语言处理（NLP）和计算机视觉（CV）领域中等众多下游任务上取得了显著的提升。因此，如何设计能够融合语言、图像、文档和视频等各种信息的预训练模型以更好的服务下游任务成为了当前的研究热点。在推荐系统中用户交互记录的稀疏性问题和冷启动问题由来已久，同时用户和物品的数量巨大，如何得到良好的用户表征和物品表征也成为了一大挑战。为了缓解这些问题，近来涌现了一批研究工作探讨如何将预训练技术应用在推荐场景下并构造预训练任务，以此提升最终的推荐性能。本文重点综述现有的基于预训练的推荐模型研究进展，对不同的预训练方法进行分类和比较，并在三个推荐系统基准数据集上对一些代表性模型进行实验和分析，相关的数据集和代码已开源，希望能对相关领域的研究人员带来便利，最后对预训练的推荐模型的未来发展趋势进行总结和展望。</div>
<div>杨纪元 (山东大学),马沐阳 (山东大学),任鹏杰 (山东大学),陈竹敏 (山东大学),任昭春 (山东大学),辛鑫 (山东大学),蔡飞 (国防科技大学) and马军 (山东大学)</div>
<p></p>
<div style="font-weight: bold">Multi-View Based Method for Tourism Similar Question Matching</div>
<div>At present, tourism community question-and-answer platforms serve as the primary means for people to acquire travel-related knowledge, allowing individuals to freely pose questions and provide answers. To enhance service efficiency, identifying similar ques-tions has become a pivotal task for these tourism community platforms. However, due to the diversity and complexity of natural lan-guage, there are instances of differently phrased similar questions and differently expressed distinct questions related to various aspects of travel. As a result, how to accurately measure the similarity between two questions remains a challenge. To address this, the paper presents a Multi-View based Joint decision Matching method MVJM, which leverages keywords, intents, and answers to ex-tract the subject information, identify the expressed purpose, and glean additional contextual information from the answer view. On the TQD and QQPa datasets, the proposed method demonstrates consistently stable performance improvement</div>
<div>Hao Wang (Shanxi University), Yang Li (Shanxi University of Finance and Economics), Suge Wang (Shanxi University), Jian Liao (Shanxi University) and Jianxing Zheng (Shanxi University)</div>
<p></p>
<div style="font-weight: bold">基于多提示学习的方面类别情感分析方法</div>
<div>基于方面类别的情感分析（Aspect-Category Sentiment Analysis, ACSA）旨在辨别评论文本中的方面类别并预测它们的情感极性。对评论文本有效的方面类别情感分析可以为相关平台（如外卖、电商等）提供合理的管理依据，为客户提供良好的消费决策，是情感分析领域重要的细粒度子任务。近年来，基于预训练语言模型微调（Fine-tuning）的方法已经为方面类别情感分析提供了有效的解决思路。然而，由于预训练语言模型和下游情感分类任务目标不一致，影响了情感分析的质量。针对此问题，本文提出了一种基于提示学习的方面类别情感分析方法（Multi-Prompt_ACSA）。首先，在提示学习的基础上进行了提示模板工程和答案工程的多样化设计。然后引入自回归预训练语言模型进行训练。进一步，基于Prompt的多样化设计集成多个不同提示模板下的情感分类结果。与其他相关模型在SemEval 2015和2016数据集上的结果相比，本文提出的方法在F1指标上可以有良好的效果提升。</div>
<div>刘锦行 (湖北工业大学),李琳 (武汉理工大学) and吴任伟 (武汉理工大学)</div>
<p></p>
<div style="font-weight: bold">基于表示对齐增强和外部知识融合的低资源跨语言文本检索</div>
<div>跨语言文本检索是使用一种语言进行查询，并从另一种语言文档集中获取相关文档的过程。在中文-越南语、泰语、缅甸语等低资源跨语言检索任务中，跨语言检索标注数据稀缺且语言差异大，导致查询和文档匹配对齐难度较大。为此，该文分别从跨语言表征对齐和外部知识融合两个层面进行改进，提出了一种基于表示对齐增强和外部知识融合的低资源跨语言文本检索方法。首先，引入多语言知识图谱来丰富查询的知识信息；在此基础上，通过文档-文档和实体文档-外部知识两方面构建了两种监督对比目标，增强模型在低资源跨语言的表示对齐能力；同时，还提出了一种知识互注意力机制，促进融合不同语言对之间的外部知识特征。实验结果表明，该方法在CLIRMatrix数据集中的中文-越南语、泰语、缅甸语检索性能相比于基线模型明显提升，尤其是中文-缅甸语上NDCG@10值提升了4.79%。</div>
<div>Yanbin Wang (Kunming University of Science and Technology), Mao Cunli (Kunming University of Science and Technology), Yongbing Zhang (Kunming University of Science and Technology), Yuxin Huang (Kunming University of Science and Technology), Shengxiang Gao (Kunming University of Science and Technology) and Ran Song (Kunming University of Science and Technology)</div>
<p></p>
<div style="font-weight: bold">基于情感分类的可解释证据提取方法</div>
<div>模型可解释任务旨在反应模型做出预测的原因以及模型的推理过程，而特定的情感可解释任务旨在预测句子情感的同时提取模型预测所依赖的证据。现有的方法在情感分类的准确度上表现良好，但提取的证据在可解释性以及鲁棒性上性能不佳。该文提出了一种基于对抗扰动和边界匹配约束的半监督证据提取的方法，首先在离散空间对样本进行数据增强，之后在表示嵌入空间进行扰动，以降低模型的对对抗样本的敏感度，提高模型鲁棒性；加入边界匹配约束以提高证据提取的精确度以及可读性；最后，利用证据提取的约束提高情感预测的准确度。该模型在LIC2022情感可解释比赛的数据集DuTrust上进行实验，结果表明相比于基线模型，该文模型在预测准确度、证据合理性以及证据一致性指标上相较基线模型分别提升了3.0%、38.9%、14.0%，并在LIC2022情感可解释比赛中排名第二。</div>
<div>Shan He (Harbin Institute of Technology (Shenzhen)), Dongfang Li (Harbin Institute of Technology (Shenzhen)), Baotian Hu (Harbin Institute of Technology (Shenzhen)) and Jindi Yu (Harbin Institute of Technology (Shenzhen))</div>
<p></p>
<div style="font-weight: bold">Multimodal Conversation Emotion Recognition Based on Clustering and Group Normalization</div>
<div>The problem of degradation of recognition effect due to the confusion of similar emotion categories recognition has been a major challenge in multimodal emotion recognition task. To address this problem, a neural network modeling approach based on clustering group normalization for relational graphs is proposed in this paper. Firstly, three modal features are extracted using three different feature extractors and spliced by incorporating speaker encoding, which enriches the feature representation and preserves the original information; secondly, contextual information is extracted using Transformer; then, after the feature nodes are input into the relational graph convolutional neural network, the nodes are clustered and grouped by clustering and independently normalized to make similar nodes more similar, which alleviates the problem of similarity of the nodes. nodes are more similar, which alleviates the problem that similar emotions are difficult to define. Through experimental validation, our network model can reach 86.34% F1 value on the IEMOCAP dataset four classification, which verifies the effectiveness of the method in this paper, and to the best of our knowledge our model achieves the best performance on this dataset.</div>
<div>Luo Qi (Guizhou University) and Gou Gang (Guizhou University)</div>
<p></p>
<div style="font-weight: bold">面向域外说话人适应场景的多层级解耦个性化语音合成</div>
<div>个性化语音合成任务旨在合成特定说话人音色的语音。传统方法在合成域外未见说话人语音时，与真实语音存在明显音色差异，解耦说话人特征仍较为困难。本文提出面向域外说话人适应场景下的多层级解耦个性化语音合成方法，通过不同粒度特征融合，有效提升零资源条件下域外说话人语音合成性能。采用快速傅里叶卷积提取说话人全局特征，以提高模型对未见说话人的泛化能力，实现句子粒度的说话人解耦；借助语音识别模型解耦音素粒度说话人特征，并通过注意力机制捕捉音素级音色特征，实现音素粒度的说话人解耦。实验结果表明，在公开数据集AISHLL3上，本文方法对域外说话人在客观评价指标说话人特征向量余弦相似度上达到了0.697，相比基线模型提高了6.25%，提升对域外未见说话人音色特征建模能力。</div>
<div>Shengxiang Gao (Kunming University of Science and Technology), Shangbin Mo (Kunming University of Science and Technology), Yuanzhang Yang (Kunming University of Science and Technology), Zhengtao Yu (Kunming University of Science and Technology), Linqin Wang (Kunming University of Science and Technology) and Ling Dong (Kunming University of Science and Technology)</div>
<p></p>
<div style="font-weight: bold">Fine-grained Intent Recognition from Pediatric Medical Dialogues with Con-trastive Learning</div>
<div>We can use dialogue system to make preliminary judgments on common pediatric diseases based on symptoms, and guide parents to pay attention to relevant symptoms based on medical knowledge, find critical diseases timely, and make preliminary judgments on common diseases, it will help parents make more appropriate judgments to a certain extent. Hence, in recent years, it has received much more attention. Intent detection is an important task in medial dialogue generation task. Existing methods usually use two separate clas-sifiers to achieve the task. However, these methods may encounter the error propagation problem. In this paper, we propose a model to combine intent detection and slot filling to achieve the fine-grained intent recognition task. Experimental results demonstrated that the proposed method could achieve better performance than pervious methods.</div>
<div>Wenbo Li (Fudan University), Qing Dong (The Affiliated Taian City Central Hospital of Qingdao University), Chao Liu (The Affiliated Taian City Central Hospital of Qingdao University) and Qi Zhang (Fudan University)</div>
<p></p>
<div style="font-weight: bold">基于多特征融合的中文医疗关系抽取</div>
<div>医疗关系抽取可以判断医疗文本中实体间的关系，在医疗领域中起积极作用。现有的关系抽取模型没有充分利用文本的全部特征，如文本的句法层次结构关系。该文提出了一种多特征融合模型（Multi Feature Fusion model, MFF），在使用实体类型标记方法处理文本中的主体和客体的基础上，使用BERT获取语义信息，并使用双向长短时记忆网络（Long Short Term Memory, LSTM）获取其上下文信息，通过图卷积网络（Graph Convolutional Network，GCN）提取多种剪枝策略下的句法依存树中的层次结构信息，最后将获取的多种特征进行融合后进行关系抽取任务。在两个中文医疗实体关系抽取数据集CMeIE和TCM上进行实验，与其它先进模型相比F1值有所提高，证明了模型的有效性。</div>
<div>Dandan Zhao (School of Computer Science and Engineering ,Dalian Minzu University), Zhihao Zhang (School of Computer Science and Engineering ,Dalian Minzu University), Jiana Meng (School of Computer Science and Engineering ,Dalian Minzu University), Wen Su (School of Computer Science and Engineering ,Dalian Minzu University), Yingchun Long (School of Mathematics and Statistics, Puer University) and Junpeng Zhang (School of Computer Science and Engineering ,Dalian Minzu University)</div>
<p></p>
<div style="font-weight: bold">基于弱监督学习的稠密向量检索模型</div>
<div>信息检索系统是人们高效搜索数据的主要方式，也是解决信息过载问题的重要途径。得益于预训练语言模型与大规模检索数据集的提出，稠密向量检索模型被广泛研究与应用。然而，受限于高昂的人工标注成本，大规模检索数据集往往是不完整标注的，包含少量正例和大量无标注样本，是一个典型的弱监督学习问题。采样无标注样本作为负例训练，会导致无标注的正例成为假负例，损害模型训练效果。该文提出应用弱监督学习领域的去偏对比学习和知识蒸馏，以缓解采样无标注时的假负例问题。在MS MARCO 段落检索数据集上进行的一系列实验表明，在采样高排名文档作为难负例时，模型效果显著下降，去偏对比学习方法能够缓解该问题；而知识蒸馏方法则能有效避免假负例问题，提升模型检索效果。</div>
<div>Yi Jia (Renmin University of China) and Jiaxin Mao (Renmin University of China)</div>
<p></p>
<div style="font-weight: bold">基于位置感知时空图卷积网络的交通流量预测</div>
<div>为更加灵活地捕捉交通流数据的时空特征，实现更加精确的多变量交通流预测，该文提出了一种位置感知时空图卷积网络的多变量时间序列预测模型 (PASTGCN)。设计了时空位置嵌入向量模块来对交通流时间序列的时空位置进行显式建模以强调不同节点的空间位置和预测时刻的周期性特征，创新地将两者融入时空依赖建模。利用融入时空位置信息的时间卷积网络来建模时间依赖，空间依赖建模中则使用扩散图卷积网络进行信息传播，并引入静态和动态的双重图学习方法以数据驱动方式捕捉变量间的空间依赖。在两个真实世界交通流数据集上进行了实验，结果表明PASTGCN模型能有效地对多变量交通流速进行预测，预测误差对比现有深度学习模型最好可降低4.68%，具有更高的预测精度。</div>
<div>王子彤 (武汉大学) and李晨亮 (武汉大学)</div>
<p></p>
<div style="font-weight: bold">A Survey of Dimensionality Reduction and Retrieval Algorithms for High Dimensional Data</div>
<div>In recent years, for large-scale model technology, high-dimensional data dimensionality reduction and retrieval methods have become an important research tasks. Nowadays, most high-dimensional data are transformed into vector representations through certain dimensionality reduction methods, and relevant vector retrieval technology is applied to achieve fast retrieval, thereby improving the performance of large models. At present, there are many and scattered dimensionality reduction methods for high-dimensional data, and the dimensionality reduction methods used in different research backgrounds are not always the same. Similarly, there are many different retrieval ideas and optimization methods in vector retrieval technology. This paper briefly describes the main ideas of recent dimensionality reduction and retrieval algorithms and related optimization methods, which will help to generate an inspiring connection between the two, thereby further optimizing the effect of retrieval algorithms.</div>
<div>Wei Shao (CAS Key Lab of Network Data Science and Technology, Institute of Computing Technology, Chinese Academy of Sciences), Gaoyu Zhu (CAS Key Lab of Network Data Science and Technology, Institute of Computing Technology, Chinese Academy of Sciences), Lei Yu (CAS Key Lab of Network Data Science and Technology, Institute of Computing Technology, Chinese Academy of Sciences) and Jiafeng Guo (CAS Key Lab of Network Data Science and Technology, Institute of Computing Technology, Chinese Academy of Sciences)</div>
<p></p>
<div style="font-weight: bold">面向图神经网络表征学习的类别知识探针</div>
<div>近来大量图神经网络方法被提出，并广泛地应用于众多领域，例如社交网络挖掘和分析、生物化学分子分类预测等。然而研究者对于图神经网络模型在执行不同下游任务时表征学习是否学习到图结构本身属性或领域数据属性是未知的，难以解释图神经网络模型知识表征中嵌入了何种类型的信息。该文提出面向图神经网络表征学习的知识探测框架，基于领域数据的类别属性设计两种类别感知的知识探针，分别为聚类探针和对比聚类探针。在引用网络、社交网路和生物网络等三个邻域的八个数据集上对7个经典的图神经网络模型的表征学习实现了系统性地知识探测和评估实验，归纳出建设性的探测和评估结论。</div>
<div>黄兴宇 (中国科学院深圳先进技术研究院), 赵明宇 (中国科学院深圳先进技术研究院) and吕子钰 (中山大学)</div>
<p></p>
<div style="font-weight: bold">基于细粒度问题类型与答案一致性校验的医学视觉问答</div>
<div>医学视觉问答旨在根据医学影像内容准确回答临床问题，具有巨大应用潜力。现有方法统一处理开放性问题和封闭性问题，忽略了开放性问题的复杂多变性，导致模型准确率较低。同时，受语言先验影响，模型容易利用数据集中问答对的偏差分布，削弱了问题与答案的深层关系，导致答非所问。为此，该文针对开放式任务提出一种即插即用的细粒度问题类型与答案一致性校验方法。首先，识别问题为开放式或封闭式任务。然后，对开放式任务问题进行细粒度分类。最后，根据问题类型生成答案掩码，掩盖无关答案，实现问题类型与答案的一致性校验，进而缓解答非所问现象。实验结果表明，该文方法能有效提高医学视觉问答准确率。</div>
<div>戴舒婷 (昆明理工大学), 刘利军 (昆明理工大学) and 杨小兵 (昆明理工大学)</div>
<p></p>
<div style="font-weight: bold">融合量子干涉信息的双重特征文本表示模型</div>
<div>在信息检索领域，量子干涉理论已经被应用于文档相关性、次序效应等核心问题的研究中，旨在建模用户认知所引起的类量子干涉现象。该文从语言理解的需求出发，利用量子理论的数学工具分析语义组合过程中存在的语义演化现象，进而提出一种融合量子干涉信息的双重特征文本表示模型（QDTM）。该模型以约化密度矩阵为语言表示的核心组件，有效建模维度级别的语义干涉信息；在此基础上，构建捕获全局特征信息与局部特征信息的模型结构，满足语言理解过程中不同粒度的语义特征需求。在文本分类和问答数据集上的实验结果表明，QDTM模型的性能超越量子启发的语言模型和神经网络文本匹配模型。</div>
<div>Hui Gao (Tianjin University), Peng Zhang (Tianjin University) and Jing Zhang (Tianjin University)</div>
<p></p>
<div style="font-weight: bold">论元角色多指称的主题事件论元抽取</div>
<div>作为信息抽取的一项重要任务，事件抽取的目标是从非结构化文本中识别事件及其类型，进而抽取事件的相关论元以及判断其角色。根据处理文本范围的不同，事件抽取可分为句子级事件抽取和篇章级事件抽取，篇章级事件抽取根据关注的内容不同又可以分为跨句事件抽取和主题事件抽取。该文主要关注能够概括篇章的主要内容的事件，即主题事件抽取任务。主题事件论元抽取作为主题事件抽取的关键部分，对整个任务的性能具有直接影响。因此，该文重点关注如何提高主题事件论元抽取的效果。当前主题事件论元抽取面临着论元角色多指称的挑战，即篇章中多个不同的论元指称对应同一个角色。针对该挑战，该文提出了一种面向论元角色多指称的论元抽取方法MSQAE。MSQAE将主题事件论元抽取任务转换为多答案问答任务，通过利用预训练语言模型中不同层次的模块捕获到的多种语义特征，计算出候选文本片段和论元多指称数量。进而采用非最大抑制算法从候选文本片段中抽取相应数量的目标论元指称集合。实验结果表明，该方法充分利用了论元角色信息，在处理论元角色多指称情况下取得了更好的效果。</div>
<div>Xing Zhang (Institute of Computing Technology, Chinese Academy of Sciences), Yucan Guo (Institute of Computing Technology, Chinese Academy of Sciences), Xiaolong Jin (Institute of Computing Technology, Chinese Academy of Sciences) and Saiping Guan (Institute of Computing Technology, Chinese Academy of Sciences)</div>
<p></p>
<div style="font-weight: bold">基于EEG的短视频用户情感倾向研究</div>
<div>该文通过用户实验，探究了差异化信息环境是否会对用户的情感倾向产生不同影响。该文将室内实验研究和田野研究结合，利用非侵入式EEG设备，收集了用户在使用包含不同情感倾向的短视频推荐系统前后的脑电信号数据和量表数据。量表方差分析发现用户的情感分数在不同情感倾向的信息环境下有显著差异（p=0.041）；不同信息环境作用后，脑电信号能量变化差异明显。差异化信息环境会对用户的情感倾向产生不同影响。</div>
<div>Bangde Du (Tsinghua University), Qingyao Ai (Tsinghua University), Yiqun Liu (Tsinghua University) and Ziyi Ye (Tsinghua University)</div>
<p></p>
<div style="font-weight: bold">基于生物实体关系感知的图神经排序</div>
<div>生物医学信息检索的性能在很大程度上取决于生物医学知识，然而现有医学知识库的知识往往是不完备和滞后的。针对不完备的知识库无法提供生物医学信息检索所需的医学知识的问题，该文提出了一种基于生物实体关系感知图神经排序模型（Entity Relation Aware Graph Neural Ranking, ERAGNR），旨在充分利用文档的内部知识来缓解外部知识库不完整所带来的问题。ERAGNR通过实体关系抽取挖掘文档中生物医学实体之间的关系，并将其与外部知识相结合，增加了语义关联，减少了查询与文档之间的语义差距。该方法首先构建知识-查询图和文档-实体图，然后将两个图融合，得到知识-查询-文档-实体图。在文本检索任务和关系抽取任务的多任务学习框架下，基于共享文本编码器和图神经网络，ERAGNR可以学习查询和文档之间的语义匹配模式，同时识别文档中实体之间的关系，从而使模型能够捕捉实体关系上下文与查询之间的语义匹配信号。实验结果表明，ERAGNR优于最先进的模型。通过生物医学关系提取任务，模型可以学习捕捉文档中实体关系上下文的能力，从而使模型能更准确地匹配查询和文档之间的语义。</div>
<div>Yichen He (South China University of Technology), Xiaofeng Liu (Digital Guangdong Network Construction Company) and Shoubin Dong (South China University of Technology)</div>
<p></p>
<div style="font-weight: bold">基于领域对比自适应模型的大学生焦虑心理分析</div>
<div>焦虑心理检测任务是利用自然语言处理技术对用户在社交媒体上发布的内容进行分析。在该文中，我们开发了一个数据集，旨在促进微博中对大学生焦虑心理检测的研究。针对数据集标注成本高等问题，该文从无监督的角度考虑对新冠疫情背景下的零样本数据进行分析，提出了基于领域对比学习的自适应模型（Domain Adaptive Network Based on Contrast Learning，DAN-CL）。DAN-CL基于预训练模型，将源文本和目标文本进行对抗性领域自适应训练，并采用对比学习方法提高模型的泛化能力。基准实验结果表明，DAN-CL的性能优于对比模型，消融实验进一步证明了模型中不同部分的有效性。此外，针对大学生的心理状况进行分析发现受疫情的影响其心理焦虑水平显著升高，该文对焦虑产生的原因具体分析并提出对策，为后疫情时代以及突发公共卫生事件下应对大学生的心理健康挑战提供理论支持。</div>
<div>Weiwei Zhu (Dalian Maritime University), Yijia Zhang (Dalian Maritime University), Guantong Liu (Dalian Maritime University), Mingyu Lu (Dalian Maritime University) and Hongfei Lin (Dalian University of Technology)</div>
<p></p>
<div style="font-weight: bold">基于内在奖励的强化学习推荐探索策略</div>
<div>近年来强化学习算法被引入推荐系统以解决探索-利用问题，改善平台上用户体验并提升系统长期效益。现有研究主要从模型层面进行探索策略设计，但大部分工作很少考虑用户体验对探索策略的影响。本研究提出通过修改奖励的方式设计探索策略，充分考虑强化学习在推荐场景下将用户建模为环境的特殊性，将商品多样性和新颖性作为内在奖励，利用用户体验指导模型的探索方向。该文在两个不同类型的真实数据集上进行实验，实验结果表明所提出方法在推荐性能和推荐商品多样性等各项指标上实现了明显的效果提升，验证了所提出探索策略的有效性。</div>
<div>Yuanqing Yu (Tsinghua University), Weizhi Ma (Tsinghua University) and Min Zhang (Tsinghua University)</div>
<p></p>
<div style="font-weight: bold">融合依存句法分析的言论抽取方法</div>
<div>互联网信息的膨胀式涌现催生了从海量信息中提取关键信息的研究热潮。新闻内容中的言论抽取是其中 的重要组成部分，其效果直接影响立场检测、观点挖掘、情感分析等下游任务的准确性。言论抽取领域的相关工作， 从基于规则式的方法、到基于机器学习和深度学习的抽取方法，效果有了明显的提升。但由于忽略了构成言论要素之 间的差异，且对于复杂的嵌套言论缺乏基本处理能力，造成言论抽取效果进一步提升遇到了瓶颈。为了解决这些问题， 该文提出了一种融合依存句法分析的言论抽取方法，实验结果显示该方法能够提高言论抽取的性能，针对最难抽取的 言论内容组成成分，中英文数据集抽取结果 F1 值分别提升 1.9，3.9，能够一致提高下游任务性能。</div>
<div>da Li (CAS-ICT), Xiangyu Zhang (CAS-ICT), Xichou Zhu (CAS-ICT), Lei Yu (CAS-ICT) and Jiafeng Guo (CAS-ICT)</div>
<p></p>
<div style="font-weight: bold">AID-GCN：基于图卷积网络的推荐系统自适应交互去噪</div>
<div>点击等用户交互在近年来被广泛应用于构建推荐系统。然而，现有绝大多数推荐算法简单地使用全部交互数据，忽略了在真实系统中噪声交互的负面影响。少数最新研究试图引入辅助信息或者预定义策略来独立地识别每个交互是否是噪声，忽略了交互数据的全局信息。因此，该文提出了一种基于图卷积网络的推荐系统自适应交互去噪框架（AID-GCN），在不引入辅助信息和预定义策略的情况下识别噪声交互。首先，AID-GCN框架为每个交互设置可训练的可靠性参数，并对该参数应用全局稀疏和低秩约束。其次，AID-GCN框架基于可靠性参数生成更真实的邻接矩阵到图卷积网络中。最后，AID-GCN框架迭代地更新图卷积网络和可靠性参数，提高基础推荐模型性能。三个公开数据集上的实验结果表明，AID-GCN框架在多种基于图卷积网络的基础推荐模型上比去噪基线算法有显著提升。</div>
<div>Shihong Yan (Tsinghua University), Weizhi Ma (Tsinghua University), Min Zhang (Tsinghua University), Yiqun Liu (Tsinghua University) and Shaoping Ma (Tsinghua University)</div>
<p></p>
<div style="font-weight: bold">一种基于核心论元的篇章级事件抽取方法</div>
<div>篇章级事件抽取可以从篇章文本中自动抽取出用户感兴趣的结构化事实信息，在金融、法律、医疗、新闻等领域有很高的应用价值。本文提出了一种基于核心论元的篇章级事件抽取选取方法CA-DocEE，该方法根据论元在篇章级事件中的分布特点定义了核心论元的选取标准，采用异质图卷积神经网络将篇章上下文信息用于增强论元实体编码，基于机器阅读理解方法捕捉句子中的深层次语义信息来进行论元角色分类。在篇章级事件抽取数据集ChFinAnn上，本文提出的方法达到了80.1%的微平均F1值，取得了与目前已知最好方法可比的效果。</div>
<div>Chengjie Sun (School of Computer Science and Technology, Harbin Institute of Technology, Harbin, P.R. China), Zongwei Li (School of Computer Science and Technology, Harbin Institute of Technology, Harbin, P.R. China), Lili Shan (Harbin Institute of Technology) and Lei Lin (Harbin Institute of Technology)</div>
<p></p>
<div style="font-weight: bold">多尺度差分算子收敛语义的命名实体识别方法</div>
<div>针对实体在平面化句子表示之间存在语义扩散到相邻单位导致语义混淆的问题，提出多尺度差分算子收敛语义的命名实体识别方法。首先利用预训练模型将句子表示为包含上下文信息的字符嵌入向量；其次通过多头双仿射将字符嵌入向量转化为平面化句子表示，平面化句子表示中的每个单元代表所包含的跨度信息；然后，采用差分信息来表征跨度单元的上下文语义突变及细节特征，从而聚合语义强度和梯度信息；最后，通过解码器识别实体类型。该模型在 ACE2005 英文、中文数据集上进行实验，F1 值分别达到了 86.85%和 89.43%。实验结果表明，与其他现有主流模型相比，该模型能更好地识别命名实体。</div>
<div>Caiwei Yang (Guizhou University), Yanping Chen (Guizhou University), Yongbin Qin (Guizhou University) and Ruizhang Huang (Guizhou University)</div>
<p></p>
<div style="font-weight: bold">Contrastive Dynamic Graph for Sequential Recommendation</div>
<div>To alleviate the problems in dynamic graph sequential recommendation, such as sparse and noisy user-item interaction data, and the requirement for a large number of labeled samples in model training, this paper proposed a new dynamic graph sequential recom-mendation method based on contrastive learning, which was called CDGSR (Contrastive Dynamic Graph for Sequential Recom-mendation). Specifically, CDGSR designed three different contrastive learning methods from coarse-grained to fine-grained: inter layer contrastive learning, twice propagation contrastive learning and random noise perturbation contrastive learning. These methods established different contrastive views for node representations in dynamic graphs to capture self-supervised information in user-item interaction data to assist in recommendation tasks. Experiments on three real-world datasets show that CDGSR outperforms the most advanced dynamic graph sequential recommendation methods and improves the accuracy of recommendation</div>
<div>Yu Cui (Zhejiang University), Jiawei Chen (Zhejiang University) and Can Wang (Zhejiang University)</div>
<p></p>
<div style="font-weight: bold">结合一阶逻辑的弱监督中文命名实体识别方法</div>
<div>针对中文命名实体识别中存在实体类型数量少、噪声多的特点，导致模型特征学习能力和泛化性差的问题。本文提出一种结合一阶逻辑的弱监督中文命名实体识别方法。首先，根据中文命名实体识别数据集的特点定义一阶逻辑知识库；其次，与自训练方法相结合，解决实体类型数量较少导致模型特征学习较差的问题；最后，将一阶逻辑知识库融入模型，纠正训练过程中的错误标签，以降低噪声来提高模型泛化能力。在公共数据集 ACE05 上相较于基线模型 F1 值提高了 2.56%，实验结果证明了本文方法的有效性。</div>
<div>Xi Tang (Beijing Forestry University) and Dongchen Jiang (Beijing Forestry University)</div>
<p></p>
<div style="font-weight: bold">一种融合词性编码信息的中文拼写校正模型</div>
<div>中文拼写校正任务的目的是检测和纠正汉语文本中存在的拼写错误。目前主流的方法致力于提取和融合中文字符的声学和图形特征等高级特征，往往忽视了词性这种底层特征所包含的信息。基于这一问题，本文提出一个新的中文拼写校正模型WPESpell(With POS Embedding Chinese Spelling Correction)，将句子的词性编码信息有效融合到校正模型中。该模型分为三个模块：(1)词性预测模块预测输入句子中每个位置的词性，并将编码器最后一个隐藏层表示传递给错字校正模块；(2)词性编码模块对预测的词性序列进行编码以获取词性信息并送入BERT(Bidirectional Encoder Representations from Trans-formers)中进一步学习；(3)错字校正模块将传递来的隐藏层表示与BERT最终层的隐藏状态合并预测每个位置的输出字符。在通用数据集SIGHAN15上的实验结果表明本文所提方法在检测水平和校正水平的Rec评价指标上优于现有的主流模型。</div>
<div>孙胜 (East China Jiaotong University) and王鹏鸣 (Wenzhou Institute of Science and Technology)</div>
<p></p>
<div style="font-weight: bold">基于融合特征多重异构网络的新浪微博社交机器人检测方法</div>
<div>基于图神经网络的社交机器人检测方法是近年来社交机器人检测领域的一个研究热点，该方法引入了社交关系网络来刻画账号之间的关联关系，进而构建了能表征多种网络关系的多重异构图神经网络，该网络结构可以更丰富地刻画账号之间的互动、关注等关系。现在图网络的方法仍然存在两个方面的问题：一是现有的网络方法构建方法相对单一，对用户社交关系的依赖性比较强、迁移性较差；二是目前社群发现方法与深度图网络模型结合的研究相对较少，缺乏对机器人社群特征的引入，导致弱化了群体操控机器人的识别效果。基于以上问题本文提出了融合群体特征多重异构网络模型MCF-RGCN，该模型针对新浪微博数据构建了用户元信息特征、用户行为特征、内容特征、时序特征、社交网络特征等五大类特征，通过引入话题共现关系构建了文本信息网络，使模型在不依赖社交关系的情况下也能获得良好的社交机器人检测效果；同时通过社群发现方法对相似特征账号进行聚类，挖掘出账号的社群属性特征作为模型输入，进一步提升了模型对具备相似群体特征的社交机器人的检测能力。在实验数据集上的实验结果表明该方法相比主流的社交机器人检测方法在F1值指标上提升近6%。</div>
<div>Zhang Huaibo (Institute of Computing Technology), Liu Xiaona (Institute of Computing Technology), Feng Haoyuan (Institute of Computing Technology), Yin Zhiyi (Institute of Computing Technology), Shen Huawei (Institute of Computing Technology) and Liu Xin (Intelligent Collaborative Perception and Cognitive Analysis Laboratory)</div>
<p></p>
<div style="font-weight: bold">SSHGCN:基于音形异构图卷积的中文纠错方法</div>
<div>中文拼写纠错是一项具有挑战性的任务，旨在自动检测和纠正中文文本中存在的拼写错误。许多拼写错误是由汉字之间的读音和形状相似性引起的，现有最新的方法已经尝试使用图卷积将字符相似性建模成图结构信息。然而目前方法的图结构忽略拼音相似关系能更好反映汉字之间的深层音近关系，并且缺少充分发挥字音和字形两种特征作用的多模态信息融合方法。因此本文在引入拼音相似关系并融合汉字形近关系，构建基于相似拼音-形近异构图的图卷积用于中文文本纠错，更加深入探索相似汉字的误用模式。在SIGHAN15基准上的多项实验评估分数均有提升，验证了该方法的有效性。</div>
<div>任俊 (Guizhou University) and黄瑞章 (Guizhou University)</div>
<p></p>
<div style="font-weight: bold">中文去毒任务的研究</div>
<div>通过改写文本以消除句子中的冒犯性含义可以达到去除文本毒性的目的，该任务在英文领域已存在一定的研究，但中文领域的文本去毒任务因数据匮乏等因素而未有太多工作。针对上述问题，本文重构了一个中文毒性语料集作为研究的数据基础。此外，中文语言表达的多样性通常会让文本的情感体现较为直接或者隐晦。为此，本文探究了文本的毒性表现形式，同时对特定类别的毒性文本成因展开了分析。基于上述分析结果，本文使用基于编辑式、生成式两类文本风格迁移模型进行文本去毒，并探究基于 Prompt 的大语言模型去除文本毒性的表现。据实验结果表明，基于编辑式的模型能有效去除显式毒性文本的毒性，且具有较高的内容保存度，生成式模型生成的文本则有更高的流畅度。此外，基于 Prompt 的大语言模型在一定程度上可以去除句子毒性，但相较于特定的风格迁移模型而言，去毒能力还有待提高。</div>
<div>Jiangsheng Liu (15179082993), Jiali Zuo (13576950813) and Yuting Hu (18779228141)</div>
<p></p>
<div style="font-weight: bold">基于动态邻居选择的知识图谱事实错误检测方法</div>
<div>知识图谱是一种重要的知识表示方法和知识存储载体，其建模知识的准确程度会极大影响下游任务的效果。然而，由于知识图谱的构建和更新通常依赖大量网络数据和自动化方法，因此所建模和获取的知识内容难免存在各种事实错误。为了解决这个问题，我们提出了一种新知识图谱事实错误检测方法，该方法动态选择待检测事实的邻居节点，通过捕捉头尾实体之间的复杂关系来判断事实是否存在错误。具体来说，首先利用图结构信息来确定每个实体的潜在邻居。然后，根据实体的上下文信息动态地选择相关邻居，进而使用高效的图注意力网络编码节点的特性。最终通过计算节点的头尾实体表示的一致性，判断待检测事实是否存在错误。我们在多个公开的知识图谱数据集上进行了实验，结果表明我们的方法在错误检测方面表现优于现有的方法。</div>
<div>Liang Gui (University of Chinese Academy of Sciences) ,Shizhu He (University of Chinese Academy of Sciences), Yao Xu(University of Chinese Academy of Sciencec), Kang Liu(University of Chinese Academy of Science) and JunZhao(University of Chinese Academy of Science)</div>
<p></p>
<div style="font-weight: bold">基于二维增强融合机制的事件论元抽取</div>
<div>针对现有的事件论元抽取研究中触发词和论元间缺少交互以及通道内部缺少交互的问题，提出基于二维增强融合机制的事件论元抽取模型。首先，为句子中的触发词打上带有事件类型的标识符，增强触发器和论元交互的同时引入了事件类型信息，并且单独利用 BERT 编码触发词再结合整句语义信息，用以强调句子中触发词的语义信息。其次我们将面向论元的标签合并到在实体识别领域中最先进的基于词-词关系预测的二维网格标记模型中以生成句子的平面化表示，最后在此基础上使用增强融合机制让网络重点关注词的某些特征并锐化事件论元位置的边缘。我们在 ACE05 数据集上进行了实验，实验结果表明本文方法相较其他的基于分类的事件论元抽取方法提升了 1.8%。</div>
<div>Luxiang Wang (Guizhou University), Yanping Chen (Guizhou University), Hui Huang (Guizhou University), Ruizhang Huang (Guizhou University) and Yongbin Qin (Guizhou University)</div>
<p></p>
<div style="font-weight: bold">基于盒嵌入的无监督任务型对话系统中的域外意图检测</div>
<div>在任务型对话系统的自然语言理解任务中，域外意图（OOD）检测对于保证系统的可靠性至关重要。与依赖手动标记OOD样本的监督学习方法不同，本文专注于无监督OOD检测的场景。为了更好地将表示学习与阈值设置相结合，并提高模型的可解释性，该文提出了一种基于盒嵌入的OOD检测方法。该方法通过盒嵌入方式将意图和类别表示为超矩形，并利用矩形的包含关系计算后验概率。盒嵌入可以更好地表示不同意图之间的层次关系，以更直观的方式表示实体。本文的方法显著提升了OOD检测的准确性，在CLINC和StackOverflow上两个基准数据集上的实验表明，该方法在不同参数下的表现均明显优于基线算法。实验证明了盒嵌入方法在域外检测任务中的有效性，并提升了模型的可解释性。</div>
<div>Heyang Xu (Beijing University of Posts and Telecommunications), Pei Wang (Beijing University of Posts and Telecommunications) and Yutao Mou (Beijing University of Posts and Telecommunications)</div>
<p></p>
<div style="font-weight: bold">构建解释增强的对话式推荐系统</div>
<div>为了更好地衡量对话式推荐系统(CRS)的可解释性，该文根据传统推荐系统的概念和CRS的特点提出了十个评估视角，并使用这些指标对现有的三个对话式推荐系统基准数据集进行了评估，发现有必要提高对话式推荐系统的解释质量。为此，本文采用人工方法拓展了已有的CRS数据集，构建了一个新的CRS 数据集，即可解释推荐对话(E-ReDial)，该数据集包括756个对话和2,000多条高质量的重写解释。该文比较了基于E-ReDial生成解释的基准方法，实验结果表明，基于E-ReDial训练的模型可以显著提高可解释性，而将知识引入模型则可以进一步提高性能。</div>
<div>郭书宇 (山东大学),孙维纬 (山东大学),任鹏杰 (山东大学),陈竹敏 (山东大学),辛鑫 (山东大学),马军 (山东大学) and任昭春 (山东大学)</div>
<p></p>
<div style="font-weight: bold">大语言模型作为高效的零样本排序器</div>
<div>大模型在相关性排序任务上展现出了较强的零样本能力。但是已有方法往往需要较为复杂的任务和指令设计，以激发大模型潜在排序能力。这类方法往往面临较高的复杂度和不稳定输出的挑战。针对上述挑战，该文提出了指令蒸馏方法。该方法利用自蒸馏，通过将复杂指令激发出的能力蒸馏到用简单指令进行推理的模型中，提高模型稳定性和效果的同时，提升模型的推理效率。在TREC-DL19，TREC-DL20和BEIR数据集上的实验上表明，本文所提出的指令蒸馏方法相较于已有的复杂指令方法在效率上高10-100倍，同时在效果上超过了已有的有监督微调和无监督指令方法。</div>
<div>Zheng Chen (Shandong University), Weiwei Sun (Shandong University), Xinyu Ma (Baidu Inc), Lingyong Yan (Baidu Inc), Shuaiqiang Wang (Baidu Inc), Pengjie Ren (Shandong University), Zhumin Chen (Shandong University), Dawei Yin (Baidu Inc) and Zhaochun Ren (Shandong University)</div>
<p></p>
<div style="font-weight: bold">融合多重特征的噪声网络对齐方法</div>
<div>网络对齐是寻找网络之间节点对应关系的任务，具有广泛的应用场景，包括数据发现，社交网络分析和知识图谱融合。然而，真实场景的网络对齐任务中存在着网络结构差异大以及锚点对噪声高的问题，给网络对齐任务带来了较大的干扰，如何减轻数据中噪声的影响，有效利用已对齐的锚点对数据仍是一项重要挑战。为此，该文提出了一种基于多轮迭代的网络对齐方法，在每轮迭代时使用多种启发式方法的组合来评估上一轮对齐结果的可靠性，以过滤其中潜在的噪声。同时，使用图神经网络增强无属性节点之间的一致性，减轻网络结构差异带来的影响。实验结果表明该方法可以在高噪声的情况下达到高准确率，验证了其有效性。</div>
<div>咸宁 (中国科学院计算技术研究所网络数据科学与技术重点实验室，中国科学院大学),范意兴 (中国科学院计算技术研究所网络数据科学与技术重点实验室，中国科学院大学),郭嘉丰 (中国科学院计算技术研究所网络数据科学与技术重点实验室，中国科学院大学) and廉涛 (太原理工大学大数据学院)</div>
<p></p>
<div style="font-weight: bold">MAVAE:用于反讽检测的多维注意力变分自编码器</div>
<div>反讽在社交媒体上是一种普遍现象，以简洁地传达意义、情感和态度。反讽检测是自然语言处理领域的一个关键研究任务，现有研究通过融入语言特征取得了一定改进，但反讽的模糊性仍然是影响该任务性能的挑战之一，现有方法难以解决这一问题。为了克服这一挑战，本文提出了一种新颖的端到端多维注意力变分自动编码器（MAVAE）网络，用于检测反讽现象。该架构由注意力编码器、注意力解码器和反讽检测器组成，能够通过结合多维表示、双向GRU和注意力机制来检测反讽。MAVAE模型不仅引入了基于多维表示的重构语义信息以提高泛化能力，还通过采用基于双向GRU和注意力机制的变分自动编码器网络来检测反讽。这种设计使得MAVAE模型能有效捕捉模糊信息并增强泛化能力，有助于反讽检测。借助常见的互联网争论语料库的实验结果证明了MAVAE模型的有效性和先进性。</div>
<div>刁宇峰 (内蒙古民族大学),杨亮 (大连理工大学),李世琪 (内蒙古民族大学),樊小超 (新疆师范大学) and林鸿飞 (大连理工大学)</div>
<p></p>

</div>

{% endcapture %}
{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}
