---
layout: page
# title: VisionADL
permalink: /VisionADL/
# description: A growing collection of your cool projects.
# nav: true
# nav_order: 2
---

<html>

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
    <title>VisionADL</title>

    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <!-- <script type="text/javascript" src="jquery.mlens-1.0.min.js"></script> -->
    <!-- <script type="text/javascript" src="jquery.js"></script> -->
    <style>
        body {
            font-family: 'Open-Sans', sans-serif;
            font-weight: 300;
            background-color: #fff;
        }

        .content {
            width: 1000px;
            padding: 25px 50px;
            margin: 25px auto;
            background-color: white;
            box-shadow: 0px 0px 10px #999;
            border-radius: 15px;
        }

        .contentblock {
            width: 950px;
            margin: 0 auto;
            padding: 0;
            border-spacing: 25px 0;
        }

        .contentblock td {
            background-color: #fff;
            padding: 25px 50px;
            vertical-align: top;
            box-shadow: 0px 0px 10px #999;
            border-radius: 15px;
        }

        a,
        a:visited {
            color: #224b8d;
            font-weight: 300;
        }

        #authors {
            text-align: center;
            margin-bottom: 20px;
        }

        #conference {
            text-align: center;
            margin-bottom: 20px;
            font-style: italic;
        }

        #authors a {
            margin: 0 10px;
        }

        h1 {
            text-align: center;
            font-size: 35px;
            font-weight: 300;
        }

        h2 {
            font-size: 30px;
            font-weight: 300;
        }

        code {
            display: block;
            padding: 10px;
            margin: 10px 10px;
        }

        p {
            line-height: 25px;
            text-align: justify;
        }

        p code {
            display: inline;
            padding: 0;
            margin: 0;
        }

        #teasers {
            margin: 0 auto;
        }

        #teasers td {
            margin: 0 auto;
            text-align: center;
            padding: 5px;
        }

        #teasers img {
            width: 250px;
        }

        #results img {
            width: 133px;
        }

        #seeintodark {
            margin: 0 auto;
        }

        #sift {
            margin: 0 auto;
        }

        #sift img {
            width: 250px;
        }

        .downloadpaper {
            padding-left: 20px;
            float: right;
            text-align: center;
        }

        .downloadpaper a {
            font-weight: bold;
            text-align: center;
        }

        #demoframe {
            border: 0;
            padding: 0;
            margin: 0;
            width: 100%;
            height: 340px;
        }

        #feedbackform {
            border: 1px solid #ccc;
            margin: 0 auto;
            border-radius: 15px;
        }

        #eyeglass {
            height: 530px;
        }

        #eyeglass #wrapper {
            position: relative;
            height: auto;
            margin: 0 auto;
            float: left;
            width: 800px;
        }

        #mitnews {
            font-weight: normal;
            margin-top: 20px;
            font-size: 14px;
            width: 220px;
        }

        #mitnews a {
            font-weight: normal;
        }

        .teaser-img {
            width: 80%;
						display: block;
						margin-left: auto;
						margin-right: auto;
        }
        .teaser-gif {
						display: block;
						margin-left: auto;
						margin-right: auto;
        }
        .summary-img {
            width: 100%;
						display: block;
						margin-left: auto;
						margin-right: auto;
        }

        .video-iframe {
            width: 1000;
            height: 800;
						margin:auto;
						display:block;
        }

      .container {
        display: flex;
        align-items: center;
        justify-content: center
      }
      .image {
        flex-basis: 40%
      }
      .text {
        font-size: 20px;
        padding-left: 20px;
      }
			.center {
				margin-left: auto;
				margin-right: auto;
			}
			.boxshadow {
				border: 1px solid;
				padding: 10px;
				box-shadow: 2px 2px 5px #888888;
			}
			.spacertr{
				height: 8px;
			}
			.spacertd{
				width: 40px;
			}

    </style>
    <!-- Global site tag (gtag.js) - Google Analytics -->
		<!--
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-98008272-2"></script>
    <script>
        window.dataLayer = window.dataLayer || [];

        function gtag() {
            dataLayer.push(arguments);
        }
        gtag('js', new Date());
        gtag('config', 'UA-98008272-2');
    </script>
    <script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-MML-AM_CHTML">
    </script>
		-->

</head>

