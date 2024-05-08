# Human-Activity-Recognition
<article xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:mml="http://www.w3.org/1998/Math/MathML" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" article-type="research-article" dtd-version="1.1">
<front>
<journal-meta>
<journal-id journal-id-type="pmc">CMC</journal-id>
<journal-id journal-id-type="nlm-ta">CMC</journal-id>
<journal-id journal-id-type="publisher-id">CMC</journal-id>
<journal-title-group>
<journal-title>Computers, Materials & Continua</journal-title>
</journal-title-group>
<issn pub-type="epub">1546-2226</issn>
<issn pub-type="ppub">1546-2218</issn>
<publisher>
<publisher-name>Tech Science Press</publisher-name>
<publisher-loc>USA</publisher-loc>
</publisher>
</journal-meta>
<article-meta>
<article-id pub-id-type="publisher-id">35512</article-id>
<article-id pub-id-type="doi">10.32604/cmc.2023.035512</article-id>
<article-categories>
<subj-group subj-group-type="heading">
<subject>Article</subject>
</subj-group>
</article-categories>
<title-group>
<article-title>Leveraging Transfer Learning for Spatio-Temporal Human Activity Recognition from Video Sequences</article-title>
<alt-title alt-title-type="left-running-head">Leveraging Transfer Learning for Spatio-Temporal Human Activity Recognition from Video Sequences</alt-title>
<alt-title alt-title-type="right-running-head">Leveraging Transfer Learning for Spatio-Temporal Human Activity Recognition from Video Sequences</alt-title>
</title-group>
<contrib-group content-type="authors">
<contrib id="author-1" contrib-type="author" corresp="yes">
<name name-style="western">
<surname>Butt</surname>
<given-names>Umair Muneer</given-names>
</name>
<xref ref-type="aff" rid="aff-1">1</xref>
<xref ref-type="aff" rid="aff-2">2</xref>
<email>umair@student.usm.my</email>
</contrib>
<contrib id="author-2" contrib-type="author">
<name name-style="western">
<surname>Ullah</surname>
<given-names>Hadiqa Aman</given-names>
</name>
<xref ref-type="aff" rid="aff-2">2</xref>
</contrib>
<contrib id="author-3" contrib-type="author">
<name name-style="western">
<surname>Letchmunan</surname>
<given-names>Sukumar</given-names>
</name>
<xref ref-type="aff" rid="aff-1">1</xref>
</contrib>
<contrib id="author-4" contrib-type="author">
<name name-style="western">
<surname>Tariq</surname>
<given-names>Iqra</given-names>
</name>
<xref ref-type="aff" rid="aff-2">2</xref>
</contrib>
<contrib id="author-5" contrib-type="author">
<name name-style="western">
<surname>Hassan</surname>
<given-names>Fadratul Hafinaz</given-names>
</name>
<xref ref-type="aff" rid="aff-1">1</xref>
</contrib>
<contrib id="author-6" contrib-type="author">
<name name-style="western">
<surname>Koh</surname>
<given-names>Tieng Wei</given-names>
</name>
<xref ref-type="aff" rid="aff-3">3</xref>
</contrib>
<aff id="aff-1">
<label>1</label>
<institution>School of Computer Sciences, Universiti Sains Malaysia</institution>
,
<addr-line>Penang, 1180</addr-line>
,
<country>Malaysia</country>
</aff>
<aff id="aff-2">
<label>2</label>
<institution>Department of Computer Science, The University of Chenab</institution>
,
<addr-line>Gujrat, 50700</addr-line>
,
<country>Pakistan</country>
</aff>
<aff id="aff-3">
<label>3</label>
<institution>Department of Software Engineering and Information System, Universiti Putra Malaysia</institution>
,
<addr-line>Selangor, 43400</addr-line>
,
<country>Malaysia</country>
</aff>
</contrib-group>
<author-notes>
<corresp id="cor1">
<label>*</label>
Corresponding Author: Umair Muneer Butt. Email:
<email>umair@student.usm.my</email>
</corresp>
</author-notes>
<pub-date publication-format="print" date-type="pub" iso-8601-date="2022-12-15">
<day>15</day>
<month>12</month>
<year>2022</year>
</pub-date>
<volume>74</volume>
<issue>3</issue>
<fpage>5017</fpage>
<lpage>5033</lpage>
<history>
<date date-type="received">
<day>24</day>
<month>8</month>
<year>2022</year>
</date>
<date date-type="accepted">
<day>26</day>
<month>10</month>
<year>2022</year>
</date>
</history>
<permissions>
<copyright-statement>© 2023 Butt et al.</copyright-statement>
<copyright-year>2023</copyright-year>
<copyright-holder>Butt et al.</copyright-holder>
<license xlink:href="https://creativecommons.org/licenses/by/4.0/">
<license-p>
This work is licensed under a
<ext-link ext-link-type="uri" xlink:type="simple" xlink:href="https://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</ext-link>
, which permits unrestricted use, distribution, and reproduction in any medium, provided the original work is properly cited.
</license-p>
</license>
</permissions>
<self-uri content-type="pdf" xlink:href="TSP_CMC_35512.pdf"/>
<abstract>
<p>Human Activity Recognition (HAR) is an active research area due to its applications in pervasive computing, human-computer interaction, artificial intelligence, health care, and social sciences. Moreover, dynamic environments and anthropometric differences between individuals make it harder to recognize actions. This study focused on human activity in video sequences acquired with an RGB camera because of its vast range of real-world applications. It uses two-stream ConvNet to extract spatial and temporal information and proposes a fine-tuned deep neural network. Moreover, the transfer learning paradigm is adopted to extract varied and fixed frames while reusing object identification information. Six state-of-the-art pre-trained models are exploited to find the best model for spatial feature extraction. For temporal sequence, this study uses dense optical flow following the two-stream ConvNet and Bidirectional Long Short Term Memory (BiLSTM) to capture long-term dependencies. Two state-of-the-art datasets, UCF101 and HMDB51, are used for evaluation purposes. In addition, seven state-of-the-art optimizers are used to fine-tune the proposed network parameters. Furthermore, this study utilizes an ensemble mechanism to aggregate spatial-temporal features using a four-stream Convolutional Neural Network (CNN), where two streams use RGB data. In contrast, the other uses optical flow images. Finally, the proposed ensemble approach using max hard voting outperforms state-of-the-art methods with 96.30% and 90.07% accuracies on the UCF101 and HMDB51 datasets.</p>
</abstract>
<kwd-group kwd-group-type="author">
<kwd>Human activity recognition</kwd>
<kwd>deep learning</kwd>
<kwd>transfer learning</kwd>
<kwd>neural network</kwd>
<kwd>ensemble learning</kwd>
<kwd>spatio-temporal</kwd>
</kwd-group>
</article-meta>
</front>
<body>
<sec id="s1">
<label>1</label>
<title>Introduction</title>
<p>
Human Activity Recognition (HAR) automatically detects people’s daily physical activities. A HAR system recognizes a person’s actions and gives feedback for intervention [
<xref ref-type="bibr" rid="ref-1">1</xref>
]. Moreover, it assigns activity labels to video sequences. The main obstacles to activity recognition systems are the complexity of activities performed and the number of subjects engaging in the activity. Activity recognition systems can be used for people detection, motion tracking, and person identification [
<xref ref-type="bibr" rid="ref-2">2</xref>
], as shown in
<xref ref-type="fig" rid="fig-1">Fig. 1</xref>
. An activity recognition system’s purpose is to recognize common human activities. However, human activity is dynamic and diverse, making accurate activity identification difficult. Practical applications such as smart homes, human-computer interaction, automated surveillance, and human healthcare are increasing the need for HAR research.
</p>
<fig id="fig-1">
<label>Figure 1</label>
<caption>
<title>
Diverse human activities in the real-world [
<xref ref-type="bibr" rid="ref-3">3</xref>
]
</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-1.png"/>
</fig>
<p>
Several researchers considered HAR research a pattern recognition problem [
<xref ref-type="bibr" rid="ref-4">4</xref>
]. Primarily, they focused on traditional machine learning approaches such as Support Vector Machine (SVM), Hidden Markov Models (HMM) and deep learning approaches. Nevertheless, conventional machine learning methods, usually referred to as shallow learning, rely on expert human knowledge to extract data characteristics, restricting the architecture designed for one environment to solving issues in another [
<xref ref-type="bibr" rid="ref-5">5</xref>
].
</p>
<p>
On the other hand, deep learning enables direct feature extraction from data without the requirement for expert knowledge or the best feature selection. In contrast, standard manual approaches depend on accurate feature extraction [
<xref ref-type="bibr" rid="ref-6">6</xref>
]. Chen et al. [
<xref ref-type="bibr" rid="ref-7">7</xref>
] presented a two-stream CNN and estimated homography between two successive frames without the aid of a human. Given the approximate homography caused by camera motion, background motion may be avoided via the warped optical flow. Two-stream CNN-based video dynamics mining techniques are presented by Liu et al. [
<xref ref-type="bibr" rid="ref-8">8</xref>
] to extract temporal data. These methods generate action data features by measuring the degree of motion in each video stream frame. At various time scales, the n-skip optical flow extraction approach is used.
</p>
<p>
The innate ability of humans to do daily activities creates numerous challenges. A person may be engaged in many tasks simultaneously [
<xref ref-type="bibr" rid="ref-9">9</xref>
]. Individual differences in performance and anthropometrics make action recognition more challenging. Lighting, occlusion, background clutter, and viewpoint alteration all contribute to action recognition difficulty. The speed at which an activity is executed substantially impacts its duration. Temporal variance is another critical issue in detecting human behavior. Researchers are working on solutions to these difficulties and the importance of action recognition in various applications [
<xref ref-type="bibr" rid="ref-10">10</xref>
].
</p>
<p>
Recently, Yadav et al. [
<xref ref-type="bibr" rid="ref-10">10</xref>
] introduced the C2-LSTM, an enhanced version of the LSTM units that perceives motion data together with spatial properties and temporal relationships. UCF101 and HMDB51, well-known benchmarks, are used to assess the network. It supports C2LSTM’s ability to capture motion in addition to spatial characteristics and temporal dependencies. Similarly, Gammulle et al. [
<xref ref-type="bibr" rid="ref-11">11</xref>
] concentrate on LSTM networks for mapping the temporal connection between prominent spatial elements after learning them using CNN. They assess four fusion techniques for integrating LSTM and convolutional neural network outputs and demonstrate that these techniques beat state-of-the-art algorithms on three UCF11, UCFSports, and jHMDB. Finally, several researchers are studying Recurrent Neural Networks (RNN), LSTM, 3D-ConvNet, and two-Stream networks to extract representational from RGB data and temporal features from optical flow images when handling spatial representations in sequential video data [
<xref ref-type="bibr" rid="ref-12">12</xref>
].
</p>
<sec id="s1_1">
<label>1.1</label>
<title>Problem Statement</title>
<p>
This study identified the following challenges in state-of-the-art research.
<list list-type="bullet">
<list-item>
<p>The Primary concern in video data is to capture spatial and temporal information.</p>
</list-item>
<list-item>
<p>The other challenges are visual appearance variation regarding subjective and objective factors and intra-class and inter-class activity variation.</p>
</list-item>
<list-item>
<p>Other challenges for building a successful deep learning model include frame redundancy, varied length activity clips, compactness, and discriminative video representations.</p>
</list-item>
</list>
</p>
</sec>
<sec id="s1_2">
<label>1.2</label>
<title>Contribution</title>
<p>
This study contributed to the following dimensions for HAR in video sequences.
<list list-type="bullet">
<list-item>
<p>First, six state-of-the-art pre-trained models are exploited to find the best model for spatial feature extraction. Second, this study uses dense optical flow following the two-stream ConvNets and BiLSTM to capture long-term dependencies for temporal feature extraction.</p>
</list-item>
<list-item>
<p>This study proposes a two-stream ConvNet to extract features from video sequences and fine-tunes a deep neural network.</p>
</list-item>
<list-item>
<p>Transfer learning is applied to extract features while reusing object identification information.</p>
</list-item>
<list-item>
<p>Seven state-of-the-art optimizers are used to fine-tune the proposed network parameters. Furthermore, two state-of-the-art datasets, UCF101 and HMDB51, are used for evaluation purposes. Finally, an ensemble is presented using max hard voting.</p>
</list-item>
</list>
</p>
<p>This study is organized as follows: Section 2 focuses on state-of-the-art techniques. Section 3 discusses the methodology in different experimental setups. Section 4 discusses the empirical results achieved. Finally, the paper concludes with the conclusion and future directions in Section 5.</p>
</sec>
</sec>
<sec id="s2">
<label>2</label>
<title>Related Work</title>
<p>
Recognizing human activity from a video is an essential use of computer vision. Human motion research began in the 1850s with E. J. Marey and E. Muybridge shooting moving people [
<xref ref-type="bibr" rid="ref-13">13</xref>
]. Various taxonomies for recognizing movement have been proposed [
<xref ref-type="bibr" rid="ref-6">6</xref>
,
<xref ref-type="bibr" rid="ref-14">14</xref>
]. The following sections discuss HAR’s two cutting-edge learning approaches (Shallow and Deep learning).
</p>
<sec id="s2_1">
<label>2.1</label>
<title>Shallow Learning</title>
<p>
An effective generalized predictive model can be produced via a machine learning approach known as model learning with as few compositional layers, as shown in
<xref ref-type="fig" rid="fig-2">Fig. 2</xref>
. It needs samples subjected to extensive research and extracted expert characteristics. Shallow learning has been widely used in literature for HAR [
<xref ref-type="bibr" rid="ref-15">15</xref>
].
</p>
<fig id="fig-2">
<label>Figure 2</label>
<caption>
<title>
A one-layer shallow learning architecture [
<xref ref-type="bibr" rid="ref-14">14</xref>
]
</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-2.png"/>
</fig>
<p>
Feature representation and categorization are two key components of action recognition systems. Features are extracted from a video to reflect its appearance and distinguish it from other videos containing distinct behaviors. A multi-class classifier can be learned using feature vectors from training films of all. The extracted feature vector from a test video can be passed to the learned classifier to identify it as one of the actions. Faridee et al. [
<xref ref-type="bibr" rid="ref-16">16</xref>
] propose DeepconvLSTM with 1-layer shallow for HAR. They validate the proposed architecture on five state-of-the-art HAR datasets. Although methodology decreases training time significantly, to improve performance, at least two-layer LSTM should be used. Moreover, it cannot perform well on sensor-based HAR.
</p>
</sec>
<sec id="s2_2">
<label>2.2</label>
<title>Deep Learning</title>
<p>
Recently, deep learning has gained popularity, and several studies have been conducted employing learning in augmented reality. Deep neural networks (DNN), CNN, RNN, and LSTM networks are some of the well-known deep learning techniques used in augmented reality. Zhang et al. [
<xref ref-type="bibr" rid="ref-17">17</xref>
] investigated DNN, CNN, and RNN for activity datasets and concluded that the RNN outperformed the findings from state-of-the-art techniques.
</p>
<p>
In deep learning, features are extracted hierarchically using non-linear transformations, as shown in
<xref ref-type="fig" rid="fig-3">Fig. 3</xref>
. CNN, RNN, and LSTM networks are all deep neural architectures. In 2014, two seminal research papers were presented by SravyaPranati et al. [
<xref ref-type="bibr" rid="ref-18">18</xref>
] and Simonyan et al. [
<xref ref-type="bibr" rid="ref-12">12</xref>
]. They reintroduced deep learning by focusing on single and two-stream deep neural networks for action recognition. In addition, significant research on the identification of human activity was carried out and validated in 2014, utilizing video-based datasets such as UCF101, Sports1M, and HMDB51 [
<xref ref-type="bibr" rid="ref-19">19</xref>
].
</p>
<fig id="fig-3">
<label>Figure 3</label>
<caption>
<title>
A glimpse of deep learning architecture [
<xref ref-type="bibr" rid="ref-14">14</xref>
]
</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-3.png"/>
</fig>
<p>
Recently, a CNN-based method was exploited to extract features through a series of max-pooling layers on the DMLSmartActions dataset [
<xref ref-type="bibr" rid="ref-20">20</xref>
]. Zheng et al. [
<xref ref-type="bibr" rid="ref-21">21</xref>
] proposed a spatiotemporal module for integrating multi-level CNN features into a hierarchical representation. While the temporal pyramid module pools frames to create several time-grained representations of snippets, the spatial pyramid module extracts multiscale appearance features from video frames. The discriminative hierarchical pooling design incorporates a powerful temporal pooling layer that functions with any CNN architecture [
<xref ref-type="bibr" rid="ref-22">22</xref>
]. Learning informative dynamics from beginning to end is achievable, thanks to the rich frame-based video representations.
</p>
<sec id="s2_2_1">
<label>2.2.1</label>
<title>Two-Stream ConvNets</title>
<p>
Muhammad et al. [
<xref ref-type="bibr" rid="ref-23">23</xref>
] perform significant experiments to extend the architecture of CNN with LSTM for large-scale video categorization. They incorporate two separate streams of processing, i.e., they combine features from both streams using three methods. To help, late fusion joins two distant frames with flattened deep hierarchical features. Early fusion stacks images as channels and learns video representations using 2D convolution. However, the suggested fusion networks have a high cost due to several factors.
</p>
<p>
Simonyan et al. [
<xref ref-type="bibr" rid="ref-12">12</xref>
] used two-stream ConvNets to recognize the video-based activity. A proposed two-stream design separates spatial and temporal features. Using 2D convolution, one stream processes an RGB image from a video clip while the other processes a stack of optical flow frames. Following that, the anticipated activity class from both streams is merged. The issue with this network topology is the extra preprocessing and computing required to calculate optical flow pictures. Transfer learning works on spatial streams from pre-trained huge image datasets but not on temporal streams. Despite the increasing computing cost, this approach’s strength can be seen by comparing it to advanced techniques like iDT [
<xref ref-type="bibr" rid="ref-10">10</xref>
]. Zhu et al. [
<xref ref-type="bibr" rid="ref-24">24</xref>
] identified that every volume, or spatiotemporal video segment, is not identical to the action class. Critical video partitions are identified and excluded from the analysis, allowing substantial video chunks to be omitted. In addition, it incorporates a novel convolutional and temporal fusion layer at later levels of the network to increase performance without raising parameters.
</p>
</sec>
<sec id="s2_2_2">
<label>2.2.2</label>
<title>ConvNets with RNNs</title>
<p>
The datasets used to train and validate HAR are distinct. HAR video clips vary in length and require extensive sliding window searching. Many researchers now use RNNs and LSTMs to simulate activity changes over time. LRCNs can learn features from variable-length inputs, unlike traditional input methods [
<xref ref-type="bibr" rid="ref-25">25</xref>
]. Donahue et al. [
<xref ref-type="bibr" rid="ref-26">26</xref>
] use encoder-decoder architecture to extract video representations. This model uses LSTM cells to build a recurrent neural network from frames extracted at each time step. This approach failed to beat the state-of-the-art but presents a significant single-frame architecture. A hierarchical multiscale RNN can learn the hierarchical temporal structure from data.
</p>
<p>
Shou et al. [
<xref ref-type="bibr" rid="ref-27">27</xref>
] proposed two methods for processing full-length video clips by modeling the video as an ordered sequence of frames with RNN and LSTM cells. Efficacious and efficient temporal action localization algorithms can locate action segments of various lengths using exhaustive searching at multiple temporal scales. Deep action proposals (DAPs) extract C3D features from every 16-frame chunk and use LSTM to predict class labels for those activity segments for temporal action localization. Buch et al. [
<xref ref-type="bibr" rid="ref-28">28</xref>
] designed a single-pass network that directly outputs an activity event’s starting and ending bounds and its action class. They utilized a segment CNN framework based on 3D ConvNets. This method divides the localization and classification networks. First, an action recognition classification network is proposed as initialization for the localization network, which then localizes action occurrences in time and predicts scores for action labels.
</p>
<p>
In a paradigm for HAR presented by Ullah et al. [
<xref ref-type="bibr" rid="ref-29">29</xref>
], saliency representations are first recovered from continuous video streams after they have been separated into their fundamental shots. The CNN method suggests significant shots. To express temporal aspects, FlowNet2 is then employed. Finally, a multilayer LSTM is used to learn temporal sequences. Khan et al. [
<xref ref-type="bibr" rid="ref-30">30</xref>
] proposed a 3-stream CNN and achieved state-of-the-art results on the Kinetics-400 dataset. They extract salient patches from appearance and motion representations, three-stream CNN abstract features, integrate frame-level descriptors into an RNN, and combine three classification scores to predict the final class labels.
</p>
</sec>
<sec id="s2_2_3">
<label>2.2.3</label>
<title>3D ConvNets</title>
<p>
Crasto et al. [
<xref ref-type="bibr" rid="ref-31">31</xref>
] use the C3D network to handle temporal activity localization. This model improves activity detection by combining an optical flow-based motion stream with the original RGB stream. In addition, an online hard mining strategy improves performance and speed detection.
</p>
<p>
He et al. [
<xref ref-type="bibr" rid="ref-32">32</xref>
] proposed Factorized Spatio-Temporal Convolutional Networks (FSTCN) to simplify 3D convolutional kernel learning. With this technique, you can learn spatial and temporal features by learning spatial representations from 2D spatial kernels in the lower layers and temporal representations from 1D temporal kernels in the upper layers. 3D convolution improves feature learning but increases parameter costs. With MicroNets and asymmetric one-directional 3D convolutions, Ullah et al. [
<xref ref-type="bibr" rid="ref-5">5</xref>
] overcame this problem. They proposed that micro nets improve feature learning by incorporating multiscale 3D convolution branches to handle the different scales of convolutional features in videos.
</p>
<p>
Fin et al. [
<xref ref-type="bibr" rid="ref-33">33</xref>
] propose an enhanced CNN based on group and depth convolution. This method can produce 3D convolutions for action recognition in video classification. 3D Channel Separated Networks (CSN) use depth-wise convolutions for local spatiotemporal connections. It reduces network parameters and introduces a strong form of regularization. Discriminative spatial and temporal features can be learned in 14 layers using these channel-separated blocks. 3D ResNet employs RGB images with motion and scenes to create patch features.
</p>
</sec>
</sec>
</sec>
<sec id="s3">
<label>3</label>
<title>Methodology</title>
<p>
The primary objective of this study is to classify human activities from video sequences. In addition to a fixed, clean background, video recording of human activities includes varying camera motions, lighting conditions, and low-quality frames. This study uses spatial and temporal information to recognize activities effectively. Moreover, a transfer learning paradigm is adopted to extract features from varied and fixed frames. With the success of LSTM and its variants, this study fine-tunes BiLSTM on extracted features for learning long-term dependencies. Finally, ensemble learning is utilized to combine all these streams.
<xref ref-type="fig" rid="fig-4">Fig. 4</xref>
provides a comprehensive explanation of the process. In addition, accuracy is used as a performance measure to evaluate the proposed methodology. The following sections discuss the methodology comprehensively.
</p>
<fig id="fig-4">
<label>Figure 4</label>
<caption>
<title>A proposed approach for our four-stream ensemble</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-4.png"/>
</fig>
<sec id="s3_1">
<label>3.1</label>
<title>Dataset Acquisition</title>
<p>This study uses two state-of-the-art HAR datasets UCF101 and HMDB-51. UCF101 is a collection of real-world action videos from YouTube that have been categorized into 101 different action types. The most difficult data set to date, UCF101, has 13320 videos from 101 action categories and offers the widest variety of actions. It also has significant variations in camera motion, object appearance and pose, object scale, viewpoint, cluttered background, illumination conditions, and other factors.</p>
<p>
UCF101 intends to promote further action recognition research by learning and examining new realistic action categories because most of the action recognition data sets that are currently accessible are not realistic and are staged by actors. The videos in the 101 action categories are divided into 25 groups, each of which may contain 4–7 action videos.
<xref ref-type="table" rid="table-1">Table 1</xref>
shows the characteristics of the UCF101 dataset.
</p>
<table-wrap id="table-1">
<label>Table 1</label>
<caption>
<title>
UCF101 dataset characteristics [
<xref ref-type="bibr" rid="ref-34">34</xref>
]
</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Parameter</th>
<th align="left">Values</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Number of actions</td>
<td align="left">101</td>
</tr>
<tr>
<td align="left">Clips</td>
<td align="left">13320</td>
</tr>
<tr>
<td align="left">Groups per action</td>
<td align="left">25</td>
</tr>
<tr>
<td align="left">Clips per group</td>
<td align="left">4–7</td>
</tr>
<tr>
<td align="left">Mean clip length</td>
<td align="left">7.21 s</td>
</tr>
<tr>
<td align="left">Total duration</td>
<td align="left">1600 mins</td>
</tr>
<tr>
<td align="left">Min clip length</td>
<td align="left">1.06 s</td>
</tr>
<tr>
<td align="left">Max clip length</td>
<td align="left">71.04 s</td>
</tr>
<tr>
<td align="left">Frame rate</td>
<td align="left">25 fps</td>
</tr>
<tr>
<td align="left">Resolution</td>
<td align="left">320 * 240</td>
</tr>
<tr>
<td align="left">Audio</td>
<td align="left">Yes (51 actions)</td>
</tr>
</tbody>
</table>
</table-wrap>
<p>
Most of the HMDB-51 [
<xref ref-type="bibr" rid="ref-35">35</xref>
] data was gathered from films, with a tiny amount coming from public databases like the Prelinger archive, YouTube, and Google videos. The dataset comprises 6849 clips, classified into 51 action categories, each of which has at least 101 clips, as shown in
<xref ref-type="table" rid="table-2">Table 2</xref>
.
</p>
<table-wrap id="table-2">
<label>Table 2</label>
<caption>
<title>
HMDB-51 dataset characteristics [
<xref ref-type="bibr" rid="ref-35">35</xref>
]
</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Parameter</th>
<th align="left">Values</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Number of actions</td>
<td align="left">51</td>
</tr>
<tr>
<td align="left">Clips</td>
<td align="left">6849</td>
</tr>
<tr>
<td align="left">Background</td>
<td align="left">Dynamic</td>
</tr>
<tr>
<td align="left">Camera motion</td>
<td align="left">Yes</td>
</tr>
<tr>
<td align="left">Release year</td>
<td align="left">2011</td>
</tr>
<tr>
<td align="left">Source</td>
<td align="left">Movies, YouTube, Web</td>
</tr>
<tr>
<td align="left">Clips per action</td>
<td align="left">Min. 101</td>
</tr>
</tbody>
</table>
</table-wrap>
</sec>
<sec id="s3_2">
<label>3.2</label>
<title>Feature Extraction</title>
<p>The feature extraction method can be quite helpful when analyzing massive datasets with only limited computational resources. The process of extracting essential data features from data and transforming them into condensed representations is referred to as feature extraction. The extracted characteristics must be simple to process, discriminatory, and accurately describe the real data set. In addition to this benefit, extracting features helps reduce redundant data. The goal of this research is to derive Spatio-temporal information from video data.</p>
<p>This research uses off-the-shelf feature extractors. These layers are combined to get the final prediction. Pre-trained networks without their final layer can be fixed feature extractors. Raw pixel data is used to extract features. This study uses the pre-trained model’s weighted layers to extract features but doesn’t change their weights during training. Instead, unsupervised, image-class-unrelated feature extraction is used. Training will change weights from generic feature maps to dataset-specific features.</p>
<p>
This technique replaces not just the final layer (for classification and regression) but also certain prior levels. Initial layers record generic features, whereas later ones focus on the specific task. This study uses six popular off-the-shelf pre-trained networks to extract features. All these models are evaluated on the UCF101 and HMDB51 datasets.
<xref ref-type="table" rid="table-3">Table 3</xref>
shows the pre-trained model specifications.
</p>
<table-wrap id="table-3">
<label>Table 3</label>
<caption>
<title>State-of-the-art pre-trained models specifications</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Total parameters</th>
<th align="left">Feature shape</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">VGG16</td>
<td align="left">14,714,688</td>
<td align="left">7 * 7 * 512</td>
</tr>
<tr>
<td align="left">InceptionV3</td>
<td align="left">21,802,784</td>
<td align="left">5 * 5 * 2048</td>
</tr>
<tr>
<td align="left">ResNet101V2</td>
<td align="left">42,626,560</td>
<td align="left">7 * 7 * 2048</td>
</tr>
<tr>
<td align="left">InceptionResNetV2</td>
<td align="left">54,336,736</td>
<td align="left">5 * 5 * 1536</td>
</tr>
<tr>
<td align="left">DenseNet121</td>
<td align="left">7,037,504</td>
<td align="left">7 * 7 * 1024</td>
</tr>
<tr>
<td align="left">NASNetMobile</td>
<td align="left">4,269,716</td>
<td align="left">7 * 7 * 1056</td>
</tr>
</tbody>
</table>
</table-wrap>
</sec>
</sec>
<sec id="s4">
<label>4</label>
<title>Result and Discussion</title>
<p>This section focuses on human activities captured with an RGB camera with many real-life applications. The main challenge with video data is capturing both spatial and temporal information. In addition, there is intra-class and inter-class activity variation. Frame redundancy, variable-length activity clips, compactness, and discriminative video representations are all challenges in deep learning. Therefore, this study proposes a generic, dense computational model.</p>
<sec id="s4_1">
<label>4.1</label>
<title>Transfer Learning with Deep Learning as a Feature Extractor</title>
<p>
Researchers are struggling to design systems that can apply experience learned from previous tasks to improve performance on a new task. Transfer learning can reduce the architecture learning time and effort, resulting in more robust and useful activity recognition systems [
<xref ref-type="bibr" rid="ref-25">25</xref>
]. Muhammad et al. [
<xref ref-type="bibr" rid="ref-23">23</xref>
] reveal that transfer learning is a good approach to action recognition. Two popular strategies for deep transfer learning are off-the-shelf pre-trained models and off-the-shelf pre-trained models as feature extractors.
</p>
<p>
This study uses Off-the-shelf models as feature extractor strategies, as shown in
<xref ref-type="table" rid="table-3">Table 3</xref>
. Deep learning models have layered architectures with distinct layers learning different characteristics. Finally, for the final forecast, these layers are linked to the last layer. Using a pre-trained network without its final layer as a fixed feature extractor is made possible by the layered design. The important concept is to use the pre-trained model’s weighted layers to extract features and not to change the layers’ weights while the model is trained with fresh data for the current job.
</p>
<p>Since the classes of the image have no bearing on the information recovered from pixels, the feature extraction is unsupervised. A new classifier is introduced and trained from scratch on top of the pre-trained model to repurpose previously learned feature maps for the UCF101 and HMDB51 datasets. Features often helpful for categorization are already present in the base network.</p>
<sec id="s4_1_1">
<label>4.1.1</label>
<title>Spatial Feature Extraction</title>
<p>
Spatial features exploit location/spatial data. CNN performs non-linear transformations in different locations of the image in the form of convolutions. VGG16, InceptionV3, ResNet101V2, InceptionResNet2 and NASNetMobile were used to extract spatial features from UCF101 and HMDB-51. Spatial features are extracted from RGB images. For RGB data, each video extracts a single frame per second. The network accepts 224 × 224 × 3 images, as shown in
<xref ref-type="fig" rid="fig-5">Fig. 5</xref>
.
</p>
<fig id="fig-5">
<label>Figure 5</label>
<caption>
<title>Network configuration for the pre-trained model to extract features</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-5.png"/>
</fig>
<p>
After extracting features, the classifier has four dense layers with ReLU activation and a dropout of 0.5. SoftMax does the final classification. Each model was compiled with categorical cross-entropy loss and an Adam optimizer with 128 batch sizes. The same network configuration has been used for temporal feature extraction.
<xref ref-type="table" rid="table-4">Tables 4</xref>
and
<xref ref-type="table" rid="table-5">5</xref>
show the experimental results obtained by applying selected pre-trained models on RGB images of HMDB51 and UCF101 datasets. Moreover, it shows that ResNet101V2 achieved high accuracy compared to other state-of-the-art pre-trained models on RGB images.
</p>
<table-wrap id="table-4">
<label>Table 4</label>
<caption>
<title>Results achieved by applying selected pre-trained to UCF101 dataset RGB images</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">VGG16</td>
<td align="left">78.59</td>
<td align="left">85.44</td>
<td align="left">28.89</td>
</tr>
<tr>
<td align="left">InceptionV3</td>
<td align="left">96.99</td>
<td align="left">96.45</td>
<td align="left">69.18</td>
</tr>
<tr>
<td align="left">
<bold>ResNet101V2</bold>
</td>
<td align="left">
<bold>98.92</bold>
</td>
<td align="left">
<bold>98.52</bold>
</td>
<td align="left">
<bold>76.46</bold>
</td>
</tr>
<tr>
<td align="left">InceptionResNetV2</td>
<td align="left">97.72</td>
<td align="left">97.58</td>
<td align="left">71.72</td>
</tr>
<tr>
<td align="left">DenseNet121</td>
<td align="left">97.79</td>
<td align="left">98.05</td>
<td align="left">70.61</td>
</tr>
<tr>
<td align="left">NASNetMobile</td>
<td align="left">98.48</td>
<td align="left">97.5</td>
<td align="left">67.62</td>
</tr>
</tbody>
</table>
</table-wrap>
<table-wrap id="table-5">
<label>Table 5</label>
<caption>
<title>Results achieved by applying selected pre-trained to HMDB-51 dataset RGB Images</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">VGG16</td>
<td align="left">69.03</td>
<td align="left">31.08</td>
<td align="left">17.39</td>
</tr>
<tr>
<td align="left">InceptionV3</td>
<td align="left">82.31</td>
<td align="left">37.07</td>
<td align="left">31.83</td>
</tr>
<tr>
<td align="left">
<bold>ResNet101V2</bold>
</td>
<td align="left">
<bold>99.0</bold>
</td>
<td align="left">
<bold>44.04</bold>
</td>
<td align="left">
<bold>36.86</bold>
</td>
</tr>
<tr>
<td align="left">InceptionResNetV2</td>
<td align="left">85.02</td>
<td align="left">39.43</td>
<td align="left">35.1</td>
</tr>
<tr>
<td align="left">DenseNet121</td>
<td align="left">92.05</td>
<td align="left">40.81</td>
<td align="left">32.85</td>
</tr>
<tr>
<td align="left">NASNetMobile</td>
<td align="left">53.25</td>
<td align="left">36.47</td>
<td align="left">20.20</td>
</tr>
</tbody>
</table>
</table-wrap>
</sec>
<sec id="s4_1_2">
<label>4.1.2</label>
<title>Temporal Feature Extraction</title>
<p>Temporal characterization occurs when a series of images are taken at different times. Correlations between the images are often used to monitor the dynamic changes of the object. We extracted a fixed number of frames per second from each clip, as per-second frame extraction did not yield good results. Therefore, we extract eight frames per second from each video clip.</p>
<p>
The pattern of apparent mobility of picture objects between two successive frames brought on by the movement of the subject or camera is known as optical flow. Each vector in the 2D vector field represents the displacement of a point from the first to the second frame. Dense optical flow may be slow but produces more accurate results since it computes the optical flow vector for each pixel in the frame. This study made dense optical flow calculations using the Franeback technique [
<xref ref-type="bibr" rid="ref-36">36</xref>
]. In addition, pre-trained ResNet50V2 has been exploited to extract temporal features due to its classification accuracy compared to the state-of-the-art [
<xref ref-type="bibr" rid="ref-37">37</xref>
]. Results were obtained by extracting eight video frames from each clip of the UCF101 and HMDB51 datasets, as shown in
<xref ref-type="table" rid="table-6">Tables 6</xref>
and
<xref ref-type="table" rid="table-7">7</xref>
.
</p>
<table-wrap id="table-6">
<label>Table 6</label>
<caption>
<title>Results of ResNet50V2 on the UCF101 dataset by extracting eight optical flow images per clip</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ResNet50V2</td>
<td align="left">87</td>
<td align="left">40.41</td>
<td align="left">79.78</td>
</tr>
</tbody>
</table>
</table-wrap>
<table-wrap id="table-7">
<label>Table 7</label>
<caption>
<title>Results of ResNet50V2 on the HMDB51 dataset by extracting eight optical flow images per clip</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ResNet50V2</td>
<td align="left">92.1</td>
<td align="left">24.30</td>
<td align="left">40.07</td>
</tr>
</tbody>
</table>
</table-wrap>
</sec>
</sec>
<sec id="s4_2">
<label>4.2</label>
<title>Optimization</title>
<p>
This study utilized seven state-of-the-art optimizers from the Keras library to fine-tune the architecture parameters, i.e., SGD [
<xref ref-type="bibr" rid="ref-38">38</xref>
], Adagrad [
<xref ref-type="bibr" rid="ref-39">39</xref>
], Adadelta [
<xref ref-type="bibr" rid="ref-40">40</xref>
], RMSprop [
<xref ref-type="bibr" rid="ref-41">41</xref>
], Adam [
<xref ref-type="bibr" rid="ref-42">42</xref>
], Adamax [
<xref ref-type="bibr" rid="ref-43">43</xref>
], Nadam [
<xref ref-type="bibr" rid="ref-44">44</xref>
]. After extracting features through ResNet, all these optimizers are used to compile the model with two dense layers for final prediction. AdaMax achieves the highest test accuracy among all, as shown in
<xref ref-type="fig" rid="fig-6">Fig. 6</xref>
.
</p>
<fig id="fig-6">
<label>Figure 6</label>
<caption>
<title>Line graph representing training loss, validation loss, and accuracy across 100 epochs</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-6.png"/>
</fig>
<p>
This study uses the AdaMax optimizer to accelerate the optimization process. AdaMax is a modification to the Adam version of gradient descent that generalizes the technique and leads to a more effective optimization for certain applications [
<xref ref-type="bibr" rid="ref-45">45</xref>
]. In its formulation, Adam, like RMSProp, uses an exponentially decaying weighted average estimate of the gradient’s variance. The update rule for individual weights in Adam is to scale their gradients inversely proportionate to the (scaled) L2 norm of their current and previous gradients. In addition, AdaMax automatically adjusts each optimization problem parameter’s step size (learning rate). A comparison of training accuracy and loss per epoch is shown in
<xref ref-type="fig" rid="fig-6">Fig. 6</xref>
. AdaMax achieves 86.14% accuracy on HMDB51 and 92.57% on UCF101 datasets.
</p>
</sec>
<sec id="s4_3">
<label>4.3</label>
<title>Activity Recognition Using BiLSTM</title>
<p>
This section discusses the results obtained using the BiLSTM model for activity recognition. BiLSTM processes the input data in two directions. Once from the beginning to the end and once from the end to the beginning. BiLSTMs are an extension of LSTM models designed to collect input information in the past and the future of a given time stamp [
<xref ref-type="bibr" rid="ref-46">46</xref>
]. To apply BiLSTM, we extract eight frames from each video clip, extract features using ResNet50V2 and apply a single layer of BiLSTM with 256 units, followed by a dropout and a dense layer with a Softmax activation function. Finally, the BiLSTM layer is applied to both RGB and Optical Flow (OF) data, and the results are shown in
<xref ref-type="table" rid="table-8">Tables 8</xref>
and
<xref ref-type="table" rid="table-9">9</xref>
.
</p>
<table-wrap id="table-8">
<label>Table 8</label>
<caption>
<title>Results obtained after applying BiLSTM on features extracted with ResNet50V2 on UCF-101</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BiLSTM (RGB)</td>
<td align="left">95.67</td>
<td align="left">85.80</td>
<td align="left">92.12</td>
</tr>
<tr>
<td align="left">BiLSTM (OF)</td>
<td align="left">86.02</td>
<td align="left">38.14</td>
<td align="left">72.85</td>
</tr>
</tbody>
</table>
</table-wrap>
<table-wrap id="table-9">
<label>Table 9</label>
<caption>
<title>Results obtained after applying BiLSTM on features extracted with ResNet50V2 on HMDB-51</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BiLSTM (RGB)</td>
<td align="left">87.86</td>
<td align="left">58.20</td>
<td align="left">76.47</td>
</tr>
<tr>
<td align="left">BiLSTM (OF)</td>
<td align="left">73.30</td>
<td align="left">21.32</td>
<td align="left">61.63</td>
</tr>
</tbody>
</table>
</table-wrap>
</sec>
<sec id="s4_4">
<label>4.4</label>
<title>Activity Recognition Using Ensemble</title>
<p>
Deep learning models are non-linear learning processes that use a stochastic training algorithm to learn. Given adequate resources, they approximate any mapping function and are adaptable, learning intricate correlations between variables [
<xref ref-type="bibr" rid="ref-4">4</xref>
]. The models have significant variations because of this flexibility. By creating many models for the issues at hand and aggregating their predictions, the high volatility of the method can be reduced. The procedure of prediction aggregation belongs to a family of ensemble learning techniques.
</p>
<p>This study uses ensemble learning to aggregate spatial and temporal information. The ensemble is applied to a four-stream CNN, where two streams use RGB data while the other uses optical flow images. Optical flow images are extracted to capture the movement or change in an action sequence. The first stream extracts one RGB image per second for varied-length clips and extracts features through ResNet101. The second stream extracts 8 RGB frames per video, extracts features through ResNet-50V2, and applies the BiLSTM layer on top. The third stream consists of extracting eight optical flow images per video, extracting features using ResNet50V2, and classifying them accordingly.</p>
<p>
The fourth stream applies BiLSTM on top and then classifies the extracted features of eight optical flow images. Finally, the ensemble is applied using hard majority voting on all four streams. Ensemble applied using hard max voting works best if all models have improved performance, as shown in
<xref ref-type="fig" rid="fig-7">Fig. 7</xref>
. The results obtained from the ensemble of those four streams on the UCF-101 and HMDB-51 datasets are shown in
<xref ref-type="table" rid="table-10">Tables 10</xref>
and
<xref ref-type="table" rid="table-11">11</xref>
. Experimental results show the supremacy of the proposed ensemble compared to other models.
</p>
<fig id="fig-7">
<label>Figure 7</label>
<caption>
<title>Activity recognition using a four-stream ensemble</title>
</caption>
<graphic mimetype="image" mime-subtype="png" xlink:href="CMC_35512-fig-7.png"/>
</fig>
<table-wrap id="table-10">
<label>Table 10</label>
<caption>
<title>Results obtained on UCF-101 for all four streams and their ensemble</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ResNet101 (RGB)</td>
<td align="left">94.18</td>
<td align="left">92.07</td>
<td align="left">92.57</td>
</tr>
<tr>
<td align="left">ResNet50 + BiLSTM (RGB)</td>
<td align="left">95.67</td>
<td align="left">85.80</td>
<td align="left">92.12</td>
</tr>
<tr>
<td align="left">ResNet50 (OF)</td>
<td align="left">87</td>
<td align="left">40.41</td>
<td align="left">79.78</td>
</tr>
<tr>
<td align="left">ResNet50 + BiLSTM (OF)</td>
<td align="left">86.02</td>
<td align="left">38.14</td>
<td align="left">72.85</td>
</tr>
<tr>
<td align="left">
<bold>Ensemble (RGB + OF)</bold>
</td>
<td align="left">
<bold>94.20</bold>
</td>
<td align="left">
<bold>93.32</bold>
</td>
<td align="left">
<bold>96.30</bold>
</td>
</tr>
</tbody>
</table>
</table-wrap>
<table-wrap id="table-11">
<label>Table 11</label>
<caption>
<title>Results obtained on HMDB-51 for all four streams and their ensemble</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Model</th>
<th align="left">Training accuracy</th>
<th align="left">Validation accuracy</th>
<th align="left">Test accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ResNet101 (RGB)</td>
<td align="left">88.64</td>
<td align="left">71.17</td>
<td align="left">86.14</td>
</tr>
<tr>
<td align="left">ResNet50 + BiLSTM (RGB)</td>
<td align="left">87.86</td>
<td align="left">58.20</td>
<td align="left">76.47</td>
</tr>
<tr>
<td align="left">ResNet50 (OF)</td>
<td align="left">92.1</td>
<td align="left">24.30</td>
<td align="left">60.07</td>
</tr>
<tr>
<td align="left">ResNet50 + BiLSTM (OF)</td>
<td align="left">73.03</td>
<td align="left">21.30</td>
<td align="left">61.63</td>
</tr>
<tr>
<td align="left">
<bold>Ensemble (RGB + OF)</bold>
</td>
<td align="left">
<bold>89.41</bold>
</td>
<td align="left">
<bold>83.32</bold>
</td>
<td align="left">
<bold>90.07</bold>
</td>
</tr>
</tbody>
</table>
</table-wrap>
<p>Two-stream ConvNets extract spatial information from RGB, and temporal information is extracted using dense optical flow images calculated on equidistant frames. Moreover, a transfer learning paradigm is adopted to extract features while reusing object identification knowledge for activity recognition. We evaluated six state-of-the-art networks: VGGNet, Inception, ResNet, InceptionResNet, DenseNet, and NASNet. These models are tested on the UCF101 and HMDB51 datasets. ResNet101V2 achieved 72.46% and 36.86% accuracy on the UCF101 and HMDB51 datasets, respectively. In addition, seven state-of-the-art optimizers are utilized for network parameter optimization. The AdaMax optimizer enhanced the accuracy by achieving 92.57% and 86.14% on the UCF-101 and HMDB-51 datasets.</p>
<p>
This study uses BiLSTM and ensemble methods for activity recognition. BiLSTM captures long-term sequential information to explore temporal information. BiLSTM achieves 92.12% and 76.47% accuracy on RGB, while 72.85% and 61.63% accuracy on optical flow. Finally, ensemble learning is used to fuse all streams using max hard voting. After applying the ensemble, the accuracy on UCF101 is increased to 96.3% and 90.07% on HMDB51. The proposed ensemble-based approach shows supremacy compared to state-of-the-art methods, as shown in
<xref ref-type="table" rid="table-12">Table 12</xref>
.
</p>
<table-wrap id="table-12">
<label>Table 12</label>
<caption>
<title>Comparison of the proposed approach with the state-of-the-art on UCF101 and HMDB51</title>
</caption>
<table frame="hsides">
<colgroup>
<col align="left"/>
<col align="left"/>
<col align="left"/>
<col align="left"/>
</colgroup>
<thead>
<tr>
<th align="left">Comparison on UCF101</th>
<th align="left">Accuracy</th>
<th align="left">Comparison on HMDB51</th>
<th align="left">Accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
3DConvNets ensemble + iDT [
<xref ref-type="bibr" rid="ref-47">47</xref>
]
</td>
<td align="left">92.70</td>
<td align="left">
Four-stream I3D [
<xref ref-type="bibr" rid="ref-50">50</xref>
]
</td>
<td align="left">99.1</td>
</tr>
<tr>
<td align="left">
Two-stream [
<xref ref-type="bibr" rid="ref-48">48</xref>
]
</td>
<td align="left">94.80</td>
<td align="left">
CSTA-I3D [
<xref ref-type="bibr" rid="ref-51">51</xref>
]
</td>
<td align="left">98.2</td>
</tr>
<tr>
<td align="left">
CatNet [
<xref ref-type="bibr" rid="ref-49">49</xref>
]
</td>
<td align="left">96.0</td>
<td align="left">
WMHI [
<xref ref-type="bibr" rid="ref-52">52</xref>
]
</td>
<td align="left">97.1</td>
</tr>
<tr>
<td align="left">ResNet (RGB)</td>
<td align="left">92.57</td>
<td align="left">ResNet (RGB)</td>
<td align="left">86.14</td>
</tr>
<tr>
<td align="left">ResNet + BiLSTM (RGB)</td>
<td align="left">92.12</td>
<td align="left">ResNet + BiLSTM (RGB)</td>
<td align="left">76.47</td>
</tr>
<tr>
<td align="left">ResNet (OF)</td>
<td align="left">79.78</td>
<td align="left">ResNet (OF)</td>
<td align="left">60.07</td>
</tr>
<tr>
<td align="left">ResNet + BiLSTM (OF)</td>
<td align="left">72.85</td>
<td align="left">ResNet + BiLSTM (OF)</td>
<td align="left">61.63</td>
</tr>
<tr>
<td align="left">
<bold>Proposed method (Ensemble (RGB + OF))</bold>
</td>
<td align="left">
<bold>96.30</bold>
</td>
<td align="left">
<bold>Proposed method (Ensemble (RGB + OF))</bold>
</td>
<td align="left">
<bold>90.07</bold>
</td>
</tr>
</tbody>
</table>
</table-wrap>
</sec>
</sec>
<sec id="s5">
<label>5</label>
<title>Conclusion and Future Work</title>
<p>HAR from video sequences is challenging due to the dynamic backgrounds and complexity of real-world applications such as video surveillance, HCI, and human behavior characterization. However, deep learning methods such as convolutional and recurrent neural networks have recently achieved state-of-the-art results by automatically learning features from raw sensor data.</p>
<p>This study focused on grouped and individual human activity in video sequences acquired with an RGB camera because of its vast range of real-world applications. It uses two-stream ConvNet to extract spatial and temporal information and proposes a fine-tuned deep neural network. Primarily, transfer learning is applied to extract features while reusing object identification information. First, six state-of-the-art pre-trained models are exploited to find the best model for spatial feature extraction. Second, this study uses dense optical flow following the two-stream ConvNets and BiLSTM to capture long-term dependencies for temporal feature extraction.</p>
<p>In addition, seven state-of-the-art optimizers are used to fine-tune the proposed network parameters. Furthermore, two state-of-the-art datasets, UCF101 and HMDB51, are used for evaluation purposes. Finally, the proposed ensemble approach using max hard voting outperforms state-of-the-art methods with 96.30% and 90.07% accuracies on the UCF101 and HMDB51 datasets. In the future, we aim to detect human activities from a multimodal dataset using 3D-ConvNets by fusing temporal and spatial features. Moreover, transfer learning will be adopted with self-distillation to enhance HAR accuracy.</p>
</sec>
</body>
<back>
<fn-group>
<fn fn-type="other">
<p>
<bold>Data Availability Statement:</bold>
This study uses UCF101 and HDMB51 datasets, which are publicly available.
</p>
</fn>
<fn fn-type="other">
<p>
<bold>Funding Statement:</bold>
This work was supported by financial support from Universiti Sains Malaysia (USM) under FRGS grant number FRGS/1/2020/TK03/USM/02/1 and the School of Computer Sciences USM for their support.
</p>
</fn>
<fn fn-type="conflict">
<p>
<bold>Conflicts of Interest:</bold>
The authors declare that they have no conflicts of interest to report regarding the present study.
</p>
</fn>
</fn-group>
<ref-list content-type="authoryear">
<title>References</title>
<ref id="ref-1">
<label>[1]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>V.</given-names>
<surname>Choutas</surname>
</string-name>
,
<string-name>
<given-names>P.</given-names>
<surname>Weinzaepfel</surname>
</string-name>
,
<string-name>
<given-names>J.</given-names>
<surname>Revaud</surname>
</string-name>
and
<string-name>
<given-names>C.</given-names>
<surname>Schmid</surname>
</string-name>
</person-group>
, “
<article-title>Potion: Pose motion representation for action recognition</article-title>
,” in
<conf-name>Proc. of CVPR</conf-name>
,
<conf-loc>Salt Lake City, Utah, USA</conf-loc>
, pp.
<fpage>7024</fpage>
–
<lpage>7033</lpage>
,
<year>2018</year>
.
</mixed-citation>
</ref>
<ref id="ref-2">
<label>[2]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>L.</given-names>
<surname>Onofri</surname>
</string-name>
,
<string-name>
<given-names>P.</given-names>
<surname>Soda</surname>
</string-name>
,
<string-name>
<given-names>M.</given-names>
<surname>Pechenizkiy</surname>
</string-name>
and
<string-name>
<given-names>G.</given-names>
<surname>Iannello</surname>
</string-name>
</person-group>
, “
<article-title>A survey on using domain and contextual knowledge for human activity recognition in video streams</article-title>
,”
<source>Expert Systems with Applications</source>
, vol.
<volume>63</volume>
, pp.
<fpage>97</fpage>
–
<lpage>111</lpage>
,
<year>2016</year>
.
</mixed-citation>
</ref>
<ref id="ref-3">
<label>[3]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>C.</given-names>
<surname>Jobanputra</surname>
</string-name>
,
<string-name>
<given-names>J.</given-names>
<surname>Bavishi</surname>
</string-name>
and
<string-name>
<given-names>N.</given-names>
<surname>Doshi</surname>
</string-name>
</person-group>
, “
<article-title>Human activity recognition: A survey</article-title>
,”
<source>Procedia Computer Science</source>
, vol.
<volume>155</volume>
, pp.
<fpage>698</fpage>
–
<lpage>703</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-4">
<label>[4]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>J.</given-names>
<surname>Wang</surname>
</string-name>
,
<string-name>
<given-names>Y.</given-names>
<surname>Chen</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Hao</surname>
</string-name>
,
<string-name>
<given-names>X.</given-names>
<surname>Peng</surname>
</string-name>
and
<string-name>
<given-names>L.</given-names>
<surname>Hu</surname>
</string-name>
</person-group>
, “
<article-title>Deep learning for sensor-based activity recognition: A survey</article-title>
,”
<source>Pattern Recognition Letters</source>
, vol.
<volume>119</volume>
, pp.
<fpage>3</fpage>
–
<lpage>11</lpage>
,
<year>2019a</year>
.
</mixed-citation>
</ref>
<ref id="ref-5">
<label>[5]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>H. A.</given-names>
<surname>Ullah</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Letchmunan</surname>
</string-name>
,
<string-name>
<given-names>M. S.</given-names>
<surname>Zia</surname>
</string-name>
,
<string-name>
<given-names>U. M.</given-names>
<surname>Butt</surname>
</string-name>
and
<string-name>
<given-names>F. H.</given-names>
<surname>Hassan</surname>
</string-name>
</person-group>
, “
<article-title>Analysis of deep neural networks for human activity recognition in videos–a systematic literature review</article-title>
,”
<source>IEEE Access</source>
, vol.
<volume>9</volume>
, pp.
<fpage>126366</fpage>
–
<lpage>126387</lpage>
,
<year>2021</year>
.
</mixed-citation>
</ref>
<ref id="ref-6">
<label>[6]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>B.</given-names>
<surname>Nguyen</surname>
</string-name>
,
<string-name>
<given-names>Y.</given-names>
<surname>Coelho</surname>
</string-name>
,
<string-name>
<given-names>T.</given-names>
<surname>Bastos</surname>
</string-name>
and
<string-name>
<given-names>S.</given-names>
<surname>Krishnan</surname>
</string-name>
</person-group>
, “
<article-title>Trends in human activity recognition with focus on machine learning and power requirements</article-title>
,”
<source>Machine Learning with Applications</source>
, vol.
<volume>5</volume>
, pp.
<fpage>100072</fpage>
,
<year>2021</year>
.
</mixed-citation>
</ref>
<ref id="ref-7">
<label>[7]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>Q. -Q.</given-names>
<surname>Chen</surname>
</string-name>
,
<string-name>
<given-names>F.</given-names>
<surname>Liu</surname>
</string-name>
,
<string-name>
<given-names>X.</given-names>
<surname>Li</surname>
</string-name>
,
<string-name>
<given-names>B. -D.</given-names>
<surname>Liu</surname>
</string-name>
and
<string-name>
<given-names>Y. -J.</given-names>
<surname>Zhang</surname>
</string-name>
</person-group>
, “
<article-title>Saliency-context two-stream convnets for action recognition</article-title>
,” in
<conf-name>IEEE ICIP</conf-name>
,
<conf-loc>Phoenix, Arizona, USA</conf-loc>
, pp.
<fpage>3076</fpage>
–
<lpage>3080</lpage>
,
<year>2016</year>
.
</mixed-citation>
</ref>
<ref id="ref-8">
<label>[8]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>Y.</given-names>
<surname>Liu</surname>
</string-name>
,
<string-name>
<given-names>Q.</given-names>
<surname>Wu</surname>
</string-name>
and
<string-name>
<given-names>L.</given-names>
<surname>Tang</surname>
</string-name>
</person-group>
, “
<article-title>Frame-skip convolutional neural networks for action recognition</article-title>
,” in
<conf-name>503 IEEE ICMEW</conf-name>
,
<conf-loc>London, U.K.</conf-loc>
, vol.
<volume>14/16</volume>
, pp.
<fpage>573</fpage>
–
<lpage>578</lpage>
,
<year>2017</year>
.
</mixed-citation>
</ref>
<ref id="ref-9">
<label>[9]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>J.</given-names>
<surname>Charmi</surname>
</string-name>
,
<string-name>
<given-names>J.</given-names>
<surname>Bavishi</surname>
</string-name>
and
<string-name>
<given-names>N.</given-names>
<surname>Doshi</surname>
</string-name>
</person-group>
, “
<article-title>Human activity recognition: A survey</article-title>
,”
<source>Procedia Computer Science</source>
, vol.
<volume>155</volume>
, pp.
<fpage>698</fpage>
–
<lpage>703</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-10">
<label>[10]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>S. K.</given-names>
<surname>Yadav</surname>
</string-name>
,
<string-name>
<given-names>K.</given-names>
<surname>Tiwari</surname>
</string-name>
,
<string-name>
<given-names>H. M.</given-names>
<surname>Pandey</surname>
</string-name>
and
<string-name>
<given-names>S. A.</given-names>
<surname>Akbar</surname>
</string-name>
</person-group>
, “
<article-title>A review of multimodal human activity recognition with special emphasis on classification, applications, challenges and future directions</article-title>
,”
<source>Knowledge-Based Systems</source>
, vol.
<volume>223</volume>
, pp.
<fpage>106970</fpage>
,
<year>2021</year>
.
</mixed-citation>
</ref>
<ref id="ref-11">
<label>[11]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>H.</given-names>
<surname>Gammulle</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Denman</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Sridharan</surname>
</string-name>
and
<string-name>
<given-names>C.</given-names>
<surname>Fookes</surname>
</string-name>
</person-group>
, “
<article-title>Two stream lstm: A deep fusion framework for human action recognition</article-title>
,” in
<conf-name>IEEE WACV</conf-name>
,
<conf-loc>Santa Rosa, CA</conf-loc>
, pp.
<fpage>177</fpage>
–
<lpage>186</lpage>
,
<year>2017</year>
.
</mixed-citation>
</ref>
<ref id="ref-12">
<label>[12]</label>
<mixed-citation publication-type="book">
<person-group person-group-type="author">
<string-name>
<given-names>K.</given-names>
<surname>Simonyan</surname>
</string-name>
and
<string-name>
<given-names>A.</given-names>
<surname>Zisserman</surname>
</string-name>
</person-group>
, “
<chapter-title>Two-stream convolutional networks for action recognition in videos</chapter-title>
,” in
<source>Advances in Neural Information Processing Systems</source>
, vol.
<volume>27</volume>
.
<publisher-loc>Montreal, Canada</publisher-loc>
: Neural Information Processing Systems Foundation, Inc. (NeurIPS), pp.
<fpage>568</fpage>
–
<lpage>576</lpage>
,
<year>2014a</year>
.
</mixed-citation>
</ref>
<ref id="ref-13">
<label>[13]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>J. D.</given-names>
<surname>Marshall</surname>
</string-name>
,
<string-name>
<given-names>T.</given-names>
<surname>Li</surname>
</string-name>
,
<string-name>
<given-names>J. H.</given-names>
<surname>Wu</surname>
</string-name>
and
<string-name>
<given-names>T. W.</given-names>
<surname>Dunn</surname>
</string-name>
</person-group>
, “
<article-title>Leaving flatland: Advances in 3D behavioral measurement</article-title>
,”
<source>Current Opinion in Neurobiology</source>
, vol.
<volume>73</volume>
, pp.
<fpage>102522</fpage>
,
<year>2022</year>
.
</mixed-citation>
</ref>
<ref id="ref-14">
<label>[14]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>V.</given-names>
<surname>Sharma</surname>
</string-name>
,
<string-name>
<given-names>M.</given-names>
<surname>Gupta</surname>
</string-name>
,
<string-name>
<given-names>A. K.</given-names>
<surname>Pandey</surname>
</string-name>
,
<string-name>
<given-names>D.</given-names>
<surname>Mishra</surname>
</string-name>
and
<string-name>
<given-names>A.</given-names>
<surname>Kumar</surname>
</string-name>
</person-group>
, “
<article-title>A review of deep learning-based human activity recognition on benchmark video datasets</article-title>
,”
<source>Applied Artificial Intelligence</source>
, vol.
<volume>36</volume>
, no.
<issue>1</issue>
, pp.
<fpage>2093705</fpage>
,
<year>2022</year>
.
</mixed-citation>
</ref>
<ref id="ref-15">
<label>[15]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>M.</given-names>
<surname>Bock</surname>
</string-name>
,
<string-name>
<given-names>A.</given-names>
<surname>Holzemann</surname>
</string-name>
,
<string-name>
<given-names>M.</given-names>
<surname>Moeller</surname>
</string-name>
and
<string-name>
<given-names>K.</given-names>
<surname>Van Laerhoven</surname>
</string-name>
</person-group>
, “
<article-title>Improving deep learning for har with shallow lstms</article-title>
,” in
<conf-name>Int. Symp. on Wearable Computers</conf-name>
,
<conf-loc>Virtually, USA</conf-loc>
, pp.
<fpage>7</fpage>
–
<lpage>12</lpage>
,
<year>2021</year>
.
</mixed-citation>
</ref>
<ref id="ref-16">
<label>[16]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>A. Z. M.</given-names>
<surname>Faridee</surname>
</string-name>
,
<string-name>
<given-names>S. R.</given-names>
<surname>Ramamurthy</surname>
</string-name>
,
<string-name>
<given-names>H. S.</given-names>
<surname>Hossain</surname>
</string-name>
and
<string-name>
<given-names>N.</given-names>
<surname>Roy</surname>
</string-name>
</person-group>
, “
<article-title>Happyfeet: Recognizing and assessing dances on the floor</article-title>
,” in
<conf-name>Proc. of HotMobile</conf-name>
,
<conf-loc>Tempe Arizona, USA</conf-loc>
, pp.
<fpage>49</fpage>
–
<lpage>54</lpage>
,
<year>2018</year>
.
</mixed-citation>
</ref>
<ref id="ref-17">
<label>[17]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>S.</given-names>
<surname>Zhang</surname>
</string-name>
,
<string-name>
<given-names>Y.</given-names>
<surname>Li</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Zhang</surname>
</string-name>
,
<string-name>
<given-names>F.</given-names>
<surname>Shahabi</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Xia</surname>
</string-name>
<etal>et al.,</etal>
</person-group>
“
<article-title>Deep learning in human activity recognition with wearable sensors: A review on advances</article-title>
,”
<source>Sensors</source>
, vol.
<volume>22</volume>
, no.
<issue>4</issue>
, pp.
<fpage>1476</fpage>
,
<year>2022</year>
.
</mixed-citation>
</ref>
<ref id="ref-18">
<label>[18]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>B.</given-names>
<surname>SravyaPranati</surname>
</string-name>
,
<string-name>
<given-names>D.</given-names>
<surname>Suma</surname>
</string-name>
,
<string-name>
<given-names>C.</given-names>
<surname>ManjuLatha</surname>
</string-name>
and
<string-name>
<given-names>S.</given-names>
<surname>Putheti</surname>
</string-name>
</person-group>
, “
<article-title>Large-scale video classification with convolutional neural networks</article-title>
,” in
<conf-name>Int. Conf. on Information and Communication Technology for Intelligent Systems</conf-name>
,
<conf-loc>Ahmedabad, India</conf-loc>
, pp.
<fpage>689</fpage>
–
<lpage>695</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-19">
<label>[19]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>A.</given-names>
<surname>Khelalef</surname>
</string-name>
,
<string-name>
<given-names>F.</given-names>
<surname>Ababsa</surname>
</string-name>
and
<string-name>
<given-names>N.</given-names>
<surname>Benoudjit</surname>
</string-name>
</person-group>
, “
<article-title>An efficient human activity recognition technique based on deep learning</article-title>
,”
<source>Pattern Recognition and Image Analysis</source>
, vol.
<volume>29</volume>
, no.
<issue>4</issue>
, pp.
<fpage>702</fpage>
–
<lpage>715</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-20">
<label>[20]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>H. D.</given-names>
<surname>Mehr</surname>
</string-name>
and
<string-name>
<given-names>H.</given-names>
<surname>Polat</surname>
</string-name>
</person-group>
, “
<article-title>Human activity recognition in smart home with deep learning approach</article-title>
,” in
<conf-name>7th ICSG</conf-name>
,
<conf-loc>Istanbul, Turkey</conf-loc>
, pp.
<fpage>149</fpage>
–
<lpage>153</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-21">
<label>[21]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>Z.</given-names>
<surname>Zheng</surname>
</string-name>
,
<string-name>
<given-names>G.</given-names>
<surname>An</surname>
</string-name>
,
<string-name>
<given-names>D.</given-names>
<surname>Wu</surname>
</string-name>
and
<string-name>
<given-names>Q.</given-names>
<surname>Ruan</surname>
</string-name>
</person-group>
, “
<article-title>Spatial-temporal pyramid based convolutional neural network for action recognition</article-title>
,”
<source>Neurocomputing</source>
, vol.
<volume>358</volume>
, pp.
<fpage>446</fpage>
–
<lpage>455</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-22">
<label>[22]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>B.</given-names>
<surname>Fernando</surname>
</string-name>
and
<string-name>
<given-names>S.</given-names>
<surname>Gould</surname>
</string-name>
</person-group>
, “
<article-title>Discriminatively learned hierarchical rank pooling networks</article-title>
,”
<source>International Journal of Computer Vision</source>
, vol.
<volume>124</volume>
, no.
<issue>3</issue>
, pp.
<fpage>335</fpage>
–
<lpage>355</lpage>
,
<year>2017</year>
.
</mixed-citation>
</ref>
<ref id="ref-23">
<label>[23]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>K.</given-names>
<surname>Muhammad</surname>
</string-name>
,
<string-name>
<given-names>A.</given-names>
<surname>Ullah</surname>
</string-name>
,
<string-name>
<given-names>A. S.</given-names>
<surname>Imran</surname>
</string-name>
,
<string-name>
<given-names>M.</given-names>
<surname>Sajjad</surname>
</string-name>
,
<string-name>
<given-names>M. S.</given-names>
<surname>Kiran</surname>
</string-name>
<etal>et al.,</etal>
</person-group>
“
<article-title>Human action recognition using attention based LSTM network with dilated CNN features</article-title>
,”
<source>Future Generation Computer Systems</source>
, vol.
<volume>125</volume>
, pp.
<fpage>820</fpage>
–
<lpage>830</lpage>
,
<year>2021</year>
.
</mixed-citation>
</ref>
<ref id="ref-24">
<label>[24]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>W.</given-names>
<surname>Zhu</surname>
</string-name>
,
<string-name>
<given-names>J.</given-names>
<surname>Hu</surname>
</string-name>
,
<string-name>
<given-names>G.</given-names>
<surname>Sun</surname>
</string-name>
,
<string-name>
<given-names>X.</given-names>
<surname>Cao</surname>
</string-name>
and
<string-name>
<given-names>Y.</given-names>
<surname>Qiao</surname>
</string-name>
</person-group>
, “
<article-title>A key volume mining deep framework for action recognition</article-title>
,” in
<conf-name>Proc. of CVPR</conf-name>
,
<conf-loc>Las Vegas, NV, USA</conf-loc>
, vol.
<volume>591</volume>
, pp.
<fpage>1991</fpage>
–
<lpage>1999</lpage>
,
<year>2016</year>
.
</mixed-citation>
</ref>
<ref id="ref-25">
<label>[25]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>M.</given-names>
<surname>Bilal</surname>
</string-name>
,
<string-name>
<given-names>M.</given-names>
<surname>Maqsood</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Yasmin</surname>
</string-name>
,
<string-name>
<given-names>N. U.</given-names>
<surname>Hasan</surname>
</string-name>
and
<string-name>
<given-names>S.</given-names>
<surname>Rho</surname>
</string-name>
</person-group>
, “
<article-title>A transfer learning-based efficient spatiotemporal human action recognition framework for long and overlapping action classes</article-title>
,”
<source>The Journal of Supercomputing</source>
, vol.
<volume>78</volume>
, no.
<issue>2</issue>
, pp.
<fpage>2873</fpage>
–
<lpage>2908</lpage>
,
<year>2022</year>
.
</mixed-citation>
</ref>
<ref id="ref-26">
<label>[26]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>J.</given-names>
<surname>Donahue</surname>
</string-name>
,
<string-name>
<given-names>L. A.</given-names>
<surname>Hendricks</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Guadarrama</surname>
</string-name>
,
<string-name>
<given-names>M.</given-names>
<surname>Rohrbach</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Venugopalan</surname>
</string-name>
<etal>et al.,</etal>
</person-group>
“
<article-title>Long-term recurrent convolutional networks for visual recognition and description</article-title>
,” in
<conf-name>Proc. of CVPR</conf-name>
,
<conf-loc>Boston, MA, USA</conf-loc>
, pp.
<fpage>2625</fpage>
–
<lpage>2634</lpage>
,
<year>2015</year>
.
</mixed-citation>
</ref>
<ref id="ref-27">
<label>[27]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>Z.</given-names>
<surname>Shou</surname>
</string-name>
,
<string-name>
<given-names>D.</given-names>
<surname>Wang</surname>
</string-name>
and
<string-name>
<given-names>S. -F.</given-names>
<surname>Chang</surname>
</string-name>
</person-group>
, “
<article-title>Temporal action localization in untrimmed videos via multi-stage cnns</article-title>
,” in
<conf-name>Proc. of CVPR</conf-name>
,
<conf-loc>Las Vegas, NV, USA</conf-loc>
, pp.
<fpage>1049</fpage>
–
<lpage>1058</lpage>
,
<year>2016</year>
.
</mixed-citation>
</ref>
<ref id="ref-28">
<label>[28]</label>
<mixed-citation publication-type="thesis">
<person-group person-group-type="author">
<string-name>
<given-names>S.</given-names>
<surname>Buch</surname>
</string-name>
,
<string-name>
<given-names>V.</given-names>
<surname>Escorcia</surname>
</string-name>
,
<string-name>
<given-names>B.</given-names>
<surname>Ghanem</surname>
</string-name>
,
<string-name>
<given-names>L.</given-names>
<surname>Fei-Fei</surname>
</string-name>
and
<string-name>
<given-names>J. C.</given-names>
<surname>Niebles</surname>
</string-name>
</person-group>
, “End-to-end, single-stream temporal action detection in untrimmed videos,” Ph.D. Dissertation,
<publisher-name>KSA, KAUST</publisher-name>
,
<publisher-loc>Saudi Arabia</publisher-loc>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-29">
<label>[29]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>A.</given-names>
<surname>Ullah</surname>
</string-name>
,
<string-name>
<given-names>K.</given-names>
<surname>Muhammad</surname>
</string-name>
,
<string-name>
<given-names>J. D.</given-names>
<surname>Ser</surname>
</string-name>
,
<string-name>
<given-names>S. W.</given-names>
<surname>Baik</surname>
</string-name>
and
<string-name>
<given-names>V. H. C.</given-names>
<surname>Albuquerque</surname>
</string-name>
</person-group>
, “
<article-title>Activity recognition using temporal optical flow convolutional features and multilayer lstm</article-title>
,”
<source>IEEE Transactions on Industrial Electronics</source>
, vol.
<volume>66</volume>
, no.
<issue>12</issue>
, pp.
<fpage>9692</fpage>
–
<lpage>9702</lpage>
,
<year>2018</year>
.
</mixed-citation>
</ref>
<ref id="ref-30">
<label>[30]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>M. A. A. H.</given-names>
<surname>Khan</surname>
</string-name>
,
<string-name>
<given-names>R.</given-names>
<surname>Kukkapalli</surname>
</string-name>
,
<string-name>
<given-names>P.</given-names>
<surname>Waradpande</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Kulandaivel</surname>
</string-name>
,
<string-name>
<given-names>N.</given-names>
<surname>Banerjee</surname>
</string-name>
<etal>et al.,</etal>
</person-group>
“
<article-title>Ram: Radar-based activity monitor</article-title>
,” in
<conf-name>IEEE 35th INFOCOM</conf-name>
,
<conf-loc>San Francisco, CA, USA</conf-loc>
, pp.
<fpage>1</fpage>
–
<lpage>9</lpage>
,
<year>2016</year>
.
</mixed-citation>
</ref>
<ref id="ref-31">
<label>[31]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>N.</given-names>
<surname>Crasto</surname>
</string-name>
,
<string-name>
<given-names>P.</given-names>
<surname>Weinzaepfel</surname>
</string-name>
,
<string-name>
<given-names>K.</given-names>
<surname>Alahari</surname>
</string-name>
and
<string-name>
<given-names>C.</given-names>
<surname>Schmid</surname>
</string-name>
</person-group>
, “
<article-title>Mars: Motion-augmented rgb stream for action recognition</article-title>
,” in
<conf-name>Proc. of the IEEE CVPR</conf-name>
,
<conf-loc>Utah, USA</conf-loc>
, pp.
<fpage>7882</fpage>
–
<lpage>7891</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-32">
<label>[32]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>K.</given-names>
<surname>He</surname>
</string-name>
,
<string-name>
<given-names>X.</given-names>
<surname>Zhang</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Ren</surname>
</string-name>
and
<string-name>
<given-names>J.</given-names>
<surname>Sun</surname>
</string-name>
</person-group>
, “
<article-title>Identity mappings in deep residual networks</article-title>
,” in
<conf-name>ECCV</conf-name>
,
<conf-loc>Amsterdam, Netherlands</conf-loc>
, pp.
<fpage>630</fpage>
–
<lpage>645</lpage>
,
<year>2016</year>
.
</mixed-citation>
</ref>
<ref id="ref-33">
<label>[33]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>Y.</given-names>
<surname>Fin</surname>
</string-name>
,
<string-name>
<given-names>Z.</given-names>
<surname>Lan</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Newsam</surname>
</string-name>
and
<string-name>
<given-names>A.</given-names>
<surname>Hauptmann</surname>
</string-name>
</person-group>
, “
<article-title>Hidden two-stream convolutional networks for 592 action recognition</article-title>
,” in
<conf-name>ACCV</conf-name>
,
<conf-loc>Kyoto, Japan</conf-loc>
, pp.
<fpage>363</fpage>
–
<lpage>378</lpage>
,
<year>2018</year>
.
</mixed-citation>
</ref>
<ref id="ref-34">
<label>[34]</label>
<mixed-citation publication-type="other">
<person-group person-group-type="author">
<string-name>
<given-names>K.</given-names>
<surname>Soomro</surname>
</string-name>
,
<string-name>
<given-names>A. R.</given-names>
<surname>Zamir</surname>
</string-name>
and
<string-name>
<given-names>M.</given-names>
<surname>Shah</surname>
</string-name>
</person-group>
, “
<article-title>Ucf101: A dataset of 101 human actions classes from videos in the wild</article-title>
,” arXiv preprint arXiv:1212.0402,
<publisher-loc>Harvard, US</publisher-loc>
,
<year>2012a</year>
.
</mixed-citation>
</ref>
<ref id="ref-35">
<label>[35]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>H.</given-names>
<surname>Kuehne</surname>
</string-name>
,
<string-name>
<given-names>H.</given-names>
<surname>Jhuang</surname>
</string-name>
,
<string-name>
<given-names>E.</given-names>
<surname>Garrote</surname>
</string-name>
,
<string-name>
<given-names>T.</given-names>
<surname>Poggio</surname>
</string-name>
and
<string-name>
<given-names>T.</given-names>
<surname>Serre</surname>
</string-name>
</person-group>
, “
<article-title>Hmdb: A large video database for human motion recognition</article-title>
,” in
<conf-name>2011 ICCV</conf-name>
,
<conf-loc>Washington, DC, United States</conf-loc>
, pp.
<fpage>2556</fpage>
–
<lpage>2563</lpage>
,
<year>2011</year>
.
</mixed-citation>
</ref>
<ref id="ref-36">
<label>[36]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>G.</given-names>
<surname>Farneback</surname>
</string-name>
</person-group>
, “
<article-title>Fast and accurate motion estimation using orientation tensors and parametric motion models</article-title>
,” in
<conf-name>Proc. 15th ICPR-2000</conf-name>
,
<conf-loc>Barcelona, Spain</conf-loc>
, vol.
<volume>1</volume>
, pp.
<fpage>135</fpage>
–
<lpage>139</lpage>
,
<year>2000</year>
.
</mixed-citation>
</ref>
<ref id="ref-37">
<label>[37]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>M.</given-names>
<surname>Rahimzadeh</surname>
</string-name>
and
<string-name>
<given-names>A.</given-names>
<surname>Attar</surname>
</string-name>
</person-group>
, “
<article-title>A modified deep convolutional neural network for detecting covid19 and pneumonia from chest x-ray images based on the concatenation of xception and resnet50v2</article-title>
,”
<source>Informatics in Medicine Unlocked</source>
, vol.
<volume>19</volume>
, pp.
<fpage>100</fpage>
–
<lpage>360</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-38">
<label>[38]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>I.</given-names>
<surname>Sutskever</surname>
</string-name>
,
<string-name>
<given-names>J.</given-names>
<surname>Martens</surname>
</string-name>
,
<string-name>
<given-names>G.</given-names>
<surname>Dahl</surname>
</string-name>
and
<string-name>
<given-names>G.</given-names>
<surname>Hinton</surname>
</string-name>
</person-group>
, “
<article-title>On the importance of initialization and momentums in deep learning</article-title>
,” in
<conf-name>ICML</conf-name>
,
<conf-loc>USA</conf-loc>
, pp.
<fpage>1139</fpage>
–
<lpage>1147</lpage>
,
<year>2013</year>
.
</mixed-citation>
</ref>
<ref id="ref-39">
<label>[39]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>J.</given-names>
<surname>Duchi</surname>
</string-name>
,
<string-name>
<given-names>E.</given-names>
<surname>Hazan</surname>
</string-name>
and
<string-name>
<given-names>Y.</given-names>
<surname>Singer</surname>
</string-name>
</person-group>
, “
<article-title>Adaptive subgradient methods for online learning and stochastic optimizations</article-title>
,”
<source>Journal of Machine Learning Research</source>
, vol.
<volume>12</volume>
, no.
<issue>7</issue>
, pp.
<fpage>2121</fpage>
–
<lpage>2159</lpage>
,
<year>2011</year>
.
</mixed-citation>
</ref>
<ref id="ref-40">
<label>[40]</label>
<mixed-citation publication-type="other">
<person-group person-group-type="author">
<string-name>
<given-names>M. D.</given-names>
<surname>Zeiler</surname>
</string-name>
</person-group>
, “
<article-title>Adadelta: An adaptive learning rate method</article-title>
,” arXiv preprint arXiv, pp.
<fpage>1212</fpage>
–
<lpage>5701</lpage>
,
<year>2012</year>
.
</mixed-citation>
</ref>
<ref id="ref-41">
<label>[41]</label>
<mixed-citation publication-type="web">
<person-group person-group-type="author">
<string-name>
<given-names>G.</given-names>
,
<surname>Hinton</surname>
</string-name>
,
<string-name>
<given-names>N.</given-names>
<surname>Srivastava</surname>
</string-name>
and
<string-name>
<given-names>K.</given-names>
<surname>Swersky</surname>
</string-name>
</person-group>
, “
<article-title>Rmsprop: A mini-batch version of rprop</article-title>
,”
<italic>Coursera475 course lecture 6-Neural Networks for Machine Learning</italic>
.
<year>2012</year>
.
<uri xlink:href="https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf">https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf</uri>
.
</mixed-citation>
</ref>
<ref id="ref-42">
<label>[42]</label>
<mixed-citation publication-type="other">
<person-group person-group-type="author">
<string-name>
<given-names>D. P.</given-names>
<surname>Kingma</surname>
</string-name>
and
<string-name>
<given-names>J.</given-names>
<surname>Ba</surname>
</string-name>
</person-group>
, “
<article-title>Adam: A method for stochastic optimization</article-title>
,” arXiv preprint arXiv, pp.
<fpage>1412</fpage>
–
<lpage>6980</lpage>
,
<year>2014</year>
.
</mixed-citation>
</ref>
<ref id="ref-43">
<label>[43]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>R.</given-names>
<surname>Llugsi</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>El Yacoubi</surname>
</string-name>
,
<string-name>
<given-names>A.</given-names>
<surname>Fontaine</surname>
</string-name>
and
<string-name>
<given-names>P.</given-names>
<surname>Lupera</surname>
</string-name>
</person-group>
, “
<article-title>Comparison between adam, adamax and adam w optimizers to implement a weather forecast based on neural networks for the andean city of Quito</article-title>
,” in
<conf-name>IEEE Fifth Ecuador Technical Chapters Meeting (ETCM)</conf-name>
,
<conf-loc>NYC, USA</conf-loc>
, pp.
<fpage>1</fpage>
–
<lpage>6</lpage>
,
<year>2021</year>
.
</mixed-citation>
</ref>
<ref id="ref-44">
<label>[44]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>T.</given-names>
<surname>Nguyen</surname>
</string-name>
,
<string-name>
<given-names>R.</given-names>
<surname>Baraniuk</surname>
</string-name>
,
<string-name>
<given-names>A.</given-names>
<surname>Bertozzi</surname>
</string-name>
,
<string-name>
<given-names>S.</given-names>
<surname>Osher</surname>
</string-name>
and
<string-name>
<given-names>B.</given-names>
<surname>Wang</surname>
</string-name>
</person-group>
, “
<article-title>Momentumrnn: Integrating momentum into recurrent neural networks</article-title>
,”
<source>Advances in Neural Information Processing Systems</source>
, vol.
<volume>33</volume>
, pp.
<fpage>1924</fpage>
–
<lpage>1936</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-45">
<label>[45]</label>
<mixed-citation publication-type="conf-proc">
<person-group person-group-type="author">
<string-name>
<given-names>S.</given-names>
<surname>Vani</surname>
</string-name>
and
<string-name>
<given-names>T. M.</given-names>
<surname>Rao</surname>
</string-name>
</person-group>
, “
<article-title>An experimental approach towards the performance assessment of various optimizers on convolutional neural network</article-title>
,” in
<conf-name>3rd ICOEI</conf-name>
,
<conf-loc>Tirunelveli, India</conf-loc>
, pp.
<fpage>331</fpage>
–
<lpage>336</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
<ref id="ref-46">
<label>[46]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>Y.</given-names>
<surname>Li</surname>
</string-name>
and
<string-name>
<given-names>L.</given-names>
<surname>Wang</surname>
</string-name>
</person-group>
, “
<article-title>Human activity recognition based on residual network and bilstm</article-title>
,”
<source>Sensors</source>
, vol.
<volume>22</volume>
, no.
<issue>2</issue>
, pp.
<fpage>635</fpage>
,
<year>2022</year>
.
</mixed-citation>
</ref>
<ref id="ref-47">
<label>[47]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>Y.</given-names>
<surname>Huang</surname>
</string-name>
,
<string-name>
<given-names>Y.</given-names>
<surname>Guo</surname>
</string-name>
and
<string-name>
<given-names>C.</given-names>
<surname>Gao</surname>
</string-name>
</person-group>
, “
<article-title>Efficient parallel inflated 3D convolution architecture for action recognition</article-title>
,”
<source>IEEE Access</source>
, vol.
<volume>8</volume>
, pp.
<fpage>45753</fpage>
–
<lpage>45765</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-48">
<label>[48]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>Y.</given-names>
<surname>Wan</surname>
</string-name>
,
<string-name>
<given-names>Z.</given-names>
<surname>Yu</surname>
</string-name>
,
<string-name>
<given-names>Y.</given-names>
<surname>Wang</surname>
</string-name>
and
<string-name>
<given-names>X.</given-names>
<surname>Li</surname>
</string-name>
</person-group>
, “
<article-title>Action recognition based on twostream convolutional networks with long-short-term spatiotemporal features</article-title>
,”
<source>IEEE Access</source>
, vol.
<volume>8</volume>
, pp.
<fpage>85284</fpage>
–
<lpage>85293</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-49">
<label>[49]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>J.</given-names>
<surname>Wang</surname>
</string-name>
,
<string-name>
<given-names>X.</given-names>
<surname>Peng</surname>
</string-name>
and
<string-name>
<given-names>Y.</given-names>
<surname>Qiao</surname>
</string-name>
</person-group>
, “
<article-title>Cascade multi-head attention networks for action recognition</article-title>
,”
<source>Computer Vision and Image Understanding</source>
, vol.
<volume>192</volume>
, pp.
<fpage>102</fpage>
–
<lpage>898</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-50">
<label>[50]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>S. A.</given-names>
<surname>Khowaja</surname>
</string-name>
and
<string-name>
<given-names>S. L.</given-names>
<surname>Lee</surname>
</string-name>
</person-group>
, “
<article-title>Semantic image networks for human action recognition</article-title>
,”
<source>International Journal of Computer Vision</source>
, vol.
<volume>128</volume>
, no.
<issue>2</issue>
, pp.
<fpage>393</fpage>
–
<lpage>419</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-51">
<label>[51]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>Y.</given-names>
<surname>Zhu</surname>
</string-name>
and
<string-name>
<given-names>G.</given-names>
<surname>Liu</surname>
</string-name>
</person-group>
, “
<article-title>Fine-grained action recognition using multi-view attentions</article-title>
,”
<source>The Visual Computer</source>
, vol.
<volume>36</volume>
, no.
<issue>9</issue>
, pp.
<fpage>1771</fpage>
–
<lpage>1781</lpage>
,
<year>2020</year>
.
</mixed-citation>
</ref>
<ref id="ref-52">
<label>[52]</label>
<mixed-citation publication-type="journal">
<person-group person-group-type="author">
<string-name>
<given-names>S.</given-names>
<surname>Chaudhary</surname>
</string-name>
and
<string-name>
<given-names>S.</given-names>
<surname>Murala</surname>
</string-name>
</person-group>
, “
<article-title>Deep network for human action recognition using weber motion</article-title>
,”
<source>Neurocomputing</source>
, vol.
<volume>367</volume>
, pp.
<fpage>207</fpage>
–
<lpage>216</lpage>
,
<year>2019</year>
.
</mixed-citation>
</ref>
</ref-list>
</back>
</article>
