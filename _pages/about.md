---
layout: about
title: about
permalink: /

profile:
  align: right
  image: MinseokLee.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  :root {
    --global-theme-color: #2c7da0;
    --global-hover-color: #2c7da0;
  }
  #recent-news {
    clear: both;
  }
  .publications li {
    margin-bottom: 0.75rem;
  }
  .news th {
    width: 20%;
    padding-right: 1rem;
    font-weight: bold;
    white-space: nowrap;
  }
  .post-header .desc:empty {
    display: none;
  }
  .post-header .post-title .font-weight-bold {
    font-weight: inherit !important;
  }
  @media (min-width: 576px) {
    .profile {
      width: 22%;
    }
  }
</style>

Hi! I am an M.S. student in [Computer Science and Engineering](https://computing.sogang.ac.kr/ko) at [Sogang University](https://www.sogang.ac.kr/en/home), Seoul, Korea, advised by [Prof. Jaeseung Choi](https://islab-sogang.github.io/) in the **Information Security Lab (ISLAB)**.
I received my B.S. from Sogang University, magna cum laude, in Feb. 2026.

My research focuses on **software testing**, especially **fuzzing**, to automatically discover security vulnerabilities in modern software.
More recently, I have been working on **AI for Security**, using large language models (LLMs) to improve software testing and vulnerability analysis.

You can reach me at **[minseoklee@sogang.ac.kr](mailto:minseoklee@sogang.ac.kr)**!

## Recent News

<div class="news">
  <table class="table table-sm table-borderless">
    <tr>
      <th scope="row">Oct. 2026</th>
      <td>
        Our paper, SPAFL++, was accepted to Computers, Materials &amp; Continua (CMC)!
        [<a href="{{ '/assets/pdf/splicing-cmc.pdf' | relative_url }}">paper</a>]
        [<a href="https://github.com/infosec-sogang/Splicing-Artifact">artifact</a>]
      </td>
    </tr>
    <tr>
      <th scope="row">Sep. 2026</th>
      <td>
        Submitted RareRank to IEEE Access, now under review.
        [<a href="https://github.com/infosec-sogang/RareRank-artifact">artifact</a>]
      </td>
    </tr>
    <tr>
      <th scope="row">Mar. 2026</th>
      <td>
        Started my M.S. at <strong>Sogang University</strong>, advised by <strong>Prof. Jaeseung Choi</strong>.
      </td>
    </tr>
    <tr>
      <th scope="row">Feb. 2026</th>
      <td>
        Graduated magna cum laude with a B.S. from <strong>Sogang University</strong>.
      </td>
    </tr>
    <tr>
      <th scope="row">Apr.–Oct. 2025</th>
      <td>Completed a collaborative research project with the <strong>National Security Research Institute</strong> on directed fuzzing using LLMs.</td>
    </tr>
    <tr>
      <th scope="row">Jan. 2025</th>
      <td>Joined <strong>ISLAB</strong> as an undergraduate researcher.</td>
    </tr>
  </table>
</div>

## Publications

<div class="publications">
  <ul>
    <li>
      Y. Ahn, <strong>M. Lee</strong>, S. Kim, and J. Choi.
      "Enhancing Splicing in Grey-box Fuzzing with Coverage-guided Target Selection and Adaptive Energy Scheduling."
      Computers, Materials &amp; Continua (CMC), 2026.
      [<a href="{{ '/assets/pdf/splicing-cmc.pdf' | relative_url }}">paper</a>]
      [<a href="https://github.com/infosec-sogang/Splicing-Artifact">artifact</a>]
    </li>
    <li>
      <strong>M. Lee</strong>, S. Kim, and J. Choi.
      "RareRank: Frequency-Based Seed Queue Minimization for Rank-Aware Seed Scheduling in Grey-Box Fuzzing."
      IEEE Access, under review.
      [<a href="https://github.com/infosec-sogang/RareRank-artifact">artifact</a>]
    </li>
  </ul>
</div>
