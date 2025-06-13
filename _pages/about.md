---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .homepage-section {
    margin-bottom: 3rem;
  }
  .homepage-section h2 {
    border-left: 4px solid #2a7ae2;
    padding-left: 1rem;
    font-size: 1.5rem;
    color: #2a7ae2;
    margin-bottom: 1rem;
  }
  .homepage-section p,
  .homepage-section li {
    text-align: justify;
  }
  .homepage-section ul {
    padding-left: 1.5rem;
  }
  .date-inline {
    font-style: italic;
    color: #666;
    font-size: 0.9rem;
  }
  .back-to-top {
    display: inline-block;
    margin-top: 1rem;
    font-size: 0.9rem;
    color: #2a7ae2;
  }
</style>

# 👋 Hi, I'm Abdul Sami

[Education](#education) |
[Research Interests](#research) |
[Projects & Publications](#publications) |
[Technical Skills](#skills) |
[Talks & Teaching](#teaching) |
[Get in Touch](#contact)

<div class="homepage-section">
<p>I am a dedicated Machine Learning researcher with a focus on generative models, including expertise in GANs, VAEs, and Diffusion Models. My current work is centered on advancing Diffusion Models to generate high-quality images, and I’m expanding my expertise in Large Language Models (LLMs) to explore the dynamic intersection of vision and language. Currently, I’m completing my Master’s in Computer Science at Soongsil University, Seoul, under the guidance of <a href="https://scholar.google.com/citations?user=YJ7fWWgAAAAJ&hl=en">Prof. Jaeyong Choi</a>. I am passionate about generative AI, computer vision, and building models that push the boundaries of creativity.</p>
</div>

<a name="education"></a>
<div class="homepage-section">
<h2>🎓 Education</h2>
<ul>
  <li><strong>M.S. in Computer Science</strong>, Soongsil University, Seoul, South Korea <span class="date-inline">(Expected Aug 2025)</span><br>
  GPA: 4.16/4.5<br>
  Researcher at System Software Lab under Prof. Jaeyong Choi<br>
  Thesis: Diffusion-Driven Image Generation with Disentangled Style and Structure-Aware Fidelity</li>
  <li><strong>B.E. in Software Engineering</strong>, Mehran University of Engineering and Technology, Pakistan <span class="date-inline">(2018--2023)</span><br>
  GPA: 3.73/4.0<br>
  Graduated as the top student in the class<br>
  Final Year Project: Real-Time Face Recognition Attendance System Using Computer Vision</li>
</ul>
<a class="back-to-top" href="#-hi-im-abdul-sami">[Back to Top]</a>
</div>

<a name="research"></a>
<div class="homepage-section">
<h2>🔬 Research Interests</h2>
<ul>
  <li>Image Generation (Diffusion Models, GANs)</li>
  <li>Multilingual Font Generation</li>
  <li>Few-shot and Zero-shot Learning</li>
  <li>Style Encoding and Transfer</li>
  <li>Computer Vision & Deep Learning</li>
  <li>Object Detection & Semantic Segmentation</li>
  <li>Human-Centered Design Tools using AI and Computer Vision</li>
</ul>
<a class="back-to-top" href="#-hi-im-abdul-sami">[Back to Top]</a>
</div>

<a name="publications"></a>
<div class="homepage-section">
<h2>📚 Projects</h2>
<p><strong>DK-Font: Diffusion-Driven Multilingual Font Generation with Phonetic Awareness and Iterative Refinement</strong><br>
Sami Abdul, Jaeyong Choi<br>
Tools: PyTorch, Diffusion Models, U‑Net, VGG‑19, ResNet, CLIP</p>
<ul>
  <li>Developed a diffusion model for font synthesis across Korean, Chinese, and Latin scripts.</li>
  <li>Used phonetic-aware encoding and iterative refinement to enhance structural accuracy and style consistency.</li>
  <li>Achieved SOTA results in SSIM, FID, and LPIPS, surpassing prior work like Diff‑Font and MX‑Font.</li>
  <li>Implemented few-shot capabilities to synthesize full font sets from just 3–5 reference glyphs.</li>
  <li>Code & demos: DK-Font repository on GitHub</li>
</ul>

<p><strong>Unified Diffusion Model with Multi-Scale Style Infusion and Structure-Aware Losses (Ongoing)</strong><br>
Tools: PyTorch, Diffusion Models, Sobel Filtering, CLIP, VGG, U-Net</p>
<ul>
  <li>Developing an enhanced diffusion-based font generation framework with unified single-phase training.</li>
  <li>Introduced Multi-Scale Style Infusion to inject style representations at encoder, bottleneck, and decoder stages.</li>
  <li>Integrated Sobel-based structural consistency loss to enforce stroke-level preservation during generation.</li>
  <li>Employed CLIP-based style loss for perceptual alignment between reference and generated glyphs.</li>
  <li>Designed for high-fidelity, structure-aware font synthesis across multilingual scripts.</li>
</ul>

<p><strong>Real‑Time Face Recognition Attendance System</strong><br>
Tools: Python, OpenCV, Face Recognition, SQLite, Tkinter</p>
<ul>
  <li>Built a desktop UI that recognizes faces from video and automatically logs attendance.</li>
  <li>Features include face registration, verification, live video feed, and database integration.</li>
</ul>

<p><strong>Hangul Font Classifier</strong><br>
Tools: PyTorch, AlexNet, torchvision</p>
<ul>
  <li>Implemented a CNN to classify 2,780 Hangul characters across font styles.</li>
  <li>Achieved ~95% accuracy in real-time image-based prediction.</li>
</ul>
<a class="back-to-top" href="#-hi-im-abdul-sami">[Back to Top]</a>
</div>

<a name="skills"></a>
<div class="homepage-section">
<h2>💻 Technical Skills</h2>
<ul>
  <li><strong>Deep Learning Frameworks:</strong> PyTorch, TensorFlow, Keras</li>
  <li><strong>Languages:</strong> Python (fluent), C++ (basic), HTML/CSS (for fun)</li>
  <li><strong>ML Tools:</strong> HuggingFace Diffusers, VGG Feature Extractors, OpenCV, NumPy</li>
  <li><strong>Model Types:</strong> Diffusion Models, GANs, Style Encoders, CNNs</li>
  <li><strong>Data Tools:</strong> Pandas, Matplotlib, Jupyter, Weights & Biases</li>
  <li><strong>Other Tools:</strong> Git, Docker, Linux, LaTeX</li>
</ul>
<a class="back-to-top" href="#-hi-im-abdul-sami">[Back to Top]</a>
</div>

<a name="teaching"></a>
<div class="homepage-section">
<h2>🧑‍🏫 Teaching & Talks</h2>
<ul>
  <li>Guest Speaker – <em>"Modern Diffusion Models for Image Generation"</em>, System Software Lab Seminar, Soongsil University <span class="date-inline">(2024)</span></li>
  <li>Teaching Assistant – <em>"Deep Learning Programming"</em>, Soongsil University <span class="date-inline">(Fall 2023)</span></li>
  <li>Presenter – <em>"Font Generation using AI"</em>, Internal Lab Meeting <span class="date-inline">(2024)</span></li>
</ul>
<a class="back-to-top" href="#-hi-im-abdul-sami">[Back to Top]</a>
</div>

<a name="contact"></a>
<div class="homepage-section">
<h2>🔗 Get in Touch</h2>
<ul>
  <li>📧 Email: abdulsamimahar001@gmail.com</li>
  <li>🌐 Portfolio: <a href="https://abdulsami101.github.io">abdulsami101.github.io</a> (Coming Soon)</li>
  <li>📍 Based in Seoul, South Korea</li>
  <li>💼 Open to PhD opportunities in Europe (Fall 2025)</li>
</ul>
<br>
<p>💡 I'm open to collaborations in generative AI and creative deep learning applications. Whether you're working on a new idea, looking for a partner in research, or just curious about fonts and image generation — let’s connect!</p>
<a class="back-to-top" href="#-hi-im-abdul-sami">[Back to Top]</a>
</div>
