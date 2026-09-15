---
layout: about
title: about
permalink: /

profile:
  align: right
  image: MinseokLee.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <div class="info-label">Email</div>
    <p class="info-email"><a href="mailto:minseoklee@sogang.ac.kr">minseoklee@sogang.ac.kr</a></p>
    <div class="info-label">Location</div>
    <p>Seoul, Korea</p>
    <div class="profile-socials">
      <a href="https://www.linkedin.com/in/minseok-lee-93ba22304/" title="LinkedIn" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-linkedin"></i></a>
      <a href="https://github.com/ms1ee" title="GitHub" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-github"></i></a>
    </div>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # contact links are shown under the profile photo instead

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
  .profile .more-info {
    margin-top: 1.25rem;
    padding: 0 0.5rem;
    font-family: inherit;
  }
  .profile .more-info p {
    display: block;
    margin: 0 0 1.25rem;
    overflow-wrap: anywhere;
  }
  .profile .more-info .info-email {
    font-size: 0.85rem;
  }
  .profile .more-info .info-label {
    margin-bottom: 0.25rem;
    font-size: 0.8rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--global-text-color-light, #828282);
  }
  .profile .profile-socials {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 1.5rem;
    font-size: 1.75rem;
  }
  .profile .profile-socials a {
    color: var(--global-text-color-light, #828282);
  }
  .profile .profile-socials a:hover {
    color: var(--global-theme-color);
  }
</style>

Hi! I am an M.S. student in Computer Science and Engineering at [Sogang University](https://sogang.ac.kr/ko/home), Seoul, Korea, in the combined B.S.–M.S. program (Mar. 2026 – present).
I am a member of **ISLAB**, advised by [Prof. Jaeseung Choi](https://islab-sogang.github.io/).
Before that, I received my B.S. in Computer Science and Engineering from Sogang University (Mar. 2020 – Feb. 2026).

My research focuses on **software testing**, especially **fuzzing**, to automatically discover security vulnerabilities in modern software.
More recently, I have been exploring **AI for Software Engineering (AI4SE)**, especially leveraging AI agents to improve software testing and vulnerability discovery.

## Recent News

<div class="news">
  <table class="table table-sm table-borderless">
    <tr>
      <th scope="row">Mar. 2026</th>
      <td>
        Started my M.S. at <a href="https://sogang.ac.kr/ko/home">Sogang University</a>, joining ISLAB (advised by
        <a href="https://islab-sogang.github.io/">Prof. Jaeseung Choi</a>).
      </td>
    </tr>
    <tr>
      <th scope="row">Feb. 2026</th>
      <td>Graduated with a B.S. in <a href="https://cs.sogang.ac.kr/cs/index_new.html">Computer Science and Engineering</a>, Magna Cum Laude.</td>
    </tr>
    <tr>
      <th scope="row">Fall 2025</th>
      <td>Won the Excellence Award (3rd place) at the Capstone Design Competition.</td>
    </tr>
    <tr>
      <th scope="row">Apr.–Oct. 2025</th>
      <td>Completed a collaborative research project with the National Security Research Institute on directed fuzzing using LLMs.</td>
    </tr>
  </table>
</div>
