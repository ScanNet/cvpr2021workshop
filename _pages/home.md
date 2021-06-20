---
layout: project
urltitle:  "ScanNet Indoor Scene Understanding Challenge"
title: "ScanNet Indoor Scene Understanding Challenge"
categories: cvpr, workshop, computer vision, computer graphics, visual learning, simulation environments, robotics, machine learning, natural language processing, reinforcement learning
permalink: /
favicon: /static/img/ico/favicon.png
bibtex: true
paper: true
acknowledgements: ""
---

<br>
<div class="row">
  <div class="col-xs-12">
    <center><h1>3rd ScanNet Indoor Scene Understanding Challenge</h1></center>
    <center><h2>CVPR 2021 Workshop</h2></center>
    <center><h3 style="color:darkblue;font-weight:100">June 20, 2021</h3></center>
  </div>
</div>

<hr>

<br>
  <center>
  <h1 style="color:blue"><a href="https://youtu.be/jr_bKmh6YUY">Join Us Here: Live Stream</a></h1>
  </center>
<br>

<div class="row" id="intro">
  <div class="col-md-12">
    <img src="{{ "/static/img/splash.jpg" | prepend:site.baseurl }}">
  </div>
</div>

<br>
<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Introduction</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      3D scene understanding for indoor environments is becoming an increasingly important area.
      Application domains such as augmented and virtual reality, computational photography, interior design, and autonomous mobile robots all require a deep understanding of 3D interior spaces, the semantics of objects that are present, and their relative configurations in 3D space.
    </p>
    <p>
      We present the first comprehensive challenge for 3D scene understanding of entire rooms at the object instance-level with 5 tasks based on the ScanNet dataset.
      The ScanNet dataset is a large-scale semantically annotated dataset of 3D mesh reconstructions of interior spaces (approx. 1500 rooms and 2.5 million RGB-D frames).
      It is used by more than 480 research groups to develop and benchmark state-of-the-art approaches in semantic scene understanding.
      A key goal of this challenge is to compare state-of-the-art approaches operating on image data (including RGB-D) with approaches operating directly on 3D data (point cloud, or surface mesh representations).
      Additionally, we pose both object category label prediction (commonly referred to as semantic segmentation), and instance-level object recognition (object instance prediction and category label prediction).
      We propose five tasks that cover this space:
    </p>
    <ul>
      <li>
        <strong>2D semantic label prediction</strong>: prediction of object category labels from 2D image representation
      </li>
      <li>
        <strong>2D semantic instance prediction</strong>: prediction of object instance and category labels from 2D image representation
      </li>
      <li>
        <strong>3D semantic label prediction</strong>: prediction of object category labels from 3D representation
      </li>
      <li>
        <strong>3D semantic instance prediction</strong>: prediction of object instance and category labels from 3D representation
      </li>
      <li>
        <strong>Scene type classification</strong>: classification of entire 3D room into a scene type
      </li>
    </ul>
      <h3 style="color:orange;font-weight:800">New This Year - Data Efficient Challenge!</h3>
    <p>In the data efficient challenge, training is conducted on  Limited Scene Reconstructions (LR) or Limited Scene Annotations (LA), for the tasks of 3D Semantic Segmentation, Instance Segmentation and Object Detection. 
    </p>
    <p>
      For each task, challenge participants are provided with prepared training, validation, and test datasets, and automated evaluation scripts.
      In addition to the public train-val-test split, benchmarking is done on a hidden test set whose raw data can be downloaded without annotations; in order to participate in the benchmark, the predictions on the hidden test set are uploaded to the evaluation server, where they are evaluated.
      Submission is restricted to submissions every two weeks to avoid finetuning on the test dataset.
      See more details at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/documentation">http://kaldir.vc.in.tum.de/scannet_benchmark/documentation</a> if you would like to participate in the challenge.
      The evaluation server leaderboard is live at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/">http://kaldir.vc.in.tum.de/scannet_benchmark/</a>.
      See the new data efficient <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/data_efficient/documentation">documentation</a> and <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/data_efficient">leaderboard</a>!.
    </p>
  </div>
