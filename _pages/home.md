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
    <center><h2>CVPR 2023 Workshop, Vancouver, Canada</h2></center>
    <center>June 19, 2023, Afternoon</center> <!-- location-->
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
    <h3 style="color:orange;font-weight:800">Highlight - Data Efficient Challenge!</h3>
    <p>In the data efficient challenge, training is conducted on  Limited Scene Reconstructions (LR) or Limited Scene Annotations (LA), for the tasks of 3D Semantic Segmentation, Instance Segmentation and Object Detection. 
    </p>
    <h3 style="color:orange;font-weight:800">Highlight - ScanNet200 Challenge!</h3>
    <p>In the ScanNet200 challenge, large-vocabulary scene understanding is challenged with 200 class categories for the tasks of 3D semantic segmentation and 3D instance segmentation. 
    </p>
    <p>
      For each task, challenge participants are provided with prepared training, validation, and test datasets, and automated evaluation scripts.
      In addition to the public train-val-test split, benchmarking is done on a hidden test set whose raw data can be downloaded without annotations; in order to participate in the benchmark, the predictions on the hidden test set are uploaded to the evaluation server, where they are evaluated.
      Submission is restricted to submissions every two weeks to avoid finetuning on the test dataset.
      See more details at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/documentation">http://kaldir.vc.in.tum.de/scannet_benchmark/documentation</a> if you would like to participate in the challenge.
      The evaluation server leaderboard is live at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/">http://kaldir.vc.in.tum.de/scannet_benchmark/</a>.
      See the data efficient <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/data_efficient/documentation">documentation</a> and <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/data_efficient">leaderboard</a>.
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
    <h2>Schedule TBD</h2>
  </div>
</div>

<!-- 
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
          <td>1:30pm - 1:45pm</td>
        </tr>
        <tr>
          <td>Invited Talk 1: Peter Wonka</td>
          <td>1:45pm - 2:15pm</td>
        </tr>
        <tr>
          <td>Invited Talk 2: Leo Guibas</td>
          <td>2:15pm - 2:45pm</td>
        </tr>
        <tr>
          <td>Winner Talk 1 </td>
          <td>2:45pm - 3:00pm</td>
        </tr>
        <tr>
          <td>Break and poster session</td>
          <td>3:00pm - 3:45pm</td>
        </tr>
        <tr>
          <td>Winner Talk 2 </td>
          <td>3:45pm - 4:00pm</td>
        </tr>
        <tr>
          <td>Invited Talk 2: Georgia Gkioxari</td>
          <td>4:00pm - 4:30pm</td>
        </tr>
        <tr>
          <td>Invited Talk 3: Tom Funkhouser</td>
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
 -->
 
<br>
<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Invited Speakers</h2>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://geometry.stanford.edu/member/guibas/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/leo.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://geometry.stanford.edu/member/guibas/">Leonidas Guibas</a></b> is the Paul Pigott Professor of Computer Science (and by courtesy), Electrical Engineering at Stanford University, where he heads the Geometric Computation group.  Dr. Guibas obtained his Ph.D. from Stanford University under the supervision of Donald Knuth. His main subsequent employers were Xerox PARC, DEC/SRC, MIT, and Stanford. He is a member and past acting director of the Stanford Artificial Intelligence Laboratory and a member of the Computer Graphics Laboratory, the Institute for Computational and Mathematical Engineering (iCME), and the Bio-X program. Dr. Guibas has been elected to the US National Academy of Engineering, the US National Academy of Sciences, the American Academy of Arts and Sciences and is an ACM Fellow, an IEEE Fellow, and winner of the ACM Allen Newell Award and the ICCV Helmholtz prize.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://gkioxari.github.io/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/georgia_gkioxari.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://gkioxari.github.io/">Georgia Gkioxari</a></b> is an Assistant Professor of Computing + Mathematical Sciences at Caltech. From 2016 to 2022, she was a research scientist at FAIR. She received her PhD from UC Berkeley, advised by Jitendra Malik. She received her bachelors in ECE at NTUA in Athens, Greece. Professor Gkioxari's work has been recognized by various awards, including the PAMI Young Researcher Award (2021), as well as the PAMI Mark Everingham Award (2021) for the Detectron Library Suite. She has also been named one of 30 influential women advancing AI in 2019 by ReWork, and nominated for the Women in AI Awards in 2020 by VentureBeat.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://peterwonka.net/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/peter_wonka.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://peterwonka.net/">Peter Wonka</a></b> is a professor of Computer Science Program (CS) at King Abdullah University of Science and Technology (KAUST). He is also the Associate Director of the Visual Computing Center (VCC) at KAUST. He holds an MS in Computer Science and in Urban Planning, and received his Ph.D. in Computer Science from the Vienna University of Technology. Before joining KAUST as a Professor of Computer Science, he has been a Postdoctoral Researcher, Georgia Institute of Technology, USA, and Associate Professor, Arizona State University, USA. Professor Wonka's main research interests lie in deep learning, computer vision, and computer graphics. He is also interested in related areas such as visualization, image processing, remote sensing, data mining, and machine learning.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://www.cs.princeton.edu/~funk/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/tom_funkhouser.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://www.cs.princeton.edu/~funk/">Tom Funkhouser</a></b> is a principal research scientist at Google and a Professor Emeritus at Princeton University.   His research interests include 3D computer vision and computer graphics, with a current focus on 3D scene understanding.   He is an ACM Fellow, a member of the ACM SIGGRAPH Academy, and a recipient of the ACM SIGGRAPH Achievement Award, Sloan Foundation Fellowship, NSF Career Award, two Excellence in Teaching Awards, and several best paper awards.
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
