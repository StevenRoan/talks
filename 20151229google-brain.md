# Google Deep Learning
* Rectified Linear Unit (ReLU)
* Publication:
  * Object recognition in images (Erhan et al., 2014). (Google photos 的Demo)
  * Object category discovery in videos (Le et al., ICML 2012). (Google photos 的Demo)
  * Speech Recognition (Vanhoucke et al, NIPS Workshop 2011)
  * Annotating images with text (Vinyals et al., arXiv 2014)
  * Pedestrian detection for self-driving cars (Angelova et al., arXiv 2014)
  * OCR: reading text from images (Goodfellow et al., ICLR 2014)
  * Nautral Language Understaging (Milolov 2013)


* Data 能用盡量用，寧可犧牲ML model的複雜度。 (當然最好的事 large data set + Powerful Model)
* Experiment Turnaround Time and Research Productivity
 * Minute, Hours
  * Interactive research
 * 1-4 days Tolerable
  * Running parallel
 * 1-4 weeks Progress stalls
  * High value experiments only
 * > 1month
  * Don't even try

* Paralleslism
 * Model Parallelism
  * Single Core: Instruction parallelism (SIMD). (加compiler flag 即可)
  * Across Core: Thread level parallelism (盡量用現有的tool)
  * Across Device: For GPUs, often limited by PCIe bandwidth
  * Across Macihne: network bandwidth / latency
 * Data Parallelism
  * Synchronously (?)
  * Convolutional models(?)
  * Recurrent model(?)



* Current Deep Learning Progress
 * Image Recognition
  * Supervision(AlexNet)
  * GoogLeNet (Inception)

  * [Rethink inception image recognition](http://gitxiv.com/posts/2PjNxA4YkSX4p3Bjt/rethinking-the-inception-architecture-for-computer-vision)

  * sequence to sequence model(?)
  * Neural Conversational Model [Vinyals & Le ICML DL Wokshop 2015](http://arxiv.org/pdf/1506.05869v3.pdf)

  * Deep model 學出來一個 black box

  * Deep Dream
   *
  * Deep learning for text
   * word embedding

   neural-art-tf

Google Brain Residency Program
  RankBrain
  ImageNet

