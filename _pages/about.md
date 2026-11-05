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

Hi! I am an M.S. student in [Computer Science and Engineering](https://cs.sogang.ac.kr/cs/index_new.html) at [Sogang University](https://sogang.ac.kr/ko/home), Seoul, Korea, in the combined B.S.–M.S. program (Mar. 2026 – present).
I am a member of **ISLAB**, advised by [Prof. Jaeseung Choi](https://islab-sogang.github.io/).
Before that, I received my B.S. in Computer Science and Engineering, *magna cum laude*, from Sogang University (Mar. 2020 – Feb. 2026).

My research focuses on **software testing**, especially **fuzzing**, to automatically discover security vulnerabilities in modern software.
More recently, I have been exploring **AI for Software Engineering (AI4SE)**, especially leveraging AI agents to improve software testing and vulnerability discovery.

You can reach me at **[minseoklee@sogang.ac.kr](mailto:minseoklee@sogang.ac.kr)**!

## Recent News

<div class="news">
  <table class="table table-sm table-borderless">
    <tr>
      <th scope="row">Oct. 2026</th>
      <td>
        Our paper on improving splicing in grey-box fuzzing was accepted to <em>Computers, Materials &amp; Continua (CMC)</em>!
        [<a href="{{ '/assets/pdf/splicing-cmc.pdf' | relative_url }}">paper</a>]
        [<a href="https://github.com/infosec-sogang/Splicing-Artifact">artifact</a>]
      </td>
    </tr>
    <tr>
      <th scope="row">Sep. 2026</th>
      <td>
        Submitted my first-author paper, <em>RareRank</em>, to <em>IEEE Access</em>, now under review.
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
        Graduated <em>magna cum laude</em> with a B.S. from <strong>Sogang University</strong>.
      </td>
    </tr>
    <tr>
      <th scope="row">Dec. 2025</th>
      <td>Won the Excellence Award (3rd place) at the Capstone Design Competition.</td>
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
