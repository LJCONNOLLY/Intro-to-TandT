---
layout: default
title: Breaking Binaries
permalink: /projects/breaking-binaries/
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
/* Use these in breaking-binaries-paige-style.md */

/* Headers */
.section-header { color: var(--color-terracotta); }
h1, h2 { color: var(--color-forest); }
h3 { color: var(--color-sage); }

/* Text */
p { color: var(--color-text-dark); }

/* Backgrounds */
body { background-color: var(--color-bg-cream); }
.callout-box { background-color: var(--color-sand); }

/* Accents */
a { color: var(--color-olive); }
a:hover { color: var(--color-rust); }
<!-- Hero Section -->
<div class="case-study-hero">
  <h1>Breaking Binaries</h1>
  <p class="subtitle">Gender Nonconforming Lesbians on Dating Apps</p>
  <p class="brief">A qualitative UX research study examining how gender nonconforming lesbians navigate dating app constraints and creatively express their identities through platform limitations.</p>
</div>

<!-- Project Details -->
<div class="project-details">
  <div class="detail-item">
    <h3>Timeline</h3>
    <p>2024-2025</p>
  </div>
  <div class="detail-item">
    <h3>Primary Methods</h3>
    <p>Semi-structured Focus Groups, Qualitative User Research, Thematic Coding</p>
  </div>
  <div class="detail-item">
    <h3>Participants</h3>
    <p>9 participants, 4 groups</p>
  </div>
</div>

**Sample Demographics:**

![Participant Demographics Dashboard showing gender identity distribution, sexuality categories, race and ethnicity, interview styles, nonbinary identification, relationship styles, and key statistics for 9 participants in the Breaking Binaries study](../../assets/participant_demographics.png)

This sample, while small, provided rich qualitative data about the intersecting experiences of gender nonconformity and lesbian identity on dating apps. The diversity in gender identities and relationship styles allowed for nuanced discussions about how different users navigate platform constraints.

<!-- Context -->
<h2 class="section-header">The Problem</h2>

<div class="callout-box">
<p>Popular dating apps like Tinder, Bumble, and Hinge have historically been designed for straight, cisgender users. Even with LGBTQ+ features added over time, these platforms often fail to serve gender nonconforming lesbians—people whose gender expression and sexual identity don't fit binary categories.

This research investigates how gender nonconforming lesbians creatively navigate dating apps that treat their identities as an afterthought, and proposes design patterns that leverage creative expression to serve all users more equitably/p>

</div>

<!-- Research Questions -->
<h2 class="section-header">Research Questions</h2>

<ul style="font-size: 1.4rem; line-height: 2; color: #5C4A3A;">
  <li>What constraints do gender nonconforming lesbians experience when trying to express their identities?</li>
  <li>How do they creatively work within and around platform limitations?</li>
  <li>How do intersecting identities (race, class) shape their experiences?</li>
  <li>What design changes would better serve this community?</li>
</ul>

<!-- Research Process -->
<h2 class="section-header">Research Process</h2>

<div class="process-steps">
  <div class="process-step">
    <div class="process-step-number">1</div>
    <h4>Planning</h4>
    <p>Literature review, theoretical framework, IRB approval</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">2</div>
    <h4>Recruitment</h4>
    <p>Snowball sampling through LGBTQ+ networks</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">3</div>
    <h4>Data Collection</h4>
    <p>4 focus groups, 60-90 min each via Zoom</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">4</div>
    <h4>Analysis</h4>
    <p>Thematic coding, intersectional analysis</p>
  </div>
  <div class="process-step">
    <div class="process-step-number">5</div>
    <h4>Synthesis</h4>
    <p>Design recommendations and deliverables</p>
  </div>
</div>

<div class="callout-box">
  <h4>Why Focus Groups?</h4>
  <p>I chose focus groups rather than individual interviews because they allow participants to build on each other's experiences and reveal collective strategies for navigating hostile systems. This collaborative approach aligns with decolonizing research methodologies that prioritize relational knowledge creation.</p>
</div>

<!-- Key Findings -->
<h2 class="section-header">Key Findings</h2>

