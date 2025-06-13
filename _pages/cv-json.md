---
layout: archive
title: "Curriculum Vitae"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

<!-- External styling and icon support -->
<link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<style>
  body {
    background: linear-gradient(to right, #f5f7fa, #c3cfe2);
  }

  .cv-summary {
  text-align: justify;
  text-justify: inter-word;
  background-color: #f9f9f9;
  padding: 1rem;
  border-left: 4px solid #2575fc;
  border-radius: 5px;
  font-size: 1rem;
  line-height: 1.6;
}
  .cv-timeline {
    margin-top: 1rem;
    border-left: 3px solid #2575fc;
    padding-left: 1.5rem;
  }

  .cv-timeline-item {
    margin-bottom: 2rem;
    padding-left: 0.5rem;
    position: relative;
  }

  .cv-timeline-item::before {
    content: "";
    position: absolute;
    top: 0.5rem;
    left: -1.1rem;
    width: 12px;
    height: 12px;
    background-color: #2575fc;
    border-radius: 50%;
  }

  .cv-timeline-header {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-bottom: 0.25rem;
  }

  .cv-degree {
    font-size: 1.1rem;
    font-weight: 600;
  }

  .cv-institution {
    font-size: 1rem;
    color: #555;
    margin-bottom: 0.3rem;
  }

  .cv-thesis,
  .cv-honors,
  .cv-courses {
    font-size: 0.95rem;
    color: #333;
    margin-bottom: 0.2rem;
  }

  .cv-date {
    font-size: 0.95rem;
    color: #888;
    text-align: right;
    min-width: 120px;
  }

  .cv-gpa {
    font-weight: normal;
    font-size: 0.95rem;
    color: #444;
  }

  .cv-timeline-item {
  margin-bottom: 2rem;
  padding-left: 0.5rem;
  position: relative;
}

  .cv-timeline-item::before {
    content: "";
    position: absolute;
    top: 0.6rem;
    left: -1.1rem;
    width: 12px;
    height: 12px;
    background-color: #2575fc;
    border-radius: 50%;
  }

  .cv-job-title {
    font-size: 1.1rem;
    font-weight: 600;
  }

  .cv-institution {
    font-size: 1rem;
    color: #444;
    margin: 0.3rem 0;
  }

  .cv-date {
    font-size: 0.95rem;
    color: #888;
    text-align: right;
    float: right;
    margin-top: -1.5rem;
  }

  .cv-job-summary {
    font-size: 0.95rem;
    color: #333;
    margin-bottom: 0.5rem;
    text-align: justify;
    text-justify: inter-word;
  }

  .cv-highlights {
    margin-left: 1.2rem;
    padding-left: 0;
    list-style: none;
  }

  .cv-highlights li {
    margin-bottom: 0.4rem;
    font-size: 0.95rem;
    color: #222;
  }

  .cv-highlights i {
    color: #2575fc;
    margin-right: 0.5rem;
  }


 

  .archive {
    width: 90%;
    max-width: 900px;
    margin: 2rem auto;
    float: none;
    padding: 2rem;
    background-color: white;
    border-radius: 1rem;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
  }
   .cv-job-summary {
  text-align: justify;
  text-justify: inter-word;
  font-size: 0.95rem;
  color: #333;
  margin-bottom: 0.8rem;
  line-height: 1.6;
}

  .cv-highlights {
    margin-left: 1.5rem;
    padding-left: 0;
    list-style: none;
  }

  .cv-highlights li {
    text-align: justify;
    text-justify: inter-word;
    margin-bottom: 0.4rem;
    font-size: 0.95rem;
    line-height: 1.6;
    color: #222;
  }

  .cv-timeline-item {
  margin-bottom: 2rem;
  position: relative;
  padding-left: 1.2rem;
}

.cv-timeline-item::before {
  content: "";
  position: absolute;
  top: 0.7rem;
  left: -0.6rem;
  width: 10px;
  height: 10px;
  background-color: #2575fc;
  border-radius: 50%;
}

.cv-job-title {
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 0.2rem;
}

.cv-institution {
  font-size: 1rem;
  color: #555;
  margin-bottom: 0.6rem;
}

.cv-job-summary {
  font-size: 0.95rem;
  color: #333;
  text-align: justify;
  text-justify: inter-word;
  margin-bottom: 0.8rem;
  line-height: 1.6;
}

.cv-highlights {
  list-style: none;
  padding: 0;
  margin: 0;
}

.cv-highlights li {
  position: relative;
  padding-left: 1.8rem;
  margin-bottom: 0.75rem;
  font-size: 0.95rem;
  color: #222;
  text-align: justify;
  text-justify: inter-word;
  line-height: 1.6;
}

.cv-highlights li i {
  position: absolute;
  top: 0.15rem;
  left: 0;
  color: #2575fc;
  font-size: 1rem;
}



  .cv-download-links {
    text-align: center;
    margin-top: 2rem;
  }

  .cv-download-links .btn {
    display: inline-block;
    margin: 0.5rem;
    padding: 0.8rem 1.5rem;
    font-size: 1rem;
    border-radius: 30px;
    text-decoration: none;
    transition: all 0.3s ease;
    font-weight: 600;
  }

  .cv-skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 1rem;
}

  .cv-skill-box {
    background-color: #f9f9f9;
    border-left: 4px solid #2575fc;
    padding: 1rem 1.2rem;
    border-radius: 8px;
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.06);
    transition: transform 0.3s ease;
  }

  .cv-skill-box:hover {
    transform: translateY(-3px);
  }

  .cv-skill-box h3 {
    margin-bottom: 0.7rem;
    font-size: 1.1rem;
    color: #333;
  }

  .cv-skill-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .cv-skill-list li {
    margin-bottom: 0.4rem;
    font-size: 0.95rem;
    color: #444;
  }

  .cv-skill-list li i {
    color: #2575fc;
    margin-right: 0.5rem;
  }

  .cv-publication-card {
    background-color: #fdfdfd;
    padding: 1.2rem;
    border-left: 4px solid #2575fc;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    transition: transform 0.3s ease;
  }

  .cv-publication-card:hover {
    transform: translateY(-4px);
  }

  .cv-publication-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 0.3rem;
  }

  .cv-publication-title {
    font-size: 1.05rem;
    font-weight: 600;
    color: #222;
  }

  .cv-publication-link {
    color: #2575fc;
    text-decoration: none;
    font-weight: 600;
  }

  .cv-publication-link:hover {
    text-decoration: underline;
  }

  .cv-publication-date {
    font-size: 0.95rem;
    color: #777;
  }

  .cv-publication-meta {
    font-size: 0.95rem;
    color: #555;
    margin-bottom: 0.4rem;
  }

  .cv-publication-summary {
    font-size: 0.95rem;
    color: #333;
    text-align: justify;
    line-height: 1.6;
    margin-bottom: 0.5rem;
  }

  .cv-publication-link-cta a {
    font-size: 0.9rem;
    color: #2575fc;
    text-decoration: none;
  }

  .cv-publication-link-cta a:hover {
    text-decoration: underline;
  }

  .cv-languages-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

  .cv-language-card {
    background-color: #f5f7fa;
    border-left: 4px solid #2575fc;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
    text-align: center;
    transition: transform 0.3s ease;
  }

  .cv-language-card:hover {
    transform: translateY(-3px);
  }

  .cv-language-title {
    font-size: 1.05rem;
    font-weight: 600;
    color: #333;
    margin-bottom: 0.3rem;
  }

  .cv-language-title i {
    margin-right: 0.4rem;
    color: #2575fc;
  }

  .cv-language-fluency {
    font-size: 0.95rem;
    color: #555;
  }

  .cv-references-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 1rem;
  }

  .cv-reference-card {
    background-color: #fdfdfd;
    border-left: 4px solid #2575fc;
    padding: 1rem 1.2rem;
    border-radius: 8px;
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.06);
    transition: transform 0.3s ease;
  }

  .cv-reference-card:hover {
    transform: translateY(-3px);
  }

  .cv-reference-name {
    font-size: 1.05rem;
    font-weight: 600;
    margin-bottom: 0.4rem;
    color: #333;
  }

  .cv-reference-name i {
    color: #2575fc;
    margin-right: 0.5rem;
  }

  .cv-reference-detail {
    font-size: 0.95rem;
    color: #555;
    line-height: 1.5;
  }




  .btn--primary {
    background: linear-gradient(to right, #6a11cb, #2575fc);
    color: white;
    border: none;
  }

  .btn--primary:hover {
    background: linear-gradient(to right, #2575fc, #6a11cb);
    transform: scale(1.05);
  }

  .btn--inverse {
    background-color: #ffffff;
    border: 2px solid #2575fc;
    color: #2575fc;
  }

  .btn--inverse:hover {
    background-color: #2575fc;
    color: white;
    transform: scale(1.05);
  }
</style>

<!-- Actual CV content pulled from JSON -->
{% include cv-template.html %}

<!-- Call-to-action buttons -->
<div class="cv-download-links">
  <a href="{{ base_path }}/files/AbdulSami_CV.pdf" class="btn btn--primary" target="_blank">
    <i class="fas fa-file-download"></i> Download CV (PDF)
  </a>
  <!-- <a href="{{ base_path }}/resume/" class="btn btn--inverse">
    <i class="fas fa-code"></i> View CV in Markdown
  </a> -->
</div>