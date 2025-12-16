---
layout: page
permalink: /teaching/
title: teaching
description: Statistics for ML lessons, tutorials, and resources.
nav: true
nav_order: 6
---

<style>
  .teach-hero {
    border-radius: 18px;
    padding: 24px;
    background: linear-gradient(135deg, rgba(13,110,253,.12), rgba(111,66,193,.10), rgba(25,135,84,.10));
    border: 1px solid rgba(0,0,0,.08);
  }
  .teach-card {
    border-radius: 16px;
    border: 1px solid rgba(0,0,0,.08);
    transition: transform .12s ease, box-shadow .12s ease;
  }
  .teach-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 24px rgba(0,0,0,.08);
  }
  .teach-badge {
    border-radius: 999px;
    padding: 6px 10px;
    font-size: .85rem;
    border: 1px solid rgba(0,0,0,.10);
    background: rgba(255,255,255,.7);
  }
  .teach-muted { opacity: .85; }
  .teach-pill {
    cursor: pointer;
    user-select: none;
  }
  .teach-pill.active {
    background: #0d6efd;
    color: #fff;
    border-color: #0d6efd;
  }
</style>

<div class="teach-hero mb-4">
  <div class="d-flex flex-wrap align-items-center justify-content-between gap-3">
    <div>
      <h2 class="mb-2">Statistics for Machine Learning</h2>
      <div class="teach-muted">
        Short lessons and videos that build solid intuition before ML models.
      </div>
      <div class="mt-3 d-flex flex-wrap gap-2">
        <a class="btn btn-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">YouTube channel</a>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://hodausama.github.io/">Blog</a>
        <a class="btn btn-outline-dark btn-sm" target="_blank" href="https://www.linkedin.com/in/hodaosama/">LinkedIn</a>
      </div>
    </div>

    <div class="text-end">
      <div class="teach-badge mb-2">Track: Statistics foundations</div><br/>
      <div class="teach-badge">Next video: Conditional vs Marginal</div>
    </div>
  </div>
</div>

<div class="row g-3 mb-3">
  <div class="col-md-6">
    <input id="teachSearch" class="form-control" placeholder="Search lessons (example: z-score, correlation, frequency)"/>
  </div>
  <div class="col-md-6 d-flex flex-wrap gap-2 justify-content-md-end">
    <span class="teach-badge teach-pill active" data-filter="all">All</span>
    <span class="teach-badge teach-pill" data-filter="basics">Basics</span>
    <span class="teach-badge teach-pill" data-filter="visualization">Visualization</span>
    <span class="teach-badge teach-pill" data-filter="python">Python</span>
    <span class="teach-badge teach-pill" data-filter="probability">Probability</span>
  </div>
</div>

<div class="row g-3" id="teachGrid">

  <div class="col-md-6 teach-item" data-tags="basics">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">1. Descriptive vs Inferential Statistics</h5>
          <span class="badge bg-primary">Basics</span>
        </div>
        <div class="teach-muted mb-3">A simple start and when to use each type.</div>
        <div class="d-flex flex-wrap gap-2">
          <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
        </div>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="basics">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">2. Cases, Variables, and Frequency Tables</h5>
          <span class="badge bg-primary">Basics</span>
        </div>
        <div class="teach-muted mb-3">From raw data to insight with core definitions.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="visualization">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">3. Choosing the Right Graph</h5>
          <span class="badge bg-success">Visualization</span>
        </div>
        <div class="teach-muted mb-3">How to visualize your data correctly in statistics.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="python visualization">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">4. Frequency Tables in Python (With Charts)</h5>
          <span class="badge bg-warning text-dark">Python</span>
        </div>
        <div class="teach-muted mb-3">Build tables and charts step by step.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="basics">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">5. Mean, Median, and Mode</h5>
          <span class="badge bg-primary">Basics</span>
        </div>
        <div class="teach-muted mb-3">Measuring the center with intuition and examples.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="basics visualization">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">6. Range, IQR, and the Box Plot</h5>
          <span class="badge bg-success">Visualization</span>
        </div>
        <div class="teach-muted mb-3">Understand dispersion and box plots clearly.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="basics">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">7. Variance and Standard Deviation</h5>
          <span class="badge bg-primary">Basics</span>
        </div>
        <div class="teach-muted mb-3">Measuring variability in a practical way.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="basics">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">8. Z-Score Standardization</h5>
          <span class="badge bg-primary">Basics</span>
        </div>
        <div class="teach-muted mb-3">Compare values using standardization.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 teach-item" data-tags="basics visualization">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start gap-2">
          <h5 class="card-title mb-1">9. Correlation Between Variables</h5>
          <span class="badge bg-success">Visualization</span>
        </div>
        <div class="teach-muted mb-3">Contingency tables and scatter plots.</div>
        <a class="btn btn-outline-primary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Watch on YouTube</a>
      </div>
    </div>
  </div>

  <div class="col-12 teach-item" data-tags="probability">
    <div class="card teach-card h-100">
      <div class="card-body">
        <div class="d-flex flex-wrap justify-content-between align-items-start gap-2">
          <div>
            <h5 class="card-title mb-1">Next video to publish</h5>
            <div class="teach-muted">Conditional vs Marginal distribution with examples and ML intuition.</div>
          </div>
          <span class="badge bg-info text-dark">Probability</span>
        </div>

        <div class="mt-3 d-flex flex-wrap gap-2">
          <a class="btn btn-primary btn-sm" target="_blank" href="https://hodausama.github.io/posts/conditional-vs-marginal/">Open the blog post</a>
          <a class="btn btn-outline-secondary btn-sm" target="_blank" href="https://www.youtube.com/@Hoda_Osama_AI">Publish on YouTube</a>
        </div>

        <div class="mt-3">
          <div class="teach-badge">Suggested video structure</div>
          <ul class="mt-2 mb-0">
            <li>Start with a real dataset example and the question you want to answer</li>
            <li>Define marginal distribution with a simple table</li>
            <li>Define conditional distribution with step by step conditioning</li>
            <li>Show 1 confusion example people make and fix it</li>
            <li>Connect to ML: naive Bayes, feature dependence, and data leakage intuition</li>
          </ul>
        </div>

      </div>
    </div>
  </div>

</div>

<script>
  (function () {
    const pills = Array.from(document.querySelectorAll(".teach-pill"));
    const items = Array.from(document.querySelectorAll(".teach-item"));
    const search = document.getElementById("teachSearch");

    let activeFilter = "all";

    function matchesFilter(el) {
      if (activeFilter === "all") return true;
      const tags = (el.getAttribute("data-tags") || "").toLowerCase();
      return tags.includes(activeFilter);
    }

    function matchesSearch(el) {
      const q = (search.value || "").trim().toLowerCase();
      if (!q) return true;
      return el.innerText.toLowerCase().includes(q);
    }

    function render() {
      items.forEach(el => {
        const ok = matchesFilter(el) && matchesSearch(el);
        el.style.display = ok ? "" : "none";
      });
    }

    pills.forEach(p => {
      p.addEventListener("click", () => {
        pills.forEach(x => x.classList.remove("active"));
        p.classList.add("active");
        activeFilter = p.getAttribute("data-filter");
        render();
      });
    });

    search.addEventListener("input", render);

    render();
  })();
</script>