<body>

    <div class="content">
			<h1>VisionADL: Vision-Based Dataset to support activities of daily living for visually impaired individuals</h1>
        <p id="authors">
            <a href="https://hchlhwang.github.io/">Hochul Hwang</a>
            <a href="https://www.linkedin.com/in/matthew-hersey-a7b9141a1/?trk=people-guest_people_search-card">Matthew Hersey</a>
            <br>
            <!-- <strong>MIT Computer Science and Artificial Intelligence Laboratory</strong> -->
            DARoS Lab @ UMass Amherst
            <br><i>Dataset 2023</i>
        </p>
				<font size="+2">
					<p style="text-align: center;">
						<a href="https://arxiv.org/pdf/2210.13368.pdf" target="_blank">[Paper]</a> &nbsp;&nbsp;&nbsp;&nbsp;
						<a href="https://github.com/chail/anyres-gan" target="_blank">[Code]</a> &nbsp;&nbsp;&nbsp;&nbsp;
						<a href="/assets/bibliography/visionadl.txt" target="_blank">[Bibtex]</a>
					</p>
				</font>
				<font size="+1">
					<p style="text-align: center;">
						Skip to:  &nbsp;&nbsp;
						<a href="#abstract">[Abstract]</a> &nbsp;&nbsp;&nbsp;&nbsp;
						<a href="#video">[Supplementary Video]</a> &nbsp;&nbsp;&nbsp;&nbsp;
						<a href="#samples">[Random Samples]</a> &nbsp;&nbsp;&nbsp;&nbsp;
					</p>
				</font>
        <p>
            <!-- <img class='teaser-img' src='img/teaser.gif'> -->
            <img class='teaser-img' src='/assets/img/visionadl/environment.png'>
            
        </p>
        <br>

		<p id="abstract"><strong>Abstract: </strong>
        Generative models operate at fixed resolution, even though
        natural images come in a variety of sizes.
        As high-resolution details are downsampled away, and low-resolution images
        are discarded altogether, precious supervision is lost.
        We argue that every pixel matters and create datasets with variable-size
        images, collected at their native resolutions.
        Taking advantage of this data is challenging; high-resolution processing is
        costly, and current architectures can only process fixed-resolution data.
        We introduce continuous-scale training, a process that samples
        patches at random scales to train a new generator with variable
        output resolutions.
        First, conditioning the generator on a target scale allows us to generate
        higher resolutions images than previously possible, without adding layers to the
        model.
        Second, by conditioning on continuous coordinates, we can sample patches that
        still obey a consistent global layout, allowing for scalable training.
        Controlled FFHQ experiments show our method takes advantage of the
        multiresolution training data better than discrete multi-scale
        approaches, achieving better FID scores and cleaner 
        high-frequency details.
        We also train on other natural image domains including churches,
        mountains, and birds, and demonstrate arbitrary scale synthesis with
        both coherent global layouts and realistic local details,
        going beyond 2K resolution in our experiments. 
				</p>
        <br clear="all">
    </div>
    <div class="content" id="summary">

        <h2 style="text-align:center;">Summary</h2>

        <p style="text-align: center;">The typical preprocessing pipeline for unconditional image synthesize resizes all images to the same size, which discards available pixels. We propose a training procedure which can leverage these additional pixels from higher resolution images for image synthesis.
        </p>
        <img class='summary-img' src='/assets/img/visionadl/one.jpg' style="width:40%;">
        <br>
        <hr>
        <p style="text-align: center;">We treat an image as a continuous 2D surface, where real images and synthesized samples correspond to discretizations of this surface. To deal with images of varied sizes, we sample patches of a fixed size at continuous resolutions and locations.</p>
        <img class='summary-img' src='/assets/img/visionadl/two.jpg' style="width:40%;">
        <br>
        <hr>
        <p style="text-align: center;">We can modify our approach to synthesize on a cylindrical image plane, which naturally creates 360 degree panoramas.
				<br>Click <a href="/assets/img/visionadl/blue_bright1.mp4">here</a> to view in video form.</p>
				<a href="/assets/img/visionadl/blue_dark1.mp4"><img class='summary-img' src='/assets/img/visionadl/blue_dark1.mp4' style='width:30%;'><img class='summary-img' src='/assets/img/visionadl/blue_bright1.mp4' style='width:30%;'></a>
				<br>
        <!-- <img class='summary-img' src='img/pano010.png'> -->
			</div>
      <div class="content" id="video">
        <h2 style="text-align:center;">Supplementary Video</h2>
				<p style="text-align: center;">Click <a href="/assets/img/visionadl/blue_dark2.mp4">here</a> to view our supplementary video!</p>
				<center>
					<iframe width="600" height="400" src="https://www.youtube.com/embed/9Y7Gvbw0qr4?rel=0&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
				</center>
      </div>

			<!-- <div class="content" id="samples">
        <h2 style="text-align:center;">Random Samples</h2>
				<p style="text-align: center;">Click on the panels below to view randomly generated patches from our model in comparison to super-resolution models. Our model is trained to synthesize images at continuous resolutions from random noise samples, and thus is not directly supervised with low-resolution and high-resolution pairs from real images.</p>
				<table style="text-align: center;" class="center">
					<tr>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/SR/birds/">
								<p style="text-align: center;">Birds</p>
								<img src="img/panel_birds.jpg" style="width:150px">
							</a>
							</div>
						</td>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/SR/church/">
								<p style="text-align: center;">Church</p>
								<img src="img/panel_church.jpg" style="width:150px">
							</a>
							</div>
						</td>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/SR/mountain/">
								<p style="text-align: center;">Mountain</p>
								<img src="img/panel_mountain.jpg" style="width:150px">
							</a>
							</div>
						</td>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/SR/ffhq6k/">
								<p style="text-align: center;">FFHQ6K</p>
								<img src="img/panel_ffhq.jpg" style="width:150px">
							</a>
							</div>
            </td>
					</tr>
				</table>
				<p style="text-align: center;">Click on the panels below to view randomly generated full image samples from our model at different sizes.</p>
				<table style="text-align: center;" class="center">
					<tr>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/full/birds/">
								<p style="text-align: center;">Birds</p>
								<img src="img/panel_birds_0.png" style="width:150px">
							</a>
							</div>
						</td>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/full/church/">
								<p style="text-align: center;">Church</p>
								<img src="img/panel_church_0.png" style="width:150px">
							</a>
							</div>
						</td>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/full/mountain/">
								<p style="text-align: center;">Mountain</p>
								<img src="img/panel_mountain_0.png" style="width:150px">
							</a>
							</div>
						</td>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/full/ffhq6k/">
								<p style="text-align: center;">FFHQ6K</p>
								<img src="img/panel_ffhq_0.png" style="width:150px">
							</a>
							</div>
            </td>
					</tr>
				</table>
				<p style="text-align: center;">Click on the panel below to view randomly generated panoramas. </p>
				<table style="text-align: center;" class="center">
					<tr>
						<td>
							<div class="boxshadow">
							<a href="http://latent-composition.csail.mit.edu/other_projects/anyres_gan/supplementary_html/panorama/">
								<p style="text-align: center;">Panoramas</p>
								<img src="img/pano026_crop.png" style="width:800px">
							</a>
							</div>
						</td>
					</tr>
				</table>
				<br>
        <hr>
    </div>       -->
    <div class="content" id="references">

        <h2>Reference</h2>

			<p>Hwang, H., Xia, T., Keita, I., Suzuki, K., Biswas, J., Lee, S. I., & Kim, D. System Configuration and Navigation of a Guide Dog Robot: Toward Animal Guide Dog-Level Guiding Work.  ICRA 2023.</p>

        <code>
			 <!-- @inproceedings{chai2022anyresolution,<br>
				 &nbsp;&nbsp;title={Any-resolution training for high-resolution image synthesis.},<br>
				 &nbsp;&nbsp;author={Chai, Lucy and Gharbi, Michael and Shechtman, Eli and Isola, Phillip and Zhang, Richard},<br>
				 &nbsp;&nbsp;booktitle={European Conference on Computer Vision},<br>
				 &nbsp;&nbsp;year={2022}<br>
			} -->
      @article{hwang2022system,<br>
      &nbsp;&nbsp;title={System Configuration and Navigation of a Guide Dog Robot: Toward Animal Guide Dog-Level Guiding Work},<br>
      &nbsp;&nbsp;author={Hwang, Hochul and Xia, Tim and Keita, Ibrahima and Suzuki, Ken and Biswas, Joydeep and Lee, Sunghoon I and Kim, Donghyun},<br>
      &nbsp;&nbsp;journal={arXiv preprint arXiv:2210.13368},<br>
      &nbsp;&nbsp;year={2022}<br>
    }
	</code>
    </div>      
    <div class="content" id="acknowledgements">
          <p><strong>Acknowledgements</strong>:
          The website template was adopted from <a href="https://chail.github.io/anyres-gan/">Lucy Chai</a>.
    <!-- </div>
</body>

</html> -->