</div>
<br>

<div class="row" id="tasks">
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_label_2d.jpg" | prepend:site.baseurl }}">
    <p>2D semantic label prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_instance_2d.jpg" | prepend:site.baseurl }}">
    <p>2D semantic instance prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_label_3d.jpg" | prepend:site.baseurl }}">
    <p>3D semantic label prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_instance_3d.jpg" | prepend:site.baseurl }}">
    <p>3D semantic instance prediction</p>
  </div>
  <!-- <div class="col-md-4">
    <p>&nbsp;</p>
  </div> -->
  <!-- <div class="col-md-4">
    <img src="{{ "/static/img/scene_type_classification.jpg" | prepend:site.baseurl }}">
    <p>Scene type classification</p>
  </div> -->
</div>

<!-- 
<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
  </div>
</div>
 -->
 
<!-- 
<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr><td>TBD</td><td>TBD</td></tr>
        <tr>
          <td>Poster Submission Deadline</td>
          <td>May 20 2020</td>
        </tr>
        <tr>
          <td>Notification to Authors</td>
          <td>May 25 2020</td>
        </tr>
        <tr>
          <td>Workshop Date</td>
          <td>June 19 2020</td>
        </tr>
      </tbody>
    </table>
  </div>
</div><br>
 -->
<!-- 
<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Posters</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      To submit a poster to the workshop, please email the poster as .pdf file to scannet@googlegroups.com.
    </p>
  </div>
</div><br>
-->

<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Schedule</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
     <table class="table table-striped">
      <tbody>
        <tr><td></td><td>PDT</td><td>CEST</td></tr>
        <tr>
          <td>Welcome and Introduction</td>
          <td>8:50am - 9:00am</td><td>5:50pm - 6:00pm</td>
        </tr>
        <tr>
          <td>Neural Surface Representations (Niloy Mitra)</td>
          <td>9:00am - 10:00am</td><td>6:00pm - 7:00pm</td>
        </tr>
        <tr>
          <td>Winner Talk: Point Cloud Instance Segmentation using Probabilistic Embeddings (Biao Zhang)</td>
          <td>10:00am - 10:10am</td><td>7:00pm - 7:10pm</td>
        </tr>
        <tr>
          <td>Winner Talk: BPNet (Wenbo Hu) </td>
          <td>10:10am - 10:20am</td><td>7:10pm - 7:20pm</td>
        </tr>
        <tr>
          <td>Winner Talk: Virtual MVFusion (Abhijit Kundu) </td>
          <td>10:20am - 10:30am</td><td>7:20pm - 7:30pm</td>
        </tr>
        <tr>
          <td>Offboard 3D Object Detection From Point Cloud Sequences (Charles Qi) </td>
          <td>10:30am - 11:00am</td><td>7:30pm - 8:00pm</td>
        </tr>
        <tr>
          <td>Towards Gigapixel 3D Imaging (Lu Fang) </td>
          <td>11:00am - 11:30am</td><td>8:00pm - 8:30pm</td>
        </tr>
        <tr>
          <td>Transfer3D: Learning Transferrable Representations of 3D Scenes (Saining Xie)</td> 
          <td>11:30am - 12:00pm</td><td>8:30pm - 9:00pm</td>
        </tr>
        <tr>
          <td>Panel Discussion and Conclusion</td>
          <td>12:00pm - 12:30pm</td><td>9:00pm - 9:30pm</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br>
