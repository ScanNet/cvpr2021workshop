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
    <center><h1>ScanNet Indoor Scene Understanding Challenge</h1></center>
    <center><h2>CVPR 2019 Workshop, Long Beach, CA</h2></center>
    <center>June 16, 2019; Hyatt Seaview B</center>
  </div>
</div>

<hr>

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
    <p>
      For each task, challenge participants are provided with prepared training, validation, and test datasets, and automated evaluation scripts.
      In addition to the public train-val-test split, benchmarking is done on a hidden test set whose raw data can be downloaded without annotations; in order to participate in the benchmark, the predictions on the hidden test set are uploaded to the evaluation server, where they are evaluated.
      Submission is restricted to submissions every two weeks to avoid finetuning on the test dataset.
      See more details at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/documentation">http://kaldir.vc.in.tum.de/scannet_benchmark/documentation</a> if you would like to participate in the challenge.
      The evaluation server leaderboard is live at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/">http://kaldir.vc.in.tum.de/scannet_benchmark/</a>.
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

<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td>Poster Submission Deadline</td>
          <td>May 15 2019</td>
        </tr>
        <tr>
          <td>Notification to Authors</td>
          <td>May 20 2019</td>
        </tr>
        <tr>
          <td>Workshop Date</td>
          <td>June 16 2019</td>
        </tr>
      </tbody>
    </table>
  </div>
</div><br>

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

<div class="row">
  <div class="col-xs-12">
    <h2>Schedule</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
     <table class="table table-striped">
      <tbody>
        <tr>
          <td>Welcome and Introduction</td>
          <td>1:45pm - 2:00pm</td>
        </tr>
        <tr>
          <td>Invited Talk 1: Jitendra Malik, <i>Seeing while moving and moving while seeing in a 3D world</i></td>
          <td>2:00pm - 2:30pm</td>
        </tr>
        <tr>
          <td>Winner Talk 1 (MinkowskiNet / Chris Choy) </td>
          <td>2:30pm - 2:45pm</td>
        </tr>
        <tr>
          <td>Winner Talk 2 (joint point-based / Hung-Yueh Chiang) </td>
          <td>2:45pm - 3:00pm</td>
        </tr>
        <tr>
          <td>Winner Talk 3 (MTML / Jean Lahoud) </td>
          <td>3:00pm - 3:15pm</td>
        </tr>
        <tr>
          <td>Winner Talk 4 (PanopticFusion / Gaku Narita) </td>
          <td>3:15pm - 3:30pm</td>
        </tr>
        <tr>
          <td>Break and poster session</td>
          <td>3:30pm - 4:00pm</td>
        </tr>
        <tr>
          <td>Invited Talk 2: Leo Guibas, <i>Deep Learning on 3D Point Clouds</i></td>
          <td>4:00pm - 4:30pm</td>
        </tr>
        <tr>
          <td>Invited Talk 3: Denver Dash, <i>Deep 3D: The New Frontier of Computer Vision</i></td>
          <td>4:30pm - 5:00pm</td>
        </tr>
        <tr>
          <td>Panel Discussion and Conclusion</td>
          <td>5:00pm - 5:30pm</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br>
<div class="row">
  <div class="col-xs-12">
    <h2>Invited Speakers</h2>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://geometry.stanford.edu/member/guibas/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/leo.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://geometry.stanford.edu/member/guibas/">Leonidas J. Guibas</a></b> heads the Geometric Computation group in the Computer Science Department of Stanford University.  He is acting director of the Artificial Intelligence Laboratory and member of the Computer Graphics Laboratory, the Institute for Computational and Mathematical Engineering (iCME) and the Bio-X program.  His research centers on algorithms for sensing, modeling, reasoning, rendering, and acting on the physical world. Professor Guibas' interests span computational geometry, geometric modeling, computer graphics, computer vision, sensor networks, robotics, and discrete algorithms --- all areas in which he has published and lectured extensively.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://people.eecs.berkeley.edu/~malik/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/jitendra.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://people.eecs.berkeley.edu/~malik/">Jitendra Malik</a></b> received the B.Tech degree in Electrical Engineering from Indian Institute of Technology, Kanpur in 1980 and the PhD degree in Computer Science from Stanford University in 1985. In January 1986, he joined the university of California at Berkeley, where he is currently the Arthur J. Chick Professor in the Department of Electrical Engineering and Computer Sciences. He is also on the faculty of the department of Bioengineering, and the Cognitive Science and Vision Science groups. During 2002-2004 he served as the Chair of the Computer Science Division, and as the Department Chair of EECS during 2004-2006 as well as 2016-2017. Since January 2018, he is also Research Director and Site Lead of Facebook AI Research in Menlo Park.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://occipital.com/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/denver.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://occipital.com/">Denver Dash</a></b> is the Director of Machine Learning at Occipital, where he focuses on combining machine learning with geometric vision to solve problems in 3d perception. In 2014 he became a Principal Engineer and approximately employee number 80 at Magic Leap, where he grew the Machine Learning team from scratch. In 2016 he became the Director of Gesture Recognition and led the development of the hand tracking system that was put into production for Magic Leap One. Prior to Magic Leap, Denver was a Sr. Research Scientist at the Intel Research lab at Carnegie Mellon University, where he served as adjunct faculty at the Robotics Institute, developing novel multi-modal approaches for computer vision and generative models for causal reasoning.
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
      <h6>Eloquent Labs, Simon Fraser University</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://msavva.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/manolis.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://msavva.github.io/">Manolis Savva</a>
      <h6>Simon Fraser University, Facebook AI Research</h6>
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
