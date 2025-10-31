---
layout: default
title: Resume
permalink: /resume/
---

<style>
.resume-container {
  max-width: 900px;
  margin: 0 auto;
  text-align: center;
}

.download-btn {
  margin: 2rem 0 3rem 0;
}

.download-btn a {
  display: inline-block;
  background-color: #9CAF88;
  color: white;
  padding: 1.5rem 3rem;
  border-radius: 8px;
  text-decoration: none;
  font-size: 1.6rem;
  font-weight: 600;
  transition: background-color 0.3s ease;
}

.download-btn a:hover {
  background-color: #8B9A77;
}

.pdf-embed {
  border: none;
  box-shadow: 0 4px 20px rgba(0,0,0,0.15);
  border-radius: 8px;
}
</style>

<div class="resume-container">
  
  <div class="download-btn">
    <a href="{{ '/assets/resume.pdf' | relative_url }}" download>Download Resume (PDF)</a>
  </div>

  <iframe src="{{ '/assets/resume.pdf' | relative_url }}" width="100%" height="1000px" class="pdf-embed"></iframe>

</div>