<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Invited Speakers</h2>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="http://www0.cs.ucl.ac.uk/staff/n.mitra/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/niloy_mitra.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="http://www0.cs.ucl.ac.uk/staff/n.mitra/">Niloy Mitra</a></b> is a Professor of Geometry Processing in the Department of Computer Science, University College London (UCL). He received his MS and PhD in Electrical Engineering from Stanford University under the guidance of Leonidas Guibas and Marc Levoy, and was a postdoctoral scholar with Helmut Pottmann at Technical University Vienna. His research interests include shape analysis, computational design and fabrication, and geometry processing. Niloy received the 2013 ACM Siggraph Significant New Researcher Award for "his outstanding work in discovery and use of structure and function in 3D objects" (UCL press release), the BCS Roger Needham award (BCS press release) in 2015, and the Eurographics Outstanding Technical Contributions Award in 2019. He received the ERC Starting Grant on SmartGeometry in 2013. His work has twice been featured as research highlights in the Communications of the ACM, twice been selected by ACM Siggraph/Siggraph Asia (both in 2017) for press release as research highlight.
    </p>
  </div>
</div><br>
<div class="row">
  <div class="col-md-12">
    <a href="http://charlesrqi.com"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/charles_qi.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="http://charlesrqi.com">Charles Qi</a></b> is a research scientist at Waymo LLC. Previously, he was a postdoctoral researcher at Facebook AI Research (FAIR) and  received his Ph.D. from Stanford University (Stanford AI Lab and Geometric Computation Group), advised by Professor Leonidas J. Guibas. Prior to Stanford, he received his B.Eng. from Tsinghua University. His research focuses on deep learning, computer vision and 3D. He has developed novel deep learning architectures for 3D data (point clouds, volumetric grids and multi-view images) that have wide applications in 3D object classification, object part segmentation, semantic scene parsing, scene flow estimation and 3D reconstruction; such deep architectures have been well adopted by both academic and industrial groups across the world. 
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="http://www.luvision.net/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/lu_fang.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="http://www.luvision.net/">Lu Fang</a></b> is an Associate Professor at Tsinghua University. She received her Ph.D from the Hong Kong University of Science and Technology in 2011, and her B.E. from Univ. of Science and Technology of China in 2007, respectively. Prof. Fang's research interests include computational imaging and 3D vision. Prof. Fang's research has been recognized by the NSFC Excellent Young Scholar Award, Multimedia Rising Star Award in ICME 2019, Best Student Paper Award in ICME 2017, and more. Prof. Fang is an currently IEEE Senior Member, and serving as an Associate Editor for IEEE TMM and TCSVT.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://vcl.ucsd.edu/~sxie/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/saining_xie.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://vcl.ucsd.edu/~sxie/">Saining Xie</a></b> is a research scientist at Facebook AI Research (FAIR). He received a PhD in computer science from the University of California San Diego in 2018, advised by Zhuowen Tu. Prior to that, he received his B.S. from Shanghai Jiao Tong University in 2013. He has broad research interests in computer vision and deep learning, with a focus on representation learning for visual recognition in both 2D and 3D. He is a recipient of the Google Ph.D. fellowship in 2017 and the Marr Prize Honorable Mention award at ICCV 2015.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-2">
    <a href="https://angeladai.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/angela.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://angeladai.github.io/">Angela Dai</a>
      <h6>Technical University of Munich</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://angelxuanchang.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/angel.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://angelxuanchang.github.io/">Angel X. Chang</a>
      <h6>Simon Fraser University</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://msavva.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/manolis.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://msavva.github.io/">Manolis Savva</a>
      <h6>Simon Fraser University</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://niessnerlab.org/members/matthias_niessner/profile.html">
      <img class="people-pic" src="{{ "/static/img/people/matthias.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://niessnerlab.org/members/matthias_niessner/profile.html">Matthias Niessner</a>
      <h6>Technical University of Munich</h6>
    </div>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-xs-12">
    <h2>Acknowledgments</h2>
  </div>
</div>
<a name="/acknowledgements"></a>
<div class="row">
  <div class="col-xs-12">
    <p>
      Thanks to <span style="color:#1a1aff;font-weight:400;"> <a href="https://visualdialog.org/">visualdialog.org</a></span> for the webpage format.
    </p>
  </div>
</div>
