# Influence Maximization and Influence Learning papers
 
<p align="center">
  <img width="300" src="im.PNG">
</p>
 <center><sup>*Image from <a href=https://slideplayer.com/slide/5260408/>Ding Zhu-Du</a> </sup></center>

A list of influence maximization and influence learning papers, organized based on the type of data they rely on, their exact target and their constraints:


- Static Network
- Time Constraint
- Location Constraint
- Topic Constraint
- Competitive
- Dynamic Network 
- Diffusion Cascades 
- Online
- Adaptive
- Influence Learning 
- Surveys
<!--- - Datasets -->


## Static Network

- **Mining the network value of customers**
  - Domingos, Pedro and Richardson, Matt
  - KDD 2001 [[Paper]](https://homes.cs.washington.edu/~pedrod/papers/kdd01a.pdf)

- **Maximizing the spread of influence through a social network**
  - Kempe, David and Kleinberg, Jon and Tardos, {\'E}va
  - KDD 2003 [[Paper]](https://www.cs.cornell.edu/home/kleinber/kdd03-inf.pdf)

- **Influential nodes in a diffusion model for social networks**
  - Kempe, David and Kleinberg, Jon and Tardos, {\'E}va
  - ICALP2005 [[Paper]](http://www.leonidzhukov.net/hse/2015/networks/papers/icalp05-inf.pdf)

- **On the submodularity of influence in social networks**
  - Mossel, Elchanan and Roch, Sebastien
  - Theory of computing 2007 [[Paper]](https://arxiv.org/pdf/math/0612046.pdf)

- **Cost-effective outbreak detection in networks**
  - Leskovec, Jure and Krause, Andreas and Guestrin, Carlos and Faloutsos, Christos and VanBriesen, Jeanne and Glance, Natalie
  - KDD 2008[[Paper]](https://www.cs.cmu.edu/~jure/pubs/detect-kdd07.pdf)

- **Efficient influence maximization in social networks**
  - Chen, Wei and Wang, Yajun and Yang, Siyu
  - KDD 2009 [[Paper]](http://snap.stanford.edu/class/cs224w-readings/chen09influence.pdf)

- **Scalable influence maximization for prevalent viral marketing in large-scale social networks**
  - Chen, Wei and Wang, Chi and Wang, Yajun
  - KDD 2010[[Paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/msr-tr-2010-2_v2.pdf)

- **Simpath: An efficient Algorithm for Influence Maximization under the Linear Threshold model**
  - Goyal, Amit and Lu, Wei and Lakshmanan, Laks VS
  - ICDM 2011[[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.722.4522&rep=rep1&type=pdf)

- **Scalable and parallelizable processing of influence maximization for large-scale social networks?**
	- Kim, Jinha and Kim, Seung-Keol and Yu, Hwanjo
	- ICDE 2013

- **Staticgreedy: solving the scalability-accuracy dilemma in influence maximization**
	- Cheng, Suqi and Shen, Huawei and Huang, Junming and Zhang, Guoqing and Cheng, Xueqi
	- CIKM 2013 [[Paper]](https://arxiv.org/pdf/1212.4779.pdf)

- **Fast and accurate influence maximization on large networks with pruned monte-carlo simulations**
	- Ohsaka, Naoto and Akiba, Takuya and Yoshida, Yuichi and Kawarabayashi, Ken-ichi
	- AAAI 2014[[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8455/8411)

- **Maximizing social influence in nearly optimal time**
  - Borgs, Christian and Brautbar, Michael and Chayes, Jennifer and Lucier, Brendan
  - SODA 2014 [[Paper]](https://arxiv.org/pdf/1212.0884.pdf)

- **IMRank: influence maximization via finding self-consistent ranking**
  - Cheng, Suqi and Shen, Huawei and Huang, Junming and Chen, Wei and Cheng, Xueqi
  - SIGIR 2014[[Paper]](https://arxiv.org/pdf/1402.3939.pdf) 

- **Sketch-based Influence Maximization and Computation: Scaling up with Guarantees**
  - Cohen, Edith and Delling, Daniel and Pajor, Thomas and Werneck, Renato F
  - CIKM 2014 [[Paper]](https://arxiv.org/pdf/1408.6282.pdf)

- **Influence maximization: Near-optimal time complexity meets practical efficiency**
  - Tang, Youze and Xiao, Xiaokui and Shi, Yanchen
  - SIGMOD 2014[[Paper]](https://arxiv.org/pdf/1404.0900.pdf)

- **Fast and accurate influence maximization on large networks with pruned monte-carlo simulations**
  - Ohsaka, Naoto and Akiba, Takuya and Yoshida, Yuichi and Kawarabayashi, Ken-ichi
  - AAAI 2014[[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8455/8411)

- **Influence maximization in near-linear time: A martingale approach**
  - Tang, Youze and Shi, Yanchen and Xiao, Xiaokui
  - SIGMOD 2015
  
- **IOn the upper bounds of spread for greedy algorithms in social network influence maximization**
  - Zhou, Chuan and Zhang, Peng and Zang, Wenyu and Guo, Li
  - TKDE 2015[[Paper]](https://www.researchgate.net/publication/277649229_On_the_Upper_Bounds_of_Spread_for_Greedy_Algorithms_in_Social_Network_Influence_Maximization)

- **Stop-and-stare: Optimal sampling algorithms for viral marketing in billion-scale networks**
  - Nguyen, Hung T and Thai, My T and Dinh, Thang N
  - SIGMOD 2016[[Paper]](https://www.researchgate.net/publication/277649229_On_the_Upper_Bounds_of_Spread_for_Greedy_Algorithms_in_Social_Network_Influence_Maximization)

- **Holistic influence maximization: Combining scalability and efficiency with opinion-aware models**
	- Galhotra, Sainyam and Arora, Akhil and Roy, Shourya
	- SIGMOD 2016[[Paper]](https://arxiv.org/pdf/1602.03110.pdf)
	 
- **Revisiting the stop-and-stare algorithms for influence maximization**
  - Huang, Keke and Wang, Sibo and Bevilacqua, Glenn and Xiao, Xiaokui and Lakshmanan, Laks VS
  - VLDB 2017[[Paper]](https://pdfs.semanticscholar.org/6d07/996dafc1cb3f20317b17398a058fd62a2683.pdf)

- **Optimizing influence diffusion in a social network with fuzzy costs for targeting nodes**
  - Ni, Yaodong and Shi, Qiaoni and Wei, Zhiyuan
  - Journal of Ambient Intelligence and Humanized Computing 2017  

- **MATI: An efficient algorithm for influence maximization in social networks**
  - Rossi, Maria-Evgenia G and Shi, Bowen and Tziortziotis, Nikolaos and Malliaros, Fragkiskos D and Giatsidis, Christos and Vazirgiannis, Michalis
  - PloS one 2018



## Time Constraint

- **Time-critical influence maximization in social networks with time-delayed diffusion process**
  - Chen, Wei and Lu, Wei and Zhang, Ning
  - AAAI 2012[[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.879.8645&rep=rep1&type=pdf)

- **Time constrained influence maximization in social networks**
  - Liu, Bo and Cong, Gao and Xu, Dong and Zeng, Yifeng
  - ICDM 2012 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6413881)


- **Influence diffusion dynamics and influence maximization in social networks with friend and foe relationships**
	- Li, Yanhua and Chen, Wei and Wang, Yajun and Zhang, Zhi-Li
	- WSDM 2013 [[Paper]](https://arxiv.org/pdf/1111.4729.pdf)
	
- **Influence spreading path and its application to the time constrained social influence maximization problem and beyond**
  - Liu, Bo and Cong, Gao and Zeng, Yifeng and Xu, Dong and Chee, Yeow Meng
  - TKDE 2013 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6547147)

- **Maximizing rumor containment in social networks with constrained time**
  - Fan, Lidan and Wu, Weili and Zhai, Xuming and Xing, Kai and Lee, Wonjun and Du, Ding-Zhu
  - ASONAM 2014 [[Paper]](https://link.springer.com/content/pdf/10.1007%2Fs13278-014-0214-4.pdf)

- **Influence spreading path and its application to the time constrained social influence maximization problem and beyond**
  - Liu, Bo and Cong, Gao and Zeng, Yifeng and Xu, Dong and Chee, Yeow Meng
  - TKDE 2014[[Paper]](http://tees.openrepository.com/tees/bitstream/10149/592745/2/592745.pdf)


- **Cost-effective viral marketing for time-critical campaigns in large-scale social networks**
  - Dinh, Thang N and Zhang, Huiyuan and Nguyen, Dzung T and Thai, My T
  - Transactions on Networking 2014 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6678627)


- **Influence maximization with novelty decay in social networks**
  - Feng, Shanshan and Chen, Xuefeng and Cong, Gao and Zeng, Yifeng and Chee, Yeow Meng and Xiang, Yanping
  - AAAI 2014 [[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/download/8485/8396)

- **Time-sensitive influence maximization in social networks**
  - Mohammadi, Azadeh and Saraee, Mohamad and Mirzaei, Abdolreza
  - Journal of Information Science 2015 [[Paper]](http://usir.salford.ac.uk/id/eprint/37193/7/JIS-3187-accepted.pdf)


- **DynaDiffuse: A Dynamic Diffusion Model for Continuous Time Constrained Influence Maximization**
  - Xie, Miao and Yang, Qiusong and Wang, Qing and Cong, Gao and De Melo, Gerard
  - AAAI 2015 [[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewPDFInterstitial/9940/9265)

- **Credit distribution for influence maximization in online social networks with time constraint**
  - Pan, Yan and Deng, Xiaoheng and Shen, Hailan
  - Smartcity 2015

- **Towards time-discounted influence maximization**
  - Khan, Arijit
  - CIKM 2016 [[Paper]](http://www.ntu.edu.sg/home/arijit.khan/Papers/TimeInf_CIKM16.pdf)

- **Maximizing time-decaying influence in social networks**
  - Ohsaka, Naoto and Yamaguchi, Yutaro and Kakimura, Naonori and Kawarabayashi, Ken-Ichi
  - ECML/PKDD 2016 [[Paper]](https://pdfs.semanticscholar.org/7124/85b1dca37377a4b94cdd814b04f73df23ecd.pdf)

- **Time-sensitive influence maximization in social networks**
  - Min Hu, Qin Liu, Hejiao Huang, Xiaohua Jia
  - ICCT 2018 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8600272)
  
- **Influence Maximization: A Time-Space Efficient Algorithm**
  - Xia, Ganming
  - IOP Conference Series: Materials Science and Engineering 2019 [[Paper]](https://iopscience.iop.org/article/10.1088/1757-899X/533/1/012048/pdf) 


## Location constraint

- **Efficient location-aware influence maximization**
  - Li, Guoliang and Chen, Shuo and Feng, Jianhua and Tan, Kian-lee and Li, Wen-syan
  - SIGMOD 2014[[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.493.9040&rep=rep1&type=pdf)

- **Location-based influence maximization in social networks**
  - Zhou, Tao and Cao, Jiuxin and Liu, Bo and Xu, Shuai and Zhu, Ziqing and Luo, Junzhou
  - CIKM 2015 [[Paper]](https://www.researchgate.net/publication/301417935_Location-Based_Influence_Maximization_in_Social_Networks)

- **Influence maximization in trajectory databases**
	- Guo, Long and Zhang, Dongxiang and Cong, Gao and Wu, Wei and Tan, Kian-Lee
	- TKDE 2016 [[Paper]](http://www.gntsuntechnologies.com/Projects/2017_java_ieee/07.pdf)
	
- **Distance-aware influence maximization in geo-social network**
  - Wang, Xiaoyang and Zhang, Ying and Zhang, Wenjie and Lin, Xuemin
  - ICDE 2016

- **Efficient distance-aware influence maximization in geo-social networks**
  - Wang, Xiaoyang and Zhang, Ying and Zhang, Wenjie and Lin, Xuemin
  - TKDE 2016

- **Geo-social influence spanning maximization**
  - Li, Jianxin and Sellis, Timos and Culpepper, J Shane and He, Zhenying and Liu, Chengfei and Wang, Junhu
  - TKDE 2017
  
- **Location-aware targeted influence maximization in social networks**
  - Su, Sen and Li, Xiao and Cheng, Xiang and Sun, Chenna
  - Association for Information Science and Technology 2018

- **Location-aware influence maximization over dynamic social streams**
  - Wang, Yanhao and Li, Yuchen and Fan, Ju and Tan, Kian-Lee
  - TOIS 2018[[Paper]](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5159&context=sis_research)

- **Multi-location Influence Maximization in Location-Based Social Networks**
  - Zhang, Zhen and Zhao, Xiangguo and Wang, Guoren and Bi, Xin
  - APWeb 2018
  

## Topic constraint

- **Topic-aware social influence propagation models**
	- Barbieri, Nicola and Bonchi, Francesco and Manco, Giuseppe
	- Knowledge and information systems 2013

- **Social influence analysis in large-scale networks**
	- Tang, Jie and Sun, Jimeng and Wang, Chi and Yang, Zi
	- KDD 2019 [[Paper]](https://cis.temple.edu/~wu/teaching/Spring%202015/KDD09_Social_Influence_Analysis.pdf)

- **Online Topic-aware Influence Maximization Queries**
	- Aslay, Cigdem and Barbieri, Nicola and Bonchi, Francesco and Baeza-Yates, Ricardo A
	- EDBT 2014 [[Paper]](https://www.researchgate.net/profile/Nicola_Barbieri2/publication/261374754_Online_Topic-aware_Influence_Maximization_Queries/links/0deec5342505dbdfc4000000/Online-Topic-aware-Influence-Maximization-Queries.pdf)

- **Scalable topic-specific influence analysis on microblogs**
	- Bi, Bin and Tian, Yuanyuan and Sismanis, Yannis and Balmin, Andrey and Cho, Junghoo
	- WSDM 2014 [[Paper]](http://oak.cs.ucla.edu/~cho/papers/wsdm2014.pdf)


- **Efficient topic-aware influence maximization using preprocessing**
	- Chen, Wei and Lin, Tian and Yang, Cheng
	- Corr 2014 [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.759.2478&rep=rep1&type=pdf)
	
- **Online topic-aware influence maximization**
	- Chen, Shuo and Fan, Ju and Li, Guoliang and Feng, Jianhua and Tan, Kian-lee and Tang, Jinhui
	- VLDB 2015 [[Paper]](https://pdfs.semanticscholar.org/0844/19435227a5bbf54d47ba54e11739756510fd.pdf)

- **Microblogging content propagation modeling using topic-specific behavioral factors**
	- Hoang, Tuan-Anh and Lim, Ee-Peng
	- TKDE 2016 [[Paper]](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4574&context=sis_research)

- **Real-time topic-aware influence maximization using preprocessing**
	- Chen, Wei and Lin, Tian and Yang, Cheng
	- Computational Social Networks 2016 

- **Octopus: An online topic-aware influence analysis system for social networks**
	- Fan, Ju and Qiu, Jiarong and Li, Yuchen and Meng, Qingfei and Zhang, Dongxiang and Li, Guoliang and Tan, Kian-Lee and Du, Xiaoyong
	- ICDE 2018 [[Paper]](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5010&context=sis_research)



## Competitive
- **Competitive influence maximization in social networks**
  - Bharathi, Shishir and Kempe, David and Salek, Mahyar
  - International workshop on web and internet economics 2007 [[Paper]](https://link.springer.com/chapter/10.1007%2F978-3-540-77105-0_31)

- **Threshold models for competitive influence in social networks**
  - Borodin, Allan and Filmus, Yuval and Oren, Joel
  - International workshop on internet and network economics 2010 [[Paper]](http://www.cs.utoronto.ca/~oren/cs_toronto/Publications_files/doc.pdf)

- **Diffusion in social networks with competing products**
  - Apt, Krzysztof R and Markakis, Evangelos
  - Symposium on Algorithmic Game Theory 2011 [[Paper]](https://arxiv.org/pdf/1105.2434.pdf)
	
- **Influence blocking maximization in social networks under the competitive linear threshold model**
  - He, Xinran and Song, Guojie and Chen, Wei and Jiang, Qingye
  - SDM 2012 [[Paper]](https://www.semanticscholar.org/paper/Influence-Blocking-Maximization-in-Social-Networks-He-Song/392ea58ff65d855c06d9035bb72ef4448e7c15e1)

- **A game-theoretic analysis of a competitive diffusion process over social networks**
	- Tzoumas, Vasileios and Amanatidis, Christos and Markakis, Evangelos
	- Workshop on Internet and Network Economics 2012 [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.720.9959&rep=rep1&type=pdf)
	
- **Clash of the contagions: Cooperation and competition in information diffusion**
  - Myers, Seth A and Leskovec, Jure
  - ICDM 2012 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6413872)

- **Game theoretic analysis of a strategic model of competitive contagion and product adoption in social networks**
  - Fazeli, Arastoo and Jadbabaie, Ali
  - Decision and Control 2012 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6426222)

- **The bang for the buck: fair competitive viral marketing from the host perspective**
  - Lu, Wei and Bonchi, Francesco and Goyal, Amit and Lakshmanan, Laks VS
  - KDD 2013 [[Paper]](https://www.cs.ubc.ca/~goyal/research/bang4buck.pdf)
   
- **Influence diffusion dynamics and influence maximization in social networks with friend and foe relationships**
  - Li, Yanhua and Chen, Wei and Wang, Yajun and Zhang, Zhi-Li
  - WSDM 2013 [[Paper]](https://arxiv.org/pdf/1111.4729.pdf)

- **Competitive contagion in networks**
  - Goyal, Sanjeev and Heidari, Hoda and Kearns, Michael
  - Games and Economic Behavior 2014 [[Paper]](https://arxiv.org/pdf/1110.6372.pdf)

- **Strategic resource allocation for competitive influence in social networks**
  - Masucci, Antonia Maria and Silva, Alonso
  - Allerton 2014 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7028557)

- **Social networks with competing products**
  - Apt, Krzysztof R and Markakis, Evangelos
  - Fundamenta Informaticae 2014 [[Paper]](https://arxiv.org/pdf/1204.5636.pdf)


- **New models for competitive contagion**
  - Draief, Moez and Heidari, Hoda and Kearns, Michael
  - AAAI 2014 [[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8399/8481)
	

- **From competition to complementarity: comparative influence diffusion and maximization**
  - Lu, Wei and Chen, Wei and Lakshmanan, Laks VS
  - VLDB 2015 [[Paper]](https://arxiv.org/pdf/1507.00317.pdf)

- **Containment of competitive influence spread in social networks**
  - Liu, Weiyi and Yue, Kun and Wu, Hong and Li, Jin and Liu, Donghua and Tang, Duanping
  - Knowledge-Based Systems 2016

- **Competitive propagation: Models, asymptotic behavior and quality-seeding games**
  - Mei, Wenjun and Bullo, Francesco
  - IEEE Transactions on Network Science and Engineering 2017 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7812795)

- **Competitive diffusion in social networks: Quality or seeding?**
  - Fazeli, Arastoo and Ajorlou, Amir and Jadbabaie, Ali
  - Transactions on Control of Network Systems 2016 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7451232)

- **Competitive rumor spread in social networks**
  - Lim, Yongwhan and Ozdaglar, Asuman and Teytelboym, Alexander
  - SIGMETRICS 2017 [[Paper]](http://t8el.com/wp-content/uploads/2015/06/Competition.pdf)

- **Dominated competitive influence maximization with time-critical and time-delayed diffusion in social networks**
  - Li, Huijuan and Pan, Li and Wu, Peng
  - Journal of computational science 2018

- **A game-theoretic approach for modeling competitive diffusion over social networks**
  - Jafari, Shahla and Navidi, Hamidreza
  - Games 2018 [[Paper]](https://www.mdpi.com/2073-4336/9/1/8/pdf)
	



##  Dynamic Network
- **On influential node discovery in dynamic social networks**
  - Aggarwal, Charu C and Lin, Shuyang and Yu, Philip S
  - SDM 2012 [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.363.1993&rep=rep1&type=pdf)
  

- **Influence maximization in dynamic social networks**
  - Zhuang, Honglei and Sun, Yihan and Tang, Jie and Zhang, Jialin and Sun, Xiaoming
  - ICDM 2013

- **On influential nodes tracking in dynamic social networks**
  - Chen, Xiaodong and Song, Guojie and He, Xinran and Xie, Kunqing
  - SDM 2015 

- **Diffusion maximization in evolving social networks**
  - Gayraud, Nathalie TH and Pitoura, Evaggelia and Tsaparas, Panayiotis
  - Online Social Networks [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.704.2290&rep=rep1&type=pdf)

- **Dynamic influence analysis in evolving networks**
  - Ohsaka, Naoto and Akiba, Takuya and Yoshida, Yuichi and Kawarabayashi, Ken-ichi
  - VLDB 2016 [[Paper]](http://www.vldb.org/pvldb/vol9/p1077-ohsaka.pdf)
	
- **Incremental influence maximization for dynamic social networks**
  - Wang, Yake and Zhu, Jinghua and Ming, Qian
  - International Conference of Pioneering Computer Scientists, Engineers and Educators 2017

- **Tracking influential individuals in dynamic networks**
  - Yang, Yu and Wang, Zhefeng and Pei, Jian and Chen, Enhong
  - TKDE 2017 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7999292)

- **Real-time influence maximization on dynamic social streams**
  - Wang, Yanhao and Fan, Qi and Li, Yuchen and Tan, Kian-Lee
  - VLDB 2017 [[Paper]](https://arxiv.org/pdf/1702.01586.pdf)

- **Fast influence maximization in dynamic graphs: A local updating approach**
  - Yalavarthi, Vijaya Krishna and Khan, Arijit
  - arXiv 2018 [[Paper]](https://arxiv.org/pdf/1802.00574.pdf)



##  Diffusion Cascades 

- **A Data-Based Approach to Social Influence Maximization**
  - Amit Goyal, Francesco Bonchi, Laks V. S. Lakshmanan
  - VLDB 2011 [[Paper]](https://arxiv.org/pdf/1109.6886.pdf)


- **Two evidential data based models for influence maximization in Twitter**
	- Jendoubi, Siwar and Martin, Arnaud and Li{\'e}tard, Ludovic and Hadji, Hend Ben and Yaghlane, Boutheina Ben
	- Knowledge-Based Systems 2017 [[Paper]](https://arxiv.org/pdf/1701.05751.pdf)

- **DiffuGreedy: An Influence Maximization Algorithm Based on Diffusion Cascades**
	- Panagopoulos, George and Malliaros, Fragkiskos D and Vazirgiannis, Michalis
	- Complex Networks and their Applications 2018 [[Paper]](https://hal-centralesupelec.archives-ouvertes.fr/hal-01958915/file/DiffuGreedy.pdf)

- **Identifying topical influencers on twitter based on user behavior and network topology**
	- Alp, Zeynep Zengin and ŞG Öğüdücü 
	- Knowledge-Based Systems 2018

- **Influence maximization by leveraging the crowdsensing data in information diffusion network**
	- Feng Wang, Wenjun Jiang, Guojun Wang, Song Guo
	- Network and Computer Applications 2019

- **Influence Maximization via representation learning**
	- Panagopoulos, George and Vazirgiannis, Michalis and Malliaros, Fragkiskos D
	- arXiv 2019 [[Paper]](https://arxiv.org/pdf/1904.08804.pdf) 
	 

##  Online

- **Online influence maximization**
	- Lei, Siyu and Maniu, Silviu and Mo, Luyi and Cheng, Reynold and Senellart, Pierre
	- KDD 2015 [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.717.2473&rep=rep1&type=pdf)


- **Influence maximization with bandits**
	- Vaswani, Sharan and Lakshmanan, Laks and Schmidt, Mark and others
	- arXiv 2016 [[paper]](https://arxiv.org/pdf/1503.00024.pdf)

- **A learning-based framework to handle multi-round multi-party influence maximization on social networks**
	- Lin, Su-Chen and Lin, Shou-De and Chen, Ming-Syan
	- KDD 2015 [[Paper]](https://mslab.csie.ntu.edu.tw/~MSLAB/publications/Conference/2015/A%20Learning-based.pdf)


- **Stochastic online greedy learning with semi-bandit feedbacks**
	- Lin, Tian and Li, Jian and Chen, Wei
	- NIPS 2015 [[Paper]](https://papers.nips.cc/paper/5930-stochastic-online-greedy-learning-with-semi-bandit-feedbacks.pdf)

- **Online influence maximization under independent cascade model with semi-bandit feedback**
	- Wen, Zheng and Kveton, Branislav and Valko, Michal and Vaswani, Sharan
	- NIPS 2017 [[Paper]](http://papers.nips.cc/paper/6895-online-influence-maximization-under-independent-cascade-model-with-semi-bandit-feedback.pdf)

- **Model-Independent Online Learning for Influence Maximization**
	- Vaswani, Sharan and Kveton, Branislav and Wen, Zheng and Ghavamzadeh, Mohammad and Lakshmanan, Laks and Schmidt, Mark
	- arXiv 2017 [[Paper]](https://pdfs.semanticscholar.org/a3a3/102b6643496a0e96b4bcf8eefa0c7e35334b.pdf)

	
- **Multi-round influence maximization**
	- Sun, Lichao and Huang, Weiran and Yu, Philip S and Chen, Wei
	- KDD 2018 [[Paper]](http://www.weiranhuang.com/publications/MRIM-KDD18.pdf)


##  Adaptive

- **Adaptive Submodularity: A New Approach to Active Learning and Stochastic Optimization**
	- Golovin, Daniel and Krause, Andreas
	- COLT 2010 [[Paper]](http://www.cs.cmu.edu/afs/cs.cmu.edu/Web/People/dgolovin/papers/colt10.pdf)


- **Adaptive influence maximization in social networks: Why commit when you can adapt?**
	- Vaswani, Sharan and Lakshmanan, Laks VS
	- arXiv 2016 [[Paper]](https://arxiv.org/pdf/1604.08171.pdf)

- **No time to observe: Adaptive influence maximization with partial feedback**
	- Yuan, Jing and Tang, Shaojie
	- arXiv 2016 [[Paper]](https://arxiv.org/pdf/1609.00427.pdf)


- **Adaptive influence maximization in dynamic social networks**
	- Tong, Guangmo and Wu, Weili and Tang, Shaojie and Du, Ding-Zhu
	- Transactions on Networking 2017 [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7478154)


- **Efficient algorithms for adaptive influence maximization**
	- Han, Kai and Huang, Keke and Xiao, Xiaokui and Tang, Jing and Sun, Aixin and Tang, Xueyan
	- VLDB 2018 [[Paper]](http://www.vldb.org/pvldb/vol11/p1029-han.pdf)

- **Adaptive submodular influence maximization with myopic feedback**
	- Salha, Guillaume and Tziortziotis, Nikolaos and Vazirgiannis, Michalis
	- ASONAM 2018 [[Paper]](https://arxiv.org/pdf/1704.06905.pdf)

- **Adaptive Influence Maximization with Myopic Feedback**
	- Peng, Binghui and Chen, Wei
	- arXiv 2019 [[Paper]](https://arxiv.org/pdf/1905.11663.pdf)

##  Influence Learning 
	
- **Prediction of information diffusion probabilities for independent cascade model**
	- Saito, Kazumi and Nakano, Ryohei and Kimura, Masahiro
	- Knowledge-based and intelligent information and engineering systems 2008 [[Paper]](https://link.springer.com/chapter/10.1007/978-3-540-85567-5_9)

- **Learning continuous-time information diffusion model for social behavioral data analysis**
	- Saito, Kazumi and Kimura, Masahiro and Ohara, Kouzou and Motoda, Hiroshi
	- ACML 2009 [[Paper]](https://link.springer.com/chapter/10.1007/978-3-642-05224-8_25)	
	
- **Learning influence probabilities in social networks**
	- Goyal, Amit and Bonchi, Francesco and Lakshmanan, Laks VS
	- WSDM 2010 [[Paper]](https://dl.acm.org/citation.cfm?id=1718518)

- **Learning the graph of epidemic cascades**
	- Netrapalli, Praneeth and Sanghavi, Sujay
	- SIGMETRICS 2012 [[Paper]](https://dl.acm.org/citation.cfm?id=2254783)

- **Sparsification of influence networks**
	- Mathioudakis, Michael and Bonchi, Francesco and Castillo, Carlos and Gionis, Aristides and Ukkonen, Antti
	- KDD 2011 [[Paper]](https://dl.acm.org/citation.cfm?id=2020492)


- **Strip: stream learning of influence probabilities**
	- Kutzkov, Konstantin and Bifet, Albert and Bonchi, Francesco and Gionis, Aristides
	- KDD 2013 [[Paper]](https://dl.acm.org/citation.cfm?id=2487657)
	

- **Scalable influence estimation in continuous-time diffusion networks**
	- Du, Nan and Song, Le and Rodriguez, Manuel Gomez and Zha, Hongyuan
	- NeurIPS 2013 [[Paper]](http://papers.nips.cc/paper/4857-scalable-influence-estimation-in-continuous-time-diffusion)
	
- **Efficient topic-aware influence maximization using preprocessing**
	- Chen, Wei and Lin, Tian and Yang, Cheng
	- CoRR 2014 [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.759.2478&rep=rep1&type=pdf)


- **Who influenced you? predicting retweet via social influence locality**
	- Zhang, Jing and Tang, Jie and Li, Juanzi and Liu, Yang and Xing, Chunxiao
	- TKDD 2015 [[Paper]](https://dl.acm.org/citation.cfm?id=2700398)

- **Seismic: A self-exciting point process model for predicting tweet popularity**
	- Zhao, Qingyuan and Erdogdu, Murat A and He, Hera Y and Rajaraman, Anand and Leskovec, Jure
	- KDD 2015 [[Paper]](https://dl.acm.org/citation.cfm?id=2783401)


- **Microblogging content propagation modeling using topic-specific behavioral factors**
	- Hoang, Tuan-Anh and Lim, Ee-Peng
	- TKDE 2016 [[Paper]](https://ieeexplore.ieee.org/abstract/document/7464876/)

- **Recurrent marked temporal point processes: Embedding event history to vector**
	- Du, Nan and Dai, Hanjun and Trivedi, Rakshit and Upadhyay, Utkarsh and Gomez-Rodriguez, Manuel and Song, Le
	- KDD 2016 [[Paper]](https://dl.acm.org/citation.cfm?id=2939875)


- **Recurrent marked temporal point processes: Embedding event history to vector**
	- Du, Nan and Dai, Hanjun and Trivedi, Rakshit and Upadhyay, Utkarsh and Gomez-Rodriguez, Manuel and Song, Le
	- KDD 2016 [[Paper]](https://dl.acm.org/citation.cfm?id=2939875)

	
- **Representation learning for information diffusion through social networks: an embedded cascade model**
	- Bourigault, Simon and Lamprier, Sylvain and Gallinari, Patrick
	- WSDM 2016 [[Paper]](https://dl.acm.org/citation.cfm?id=2835817)

	
- **Scalable Influence Maximization for Multiple Products in Continuous-Time Diffusion Networks.**
	- Du, Nan and Liang, Yingyu and Balcan, Maria-Florina and Gomez-Rodriguez, Manuel and Zha, Hongyuan and Song, Le
	- JMLR 2017 [[Paper]](http://www.jmlr.org/papers/volume18/14-400/14-400.pdf)

- **Predicting information diffusion probabilities in social networks: A Bayesian networks based approach**
	- Varshney, Devesh and Kumar, Sandeep and Gupta, Vineet
	- Knowledge-Based Systems 2017 [[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705117303180)

- **Cascade dynamics modeling with attention-based recurrent neural network**
	- Wang, Yongqing and Shen, Huawei and Liu, Shenghua and Gao, Jinhua and Cheng, Xueqi
	- IJCAI 2017 [[Paper]](https://www.ijcai.org/proceedings/2017/0416.pdf)

- **Cascade Dynamics Modeling with Attention-based Recurrent Neural Network**
	- Wang, Yongqing and Shen, Huawei and Liu, Shenghua and Gao, Jinhua and Cheng, Xueqi
	- IJCAI 2017 [[Paper]](https://www.ijcai.org/proceedings/2017/0416.pdf)


- **Topological recurrent neural network for diffusion prediction**
	- Wang, Jia and Zheng, Vincent W and Liu, Zemin and Chang, Kevin Chen-Chuan
	- ICDM 2017 [[Paper]](https://ieeexplore.ieee.org/abstract/document/8215520/)

- **{DeepCas}: An end-to-end predictor of information cascades**
	- Li, Cheng and Ma, Jiaqi and Guo, Xiaoxiao and Mei, Qiaozhu
	- International Conference on World Wide Web (The WebConf) 2017 [[Paper]](https://dl.acm.org/citation.cfm?id=3052643)	

- **Data-Driven Influence Learning in Social Networks**
	- Wang, Feng and Jiang, Wenjun and Wang, Guojun and Xie, Dongqing
	- Symposium on Parallel and Distributed Processing with Applications (ISPA/IUCC) 2017 [[Paper]](https://ieeexplore.ieee.org/abstract/document/8367407/)
	
- **COSINE: community-preserving social network embedding from information diffusion cascades**
	- Zhang, Yuan and Lyu, Tianshu and Zhang, Yan
	- AAAI 2018 [[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/16364)
	
- **Inf2vec: Latent Representation Model for Social Influence Embedding**
	- Feng, Shanshan and Cong, Gao and Khan, Arijit and Li, Xiucheng and Liu, Yong and Chee, Yeow Meng
	- ICDE 2018 [[Paper]](https://ieeexplore.ieee.org/abstract/document/8509310/)

- **A Sequential Neural Information Diffusion Model with Structure Attention**
	- Wang, Zhitao and Chen, Chengyao and Li, Wenjie
	- CIKM 2018 [[Paper]](https://dl.acm.org/citation.cfm?id=3269275)
		
- **Learning Diffusion using Hyperparameters**
	- Kalimeris, Dimitris and Singer, Yaron and Subbian, Karthik and Weinsberg, Udi
	- ICML 2018 [[Paper]](https://www.sciencedirect.com/science/article/pii/S1053811915006874)

- **{DeepInf: Modeling influence locality in large social networks}**
	- Qiu, JZ and Tang, Jian and Ma, Hao and Dong, YX and Wang, KS and Tang, J
	- KDD 2018 [[Paper]](https://arxiv.org/pdf/1807.05560.pdf)

- **DeepDiffuse: Predicting the 'Who' and 'When' in Cascades**
	- Islam, Mohammad Raihanul and Muthiah, Sathappan and Adhikari, Bijaya and Prakash, B Aditya and Ramakrishnan, Naren
	- ICDM 2018 [[Paper]](https://ieeexplore.ieee.org/abstract/document/8594943/)
		
- **Learning Influence Probabilities and Modelling Influence Diffusion in Twitter**
	- Zhang, Zizhu and Zhao, Weiliang and Yang, Jian and Paris, Cecile and Nepal, Surya
	- TheWebConf 2019 [[Paper]](https://dl.acm.org/citation.cfm?id=3308560.3316701)
	
- **Information Diffusion Prediction with Network Regularized Role-based User Representation Learning**
	- Wang, Zhitao and Chen, Chengyao and Li, Wenjie
	- TKDD 2019 [[Paper]](https://dl.acm.org/citation.cfm?id=3314106)
	

		

##  Surveys
- **A survey of models and algorithms for social influence analysis**
	- Sun, Jimeng and Tang, Jie
	- Social network data analytics 2011 [[Paper]](https://link.springer.com/chapter/10.1007/978-1-4419-8462-3_7)
		 
- **Information and influence propagation in social networks**
	- Chen, Wei and Lakshmanan, Laks VS and Castillo, Carlos
	- Synthesis Lectures on Data Management 2013 [[Paper]](https://www.morganclaypool.com/doi/abs/10.2200/s00527ed1v01y201308dtm037)

- **Recent advances in information diffusion and influence maximization in complex social networks**
	- Zhang, Huiyuan and Mishra, Subhankar and Thai, My T and Wu, J and Wang, Y
	- Opportunistic Mobile Social Networks 2014 [[Paper]](https://content.taylorfrancis.com/books/e/download?dac=C2013-0-16181-0&isbn=9781466594951&doi=10.1201/b17231-9&format=pdf)

- **Diffusion models and approaches for influence maximization in social networks**
	- Tejaswi, V and Bindu, PV and Thilagam, P Santhi
	- ICACCI 2016 [[Paper]](https://ieeexplore.ieee.org/abstract/document/7732235/)

- **Influence maximization in the field: The arduous journey from emerging to deployed application**
	- Yadav, Amulya and Wilder, Bryan and Rice, Eric and Petering, Robin and Craddock, Jaih and Yoshioka-Maxwell, Amanda and Hemler, Mary and Onasch-Vera, Laura and Tambe, Milind and Woo, Darlene
	- Autonomous agents and multiagent systems 2017 [[Paper]](https://dl.acm.org/citation.cfm?id=3091152)
	

- **Debunking the myths of influence maximization: An in-depth benchmarking study**
	- Arora, Akhil and Galhotra, Sainyam and Ranu, Sayan
	- SIGMOD 2017 [[Paper]](https://dl.acm.org/citation.cfm?id=3035924)

- **Influence maximization in large social networks: Heuristics, models and parameters**
	- Sumith, N and Annappa, B and Bhattacharya, Swapan
	- Future Generation Computer Systems 2018 [[Paper]](https://www.sciencedirect.com/science/article/pii/S0167739X18301092)
	
- **A Survey on Influence Maximization in a Social Network**
	- Banerjee, Suman and Jenamani, Mamata and Pratihar, Dilip Kumar
	- arXiv preprint arXiv:1808.05502 2018 [[Paper]](https://arxiv.org/abs/1808.05502)
	
- **Influence maximization on social graphs: A survey**
	- Li, Yuchen and Fan, Ju and Wang, Yanhao and Tan, Kian-Lee
	- TKDE 2018 [[Paper]](https://ieeexplore.ieee.org/abstract/document/8295265/)
	
- **A Survey on Influence and Information Diffusion in Twitter Using Big Data Analytics**
	- El Bacha, Radia and Zin, Thi Thi
	- Big Data Analysis and Deep Learning Applications 2018 [[Paper]](https://link.springer.com/chapter/10.1007/978-981-13-0869-7_5)
	

	