<div class="findings-grid">
  <div class="finding-card">
    <span class="finding-number">1</span>
    <h3>DIY-ing Identity Expression</h3>
    <p>Dating apps force users to select singular, fixed categories for gender and sexuality that don't capture complexity.</p>
    <div class="quote-highlight">
      "The only way I could show how my gender presentation fluctuates is by uploading multiple photos and explicitly writing about it in my bio." — Angel(pseudonym)
    </div>
    <p><strong>What users did:</strong> Uploaded multiple photos, wrote extensive bios, repurposed interest tags as identity signals.</p>
  </div>

  <div class="finding-card">
    <span class="finding-number">2</span>
    <h3>Algorithmic Invisibility</h3>
    <p>Algorithms designed for binary categories struggle to match nonbinary lesbian users.</p>
    <div class="quote-highlight">
      "I had to say I'm a 'woman interested in women' even though I'm nonbinary, because otherwise I wouldn't show up for other lesbians." — Ruka (pseudonym)
    </div>
    <p><strong>Impact:</strong> Users forced to misrepresent themselves to be visible.</p>
  </div>

  <div class="finding-card">
    <span class="finding-number">3</span>
    <h3>Rejecting Commodification</h3>
    <p>100% of participants said they would never pay for app features.</p>
    <div class="quote-highlight">
      "Paying for a dating app is a new level of desperation. Being super-liked by someone who paid is a major turnoff." — Gina (pseudonym)
    </div>
    <p><strong>Insight:</strong> Monetization strategies don't resonate with all user groups.</p>
  </div>

  <div class="finding-card">
    <span class="finding-number">4</span>
    <h3>Racial Algorithmic Dynamics</h3>
    <p>Dating app algorithms can reinforce racial segregation patterns.</p>
    <div class="quote-highlight">
      "After matching with a few white people, that seemed the be the only race that appeared in my feed" — Wula (pseudonym)
    </div>
    <p><strong>But also:</strong> "Dating apps helped me connect with people of color in my segregated city." — Matisse</p>
  </div>
</div>

<!-- Recommendations -->
<h2 class="section-header">Design Recommendations</h2>

<ul class="recommendations-list">
  <li>
    <h4>Implement Flexible Identity Systems</h4>
    <p>Allow multiple selections for both gender and sexuality. Add free-text fields alongside structured options. Enable identity evolution without losing connection history.</p>
  </li>
  <li>
    <h4>Redesign Matching Algorithms</h4>
    <p>Match based on values and compatibility, not just demographics. Give users visibility control across gender categories. Test algorithms with diverse user groups before launch.</p>
  </li>
  <li>
    <h4>Increase Transparency & User Control</h4>
    <p>Explain how matching algorithms work. Give users control over feed diversity. Audit for racial bias regularly.</p>
  </li>
  <li>
    <h4>Reconsider Monetization Models</h4>
    <p>Design for meaningful connection over engagement maximization. Be transparent about what paid features actually provide. Avoid artificial scarcity tactics.</p>
  </li>
  <li>
    <h4>Center Marginalized Users in Design</h4>
    <p>Include nonbinary lesbians in user research from the beginning. Build diverse product teams. Create ongoing advisory boards from LGBTQ+ communities.</p>
  </li>
</ul>

<div class="callout-box">
  <h4>Key Contributions</h4>
  <ul style="font-size: 1.3rem; line-height: 1.8;">
    <li>Provides evidence-based recommendations for inclusive dating app design</li>
    <li>Centers marginalized voices typically excluded from product development</li>
    <li>Demonstrates how qualitative research can drive design decisions</li>
  </ul>
</div>

<!-- Skills Demonstrated -->
<h2 class="section-header">Skills Demonstrated</h2>

<div class="findings-grid">
  <div class="finding-card">
    <h3>Research Design</h3>
    <p>Study planning, methodology selection, theoretical framework application</p>
  </div>
  <div class="finding-card">
    <h3>Facilitation</h3>
    <p>Focus group moderation, creating safe discussion spaces, managing group dynamics</p>
  </div>
  <div class="finding-card">
    <h3>Analysis</h3>
    <p>Thematic coding, intersectional analysis, pattern identification across data sets</p>
  </div>
  <div class="finding-card">
    <h3>Technical Communication</h3>
    <p>Translating complex findings into actionable insights, presenting to diverse audiences</p>
  </div>
</div>

<!-- Footer CTA -->
<div style="text-align: center; margin: 4rem 0; padding: 3rem; background-color: #F5F1E8; border-radius: 12px;">
  <h3 style="font-size: 2rem; color: #5C4A3A; margin-bottom: 1rem;">Want to discuss this research?</h3>
  <p style="font-size: 1.4rem; color: #8B7355; margin-bottom: 2rem;">I'd love to talk about inclusive UX research methods and design recommendations.</p>
  <a href="mailto:LJConnolly@ucf.edu" style="display: inline-block; background-color: #9CAF88; color: white; padding: 1rem 2.5rem; border-radius: 8px; text-decoration: none; font-size: 1.4rem; font-weight: 600;">Get in Touch</a>
</div>