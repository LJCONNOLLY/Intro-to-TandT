---
layout: default
title: Neurodivergent Student Research
permalink: /projects/neurodivergent-student-research/
---

<style>
/* Case Study Specific Styles */
.case-study-hero {
  background: linear-gradient(135deg, #F5F1E8 0%, #E8DCC4 100%);
  padding: 4rem 2rem;
  margin: -2rem -2rem 3rem -2rem;
  text-align: center;
}

.case-study-hero h1 {
  font-size: 3.2rem;
  margin-bottom: 1rem;
  color: #5C4A3A;
}

.case-study-hero .subtitle {
  font-size: 1.8rem;
  color: #8B7355;
  margin-bottom: 2rem;
}

.case-study-hero .brief {
  font-size: 1.4rem;
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.8;
  color: #5C4A3A;
}

.project-details {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  background-color: #FFFDF9;
  padding: 2.5rem;
  border-radius: 12px;
  margin: 3rem 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

.detail-item h3 {
  font-size: 1.3rem;
  color: #9CAF88;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-bottom: 0.5rem;
  font-weight: 600;
}

.detail-item p {
  font-size: 1.4rem;
  color: #5C4A3A;
  margin: 0;
}

.section-header {
  font-size: 2.5rem;
  color: #5C4A3A;
  margin: 4rem 0 2rem 0;
  padding-bottom: 1rem;
  border-bottom: 3px solid #9CAF88;
}

.callout-box {
  background-color: #F5F1E8;
  border-left: 5px solid #9CAF88;
  padding: 2rem;
  margin: 2rem 0;
  border-radius: 8px;
}

.callout-box h4 {
  color: #5C4A3A;
  margin-top: 0;
  font-size: 1.8rem;
}

.findings-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.finding-card {
  background-color: #FFFDF9;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.08);
  transition: transform 0.3s ease;
}

.finding-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
}

.finding-number {
  display: inline-block;
  background-color: #9CAF88;
  color: white;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  text-align: center;
  line-height: 40px;
  font-weight: bold;
  margin-bottom: 1rem;
  font-size: 1.6rem;
}

.finding-card h3 {
  color: #5C4A3A;
  margin-top: 0;
  font-size: 1.8rem;
}

.quote-highlight {
  font-style: italic;
  color: #8B7355;
  font-size: 1.3rem;
  padding: 1.5rem;
  background-color: #F5F1E8;
  border-radius: 8px;
  margin: 1.5rem 0;
}

.recommendations-list {
  counter-reset: recommendation;
  list-style: none;
  padding: 0;
}

.recommendations-list li {
  counter-increment: recommendation;
  background-color: #FFFDF9;
  padding: 2rem;
  margin-bottom: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  position: relative;
  padding-left: 5rem;
}

.recommendations-list li::before {
  content: counter(recommendation);
  position: absolute;
  left: 2rem;
  top: 2rem;
  background-color: #9CAF88;
  color: white;
  width: 35px;
  height: 35px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  font-size: 1.4rem;
}

.recommendations-list h4 {
  margin-top: 0;
  color: #5C4A3A;
  font-size: 1.6rem;
}

.impact-metrics {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.metric-card {
  background: linear-gradient(135deg, #9CAF88 0%, #8B7355 100%);
  color: white;
  padding: 2rem;
  border-radius: 12px;
  text-align: center;
}

.metric-card .number {
  font-size: 3rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
}

.metric-card .label {
  font-size: 1.3rem;
}

.process-steps {
  display: flex;
  justify-content: space-between;
  margin: 3rem 0;
  flex-wrap: wrap;
  gap: 1rem;
}

.process-step {
  flex: 1;
  min-width: 200px;
  text-align: center;
  padding: 1.5rem;
}

.process-step-number {
  background-color: #9CAF88;
  color: white;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  margin: 0 auto 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.8rem;
  font-weight: bold;
}

.process-step h4 {
  color: #5C4A3A;
  font-size: 1.4rem;
  margin: 1rem 0 0.5rem;
}

.process-step p {
  font-size: 1.2rem;
  color: #8B7355;
}
</style>

<!-- Hero Section -->
<div class="case-study-hero">
  <h1>Neurodivergent Student Research</h1>
  <p class="subtitle">Exploring Digital Learning Environments</p>
  <p class="brief">A qualitative UX research study investigating how neurodivergent students experience digital learning platforms and what design changes could better support diverse cognitive styles and learning needs.</p>
</div>

<!-- Project Details -->
<div class="project-details">
  <div class="detail-item">
    <h3>Timeline</h3>
    <p>2026</p>
  </div>
  <div class="detail-item">
    <h3>Primary Methods</h3>
    <p>Qualitative Interviews, User Experience Analysis, Accessibility Audits</p>
  </div>
  <div class="detail-item">
    <h3>Participants</h3>
    <p>12 neurodivergent students</p>
  </div>
</div>

<!-- Context -->
<h2 class="section-header">The Problem</h2>

<div class="callout-box">
<p>Digital learning environments have become essential in higher education, but they're often designed with neurotypical users in mind. Learning Management Systems (LMS), video conferencing tools, and educational software frequently create barriers for neurodivergent students—specifically focusing on those with ADHD, autism, and dyslexia.</p>

<p>This research explores how neurodivergent students navigate these platforms, what challenges they face, and how educational technology can be redesigned to support cognitive diversity.</p>
</div>

<!-- Research Questions -->
<h2 class="section-header">Research Questions</h2>

<ul style="font-size: 1.4rem; line-height: 2; color: #5C4A3A;">
  <li>What specific barriers do neurodivergent students encounter in digital learning environments?</li>
  <li>How do they develop workarounds and coping strategies?</li>
  <li>What features or accommodations would better support their learning?</li>
  <li>How do different neurodivergent profiles experience the same platforms differently?</li>
</ul>

<!-- Research Process -->
<h2 class="section-header">Research Process</h2>

<div class="process-steps">
  <div class="process-step">
    <div class="process-step-number">1</div>
    <h4>Planning</h4>
    <p>Literature review, IRB approval, participant recruitment strategy</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">2</div>
    <h4>Recruitment</h4>
    <p>Recruited through disability services, student organizations</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">3</div>
    <h4>Data Collection</h4>
    <p>Semi-structured interviews, 45-60 min each, via Zoom or in-person</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">4</div>
    <h4>Analysis</h4>
    <p>Thematic coding, pattern identification across neurodivergent profiles</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">5</div>
    <h4>Synthesis</h4>
    <p>Design recommendations and accessibility guidelines</p>
  </div>
</div>

<div class="callout-box">
  <h4>Why This Research Matters</h4>
  <p>Neurodivergent students represent approximately 15-20% of the student population, yet their needs are rarely centered in educational technology design. By understanding their experiences, we can create platforms that work better for everyone—not just as accommodations, but as core design principles.</p>
</div>

<!-- Key Findings -->
<h2 class="section-header">Key Findings</h2>

<div class="findings-grid">
  <div class="finding-card">
    <span class="finding-number">1</span>
    <h3>Sensory Overload</h3>
    <p>Overwhelming visual interfaces with excessive colors, animations, and information density created cognitive exhaustion.</p>
    <div class="quote-highlight">
      "By the end of a Zoom class, I'm so drained from processing everyone's faces and the chat and my notes all at once. I can't learn like that."
    </div>
    <p><strong>Impact:</strong> Students avoided synchronous online sessions or experienced burnout.</p>
  </div>

  <div class="finding-card">
    <span class="finding-number">2</span>
    <h3>Navigation Complexity</h3>
    <p>Inconsistent menu structures and deeply nested content made it difficult for students to locate assignments and materials.</p>
    <div class="quote-highlight">
      "Every professor organizes their Canvas page differently. I spend more time hunting for where they hid the assignment than actually doing it."
    </div>
    <p><strong>What users did:</strong> Created external organization systems, took extensive screenshots.</p>
  </div>

  <div class="finding-card">
    <span class="finding-number">3</span>
    <h3>Time Management Barriers</h3>
    <p>Notification systems either overwhelmed students with constant alerts or failed to provide timely reminders.</p>
    <div class="quote-highlight">
      "I get 50 Canvas notifications a day, so I turned them all off. Then I missed a major deadline."
    </div>
    <p><strong>Need:</strong> Customizable, priority-based notification systems with visual/temporal cues.</p>
  </div>

  <div class="finding-card">
    <span class="finding-number">4</span>
    <h3>Social Communication Challenges</h3>
    <p>Discussion boards and group project tools lacked structure for clear, asynchronous communication.</p>
    <div class="quote-highlight">
      "I never know if I'm responding at the right 'depth' or if I'm supposed to respond to everyone or just one person. The rules aren't clear."
    </div>
    <p><strong>Impact:</strong> Students avoided participation or experienced social anxiety.</p>
  </div>
</div>

<!-- Recommendations -->
<h2 class="section-header">Design Recommendations</h2>

<ul class="recommendations-list">
  <li>
    <h4>Implement Customizable Interfaces</h4>
    <p>Allow users to control color schemes, animation, information density, and layout. Provide sensory-friendly modes with reduced visual complexity. Enable persistent customization across sessions.</p>
  </li>
  <li>
    <h4>Standardize Navigation Patterns</h4>
    <p>Create consistent organizational structures across courses. Implement breadcrumb navigation and clear visual hierarchies. Provide multiple pathways to the same content (calendar view, list view, timeline).</p>
  </li>
  <li>
    <h4>Redesign Notification Systems</h4>
    <p>Allow granular control over notification types and timing. Implement smart prioritization based on deadlines and user behavior. Provide visual timeline views of upcoming tasks and deadlines.</p>
  </li>
  <li>
    <h4>Structure Social Interactions</h4>
    <p>Provide clear templates and examples for discussion posts. Make participation expectations explicit. Offer alternative ways to contribute (text, voice, video options).</p>
  </li>
  <li>
    <h4>Build in Focus Support</h4>
    <p>Create distraction-free reading and writing modes. Allow users to hide non-essential interface elements. Implement keyboard shortcuts and command palettes for power users.</p>
  </li>
  <li>
    <h4>Center Accessibility from the Start</h4>
    <p>Include neurodivergent students in usability testing. Design with cognitive accessibility as a core requirement, not an afterthought. Create ongoing feedback mechanisms with disabled student communities.</p>
  </li>
</ul>

<div class="callout-box">
  <h4>Universal Design Principle</h4>
  <p>Features designed for neurodivergent students often benefit all users. Customizable interfaces, clear navigation, and flexible notification systems improve the experience for everyone navigating complex digital environments.</p>
</div>

<!-- Impact -->
<h2 class="section-header">Project Impact</h2>

<div class="impact-metrics">
  <div class="metric-card">
    <div class="number">3</div>
    <div class="label">Presentations to university IT committees</div>
  </div>
  <div class="metric-card">
    <div class="number">50+</div>
    <div class="label">Faculty members reached through workshops</div>
  </div>
  <div class="metric-card">
    <div class="number">2</div>
    <div class="label">LMS vendors shared recommendations with</div>
  </div>
</div>

<!-- Skills Demonstrated -->
<h2 class="section-header">Skills Demonstrated</h2>

<div class="findings-grid">
  <div class="finding-card">
    <h3>Research Design</h3>
    <p>Study planning, methodology selection, working with vulnerable populations, ethical research practices</p>
  </div>
  <div class="finding-card">
    <h3>Qualitative Methods</h3>
    <p>Semi-structured interviewing, creating safe research environments, active listening</p>
  </div>
  <div class="finding-card">
    <h3>Analysis</h3>
    <p>Thematic coding, pattern identification, synthesizing insights across diverse experiences</p>
  </div>
  <div class="finding-card">
    <h3>Accessibility Expertise</h3>
    <p>Understanding cognitive accessibility, WCAG guidelines, assistive technology compatibility</p>
  </div>
  <div class="finding-card">
    <h3>Stakeholder Communication</h3>
    <p>Translating research into actionable recommendations for IT teams, faculty, administrators</p>
  </div>
  <div class="finding-card">
    <h3>Advocacy</h3>
    <p>Centering marginalized voices, presenting disability research to non-disabled audiences</p>
  </div>
</div>

<!-- Footer CTA -->
<div style="text-align: center; margin: 4rem 0; padding: 3rem; background-color: #F5F1E8; border-radius: 12px;">
  <h3 style="font-size: 2rem; color: #5C4A3A; margin-bottom: 1rem;">Interested in accessibility research?</h3>
  <p style="font-size: 1.4rem; color: #8B7355; margin-bottom: 2rem;">I'd love to discuss how UX research can drive inclusive design in educational technology.</p>
  <a href="mailto:LJConnolly@ucf.edu" style="display: inline-block; background-color: #9CAF88; color: white; padding: 1rem 2.5rem; border-radius: 8px; text-decoration: none; font-size: 1.4rem; font-weight: 600;">Get in Touch</a>
</div>