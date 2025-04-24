---
layout: default
title: Home
---


<section class="hero">
  <div class="hero-text">
    <h2>Welcome to Reedsport School District</h2>
    <p>Empowering students. Supporting community. Inspiring futures.</p>
  </div>
</section>

<section class="site-content">
  <div class="container">
    <p>Reedsport School District 105 is committed to delivering a high-quality education in a supportive and inclusive environment. With a focus on academics, enrichment, and student well-being, we prepare students from PreK through 12th grade to thrive in a changing world.</p>

    <div class="home-cards">
      <div class="home-card">
        <h3>District Snapshot</h3>
        <table>
          <tr><td><strong>Schools:</strong></td><td>2</td></tr>
          <tr><td><strong>Grades Served:</strong></td><td>PreK–12</td></tr>
          <tr><td><strong>Enrollment:</strong></td><td>~500 students</td></tr>
          <tr><td><strong>Location:</strong></td><td>Reedsport, Oregon</td></tr>
        </table>
      </div>

      <div class="home-card alert">
        <h3>Stay Informed</h3>
        <p>Check ParentSquare or our News section for school announcements, closures, and emergency alerts.</p>
        <ul>
          <li><a href="/pages/calendar.html">Instructional Calendar</a></li>
          <li><a href="https://parentsquare.com/" target="_blank">ParentSquare Login</a></li>
          <li><a href="/pages/contact.html">Staff Directory</a></li>
        </ul>
      </div>

      <div class="home-card">
        <h3>Explore Our Schools</h3>
        <ul>
          <li><a href="/pages/highland.html">Highland Elementary School</a></li>
          <li><a href="/pages/rccs.html">Reedsport Community Charter School</a></li>
        </ul>
      </div>

      <div class="home-card light">
        <h3>Quick Links</h3>
        <ul>
          <li><a href="/pages/student-support-site.html">Student Support Site</a></li>
          <li><a href="/pages/tutoring-resources.html">Tutoring Resources</a></li>
          <li><a href="/pages/jobs.html">Employment Opportunities</a></li>
        </ul>
      </div>
    </div>
  </div>
</section>

<style>
.home-cards {
  display: grid;
  gap: 1.5rem;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  margin-top: 2rem;
}
.home-card {
  background: #ffffff;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.08);
}
.home-card h3 {
  margin-top: 0;
  color: #b60000;
}
.home-card.alert {
  background: #fff3f3;
  border-left: 6px solid #b60000;
}
.home-card.light {
  background: #f8f8f8;
}
.home-card table {
  width: 100%;
  border-collapse: collapse;
}
.home-card td {
  padding: 0.4rem;
  border-bottom: 1px solid #eee;
}
</style>
